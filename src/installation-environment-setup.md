# Installation environment setup

As `Substrate` is written by `Rust`, then you need to install something before you can run or develop your 
first `Blockchain` on your computer:


### The compilation tool set

- MacOS

    ```bash
    # Make sure Homebrew is up-to-date, install openssl and cmake
    brew update
    brew install openssl cmake
    ```

- Ubuntu/Debian

    ```bash
    sudo apt update
    # May prompt for location information
    sudo apt install -y cmake pkg-config libssl-dev git build-essential clang libclang-dev curl libz-dev
    ```

- Arch Linux

    ```bash
    pacman -Syu --needed --noconfirm cmake gcc openssl-1.0 pkgconf git clang
    export OPENSSL_LIB_DIR="/usr/lib/openssl-1.0"
    export OPENSSL_INCLUDE_DIR="/usr/include/openssl-1.0"
    ```

</br>

`Substrate` development is easiest on Unix-based operating systems like `macOS` or Linux. So if you're using
`Windows`, Please refer to the latest [guide for Windows users](https://substrate.dev/docs/en/knowledgebase/getting-started/windows-users).


### Rust Developer Environment

If you go back and have a look at the `Substrate` architecture diagram in the previous chapter, you will notice
that there is a very important  `runtime` component that represents the business logic that defines its behavior.

That `runtime` actually can be written in any programming language that can be compiled as the `WebAssembly (WASM)` format.
So, that's why you need to use the `nightly` rust toolchain by the settings below:

```bash
# Install the `nightly` toolchain if you don't have yet
rustup toolchain add nightly

# Update the `nightly` toolchain if you've already installed
rustup update nightly

# Add `WebAssembly (WASM)` target support for the `nightly` build
rustup target add wasm32-unknown-unknown --toolchain nightly


# Then you can confirm whether it exists or not by running
rustup target list --toolchain nightly | grep installed | grep wasm
# wasm32-unknown-unknown (installed)
```

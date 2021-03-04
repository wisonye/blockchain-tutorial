# What is `Substrate`

`Substrate` is a flexible framework for building modular, efficient, and upgradeable `blockchains`. 

`Substrate` is written in the `Rust` programming language and is maintained by **Parity Technologies**.

</br>

This screenshot is the best way to describe what is `Substrate`:

![what-is-substrate](./images/what-is-substrate.png)

</br>

If you think about that a `Blockchain` works like a `State Machine` which means
it keep creating the `New State` from the `Previous State` to generate the `Next Block` 
and then attach it back to the `Blockchain`.

</br>

As well-known that any computer can become a `Blockchain Node` to hold the entire `blockchain` historical
blocks and generate a new block. But the question is how to make that happen?

The answer is that a `client application` needs to be run on that particular computer, that `client application`
is call `Substrate Client`. Here is the architecture of a typical `Substrate Client` application:


![substrate-arch.png](./images/substrate-arch.png)


Yup, I know, it looks very complicated right now. But relax, just leave it at this moment. The only thing you 
need to know is that it just an application that runs inside your computer, and it will handle all `Blockchain` 
behaviours for you. 

In the rest chapters, the concepts below are the same:

- `Blockchain Node`
- `Node`
- `Blockchain Backend (Application)`
- `Substrate Client (Application)`

They all mean the `Blockchain Node Application` that run on your local computer to provide the normal `Blockchain` functionality,
plz keep that in mind.

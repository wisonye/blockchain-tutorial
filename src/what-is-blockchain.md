# What is `Blockchain`

## `Blockchain` is NOT

- `Blockchain` is NOT `Bitcoin`!!! It's not any kind of coin (virtual cryptocurrency).
- `Blockchain` is NOT an online application.

## So what `Blockchain` is

Let's answer this question step by step:

- `Blockchain` is a network.
- `Blockchain` is distributed network.
- `Blockchain` is decentralized distributed network.
- `Blockchain` is decentralized distributed peer-to-peer network.
- `Blockchain` is decentralized distributed peer-to-peer network that holds a bunch of data.

## What's inside the `Blockchain` 


```
   Genesis                                     Current
   block              block                    block
+-----------+     +-----------+             +-----------+
| header    |     | header    |             | header    |
+-----------+ --> +-----------+ --> ... --> +-----------+ 
| Body/Data |     | Body/Data |             | Body/Data |
+-----------+     +-----------+             +-----------+
```

A single element inside the `Blockchain` to hold some encrypted data is called a `block`.

Each `block` usually includes `header` and `body` which is the meaningful `data` of a bunch
of `transaction`.

Each `block` has the previous `block` hash value and point to its parent, so they can link
together become a chain, that's why we call it `Blockchain`.

## Why `Blockchain` is so special

- `Blockchain` use a P2P (peer-to-peer) network to eliminate a number of risks that come with 
data being held centrally. Every computer/hardware as a `node` persists the entire copy of 
the `Blockchain` which means all blockchain data won't be disappeared by losing any of `node`.
That's why it calls `Decentralized`.

- Each `block` is unalterable/immutable, so the entire `Blockchain` also become unalterable.
Nobody can modify the data inside the `block` after the `block` has been generated and attached
back to the `Blockchain`.  As all data are immutable, so everything can trust the data once, no 
need to worry about it's `fake`. It makes all business data become truly transparent.

## Is that `Blockchain` is undestroyable?

....mmh, from the design theory, should be YES as soon as the Internet still exists or any
computer (node) still can power on?:)

</br>


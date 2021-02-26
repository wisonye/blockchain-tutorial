# More about `Blockchain`

### `Blockchain` can have different types:

- Public Blockchain

    Everybody can access the `Blockchain` witout any restriction. Anyone can make `transaction`
    that `Blockchain`.

- Private Blockchain:

    On one can join unless invited by the `Blockchain` network administrator. Making a `transaction` 
    will be under some sort of restrictions.

### How to control who and when can create a new `Block`

That's talking about the consensus mechanism. 

As everyone has the ability to generate a new block with a bunch of transaction data and attach it back
to the main chain, so how to make sure that it's fair and efficient to generate a block and all users 
are finally in the same state becomes a problem.

There is two best-known consensus mechanism applies to the exists `blockchain`:

- Proof of Stake (PoS)

    The creator of the next block is chosen via various combinations of random selection and wealth or age 
    (i.e., the stake).  No need to do a heavy computation (time and electricity consuming) before you can 
    create the new block.

    [Here](https://en.wikipedia.org/wiki/Proof_of_stake) is the detil.

- Proof of Work (PoW)

    For creating the new block, you have to do a very heavy computation and get the right result. The best 
    case is `mining` in the `bitcoin` blockchain.
    
    The block creator needs to solve computationally intensive puzzles to validate transactions and create 
    new blocks. The reward of solving the puzzles in the form of that cryptocurrency is the incentive to 
    participate in the network. The PoW mechanism requires a vast amount of computing resources, which 
    consume a significant amount of electricity. 
    

    [Here](https://en.wikipedia.org/wiki/Proof_of_work) is the detil.


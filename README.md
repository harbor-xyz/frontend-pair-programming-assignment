# Harbor Frontend Pair Programming Assignment

Welcome to the Harbor frontend pair programming assignment.

The code in this assignment is broken. It is your job to figure out why.

## Reproducing the Bug

To reproduce the error -

1. After running `yarn`
2. In a terminal window, run `npx hardhat node --no-deploy`
3. In another terminal window, run `npx hardhat deploy --network localhost`

You should see this error -

```
HardhatError: HH700: Artifact for contract "Greeter" not found.
```

## Pre-requisite Knowledge

1. Everything in the `deploy` folder will get executed in alphabetical order.
2. An `artifact` is what is needed to deploy a smart contract onto a blockchain. It is a collection of folders, but ultimately boils down to a json object that has the necessary bytecode.
3. The bug is _not_ in the `deploy` folder.

## What we are looking for

1. What is your thought process when finding this bug? Is it systematic? Is it clear? Can you explain it?
2. How deep are you willing to go in order to find the solution?

If you get the bug (and the fix) - fantastic! However, we care a lot more about your thought process.

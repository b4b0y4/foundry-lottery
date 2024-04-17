# Provably Random Raffle Contracts

contract address: `0xD62406D2e5f7CaCeBEBDDE7b58Bef28614583B1e`

## About

This code is to create a random smart contract lottery.

## What we want it to do?

1. Users can enter by paying for a ticket
   1. The ticket fees are going to go to the winner during the draw
2. After X period of time, the lottery will automatically draw a winner
   1. This will be done programatically
3. Using Chainlink VRF and chainlink Automation
   1. Chainlink VRF -> Randomness
   2. chainlink Automation -> time based trigger


## Tests

1. Write some deply scripts
2. Write our tests
   1. work on a local chain
   2. Forked Testnet
   3. Forked Mainnet
# Blockchain Transaction Lifecycle

This document describes the high-level lifecycle of a blockchain transaction,
from the moment a user creates it to when it becomes part of the blockchain.

## Transaction Creation
A user creates a transaction using a wallet or application.
The transaction specifies details such as the sender, recipient, and intended action.

## Signing
The transaction is signed by the user’s wallet.
This signature proves that the transaction was authorized by the sender.

## Broadcast
The signed transaction is broadcast to the blockchain network.
Nodes that receive the transaction share it with other nodes.

## Inclusion in a Block
A block producer includes the transaction in a block.
Once the block is added to the blockchain, the transaction is considered confirmed.

## State Update
As part of block processing, the blockchain updates its state.
Balances and other contract data reflect the effects of the transaction.

## Result
After confirmation, applications and users can observe the transaction outcome

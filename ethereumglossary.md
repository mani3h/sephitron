## 51% Attack

A type of attack on a decentralized network where a group gains control of the majority of the nodes. This would allow them to defraud the blockchain by reversing transactions and double spending ether and other tokens.

## account 

An object containing an address, balance, nonce and optional storage and code. An account can be a contract account or an externally owned account (EOA).

## address

Most generally, this represents EOA or contract that can receive (destination address) or send (source address) transactions on the blockchain.More specifically, it is the rightmost 160 bits of a Keccak hash of an ECDSA public key. 

## application binary interface (ABI)

The standard way to interact with contracts in the Ethereum ecosystem, both from outside the blockchain and for contract-to-contract interactions.

## application programming interface

An application programming interface (API) is a set of definitions for how to use a piece of software. An API sits between an application and a web browser, and facilitates the transfer of data between them.

## assert

In solidity, assert(false) compiles to 0xfe, an invalid opcode, which uses up all remaining gas and reverts all changes.When an assert() statement fails, something very wrong and unexpected is happening and you will need to fix your code. You should use assert() to avoid conditions that should never,ever occur.

## attestation

A validator vote for a Beacon chain or shard block. Validators must attest to blocks, signaling that they agree with the state proposed by the block.

## Beacon Chain

An Eth2 upgrade that will become the coordinator for the Ethereum network. It introduces proof-of-stake and validators to Ethereum. It will eventually be merged with Mainnet.

## big-endian

A positional number representation where the most significant digit is first in the memory. The opposite of little-endian, where the least significant digit is first.

## block

A collection of required information (a block header) about the comprised transactions, and a set of other block headers known as ommers. Blocks are added to the Ethereum network by miners.

## blockchain

In Ethereum, a sequence of blocks validated by the proof-of-work system, each linking to its predecessor all the way to the genesis block.There is no block size limit,it instead uses varying gas limits.

## bytecode
An abstract instruction set designed for effiecient execution by a software interpreter or a virtual machine. Unlike human-readable source code, bytecode is expressed in numeric format.

## Byzantium fork

The first two hard forks for the Metrpolis development stage. It included EIP-649 Metropolis Difficulty Bomb Delay and Block Reward Reduction, where the Ice Age was deleayed by 1 year and the block reward was reduced from 5 to 3 ether.

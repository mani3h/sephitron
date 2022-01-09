## 51% Attack

A type of attack on a decentralized network where a group gains control of the majority of the nodes. This would allow them to defraud the blockchain by reversing transactions and double spending ether and other tokens.

## account 

An object containing an address, balance, nonce and optional storage and code. An account can be a contract account or an externally owned account (EOA).

## address

Most generally, this represents EOA or contract that can receive (destination address) or send (source address) transactions on the blockchain.More specifically, it is the rightmost 160 bits of a Keccak hash of an ECDSA public key. 

## application binary interface (ABI)

The standard way to interact with contracts in the Ethereum ecosystem, both form outside the blockchain and for contract-to-contract interactions.

## application programming interface

An application programming interface (API) is a set of definitions for how to use a piece of software. An API sits between an application and a web browser, and facilitates the transfer of data between them.

## assert

In solidity, assert(false) compiles to 0xfe, an invalid opcode, which uses up all remaining gas and reverts all changes.When an assert() statement fails, something very wrong and unexpected is happening and you will need to fix your code. You should use assert() to avoid conditions that should never,ever occur.

## attestation

A validator vote for a Beacon chain or shard block. Validators must attest to blocks, signaling that they agree with the state proposed by the block.


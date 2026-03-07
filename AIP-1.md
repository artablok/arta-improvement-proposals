# AIP-1: ART20 Token Standard

Author: Arta Blockchain
Status: Draft
Type: Standard
Created: 2026

## Abstract
ART20 defines the standard interface for fungible tokens on the Arta Blockchain.

## Motivation
A common token standard allows wallets, exchanges, and applications to interact with tokens in a predictable way.

## Specification
Required functions:

- totalSupply()
- balanceOf(address)
- transfer(address,uint256)
- approve(address,uint256)
- transferFrom(address,uint256)

## Compatibility
ART20 is designed to be compatible with ERC20-based tooling.
## Security Considerations

Implementations of ART20 should follow secure smart contract development practices.

Developers should ensure protection against common vulnerabilities such as:

- integer overflow or underflow
- reentrancy
- improper access control

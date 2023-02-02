# Awesome Ethereum (Blockchain) - What's News?


Weekly ethereum improvement proposal (eip) updates.


Note: For weekly solidity (contract) programming "dev stuff"
updates - see [**NEWS »**](NEWS.md)




## Week 04/2023 - Monday, January 22th to Sunday, January 29th


- [ERC6366](https://github.com/ethereum/EIPs/pull/6366/files): Permission token
  - Description: A new token that held the permission of an address in an ecosystem
  - Abstract: This EIP offers an alternative to Access Control Lists (ACLs) for granting authorization and enhancing security. Each permission is represented by a single bit in `uint256` from which we can defined up to `256` permissions and `2²⁵⁶` roles. This approach use bitwise operator and bitmask to determine the access right which is much more efficient and flexible than `string` comparison or `keccak()`. We are able to specify the importance of permission based on the bit order.
- [ERC6372](https://eips.ethereum.org/EIPS/eip-6372): Contract clock
  - Description: An interface for exposing a contract's clock value and details
  - Abstract: Many contracts rely on some clock for enforcing delays and storing historical data. While some contracts rely on block numbers, others use timestamps. There is currently no easy way to discover which time-tracking function a contract internally uses. This EIP proposes to standardize an interface for contracts to expose their internal clock and thus improve composability and interoperability.
- [ERC6381](https://github.com/ethereum/EIPs/pull/6381/files): Emotable extension for non-fungible tokens (NFT)s
  - Description: An interface for Non-Fungible Tokens extension allowing for reacting to them using Unicode emojis.
  - Abstract: The Emotable Extension for Non-Fungible Tokens standard extends EIP-721 by allowing NFTs to be emoted at. This proposal introduces the ability to react to NFTs using Unicode standardized emoji.
- [EIP6384](https://github.com/ethereum/EIPs/pull/6384/files): Humanly readable offline signatures
  - Description: A method for retrieving a human-readable description of EIP-712 typed and structured data.
  - Abstract: This EIP introduces the `evalEIP712Buffer` function, which takes an EIP-712 buffer and returns a human-readable text description.



## Week 03/2023 - Monday, January 16th to Sunday, January 21st


- [ERC6299](https://github.com/ethereum/EIPs/pull/6299/files): Lockable tokens
- [ERC6315](https://github.com/ethereum/EIPs/pull/6315/files): ERC2771 Account Abstraction
- [ERC6327](https://github.com/ethereum/EIPs/pull/6327/files): Elastic signature
- [ERC6353](https://github.com/ethereum/EIPs/pull/6353/files): Charity token
- [ERC6357](https://github.com/ethereum/EIPs/pull/6357/files): Single-contract Multicall
- [ERC6358](https://github.com/ethereum/EIPs/pull/6358/files): Omniverse DLT


## Week 02/2023 - Monday, January 9th to Sunday, January 15th

- [ERC6150](https://github.com/keeganlee/EIPs/blob/80571ca99550c576c807a5ba50ccf25e27f9f21e/EIPS/eip-6150.md): Hierarchical non-fungible tokens (NFT)s



## Week 01/2023 - Monday, January 2nd to Sunday, January 8th


- [EIP6212](https://github.com/ethereum/EIPs/pull/6260/files): Buyable non-fungible tokens (NFTs) on-chain and royalties
  - Description: Allowing tokens to be buyable and enforce royalties directly on-Chain
- [EIP6268](https://github.com/ethereum/EIPs/pull/6268/files): Non transferability indicator for ERC1155
  - Description: An extension of EIP-1155 for indicating the transferability of the token.
- [EIP6269](https://github.com/ethereum/EIPs/pull/6269/files): Full EVM equivalence
  - Description: Canonicalise the definition of Full EVM Equivalence



## Week 52/2022 - Monday, December 26th to Sunday, January 1st 2023


- [EIP6220](https://github.com/ethereum/EIPs/pull/6220/files): Composable NFTs utilizing equipable parts
- [EIP6224](https://github.com/ethereum/EIPs/pull/6224/files): Contracts registry the dependency injector
- [EIP6228](https://github.com/ethereum/EIPs/pull/6228/files): Extreme ЕRС20, meta-transaction token (MTT)
- [EIP6229](https://github.com/ethereum/EIPs/pull/6229/files): Tokenized vaults with lock-in period
- [EIP6239](https://github.com/ethereum/EIPs/pull/6239/files): Semantic soulbound tokens



## Sources

Thanks to the Week in Ethereum - EIPs/Standards weekly news updates.


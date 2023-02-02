# Awesome Solidity - What's News?


<!--
https://weekinethereumnews.com/week-in-ethereum-news-january-28-2023/
-->

## Week 04/2023 - Monday, January 22th to Sunday, January 29th

EIPs/Standards
- [ERC6366](https://github.com/ethereum/EIPs/pull/6366/files): Permission token
- [ERC6372](https://eips.ethereum.org/EIPS/eip-6372): Contract clock
- [ERC6381](https://github.com/ethereum/EIPs/pull/6381/files): Emotable extension for non-fungible tokens (NFT)s
- [EIP6384](https://github.com/ethereum/EIPs/pull/6384/files): Humanly readable offline signatures


Dev Stuff

- Foundry:
  - ChugSplash [Foundry](https://github.com/chugsplash/chugsplash-foundry#readme): deploy & manage upgradeable contracts, upgrade OpenZeppelin Transparent proxies, supports mainnet & Optimism
  - [Deal cheat code](https://twitter.com/paulrberg/status/1619059764180434944) mints ERC20 tokens in tests
- [EVM call stipend](https://twitter.com/wadealexc/status/1619030019803848704) (2300 gas) explainer
- OpenZeppelin [proposal to mitigate ERC4626 inflation attacks](https://ethereum-magicians.org/t/address-eip-4626-inflation-attacks-with-virtual-shares-and-assets/12677) with virtual assets & shares
- [Sparse-arr-lib](https://github.com/clabby/sparse-arr-lib#readme): Solidity library for sparse arrays, work in progress
- [Optimizing using Yul](https://medium.com/@MarqyMarq/using-yul-to-optimize-gas-costs-b4feccdb5172) via example rock, paper & scissors contracts
- Samczsun's [signature database](https://twitter.com/samczsun/status/1618161664624594945): exportable, add to canonical list via GitHub
- [Clipshot](https://clipshot.xyz/): ERC1155 token holder snapshots as CSV
- [Hydralisk](https://github.com/paulpierre/hydralisk#readme): Python CLI for bulk wallet creation
- [Walk through of building bear traps](https://paulbrower.codes/posts/bear-traps-in-the-dark-forest/) for MEV bot front-runners
- DamnVulnerableDefi [ABI smuggling solution](https://medium.com/@mattaereal/damnvulnerabledefi-abi-smuggling-challenge-walkthrough-plus-infographic-7098855d49a)
- [Uniswap v3 math](https://uniswap.org/blog/uniswap-v3-math-primer) explainer



<!--
https://weekinethereumnews.com/week-in-ethereum-news-january-21-2023/
-->

## Week 03/2023 - Monday, January 16th to Sunday, January 21st

EIPs/Standards

- [ERC6299](https://github.com/ethereum/EIPs/pull/6299/files): Lockable tokens
- [ERC6315](https://github.com/ethereum/EIPs/pull/6315/files): ERC2771 Account Abstraction
- [ERC6327](https://github.com/ethereum/EIPs/pull/6327/files): Elastic signature
- [ERC6353](https://github.com/ethereum/EIPs/pull/6353/files): Charity token
- [ERC6357](https://github.com/ethereum/EIPs/pull/6357/files): Single-contract Multicall
- [ERC6358](https://github.com/ethereum/EIPs/pull/6358/files): Omniverse DLT

Dev Stuff

- Foundry:
  - Foundry [best practices](https://twitter.com/msolomon44/status/1616072891820539904)
  - forge-std [v1.3.0](https://github.com/foundry-rs/forge-std/releases/tag/v1.3.0): InvariantTest helper contract, Multicall3 interface & getTokenBalances helper, StdChains chain alias, parseJson & assumePayable cheat codes and decimal assertions
  - Invariant testing: [example](https://github.com/lucas-manuel/invariant-example/#readme) repo to experiment, also see Maple Finance invariant tests
  - [forge doc](https://twitter.com/r_krasiuk/status/1615444642195202055): documentation generator using natspec, outputs markdown
- Solidity [preview of user-defined operators](https://forum.soliditylang.org/t/feature-preview-user-defined-operators/1435) in upcoming v0.8.18
- Fe language [bountiful round 2](https://blog.fe-lang.org/posts/bountiful-round-2/) bug bounty contest
- Beginners guide to [Yul (intermediate language)](https://medium.com/@markjonathas/beginners-guide-to-yul-12a0a18095ef)
- [Guide to contract decompilation](https://jbecker.dev/research/diving-into-decompilation/), as implemented by heimdall-rs (decompiler)
- [Solidity-merkle-trees](https://github.com/polytope-labs/solidity-merkle-trees#readme): Solidity library to verify multi-proofs of Merkle trees
- [ERC5267 demo website](https://eip5267.vercel.app/) to retrieve ERC712 domain
- [The Graph](https://twitter.com/graphprotocol/status/1615772852745027594) adds support for Arbitrum & Optimism


<!--
https://weekinethereumnews.com/week-in-ethereum-news-january-14-2023.html/
-->


## Week 02/2023 - Monday, January 9th to Sunday, January 15th

EIPs/Standards

- [ERC6150](https://github.com/keeganlee/EIPs/blob/80571ca99550c576c807a5ba50ccf25e27f9f21e/EIPS/eip-6150.md): Hierarchical non-fungible tokens (NFT)s

Dev Stuff

- Hardhat and Foundry plugin [v1](https://github.com/NomicFoundation/hardhat/releases/tag/%40nomicfoundation/hardhat-foundry%401.0.0)
- Foundry toolchain now [caches RPC calls in CI flows](https://github.com/foundry-rs/foundry-toolchain)
- If you've deployed a contract to Mainnet, Goerli, or Sepolia before Nov 15, 2022, you can [claim 10 goerli + 10 sepolia eth](https://grabteeth.xyz/)
- [Chugsplash](https://twitter.com/ChugSplash_io/status/1611598563301007360): tool to deploy and upgrade smart contracts securely
- [Turborepo starter kit](https://github.com/alexallah/ethereum-healthmon): NextJS, WAGMI, Ethers, Tailwind, Hardhat, Typechain
- Paul Berg on solving [stack too deep](https://twitter.com/PaulRBerg/status/1612043506545033218)
- Now over [225 contracts to fork and easily deploy](https://www.cookbook.dev/) on Cookbook.dev
- [Node health monitoring](https://github.com/alexallah/ethereum-healthmon) tool




## Week 01/2023 - Monday, January 2nd to Sunday, January 8th


## Week 52/2022 - Monday, December 26th to Sunday, January 1st 2023


## Week 51/2022 - Monday, December 19th to Sunday, December 25th


## Week 50/2022 - Monday, December 12th to Sunday, December 18th


## Week 49/2022 - Monday, December 5th to Sunday, December 11th


## Week 48/2022 - Monday, November 28th to Sunday, December 4th


## Week 47/2022 - Monday, November 21st to Sunday, November 27th


## Week 46/2022 - Monday, November 14th to Sunday, November 20th


## Week 45/2022 -  Monday, November 7th to Sunday, November 13rd


## Week 44/2022 - Monday, October 31st to Sunday, November 6th


## Week 43/2022 - Monday, October 24th to Sunday, October 30th


## Week 42/2022 - Monday, October 17th to Sunday, October 23rd







## Sources

Thanks to the Week in Ethereum - Stuff For (Solidity) Developers
weekly news updates.




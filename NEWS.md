# Awesome Solidity - What's News?

Weekly solidity (contract) programming "dev stuff" updates.


Bonus: For weekly ethereum improvement proposal (eip) updates - see [**ETHEREUM »**](ETHEREUM.md)


<!--
https://weekinethereumnews.com/week-in-ethereum-news-february-4-2023/
-->

## Week 05/2023 - Monday, January 30th to Sunday, February 5th


- Solidity [v0.8.18](https://blog.soliditylang.org/2023/02/01/solidity-0.8.18-release-announcement/): Paris default EVM version, adds block.prevrandao & deprecates block.difficulty, adds flag to not append CBOR metadata, deprecates selfdestruct and improves bytecode generation from Yul
- [Codeslaw](https://www.codeslaw.app/): search verified contracts
- [ERC721X](https://github.com/indeliblelabs/contracts/blob/main/src/contracts/extensions/ERC721X.sol): ERC721 extension to auto expire transfer approvals after 30 days
- Guide [to libraries in Solidity](https://medium.com/@MarqyMarq/deep-dive-into-solidity-libraries-e9bd7f9061fb)
- Ape [v0.6.0](https://twitter.com/apeframework/status/1620843786497847296) (Python contract framework): beta support for Multicall3, adds per-function encode/decode methods and run scripts in nested subdirectories
- MatchboxDAO's 0xMonaco race entries: [first](https://github.com/marktoda/monaco), [second](https://typefully.com/gretzke/DTU1xJn), [third](https://twitter.com/NotDeGhost/status/1619845952998887424) & [disqualified bug exploiter](https://twitter.com/zellic_io/status/1620844495226179586)
- Secureum RACE #14: [8 question Solidity quiz & answers](https://ventral.digital/posts/2023/1/30/race-14-of-the-secureum-bootcamp-epoch-infinity)
- Capture the Flag (CTF) solutions using Ape & Vyper: [Ethernaut](https://github.com/0xJCN/Ethernaut-CTF), [Damn vulnerable DeFi](https://github.com/0xJCN/Damn-Vulnerable-DeFi-V3-CTF) & [EthernautDAO](https://github.com/0xJCN/EthernautDAO-Challenges)
- [Guide to using SMTChecker](https://www.truscova.com/blog_article_5.php) with Hardhat
- [Halmos](https://github.com/a16z/halmos#readme): symbolic testing reusing Foundry tests for formal verification
- [Wagmi CLI](https://twitter.com/wagmi_sh/status/1620097176738357248) (React hooks): generate code, connect to Foundry/Hardhat projects & create plugins
- [Universal bridge](https://github.com/ZeframLou/universal-bridge#readme): common interface to send a message to a supported network using official bridges
- [zkLLVM compiler](https://blog.nil.foundation/2023/02/02/circuit-compiler.html): circuit compiler for languages such as C/C++
- [Spartan-ecdsa](https://personaelabs.org/posts/spartan-ecdsa/): verify secp256k1 ECDSA signatures in zk, proofs in browser in 5 seconds
- [In-browser recursive proving & verification](https://twitter.com/nibnalin/status/1621059453570412544) added to Nova & Nova Scotia



<!--
https://weekinethereumnews.com/week-in-ethereum-news-january-28-2023/
-->

## Week 04/2023 - Monday, January 22th to Sunday, January 29th


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
https://weekinethereumnews.com/week-in-ethereum-news-january-14-2023/
-->


## Week 02/2023 - Monday, January 9th to Sunday, January 15th


- Hardhat and Foundry plugin [v1](https://github.com/NomicFoundation/hardhat/releases/tag/%40nomicfoundation/hardhat-foundry%401.0.0)
- Foundry toolchain now [caches RPC calls in CI flows](https://github.com/foundry-rs/foundry-toolchain)
- If you've deployed a contract to Mainnet, Goerli, or Sepolia before Nov 15, 2022, you can [claim 10 goerli + 10 sepolia eth](https://grabteeth.xyz/)
- [Chugsplash](https://twitter.com/ChugSplash_io/status/1611598563301007360): tool to deploy and upgrade smart contracts securely
- [Turborepo starter kit](https://github.com/alexallah/ethereum-healthmon): NextJS, WAGMI, Ethers, Tailwind, Hardhat, Typechain
- Paul Berg on solving [stack too deep](https://twitter.com/PaulRBerg/status/1612043506545033218)
- Now over [225 contracts to fork and easily deploy](https://www.cookbook.dev/) on Cookbook.dev
- [Node health monitoring](https://github.com/alexallah/ethereum-healthmon) tool



<!--
https://weekinethereumnews.com/week-in-ethereum-news-january-7-2023/
 -->

## Week 01/2023 - Monday, January 2nd to Sunday, January 8th


- [Solidity compiler appends encoded IPFS hash of contract metadata](https://mirror.xyz/joenrv.eth/DdbK6GR-CkeYxHoU8sKl0AFYbGeQwZcvCM5Qvzipr0g) to bytecode for verification
- Guide to [using PrevRandao](https://soliditydeveloper.com/prevrandao)
- Paul Berg: [Solidity supports functions as parameters](https://twitter.com/paulrberg/status/1609917508223475712), useful in testing e.g. [Seaport](https://github.com/ProjectOpenSea/seaport/blob/1.2/test/foundry/FulfillOrderTest.t.sol#L64-L71)
- [EVM quirks](https://twitter.com/jtriley_eth/status/1609216690147020803) and how they are handled in Solidity & Vyper
- [Setup remixd](https://jamesbachini.com/remixd-tutorial/) to use Remix with local filesystem
- Capture the Flag (CTFs):
  - [Mr Steal Yo Crypto](https://mrstealyocrypto.xyz/), uses Hardhat
  - Making of [HappyNewYear CTF](https://mirror.xyz/vicnaum.eth/reNCgNs7e0rDNx7h8Yt0a9xbS7wFss4950Dl8tYr2kY)
  - Damn Vulnerable DeFi [backdoor solution](https://stermi.xyz/blog/damn-vulnerable-defi-challenge-11-solution-backdoor)
  - [Shop puzzle](https://twitter.com/0xCygaar/status/1610114831000170496) & solution
  - Secureum bootcamp [race-13 quiz solution](https://ventral.digital/posts/2023/1/3/race-13-of-the-secureum-bootcamp-epoch)
- [TurboETH](https://twitter.com/KamesGeraghty/status/1609872647965261825): dapp build system, app template, ERC20 & ERC721 components & hooks, beta
- Use TrueBlocks to [find all contracts created by an address](https://tjayrush.medium.com/recipe-factories-ce78fa4c5f5b)
- [Guide to equivalence checking](https://www.truscova.com/blog_article_2.php) Solidity functionality with a reference implementation using Z3 theorem prover
- [UniRep protocol](https://mirror.xyz/privacy-scaling-explorations.eth/FCVVfy-TQ6R7_wavKj1lCr5dd1zqRvwjnDOYRM5NtsE): private & non-repudiable reputation system


<!--
https://weekinethereumnews.com/week-in-ethereum-news-december-31-2022/
-->

## Week 52/2022 - Monday, December 26th to Sunday, January 1st 2023


- Foundry [Chisel](https://github.com/foundry-rs/foundry/tree/master/chisel#readme): Solidity REPL
- [Etherscan contract verification API](https://twitter.com/etherscan/status/1608796718677753858) adds failure message
- [Uniswap poor oracle](https://github.com/timeless-fi/uniswap-poor-oracle#readme): flash loan proof Uniswap v3 price-out-of-range oracle
- [Norswap on ERC2535 (Diamonds)](https://twitter.com/norswap/status/1607425088491753472): only use to circumvent contract size limitations
- [Fallback](https://github.com/nathanhleung/fallback#readme): create web apps in Solidity, proof of concept
- [Huff-immutables](https://github.com/vicnaum/huff-immutables#readme): constructor-initialized immutables in Huff
- VSCode Solidity Inspector [v0.0.3](https://github.com/PraneshASP/vscode-solidity-inspector/releases/tag/v0.0.3): view contract storage layout
- Understanding [EVM instruction boundaries](https://mirror.xyz/vicnaum.eth/zJX21EV6bjrPcL_8fnI-0zoChvBw-ZscbL7S7inroro) plus an [EVM regex decompiler](https://gist.github.com/vicnaum/492d9ccfb66dc0f50b1fd8f99239f6a7) (Perl compatible regex)
- [Noble-curves](https://github.com/paulmillr/noble-curves#readme): elliptic curves in JavaScript, zero-dependencies
- Wagmi (React hooks) [v0.10.0](https://github.com/wagmi-dev/wagmi/releases/tag/wagmi%400.10.0): WalletConnect v2 support and useWatchPendingTransactions hook
- [ENS Profile API](https://blog.indexing.co/posts/6xGR3GSQ2lY5Lpo0WRWJlqMutSt241RxdOsDg_ABXRo): access via GraphQL




<!--
https://weekinethereumnews.com/week-in-ethereum-news-december-24-2022/
-->

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




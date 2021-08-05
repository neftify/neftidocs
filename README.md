# Getting Started

The Neftify protocol enables the seamless exchange of the time value between ERC-20 and ERC-721 tokens on Ethereum. It opens up new avenues for more sophisticated functionality between these two asset markets beyond outright swaps. The protocol is intended to be fully decentralized, prioritizing security, censorship resistance, and community control over the exclusive benefits that come with traditional centralization; Neftify is a public good. 

For the first version of the protocol, the central team will maintain control over the protocol until it is able to develop it into a viable DAO. After v1, the team will launch v2 and hand over control of the protocol to the community following Jesse Walden’s [Progressive Decentralization](https://a16z.com/2020/01/09/progressive-decentralization-crypto-product-management/) playbook. 

Neftify’s technical docs can be found [here](https://docs.neftify.com). They serve as a project overview for how Neftify works, how to use it, and how to build on top of it. These docs are actively maintained and updates will be added on an ongoing basis.

# How It Works
Neftify’s main contract, neftiswap, is the primary entry point for all interactions that take place with the protocol. It automates the asset swap that takes place when a user puts up collateral to borrow an NFT by supplying that collateral to an external interest rate protocol. For now, the collateral is deposited individually as opposed to being pooled together.

![ERC20 to ERC721 swap](assets/erc20-erc721.png)

Neftify utilizes a collateralization model in order to adjust the amount of collateral required to borrow an NFT. The model is a function of time that rewards longer lock ups by decreasing the amount of collateral required to borrow. This is similar to the constant product formula used by liquidity pools to offset non-unit token ratios, except it is used to maintain constancy between the ratio of time to collateral.

It's important to note that the lending party sets the collateral requirements for borrowing, as well as the maximum lending period; the collateralization model is only used to extrapolate how much collateral is required for lending periods that are shorter than the maximum allowed.

# Resources

* [Website](https://neftify.com)
* [Github](https://github.com/neftify)
* [Twitter](https://twitter.com/neftify)
* [Reddit]()
* [Discord]()
* [Email](mailto:neftifymsg@gmail.com?Subject=Contact%20Neftify)
* [Docs](https://docs.neftify.com)
* [Whitepaper](https://neftify.com/neftify-whitepaper.pdf)

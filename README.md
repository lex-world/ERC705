### Simple Summary
A standard interface for Auctionable Non-Fungible Assets (ANFA).
`NFT = Utility + Ownership History + Future Value + Liquidity Premium`
`ANFA = Utility + Ownership History + Future Value + Liquidity Premium + ` **Auction**

### Abstract
The following standard allows the use of the standard API for Auctionable Non-Fungible Assets(ANFA) within smart contracts. This standard provides the basic functionality of tracking, transfer, and asset auction.

We have considered the terms of use of Auctionable Non-Fungible Assets(ANFA) and referrals to third party brokers / wallets / auctioneers (“operators”). Commercial Goods can represent ownership over digital or tangible assets. We have considered a wide range of goods, and we know you will dream of many more:

Virtual collectables - Unique Images, Game Cards
Auctionable Non-Fungible Assets(ANFA) are distinguishable and you must track the ownership of each one separately.

### Motivation
A standard interface allows wallet/broker/auction applications to work with any ANFA on Ethereum. We provide for simple ERC-705 smart contracts as well as contracts that track an arbitrarily large number of ANFA. Additional applications are discussed below.

This standard is inspired by the ERC-721 token standard. EIP-721 is insufficient for auctioning NFTs because each asset is distinct (non-fungible) and every unique deserves to be positively populated on price rather being constant asset.
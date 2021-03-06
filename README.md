# 100DaysOfBlockchain
I have taken up the **#100DaysOfBlockchain** challenge where I will commit to code or study Blockchain for minimum of 1 hour for the next 100 Days.

I'll be tweeting my progress with **#100DaysOfBlockchain** hashtag on my Twitter account [@bhalla98](https://twitter.com/bhalla98)

## Goals
I will be Learning and Practicing below technologies/protocols.
- Cryptocurrencies and Algorithmns
- Cryptography behind Blockchain
- Cryptoeconomics 
- Bitcoin programming Basics
- Ethereum DAPPs
- Hyperledger Fabric, Hyperledger Composer
- Blockchain Use Cases in Enterprise
- Solidity programming
- Javascript, web3.js, (Other frontend tools for DApp Development)
- Exploring some of the other available ICOs options:
  - Ethereum, Waves, NXT, NEM, EOS, Stellar, LoomNetwork
- Exploring new Blockchains:
  - Corda, Ripple, Quorum, BigChainDB
- Sidechains
- Non Fungible Token Applications

## Completed Courses
[IBM Blockchain Foundation for Developers](https://www.coursera.org/learn/ibm-blockchain-essentials-for-developers)

[Blockchain Architecture Design and Use Cases](https://onlinecourses.nptel.ac.in/noc18_cs47/preview)

## Ongoing Courses
[Ethereum and Solidity: The Complete Developer's Guide](https://www.udemy.com/ethereum-and-solidity-the-complete-developers-guide/)

[Bitcoin and Cryptocurrency Technologies](https://www.coursera.org/learn/cryptocurrency)

## Log
### Day 99-100: [0x + Coinlist Hackathon 2019](https://coinlist.co/build/0x) 

![Screenshot](https://github.com/bhalla98/100DaysOfBlockchain/blob/master/ETHOptionsLOGO.jpg)

**Progress:** 
- Worked on ETHOptions and received an Honorable Mention and was one of [0x](https://0x.org) Core Team’s favorite projects

**Project Summary:**
- ETHOptions is a decentralized ERC20 Options trading platform to hedge against your crypto investments by leveraging profits and managing risks

**Description:** 
- An option is a contract that gives an investor the right — but not the obligation — to buy/sell a Crypto Asset (ERC20 Token) at a certain price within a certain period of time. Options Sellers receive ERC20 Option Tokens, generated against their deposited BaseTokens in Escrow, after setting the strike price & expiry time. The Option Seller then creates orders to our 0x Options Relayer to exchange the ERC20 Options Tokens against a Premium (fraction of Strike Price), paid by the Option Buyer in terms of QuoteToken. Exchange of ERC20 Option Tokens & Premium is done by 0x Exchange. The buyer can now choose to exercise his Option Tokens within the expiry time to purchase the locked BaseTokens at Strike Prices, in terms of QuoteTokens. Buyer can then sell BaseTokens in the market, thereby making a profit of (MarketPrice - StrikePrice) per locked BaseToken.

**Links:** 
- [ETHOptions](https://coinlist.co/build/0x/projects/54758bd0-4f06-4e1f-82a3-8cd302d2695c)
- [0x + Coinlist Hackathon Recap](https://blog.0xproject.com/0x-coinlist-hackathon-recap-e453b1195533)

### Day 98: Smartcontract Testing
#### Progress: 
#### 1. Smartcontract Best Practices - Consensys 
- [Smartcontract Best Practices](https://consensys.github.io/smart-contract-best-practices/general_philosophy/)

#### 2. Decentralized Application Security Project (DASP)
- [DASP-Top 10](https://dasp.co)

#### 3. Crowdsale Contract & Testing
- [How its made: Crowdsale Contract](https://medium.com/@VladimirTikhomirov/how-its-made-crowdsale-contract-1120b487cc4a)
- [Smartcontract Testing Guide](https://medium.com/ethereum-developers/the-ultimate-guide-to-test-your-smart-contract-ddc65fbb5ba5)
- [Testing Smartcontract with JS - 1](https://medium.com/@gus_tavo_guim/testing-your-smart-contracts-with-javascript-40d4edc2abed)
- [Testing Smartcontract with JS - 2](https://medium.com/@gus_tavo_guim/beautifying-your-smart-contract-tests-with-javascript-4d284efcb2e8)
- [Smart Contract Auditing: Human vs. Machine](https://blog.coinfabrik.com/smart-contract-auditing-human-vs-machine/)

#### 4. Smartcontract - Research Papers
- [YODA-Computationally Intensive Contracts (IIT-D)](https://arxiv.org/pdf/1811.03265.pdf)
- [Contract Vulnerabilities & Security Tools](https://brage.bibsys.no/xmlui/bitstream/handle/11250/2479191/18400_FULLTEXT.pdf?sequence=1)
- [SECURIFY-Practical Security Analysis of Contracts](https://arxiv.org/pdf/1806.01143.pdf)

### Day 97: Smart Contract Vulnerabilities
**Progress:** 
- Read about the Top 10 Smart contract vulnerabilities listed under **Decentralized Application Security Project (DASP)** of 2018

**Links:**
1. [Smart Contract Vulnerabilities](https://dasp.co)
2. [Open Source Licensing in Blockchain Projects](https://medium.com/@info_45047/open-source-licensing-and-its-trends-in-blockchain-b40e085c3749)

### Day 96: IPFS & Filecoin
**Progress:**
- P2P network, similar to BitTorrent
- Model encompasses : 
    - Database: for storage
    - Blockchain: decentralized, P2P storage system
    - Economics: incentives users to store(host) files in the network
    - Git: for Version history

#### How To Search Files?
- Centralized Internet uses “Location Based Addressing” (ie, IP addresses/domain names) to find files
- IPFS uses “Content Based Addressing” to find files :
    - Users ask network for file with certain hash
    - Users can verify the received file since they use **Hash Functions**
- IPFS removes duplication of files, since hash exists, creating files only once. Therefore, making network more **efficient**

#### How IPFS Stores Files?
- Files stores in **IPFS Objects**
- Each IPFS Object stores upto 256Kb (including links to other IPFS Objects)
- Bigger Files are split up & stored in multiple IPFS objects, & then a single empty IPFS Object stores links to all other IPFS Objects connecting the file

- Immutable Data store (once added, can’t be changed)

#### Versioning
- Creates new **commit object** every time a file is created/changed
- When a file is edited, new commit object created, links to :
    - Newly edited file
    - Previous Commit Object 
- Therefore, making version history of files possible to access

#### Limitations
- Keeping files available
- Nodes keep cache of downloaded files to share with other nodes for access
- But if those nodes hosting a specific file go offline, then file doesn’t exist on on IPFS

#### Solution
1. Incentivise nodes to store files
2. Proactively distribute files among nodes to ensure certain amount of copies always exist

- Filecoin, created on top of IPFS, uses above solutions to create a Decentralized Market for Storage
  - incentives nodes based on how long they host the file 
  - creates replicas of files to ensure availability of files at all times

**Links:**
1. [IPFS](https://ipfs.io)
2. [Filecoin](https://filecoin.io)

### Day 95: ICO Smart Contracts
**Progress: Researched on smart contracts of some of the successful ICO’s & Crowdsale Projects** 

#### 1. ICO SmartContracts
Ethereum smart contracts that have been used during successful ICOs.

- [Github](https://github.com/blockstarter/ico-contracts)

#### 2. Swarm Fund
Swarm brings unprecedented access to investors, and the infrastructure for security tokens and the future of investing.

- [Swarm Fund Github](https://github.com/swarmfund)

#### 3. Blocksquare - EFiat
eFIAT is a not-for-profit, fully transparent, publicly auditable protocol to migrate USD, EUR, JPY and other world currencies to the Ethereum blockchain - no banks, no escrow, no reserves, just code!

- [Blocksquare EFiat Github](https://github.com/blocksquare/eFIAT)

#### 4. AirSwap
AirSwap is a peer-to-peer trading network built on Ethereum. Our mission is to empower people through global, frictionless trade.

- [AirSwap Github](https://github.com/airswap)

#### 5. Lunyr
A decentralized world knowledge base where users earn rewards for contributing and peer reviewing

- [Lunyr Github](https://github.com/Lunyr)

#### 6. Harbor-RToken
Powering the Future of Crypto-Securities

- [Harbor RToken Github](https://github.com/harborhq/r-token)

#### 7. PlutusDEX
Make payments with your Plutus Debit Card and earn a reward on the Blockchain. With Plutus you don’t have to wait for merchants to accept Bitcoin.

- [PlutusDEX Github](https://github.com/PlutusIt/PlutusDEX)

#### 8. Sirin Labs Crowdsale
Launched Finney-Blockchain smartphone 

- [Sirin Labs Github](https://github.com/sirin-labs/crowdsale-smart-contract)

#### 9. Ubiatar PreSell Campaign
P2P Marketplace for Ubiatar Service

- [Ubiatar Github](https://github.com/Ubiatar/PreSellCampaign)

#### 10. Global REIT
Tokenized Real Estate 

- [Global REIT Github](https://github.com/globalreit/GREM)

#### 11. Agentmile Estate Token
The world's first decentralized commercial real estate marketplace.

- [Estate Token Github](https://github.com/AgentMile/estate-token)

#### 12. Profit Sharing Contract
- [Github Link](https://github.com/adamdossa/ProfitSharingContract)

#### 13. Crowdsale Contracts Github
- [Crowdsale Contracts Github](https://github.com/topics/crowdsale?o=desc&s=updated)

### Day 94: Tokenized Real Estate & Equity
**Progress:**
- Researched on Blockchain projects in Real Estate Industry & Tokenized Equity

#### 1. Harbor Platform
- Decentralized compliance protocol to standardize Issuance & Trading of crypto-securities on Blockchain
- Smart Contracts: 
	- **R-token:** Permissioned ERC20 Token, enables token transfers to occur iff approved by on-chain Regulator Service
 	- **Regulatory Service:** Depends on off-chain Trade Controller (Trade controller is Harbor in initial implementation)
		- **Trade Controller:** determines **participant-level permissions** & **token-level settings**  
 	- **Service Registry:** connects appropriate Regulator Service to R-token smartcontract

**Links:**
1. [Harbor](https://harbor.com)
2. [Harbor Whitepaper](https://harbor.com/rtokenwhitepaper.pdf)
3. [Harbor Github](https://github.com/harborhq/r-token)

#### 2. Abacus Protocol  
**Links:**
1. [Abacus Protocol](https://abacusprotocol.com)
2. [Abacus Protocol Whitepaper](https://github.com/abacusprotocol/whitepaper/blob/master/whitepaper.pdf)

#### 3. Brickblock 
**Links:**
1. [Brickblock](https://www.brickblock.io)
2. [Brickblock Whitepaper](https://github.com/brickblock-io/whitepaper-general)
3. [Brickblock Smart Contracts](https://github.com/brickblock-io/smart-contracts)

#### 4. Neufund
- Neufund is an equity fundraising platform on blockchain. It tokenizes real-world assets with legally enforceable security tokens.

**Links:**
1. [Neufund](https://neufund.org)
2. [Neufund-Whitepaper](https://neufund.org/cms_resources/whitepaper.pdf)
3. [Neufund-Github](https://github.com/Neufund)
4. [Economics of Entangled Tokens](https://blog.neufund.org/economics-of-entangled-tokens-9fc5b084e2d2)
5. [Simple Agreement of Future Tokens (SAFT)](https://medium.com/@argongroup/explaining-the-simple-agreement-for-future-tokens-framework-15d5e7543323)

### Day 93: Issuance of Tokens & Dividends via Smart Contract
**Progress:**  
#### 1. Issuance of tokens
**Links:**
1. [How to issue your own token on Ethereum in less than 20 minutes.](https://medium.com/bitfwd/how-to-issue-your-own-token-on-ethereum-in-less-than-20-minutes-ac1f8f022793)
2. [6 Steps to ERC20 Tokens and ICO Smart Contracts](https://medium.com/coinmonks/6-steps-to-erc20-tokens-and-ico-smart-contracts-e90523afafa1)
3. [How To Create Token and Initial Coin Offering Contracts Using Truffle + Zeppelin Solidity](https://blog.zeppelin.solutions/how-to-create-token-and-initial-coin-offering-contracts-using-truffle-openzeppelin-1b7a5dae99b6)

#### 2. Dividends via Smart Contract
- Dividend paying contracts distribute dividends to investors proportional to their token ownership

- Dividends should be paid out in proportion to token balances, instead of current balances. 
- Since current balances vary over time, using them could allow for the below attack :
    1. If Party A, affter claiming its share from the dividend transfers its tokens to Party B, Party B will now have that share in the dividend, and can claim that again. Leading to party A’s share being claimed twice 

**Problem**: Token’s total balance gets altered

**Smart Contract Limitation:** Distributing dividends to each investor is a Txn in itself. Each Txn costs gas and, hence, becomes very expensive. 


#### APPROACHES 
1. Etheroll Approach : Freeze token transfers during payment periods, ensuring token balances to be fixed. 

	Problem: Token trading is paused temporarily, not suitable for exchanges, irritating for users

2. E4Row Approach : Uses payrunID to stop accounts that are involved in token transfer after a payrun has begun for claiming their dividend

	Problem: May penalize accounts who transferred tokens during pay runs but weren’t trying to cheat 	the system 

3. ERC20 token : Dividends associated with each accounts can be in 3 states
    1. “Not yet credited” to account (ie, All new dividends owed to an account start with this state)
    2. “Credited, but not Transferred” (When account is part of Transfer/Withdrawal)
    3. “Transferred State” (When the account makes a withdrawal of its dividend)

- Contract uses 3 values to track state of Dividend Payment:
  -  `dividendPerToken` :  (Total Ether Collected) / (Total Token Supply); Constant value, doesn’t reduce with Withdrawals
  - `dividendBalanceOf` : maps account to amount of ether credited to it, but not transferred; Withdrawals reduce this amount
  - `dividendCreditedPerToken` : maps accounts to total amount of ether per token credited to it previously, ie, added to `dividendBalanceOf`

- Smart Contract handles token transfers by updating account’s `dividendBalanceOf` & `dividendCreditedPerToken`
- It accepts “Dividend Deposit” & “Per account Withdrawal” values

**Token Transfer Functions**
- Updates values associated to track dividends owed to an account
- Updates Sender's & Receiver's account balances

**Deposit Function**
- Accepts Ether to be distributed as Dividend
- Updates global `dividendPerToken`

**Withdrawal Function**
- Updates Dividend owed, & transfers it

**Links:**

1. [Different Approaches for Dividend payment contracts](https://medium.com/@adam.dossa/dividend-payment-contract-based-on-minimetoken-90e5ba7c85d5)
2. [Writing A Simple Dividend Token Contract](https://programtheblockchain.com/posts/2018/02/07/writing-a-simple-dividend-token-contract/)

### Day 92: 0x Protocol
**Progress:**
- Read about 0x Project. 0x is an open protocol that enables the peer-to-peer exchange of assets on the Ethereum blockchain.

**Thoughts:** 
- 0x solves lack of standardization, that leads to redundancy
    - User’s don’t wanna use 5 tokens for 5 different utilities being executed on their respective dapps
    - Parallel redundancy - DApps having parallel implementation on a similar type of smart contract )
- 0x protocol allows other smart contracts to programmatically execute trades on a single line of solidity code 
    - enables efficient functioning of smart contracts
    - enables interoperability among diff dapps and smart contracts
- Stable coins by users can be used to purchase ZRX that’ll fuel trades for other tokens that dapp uses

- Altering orders on chain on DEX, cost you gas. Hence, relayers handle order books off-chain, and settlements handles on-chain. 
- 0x protocol uses off-chain order relay and on-chain order settlements, 0x enables 2 types of orders 
    - 1. Point to Point Order
    - 2. Broadcast  Order
- Cryptographic signed orders are broadcasted off-chain. Interested counterparties inject 1/more orders on SC to execute trade trustlessly on-chain

#### POINT TO POINT: 
- used for OTC (over the counter sale ) exchange
- anyone can perform OTC exchanges
- Orders are fulfilled by specified Takers Addresses ONLY, ie, Traders will execute their own trades

#### BROADCAST: 
- Consists of Makers, Takers, Relayers
- Relayers: DEX, PARADEX, OPENRELAY, etc
- Anyone can fill an order, not just a specified address
- There’s txn fee structure to incentives Relayers for hosting order books
- Maker decides Maker fee, Taker fee for Relayers 

#### PROCESS: 
1. Relayer sets his fee recipient address and his fee schedule
2. Maker creates an order, setting FeeA & FeeB that satisfy Relayer’s fee schedule and his address, and signs the order w/ Maker’s private key
3. Maker transmits this signal order to relayer
4. Relayer receives order, validates the order for require fee & signature, then posts order to order book
5. Taker’s receive an updated version of Order Book, that includes Maker’s order
6. Taker has an option to fill Maker’s order by submitting to exchange contract on Ethereum Blockchain 

- Relayer’s have the power to accept/reject orders. Hence, if Maker really wants his order to be posted to a specific order book, they set MakerFee & TakerFee
- Taker has an option to fill/not fill the order. If they decide to fill, then they have to pay the set FeeB

#### ORDER BOOK:
- Centralized Ex. use a matching engine to fill market orders on behalf of users. Users have to trust the prices 
- But, in DEX, Relayers don’t execute orders on behalf, they just recommend prices to Takers, & Takers decide whether to sign/not sign the order and send it to the Blockchain 
- Contract stores a reference to previously Filled Orders to prevent an order being filled multiple times 
- Partial Orders can be executed by Taker by specifying argument called “valueFill” when calling exchange SC function, ie, valueFill should be <= total units of valueA
- Makers can cancel orders but it costs gas. Cancel Function maps order’s hash to order’s max value which prevents subsequent fills

#### 0x Protocol UseCases:
1. User can use a single token to buy other security tokens offered by various companies 
    1. (money/crypto to buy security tokens?)
    2. 0x can use interoperability amongst various security tokens that can be bought by a single crypto token by user
2. During dividends, when a user gets profits from his portfolio
    1. 0x can transfer dividends in a single token that the user accepts, ie, something like a stable coin

**Links:** 
1. [0x Docs](https://0xproject.com/docs/contracts#Introduction)
2. [0x White Paper](https://0xproject.com/pdfs/0x_white_paper.pdf)
3. [0x Github](https://github.com/0xProject)
4. [0x Blogs](https://blog.0xproject.com/latest)
5. [0x Protocol Explained - Part 1](https://www.youtube.com/watch?v=hWYxUfDM8sE)
6. [0x Protocol Explained - Part 2](https://www.youtube.com/watch?v=YBfqLOLaym4)
7. [0x Protocol Explained - Part 3](https://www.youtube.com/watch?v=PIiLBTyoQw0)

### Day 91: Ethereum Transaction
**Progress:** 

Read in detail on the following topics : 
- Accounts
- Gas & Payments
- Transaction & Messages
- Blocks
- Transaction Execution
- Execution Model
- Mining

**Thoughts:**  
#### Transaction execution 
1. Validation of Txn
    1. Intrinsic Gas :
        1. Predefined gas fee = 21000
        2. Storage gas fee = 4(x) + 68(y)
        3. Contract Creation fee = 32000
    2. Upfront Cost : 
        1. Gas limit + Gas price + Value
2. Deduct upfront cost from sender’s balance; Increment nonce of sender’s account by 1 to account for current txn  
3. Calculate the remaining gas as :
    1. Gas limit - Intrinsic Gas
4. Txn starts executing, Ethereum maintains substate(info req. after txn execution) such as :
    * Self-destruct set: a set of accounts (if any) that will be discarded after the transaction completes.
    * Log series: archived and indexable checkpoints of the virtual machine’s code execution.
    * Refund balance: the amount to be refunded to the sender account after the transaction. Remember how we mentioned that storage in Ethereum costs money, and that a sender is refunded for clearing up storage? Ethereum keeps track of this using a refund counter. The refund counter starts at zero and increments every time the contract deletes something in storage.
5. Various computations req by Txn are processed. Once all steps are processed, & no invalid state remains, state is finalized by : 
    1. determining amount of unused gas needed to refunded to user
    2. refunding refund balance for clearing storage
6. After sender is refunded : 
    * the Ether for the gas is given to the miner
    * the gas used by the transaction is added to the block gas counter (which keeps track of the total gas used by all transactions in the block, and is useful when validating a block)
    * all accounts in the self-destruct set (if any) are deleted
7. Finally, we’re left with the new state and a set of the logs created by the transaction.

**Links:** [How does Ethereum work, anyway?](https://medium.com/@preethikasireddy/how-does-ethereum-work-anyway-22d1df506369)

### Day 90: Truffle
**Progress: Truffle tutorial for DApp**

#### 1. Finished a tutorial on building a Pet Shop DApp**
Tech stack used :
- Development Tool : [Truffle](https://truffleframework.com) 
- Local Blockchain Deployment : [Ganache](https://truffleframework.com/ganache)
- Smart Contracts : [Solidity](https://solidity.readthedocs.io/en/v0.5.6/)
- Smart Contract Testing : Javascript
- User Interface : [Web3](https://web3js.readthedocs.io/en/1.0/)
- DApp Interaction Extension : [Metamask](https://metamask.io)

**Links:** 
[Ethereum - Pet Shop](https://truffleframework.com/tutorials/pet-shop)

#### 2. Ethereum Development Tutorial - Devslopes**
**Progress:**
- Developed & Deployed a standard ERC20 Token smart contract using Solidity, built upon `zeppelin-solidity` to ensure stability and security, as well as ERC20 compliance.

**Links:** 
1. [Course Link](https://www.devslopes.com/courses/ethereum-blockchain)
2. [Github Repo Link](https://github.com/bhalla98/SBCoin)

### Day 89: November 3, 2018
**Progress:** Watched videos explaining 0x Protocol 

**Thoughts:** Gives an easy, understandable explanation of 0x Protocol. Covers everything from their white paper.

**Links:** 
1. [0x Protocol Explained - Part 1](https://www.youtube.com/watch?v=hWYxUfDM8sE)
2. [0x Protocol Explained - Part 2](https://www.youtube.com/watch?v=YBfqLOLaym4)
3. [0x Protocol Explained - Part 3](https://www.youtube.com/watch?v=PIiLBTyoQw0)

### Day 88: November 2, 2018
**Progress:** Read 0x Protocol White Paper

**Thoughts:** Allows developing of standardized decentralized exchanges, making trading of crypto-to-crypto, ERC20 tokens easily. 

**Links:** [0x Protocol - White Paper](https://0xproject.com/pdfs/0x_white_paper.pdf)

### Day 87: November 1, 2018
**Progress:** Read in detail about Ethereum Architecture and how it actually works, what exactly happens under the hood

**Thoughts:** Gives a detailed description of the following topics : 
- Accounts
- Gas & Payments
- Transaction & Messages
- Blocks
- Transaction Execution
- Execution Model
- Mining

**Links:** [How does Ethereum work, anyway?](https://medium.com/@preethikasireddy/how-does-ethereum-work-anyway-22d1df506369)

### Day 86: October 31, 2018
**Progress:** Finished a tutorial on building a Pet Shop DApp 

**Thoughts:** Tech stack used :
- Development Tool : [Truffle](https://truffleframework.com) 
- Local Blockchain Deployment : [Ganache](https://truffleframework.com/ganache)
- Smart Contracts : Solidity
- Smart Contract Testing : Javascript
- User Interface : Web3
- DApp Interaction Extension : [Metamask](https://metamask.io)

**Links:** [Ethereum - Pet Shop](https://truffleframework.com/tutorials/pet-shop)

### Day 76-85: October 19-28, 2018
**Progress:** Prepared for the final test & completed **Blockchain Architecture Design and Use Cases** course 

**Thoughts:** This course offered a deep level understanding of various topics :
1. Cryptography behind Blockchain
2. Consensus Algorithms
3. Hyperledger Fabric & Hyperledger Composer
4. Blockchain Industry/Enterprise Use Cases
5. Blockchain Research Aspects

**Links:** [Course Link](https://onlinecourses.nptel.ac.in/noc18_cs47/preview)

### Day 75: October 18, 2018
**Progress:** Learnt about Ethereum’s Architecture & its concepts of Smart Contracts, Gas, Transactions, EVM and additional upcoming capabilities, from **Blockchain Architecture Design and Use Cases**

**Thoughts:** Additional/Upcoming Capabilities : 
- Raiden state channels suggests that parties need to use blockchain only for resolving disputes, but otherwise perform transactions off-chain.
- Sharding, in which nodes are partitioned so that they don’t have to store & process entire blockchain. 

**Links:** [Ethereum Ecosystem](https://youtu.be/GLgu7l7YhDw)

### Day 68-74: October 11-17, 2018
**Progress:** Watched Videos of Week 11 and submitted its assignment, of **Blockchain Architecture Design and Use Cases**

**Thoughts:** This week was all about Research aspects of Blockchain. These were the following topics : 
- Secure Multiparty Computation: A security protocol with the goal to create methods for nodes to jointly compute a function using their inputs without actually revealing their inputs. 
- Algorand: Scalable Byzantine Agreement for Cryptocurrencies
- Blockchain for Big Data
- Blockchain and AI

**Links:** 
- [Secure Multiparty Computation](https://youtu.be/5VFnMGMoEDQ)
- [Algorand - I](https://youtu.be/Q1LgYokejfc)
- [Algorand - II](https://youtu.be/5KdtIWoygXI)
- [Blockchain for Big Data](https://youtu.be/HXjToUWO568)
- [Blockchain and AI](https://youtu.be/7NHgpO4RXMM)

### Day 67: October 10, 2018
**Progress:** Read a research paper on Blockchain and Scalability

**Thoughts:** Paper discusses various scalability issues with Bitcoin & Ethereum blockchain. It explains & compares recent proposals like the lighting protocol, sharding, super quadratic sharding, DPoS to solve these issues. 

**Links:** [Blockchain and Scalability](https://ieeexplore.ieee.org/abstract/document/8431962)

### Day 66: October 9, 2018
**Progress:** Watched Lecture on [ByzCoin](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/kogias), & submitted Week 10 assignment, of **Blockchain Architecture Design and Use Cases**

**Thoughts:** ByzCoin provides a solution to resolve the scalability issues of Bitcoin & demonstrates how to securely process hundreds of transactions per second among hundreds to thousands of decentralized miners.

**Links:** [Research Aspects - ByzCoin](https://youtu.be/m1s2F_626iI)

### Day 65: October 8, 2018
**Progress:** Watched Lectures 48-49 on [Bitcoin-NG](https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-eyal.pdf) & [Collective Signing](https://github.com/dedis/cothority/tree/master/cosi), of Week 10, of **Blockchain Architecture Design and Use Cases**

**Thoughts:** Concepts Covered :
- L48: **Bitcoin-NG**
    - PoW Fairness & Scalability 
    - Bitcoin-NG Working Principles
    - Key blocks & Microblocks
- L49: **Collective Signing**
    - Authority and Digital Signature
    - Collective Signing (CoSi)
    - Shnorr Multisignature and BLS Signatures

**Links:** 
1. [Research Aspects - Bitcoin-NG](https://youtu.be/ViSX9fhsDGM)
2. [Research Aspects - Collective Signing](https://youtu.be/-fdAgEx1m_M)

### Day 64: October 7, 2018
**Progress:** Watched Lecture 47 - “Research Aspects – I (Consensus Scalability)”, of Week 10, of **Blockchain Architecture Design and Use Cases**

**Thoughts:** Concepts Covered : 
- PoW vs BFT Consensus 
- Consensus Finality 
- Consensus Scalability

**Links:** [Research Aspects – I (Consensus Scalability)](https://youtu.be/-Nzb85demnI)

### Day 63: October 6, 2018
**Progress:** Watched Lecture 46 - “Blockchain Security – III (Fabric SideDB)”, of Week 10, of **Blockchain Architecture Design and Use Cases**

**Thoughts:**  Concepts Covered : 
- SideDB Motivation
- SideDB Overview

**Links:** [Blockchain Security – III (Fabric SideDB)](https://youtu.be/zMx26lejBTM)

### Day 62: October 5, 2018
**Progress:** Played around with IBM Blockchain Starter Pack & Revisited Lectures 25-26 on Hyperledger Fabric Demo, of **Blockchain Architecture Design and Use Cases**

**Thoughts:** IBM Blockchain Starter Pack provides a local environment to build & test Blockchain applications for proof of concept, and how to operate a business network running on a Blockchain. 

**Links:** 
1. [IBM Blockchain Starter Pack](https://www.ibm.com/blockchain/getting-started)
2. [IBM Blockchain Platform Documentation](https://console.bluemix.net/docs/services/blockchain/index.html#ibm-blockchain-platform)
3. [Fabric Demo on IBM Blockchain - I](https://youtu.be/5Y_yXYA7O0c)
4. [Fabric Demo on IBM Blockchain - II](https://youtu.be/9usrTmq28Fg)

### Day 61: October 3, 2018
**Progress:** Watched Lectures 43-45 and submitted the quiz, of Week 9, of **Blockchain Architecture Design and Use Cases**

**Thoughts:** Concepts covered : 
- L43: Overview of Blockchain Security 
- L44: Identities & Policies, Membership & Access Control, Blockchain Crypto Service Providers
- L55: Privacy in a Blockchain System and through Fabric Channels, Smart Contract Confidentiality

**Links:** 
1. [Blockchain Security - (Overview)](https://youtu.be/UAkFy33SMFo)
2. [Blockchain Security - (Membership & Access Control in Fabric)](https://youtu.be/ng-hMpik9n4)
3. [Blockchain Security - (Privacy in Fabric)](https://youtu.be/Op9Q8kQKbXw)

### Day 60: October 2, 2018
**Progress:** Watched Lecture 42 - “Blockchain in Government – (Tax Payments and Land Registry Records)”, of Week 9, of **Blockchain Architecture Design and Use Cases**

**Thoughts:** Learnt how Blockchain is used for Tax Payments and managing Land Registry Records. 

**Links:** [Blockchain in Government – (Tax Payments and Land Registry Records)](https://youtu.be/i6Y5hUsikRk)

### Day 59: October 1, 2018
**Progress:** Watched Lecture 41 - “Blockchain in Government – (Hyperledger Indy)”, of Week 9, of **Blockchain Architecture Design and Use Cases**

**Thoughts:** Learnt about [Hyperledger Indy](https://www.hyperledger.org/projects/hyperledger-indy), a DLT for Decentralized Digital Identity, and how it works. 

**Links:** [Blockchain in Government - (Hyperledger Indy)](https://youtu.be/qF4P7hKjQPY)

### Day 53-58: September 21-26, 2018
**Progress:** Watched Videos of Week 8 and submitted its assignment, of **Blockchain Architecture Design and Use Cases**

**Thoughts:** This week covered industry level applications of Blockchain in : 
- Supply Chain, Healthcare, Energy markets, Media
- Government (Advantages, Use cases, Digital Identity)

**Links:** 
1. [Blockchain in Other Industries](https://youtu.be/mWiAMBDYkvs)
2. [Blockchain in Government - (Advantages)](https://youtu.be/6aUzbMk-kK8)
3. [Blockchain in Government - (Use Cases)](https://youtu.be/ldn7Qw5Xszs)
4. [Blockchain in Government - (Digital Identity)](https://youtu.be/MKS3p2AXsY8)

### Day 52: September 20, 2018
**Progress:** Watched Lecture 36 - “Blockchain in Supply Chain - II”, of Week 8 of **Blockchain Architecture Design and Use Cases**

**Thoughts:** Concepts covered : 
- Everledger, and how they track provenance of diamonds from mines to jewellery stores to combat frauds.
- The Diamond Lifecycle. 
- Addressing Supply Chain Fraud through Blockchain. 

**Links:** [Blockchain in Supply Chain - II](https://youtu.be/6PjhwnaScKU)

### Day 51: September 19, 2018
**Progress:** Revisited Week 7 Lectures & submitted its quiz of **Blockchain Architecture Design and Use Cases**

**Thoughts:** After this week, I understood how Blockchain can be used in Financial Services & Global Trade Logistics. Got an overview of Blockchain in Supply Chain Management. 

**Links:** [Course Link](https://onlinecourses.nptel.ac.in/noc18_cs47/preview)

### Day 50: September 18, 2018
**Progress:** Watched Lecture 35 - **“Blockchain in Supply Chain – I”**, of Week 7 of **Blockchain Architecture Design and Use Cases** 

**Thoughts:** Concepts covered : 
- Food Safety and Food Traceability 
- Supply Chain Orchestration

**Links:** [Blockchain in Supply Chain – I](https://youtu.be/UAkTaOXO6Go)

### Day 49: September 17, 2018
**Progress:** Watched Lectures 33-34, of Week 7 of **Blockchain Architecture Design and Use Cases** on: 
- L33: Financial Trade 
- L34: Revolutionizing Global Trade

**Thoughts:** Concepts covered : 
- **L33: Financial Trade**
    - Blockchain Enabled Trade
    - We.Trade - Trade Finance Network 
    - Supply Chain Financing
- **L34: Revolutionizing Global Trade**
    - Blockchain for Trade Logistics 
    - Global Trade Digitization 
    - Blockchain for Container Management

**Links:** 
- [Financial Trade](https://youtu.be/Xtkwfn5gBtU)
- [Revolutionizing Global Trade](https://youtu.be/6gXjzIkZzEk)

### Day 48: September 16, 2018
**Progress:** Completed Week 5 & 6 and submitted the final assignment of **IBM Blockchain Foundation for Developers**

**Thoughts:** Feels great to complete **IBM Blockchain Foundation for Developers** course. Now, building projects using Hyperledger tools is the next goal. Got the foundational knowledge on: 
- Blockchain and DLT in a business environment
- Blockchain solution components
- Use cases of Blockchain, How to transfer assets in a network
- Modeling & building simple business networks using Hyperledger Composer
- Hyperledger Fabric
- Methods to arrive at consensus

**Links:** [Course Link](https://www.coursera.org/learn/ibm-blockchain-essentials-for-developers)

### Day 47: September 15, 2018
**Progress:** Explored & Read about the [Brave browser](https://brave.com)

**Thoughts:** It has an interesting business model where it strips out ads from websites, replaces them with its own ads, for which users get paid in Basic Attention Tokens (BATs) if they view these ads. It then allows users to use BATs for payments to other sites. 

**Links:** 
1. [The Brave Browser Basics](https://googleweblight.com/i?u=https://www.computerworld.com/article/3292619/web-browsers/the-brave-browser-basics-what-it-does-how-it-differs-from-rivals.html&hl=en-IN)
2. [Youtube Link](https://www.youtube.com/watch?v=tOHh6OlYqOU&t=46s)

### Day 46: September 14, 2018
**Progress:** Watched Lecture 32 - “Blockchain in Financial Service – II (Compliance and Mortgage)” of **Blockchain Architecture Design and Use Cases**. Concepts covered :
- KYC
- Privacy Consents 
- Mortgage over Blockchain 

**Thoughts:** KYC process could get a lot more quicker and automated through blockchain, which can be very beneficial for a country like India. 

**Links:** [Lecture 32](https://youtu.be/mYarAgmwZJM)

### Day 45: September 13, 2018
**Progress:** Watched Lecture 31 - “Blockchain in Financial Service – I (Payments and Secure Trading)” of **Blockchain Architecture Design and Use Cases**. Concepts covered :
- Cross border payments
- Stellar and Ripple
- Project Ubin

**Thoughts:** Looked into Payments and Security Trading of Financial services, and how blockchain is transforming this sector.

**Links:** [Lecture 31](https://youtu.be/ud3rxnbdIBQ)

### Day 44: September 12, 2018
**Progress:** Watched Lectures 27-30, and submitted Quiz-5 & Quiz-6 of **Blockchain Architecture Design and Use Cases**. Concepts covered :
- Goals & key development concepts of Hyperledger Composer
- Adminstrator key concepts, Mapping of Composer to Fabric chain code
- Blockchain Use Cases in Industries

**Thoughts:** Last 2 weeks were all about Hyperledger Fabric & Composer. Learnt a lot about its architecture, how to setup the network, instantiating its chaincode, running applications on it. 

**Links:** 
1. [Lecture 27](https://youtu.be/iDiaGY31lK0)
2. [Lecture 28](https://youtu.be/czpYqlyHL3o)
3. [Lecture 29](https://youtu.be/CJo4mX_STZU)
4. [Lecture 30](https://youtu.be/GD1_-dcCWA4)

### Day 43: September 11, 2018
**Progress:** Watched Lectures 23-26 of **Blockchain Architecture Design and Use Cases**. Concepts covered :
- L23: Organization and Consortium Network, Membership Service Provider, Transaction Signing
- L24:  Setting up Fabric Network, Endorsement policies
- L25: Demo of blockchain network as different organizations, Setting & Deploying on IBM Cloud
- L26: Demo of an asset transfer application, its underlying code & client SDK code

**Thoughts:** Too much to grasp for a single day. Will be revisiting these videos during the weekend. 

**Links:** 
1. [Lecture 23](https://youtu.be/4ujj5knD3pg)
2. [Lecture 24](https://youtu.be/eWIa-hfn2WE)
3. [Lecture 25](https://youtu.be/5Y_yXYA7O0c)
4. [Lecture 26](https://youtu.be/9usrTmq28Fg)

### Day 42: September 10, 2018
**Progress:** Learnt about Sharing in Ethereum Network. 
- In Bitcoin & Ethereum, all nodes have to store all data on Blockchain locally and process all transactions
- Sharding divides Blockchain data amongst nodes & allow nodes to process different transactions in parallel. 

**Thoughts:** Sharding can help the network fix its scalability & performance issues and allow more transactions to be processed quickly without sacrificing security.  

**Links:** 
1. [What are Ethereum Nodes And Sharding?](https://blockgeeks.com/guides/what-are-ethereum-nodes-and-sharding/)
2. [How to Scale Ethereum: Sharding Explained](https://medium.com/prysmatic-labs/how-to-scale-ethereum-sharding-explained-ba2e283b7fce)
3. [Programmer explains Ethereum Sharding](https://www.youtube.com/watch?v=m4Kcgj4mSh8)

### Day 41: September 9, 2018
**Progress:** Completed Week 4 of **IBM Blockchain Foundation for Developers**.
- Learnt Hyperledger Composer’s deeper structures and components: Business Network Archive(Models, Script File, Access Control Language, Metadata), and Roles(Solution Developer, Solution Administrator)
- Learnt how to build a Blockchain-based Digital Bank

**Thoughts:** Hyperledger Composer, compared to chaincode, can more quickly model, build and deploy business networks and applications that allow participants to make transactions and exchange assets in a network. Going to look more into the labs & tutorials during the weekend. 

**Links:** [Course Link](https://www.coursera.org/learn/ibm-blockchain-essentials-for-developers)

### Day 40: September 8, 2018
**Progress:** 
- Revisited Lectures 15-18 on various algorithms to arrive at consensus in a Distributed System of participants, of **Blockchain Architecture Design and Use Cases**. 
- Algorithms: [PAXOS](https://en.wikipedia.org/wiki/Paxos_(computer_science)), [RAFT](https://en.wikipedia.org/wiki/Raft_(computer_science)), [BFT](https://en.wikipedia.org/wiki/Byzantine_fault_tolerance), [PBFT](https://blockonomi.com/practical-byzantine-fault-tolerance/)

**Thoughts:** The various methods to achieve consensus during failure of nodes in Synchronous and Asynchronous Distributed Network have intrigued me the most in this course. 

**Links:** 
1. [Lecture 15](https://youtu.be/KEe6kjzOzUU)
2. [Lecture 16](https://youtu.be/HD81QFvPF2A)
3. [Lecture 17](https://youtu.be/naj_LG8Pu0I)
4. [Lecture 18](https://youtu.be/Xiy0MS4t_2w)

### Day 39: September 7, 2018
**Progress:** Watched Lecture 22 - “Hyperledger Fabric - Details” of Week 5,  of **Blockchain Architecture Design and Use Cases**. Concepts covered :
- Ordering Service 
- Channels in Fabric
- Fabric Peers
- Certificate Authority 

**Thoughts:** Learning about Single Channel & Multi-Channel Networks, and how Peers work and connect to these channels, and other concepts gave a detailed Architecture of Hyperledger Fabric. 

**Links:** [Lecture 22](https://youtu.be/xjliVltyLRk)

### Day 38: September 6, 2018
**Progress:** Watched Lecture 21 - “Hyperledger Fabric - Transaction Flow” of Week 5,  of **Blockchain Architecture Design and Use Cases**. Concepts covered :
- Fabric Architecture
- Transaction Flow in Fabric 

**Thoughts:** Learnt about the Architecture. Also dwelled into how a transaction is going to get committed by all peers in Blockchain network in a consistent manner. 

**Links:** [Lecture 21](https://youtu.be/nBXr7dLXAbE )

### Day 37: September 5, 2018
**Progress:** Watched Lectures 16-20 of Week 4, submitted Quiz-4 of **Blockchain Architecture Design and Use Cases**. Concepts covered :
- L16: RAFT Consensus, Byzantine General Problem 
- L17: Byzantine Fault Tolerant System, Consensus achieved in Synchronous System, Lamport-Shostak-Pease BFT Algorithm
- L18: BFT over Asynchronous Systems, Practical Byzantine Fault Tolerance 
- L19: Overview of Blockchain for Enterprise-grade Solutions 
- L20: Blockchain Components and Concepts

**Thoughts:** Covered methods to achieve Consensus over Synchronous & Asynchronous Systems when the nodes crash, network fails or when nodes behave maliciously. Started with Blockchain for Enterprise. Learnt about Actors, Components in Blockchain Solution & how Applications interact with Ledgers

**Links:** 
1. [Lecture 16](https://youtu.be/HD81QFvPF2A)
2. [Lecture 17](https://youtu.be/naj_LG8Pu0I)
3. [Lecture 18](https://youtu.be/Xiy0MS4t_2w)
4. [Lecture 19](https://youtu.be/oqnc0WBahMw)
5. [Lecture 20](https://youtu.be/TOlv1nRDdfs)

### Day 36: September 4, 2018
**Progress:** Revisited Week 3 Lecture materials & submitted Quiz-3 of **Blockchain Architecture Design and Use Cases**

**Thoughts:** Finally done with Week 3. Upcoming weeks is going to be more towards Blockchain For Enterprise. So really excited about that. 

**Links:** [Course Link](https://onlinecourses.nptel.ac.in/noc18_cs47/preview)

### Day 35: September 3, 2018
**Progress:** 
1. Read FAQ-3 & Watched Lectures 13-15 of **Blockchain Architecture Design and Use Cases**. Concepts covered :
    - L13: Bitcoin Mining, Mining Difficulty, Mining Pool
    - L14: Permissioned Blockchain, Use Cases, Design Issues, State Machine Replication
    - L15: Consensus in Permissioned Blockchain, Distributed Consensus in closed environment, PAXOS
2. Read about Stablecoins

**Thoughts:**  
1. I wish i knew about mining back in the days. 
2. PAXOS is one of the earliest suggested ways to achieve consensus. It’s difficult to explain it theoretically but easy to understand in practical. 
3. Stablecoins could bring more mass adoption from Governments. Didn’t understand Seignorage Shares, would have to look more into that.

**Links:** 
1. [Lecture 13](https://youtu.be/FT23I17mGNE)
2. [Lecture 14](https://youtu.be/ZrWKTjjtZYU)
3. [Lecture 15](https://youtu.be/KEe6kjzOzUU)
4. [An Overview of Stablecoins](https://hackernoon.com/an-overview-of-stablecoins-cf3fac75dcf7)

### Day 34: September 2, 2018
**Progress:** 
1. Learnt how to transfer assets in blockchain network using Hyperledger Composer & finished Week 3 of **IBM Blockchain Foundation for Developers**
2. Learnt about Sidechains and working of [Loom Network](https://loomx.io)

**Thoughts:** 
1. Got an overview of [Hyperledger Composer](https://hyperledger.github.io/composer/latest/) & now I’m understanding how participants interacts in a network. 
2. Sidechains are extensions to existing blockchain which help in the scaling of decentralized apps by running computations on it securing assets as NFT that can be used in 

**Links:** 
1. [Course Link](https://www.coursera.org/learn/ibm-blockchain-essentials-for-developers)
2. [Loom Network - Review](https://youtu.be/OHa9cPH7zMA)

### Day 33: September 1, 2018
**Progress:** Explored [Blockstack](https://blockstack.org) and its tutorials
 
**Thoughts:** Tutorials were pretty informative. Lets see if I use Blockstack for a future project. 

**Links:** [Tutorials](https://blockstack.org/tutorials/)

### Day 32: August 31, 2018
**Progress:** 
1. Read Bitcoin Script Guide Part 2 via [Blockgeeks](https://blockgeeks.com)
2. Read about Iran’s national cryptocurrency being a Shitcoin

**Thoughts:** 
1. Part 2 covers the logic behind various Bitcoin Transaction scenarios.
2. No Comments on Iran’s National Cryptocurrency. 

**Links:** 
1. [The Best Step-by-Step Bitcoin Script Guide Part 2](https://blockgeeks.com/guides/bitcoin-script-guide-part-2/)
2. [Iran’s National Cryptocurrency - Textbook Example of a Shitcoin](https://decentralpost.com/2018/08/30/iran-unveiled-its-national-cryptocurrency-and-it-is-a-textbook-example-of-a-shitcoin/)

### Day 31: August 30, 2018
**Progress:** 
1. Watched Lectures 1-13 in Module 1 “What is Ethereum?” of **Ethereum and Solidity: The Complete Developer's Guide**
2. Read about Ethereum’s next upgrade, [Constantinople](https://www.coindesk.com/ethereum-is-testing-code-for-its-next-hard-fork/) which could be the biggest Blockchain Test 

**Thoughts:** 
1. Understood concepts of Solidity Functions, Wei, Gas, Ether, Mnemonic Phrases.
2. Constantinople will make the Ethereum network more efficient and less costly in terms of fees and also create a hard deadline for [The Difficulty Bomb](https://www.coindesk.com/before-the-bomb-hits-why-the-race-is-on-to-alter-ethereums-economics/), a piece of code that would eventually push the blockchain into an [Ice Age](https://www.coindesk.com/ice-age-coming-ethereum-users-vote-reducing-block-reward/), where no further blocks can be formed, if left untouched.

**Links:** 
1. [Course Link](https://www.udemy.com/ethereum-and-solidity-the-complete-developers-guide/)
2. [Ethereum’s October Upgrade Could Be $29B Blockchain’s Biggest Test](https://www.coindesk.com/ethereums-october-upgrade-could-be-29-billion-blockchains-biggest-test-yet/)

### Day 30: August 29, 2018
**Progress:** Read Bitcoin Script Guide Part 1 via [Blockgeeks](https://blockgeeks.com)

**Thoughts:** Brushed up my knowledge of the Bitcoin Script.

**Links:** [The Best Step-by-Step Bitcoin Script Guide Part 1](https://blockgeeks.com/guides/best-bitcoin-script-guide/?utm_source=twitter&utm_medium=social&utm_campaign=SocialWarfare/BG)

### Day 29: August 28, 2018
**Progress:** Explored Github organizations on cryptoeconomics, DApps, Ethereum by [Karl Floersch](https://github.com/karlfloersch)

**Thoughts:** A nice go to place for papers regarding Cryptoeconomics, Decentralized Applications, Game Theory, Ethereum.

**Links:** 
1. [Cryptoeconomics](https://github.com/cryptoeconomics-study)
2. [DApp Studies](https://github.com/dapp-studies)
3. [Ethereum Research](https://github.com/ethresearch)

### Day 28: August 27, 2018
**Progress:** Watched Lectures 11-12 of **Blockchain Architecture Design and Use Cases**. Concepts covered :
- Bitcoin Consensus, PoW, Hashcash PoW
- Attacks on PoW, PoS, Proof of Burn, Proof of Elapsed Time

**Thoughts:** Got a good understanding of Consensus in Bitcoin network and the various methods to achieve it.

**Links:** 
1. [Lecture 11](https://www.youtube.com/watch?v=Zd2kbhrRB2c)
2. [Lecture 12](https://www.youtube.com/watch?v=Zo5br6gpTAI)

### Day 27: August 26, 2018
**Progress:** Read about:
1. The major things missing in Blockchain Industry
2. Electricity Consumption of BTC, BCH, ETH, LTC & XMR

**Thoughts:** 
1. First article speaks about Infrastructure suggestions on everything from UX to Interoperability to Digital Reserves to Stablecoins.
2. Second article explains how enormous is the electricity usage of such coins, equivalent to power consumption of many countries annually. 

**Links:** 
1. [The Four Major Things Missing In The Blockchain Industry](https://blockchainatberkeley.blog/4-things-missing-in-the-blockchain-industry-50f97bec098c)
2. [Electricity Consumption of BTC, BCH, ETH, LTC & XMR](https://www.ofnumbers.com/2018/08/26/how-much-electricity-is-consumed-by-bitcoin-bitcoin-cash-ethereum-litecoin-and-monero/)

### Day 26: August 25, 2018
**Progress:** Watched Lectures 1-13 in Module 1 “What is Ethereum?” of **Ethereum and Solidity: The Complete Developer's Guide**

**Thoughts:** Understood the basic structure of Ethereum Blockchain and the lifecycle of a transaction.

**Links:** [Course Link](https://www.udemy.com/ethereum-and-solidity-the-complete-developers-guide/)

### Day 25: August 24, 2018
**Progress:** 
1. Watched Lecture 19 on Blockchain for Enterprise of **Blockchain Architecture Design and Use Cases**
2. Read **Smart Contracts**, 1994 article by Nick Szabo

**Thoughts:** Hoping to be well aware of the Use Cases of Blockchain for Enterprise and to have a solid side project in this domain by the end of the challenge. Also, great to see a 2 decade old concept of Smart Contracts having immense applications now.

**Links:** 
1. [Blockchain For Enterprise](https://youtu.be/oqnc0WBahMw )
2. [Smart Contracts - Nick Szabo](http://www.fon.hum.uva.nl/rob/Courses/InformationInSpeech/CDROM/Literature/LOTwinterschool2006/szabo.best.vwh.net/smart.contracts.html)

### Day 24: August 23, 2018
**Progress:** 
1. Revisited Week 2 Lectures & submitted its quiz of **IBM Blockchain Foundation for Developers**
2. Listened to a podcast by [@InsureBlock](https://twitter.com/Insureblock) on Blockchain for Enterprises

**Thoughts:** As I said, repetition is the mother of all skills. I also feel podcasts deliver substantial knowledge and its retained for long too. 

**Links:** [Podcast](http://www.insureblocks.com/ep-20-the-journey-from-bitcoin-to-enterprise-blockchain/)

### Day 23: August 22, 2018
**Progress:** 
1. Watched Lecture 10-“Distributed Consensus” & completed Week 2 of **Blockchain Architecture Design and Use Cases**
2. Studied Script language for Bitcoin transaction

**Thoughts:** Didn’t know I’d be learning a language like Script as well. It has some pretty interesting functions though. 

**Links:** 
1. [Lecture 10](https://youtu.be/x964Nw-xJw8  )
2. [Script Language](https://en.bitcoin.it/wiki/Script )

### Day 22: August 21, 2018
**Progress:** Read about:
1. What’s Next for Apps?
2. Govt. of Australia now accepting payment of bills using Bitcoin & other cryptocurrencies

**Thoughts:** The future of DApps and global acceptance of Cryptocurrencies looks positive. 

**Links:** 
1. [What’s Next for Apps?](https://blog.stateofthedapps.com/evolving-technology-whats-next-for-dapps-578e74ae906d)
2. [Citizens of Australia can now pay bills using cryptocurrencies ](https://bloqwire.com/australians-can-now-pay-bills-using-bitcoin-with-cointree-and-gobbill-partnership/)

### Day 21: August 20, 2018
**Progress:** Read about **Zero Knowledge Proofs of Identity** from a book on Applied Cryptography by Bruce Schneier

**Thoughts:** The applications of ZKP of identity explained in this book mainly revolve around identity theft. 

**Links:** 
1. [Applied Cryptography - Bruce Schneier](https://books.google.co.in/books/about/Applied_cryptography.html?id=A6ZO2D6ayNwC&source=kp_cover&redir_esc=y)
2. [Extract from Book](https://drive.google.com/file/d/1wT4gzvhR8Q75ECmEik86gSOh7wo2zbZ8/view)

### Day 20: August 19, 2018
**Progress:** Watched Lectures 8-9 of **Blockchain Architecture Design and Use Cases**. Concepts covered :
- Bitcoin Scripts, Bitcoin P2P Network
- Transactions, Block Mining, Block Propagation, Block Relay

**Thoughts:** Understood how a block is formed in a blockchain and its life cycle

**Links:** 
1. [Lecture 8](https://youtu.be/k42p-w7hBT4)
2. [Lecture 9](https://youtu.be/H3F8f40UgAM)

### Day 19: August 18, 2018
**Progress:** Revised notes of Lecture 1-7 and read FAQ-1 & FAQ-2 of **Blockchain Architecture Design and Use Cases** 

**Thoughts:** Always good to revise what is learnt. Repetition is the mother of all skills. 

**Links:** [Course Link](https://onlinecourses.nptel.ac.in/noc18_cs47/preview)

### Day 18: August 17, 2018
**Progress:** 
1. Watched Blockchain for Supply Chain by [@SirajRaval](https://www.youtube.com/channel/UCWN3xxRkmTPmbKwht9FuE5A)
2. Read about IBM and Maersk’s Blockchain Blockchain Supply Chain platform

**Thoughts:** Blockchain in Supply Chain Management always intrigues me.

**Links:** 
1. [Blockchain for Supply Chain - Siraj Raval](https://twitter.com/sirajraval?lang=en)
2. [IBM & Maersk’s Blockchain Blockchain Supply Chain](https://www.coindesk.com/90-companies-join-ibm-and-maersks-blockchain-supply-chain/)

### Day 17: August 16, 2018
**Progress:** Watched Week 2 Lectures of **IBM Blockchain Foundation for Developers**

**Thoughts:** 	Learnt about:
- Use cases for blockchain in business: financial services, supply chains, auditing and record keeping, and letters of credit
- Best practices for getting started with blockchain and applying it to your business network

**Links:** [Course Link](https://www.coursera.org/learn/ibm-blockchain-essentials-for-developers)

### Day 16: August 15, 2018
**Progress:** 
1. Watched Week 1 Lectures of **IBM Blockchain Foundation for Developers**
2. Explored some of the 40 promising Ethereum DApps

**Thoughts:** Got an idea of Blockchain and distributed ledger systems in a business environment.

**Links:** 
1. [Course Link](https://www.coursera.org/learn/ibm-blockchain-essentials-for-developers)
2. [40 Ethereum Dapps](https://media.consensys.net/40-ethereum-apps-you-can-use-right-now-d643333769f7)

### Day 15: August 14, 2018
**Progress:** Read about Major Blockchain Trends outlined by Deloitte  

**Thoughts:** Good overview of some of the upcoming Blockchain trends.

**Links:** [Major Blockchain Trends outlined by Deloitte](https://www.forbes.com/sites/andrewarnold/2018/08/13/the-6-major-blockchain-trends-for-2018-outlined-by-deloitte/#3e68bd1a4844)

### Day 14: August 13, 2018
**Progress:** Watched Lectures 6-7 of **Blockchain Architecture Design and Use Cases**. Concepts covered :
- Digital Signatures, Public Key Cryptography
- Creation of coins, Double Spending, FORTH-precursor for Bitcoin Scripting

**Thoughts:** 
- Got a clear understanding of how digital signatures and symmetric & asymmetric(public-key) cryptography works
- Bitcoin Script is somewhat similar to Assembly language used in microprocessors. 

**Links:** 
1. [Lecture 6](https://youtu.be/43A0oxLDxYg)
2. [Lecture 7](https://youtu.be/SMRfeBdadlQ)

### Day 13: August 12, 2018
**Progress:** 
1. Watched Lectures 2-5 of **Blockchain Architecture Design and Use Cases** 
2. Read about Vitalik’s new consensus algorithm to make 51% attack obsolete, & requires 99% nodes for attack

**Thoughts:** The new consensus algorithm could make Ethereum the most secure public blockchain using the new concept of “Observer Nodes”.

**Links:** 
1. [Course Link](https://onlinecourses.nptel.ac.in/noc18_cs47/preview)
2. [Vitalik’s New Consensus Algorithm](https://blockmanity.com/news/ethereum/vitaliks-new-consensus-algorithm-make-51-attack-obsolete-requires-99-nodes-attack/)

### Day 12: August 11, 2018
**Progress:** 
1. Read about application of Blockchain in Supply Chain
2. Watched “Introduction to Blockchain-I (Basics)” of **Blockchain Architecture Design and Use Cases** 

**Thoughts:** A side project on implementing Blockchain in Supply Chain Management would be fun.

**Links:** 
1. [Blockchain in Supply Chain](https://www.verypossible.com/blog/top-blockchain-use-cases-for-supply-chain-management)
2. [Introduction to Blockchain-I (Basics)](https://www.youtube.com/watch?v=mzPoUjQC4WU)

### Day 11: August 10, 2018
**Progress:** Watched Week 2 Lectures of **Bitcoin and Cryptocurrency Technologies**

**Thoughts:** Lectures on Distributed Consensus, Proof of Work and Incentivising participants surely creates a deeper interest in Cryptoeconomics.

**Links:** [Course Link](https://www.coursera.org/learn/cryptocurrency)

### Day 10: August 9, 2018
**Progress:** Read about how the top software and consultancy giants are using Blockchain 

**Thoughts:** Blockchain is beginning to have mass adoption in big firms. It has certainly created an economy and this technology is here to stay.

**Links:** 
1. [IBM Research](https://www.research.ibm.com/blockchain/)
2. [Goldman Sachs](https://www.goldmansachs.com/insights/pages/blockchain/)
3. [Accenture](https://www.accenture.com/us-en/insights/blockchain-index)
4. [Walmart](https://www.newsbtc.com/2018/06/06/walmart-leading-way-blockchain-based-tracking-systems/)

### Day 9: August 8, 2018
**Progress:** Learn about Cryptographic Hash Functions 

**Thoughts:** They are one of the underlying technologies that make Blockchain so secure

**Links:** 
1. [The In’s and Outs of Cryptographic Hash Functions](https://blockgeeks.com/guides/cryptographic-hash-functions/)
2. [Cryptographic Hash Function - Video 1](https://www.youtube.com/watch?v=0WiTaBI82Mc&feature=youtu.be)
3. [Cryptographic Hash Function - Video 2](https://youtu.be/0rO6KfQq1Rk)

### Day 8: August 7, 2018
**Progress:** 
1. Read about why Web 3.0 matters 2. Read about Blockchain Technology stack behind Web 3.0

**Thoughts:** Interesting how the web has changed from observation(Web 1.0) of static web pages, to participation(Web 2.0) with other peers using social media, and now changing to decentralization(Web3.0)

**Links:** 
1. [Why Web 3.0 Matters](https://medium.com/@matteozago/why-the-web-3-0-matters-and-you-should-know-about-it-a5851d63c949)
2. [Blockchain Technology Stack Behind Web3.0](https://101blockchains.com/web-3-0-blockchain-technology-stack/)

### Day 7: August 6, 2018
**Progress:** Watched Week 1 videos of Bitcoin and Cryptocurrency Technologies course on Coursera 

**Thoughts:** Always good to brush up on the basics every now and then 

**Links:** [Course Link](https://www.coursera.org/learn/cryptocurrency)

### Day 6: August 5, 2018
**Progress:** 
1. Listened to a podcast by [Invest Like A Boss](https://twitter.com/Investlikeaboss). 
2. Read about Bakkt, a new crypto asset platform, by ICE (parent company of NYSE)

**Thoughts:** Its good to see companies in Stocks Industry getting involved in the Crypto Market as well.

**Links:** 
1. [Podcast Link](https://investlikeaboss.libsyn.com/71-bitcoin-vs-ethereum-and-the-future-of-the-internet-ivan-on-tech)
2. [Bakkt Article 1](http://fortune.com/longform/nyse-owner-bitcoin-exchange-startup/)
3. [Bakkt Article 2](https://www.ccn.com/bitcoin-could-be-first-worldwide-currency-nyse-owner/amp/?__twitter_impression=true)

### Day 5: August 4, 2018
**Progress:** Read articles on blockchain implementation in iOS using Swift

**Thoughts:** A CocoaPod dedicated to blockchain implementation in iOS would be fun to work with. It would also increase the production of blockchain based iOS Apps.

**Links:** 
1. [Basic Blockchain](https://www.appcoda.com/blockchain-introduction/)
2. [Implementing Driving Records Blockchain in iOS](https://hackernoon.com/implementing-driving-records-blockchain-in-ios-using-swift-23fb258819b1)

### Day 4: August 3, 2018
**Progress:** Read about Applications of Blockchain and Cryptokitties 1. [Real World Applications Of Blockchain](https://blockgeeks.com/guides/blockchain-applications-real-world/ …)
2. [Cryptokitties](https://blockgeeks.com/guides/cryptokitties/ …)
3. [ERC-721 Standard and its unique tokens](https://medium.com/@marc.couzic/the-erc-721-standard-and-its-unique-tokens-6280b1a0c656) 

**Thoughts:** Really excited to see what Blockchain can do in Supply Chain. Would want to work with ERC-721 Tokens to create an interesting project.

### Day 3: August 2, 2018
**Progress:** Read about Applications of blockchain in crowdfunding, file storage(IPFS), prediction markets(Augur), sharing economy(Openbazaar). Read about Title registration in land,patents,etc. in Honduras, Georgia, Sweden.

**Thoughts:** Interesting to see the use of Non Fungible Tokens. 

**Links:** [Sweden partnering up with Chromaway for Title Registration](https://chromaway.com/landregistry/)

### Day 2: August 1, 2018
**Progress:** Read about [Zero Knowledge Proofs](https://en.m.wikipedia.org/wiki/Zero-knowledge_proof) and [ZK-Snarks](https://z.cash/technology/zksnarks.html), and how ZCash uses **ZK-Snarks**.
    
**Thoughts:** Zero Knowledge Proofs add an extra layer of privacy to the blockchain.
ZK-Snarks proves a computational fact about some data without revealing the actual data. 

### Day 1: July 31, 2018
**Progress:** Read about [Cryptoeconomics](https://blockgeeks.com/guides/what-is-cryptoeconomics/?utm_source=twitter&utm_medium=social&utm_campaign=SocialWarfare/BG), the underlying principle of how blockchains work.

**Thoughts:** "Cryptology" brings Hashing, Signatures, Distributed Consensus, Immutability to Blockchain. "Economics" incentivises users to get work done by either issuing tokens & privileges or by rewarding/punishing the participants.


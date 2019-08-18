

####**UNIDAO**
___

#DAO Universe
###Whitepaper

*07 June 2019*

##Introduction
DAO stands for decentralized autonomous organization, while DAO Fund is technologically operated and regulated investment fund with decentralized governance on public, permissionless distributed ledger. It provides a new alternative vehicle for collective investments infrastructure, easy to use for anyone seeking an exposure to digital assets with fully transparent operations.

##Motivation
At the moment, starting traditional investment fund is complicated and very capital intensive. Onboarding new clients requires compliance with vast number of regulations and requirements. All for the sake of protecting investors interests and capital control. Many processes in operations are not digital and require a lot of functional stuff. Compliance costs with paperwork processes originate quite a lot of direct and indirect costs, especially legal. Running Investment Fund is viable only after a certain scale of assets under management (AUM), which should be quite significant. Those barriers to entry create a superset of players operating at scale, while the costs are mostly laid down on a client.

A lot of intermediaries involved to create a necessary conflict of interests, yet fraud and overindulgence are still flourishing on the market, as overcentralization problems occur. That problem may be aggravated dealing with digital sovereign assets on the blockchain.

We believe that DAO can solve many issues with centralization and cooperation, unlocking the ability to create community investment vehicle fairly distributing rewards for outstanding performance of governors. That is why DAO Universe was created.

##Overview
Conceptually, as planets in the Universe subject to laws of physics, DAO’s in DAO Universe are subject to economic laws, governed by its inhabitants. Inhabitants pursue a common goals and rely on each other to make investment decision hoping to increase the size of their DAO and value per each participant. 
The main goal of DAO Universe is increasing the value of assets under management and increasing its social influence. 

As DAO’s in DAO Universe exists solely on the blockchain and owns digital assets to provide unprecedented transparency of asset management and decision making and higher risk/reward.

##Definitions
**DAO** - An organization represented by rules encoded as a computer program that is transparent, controlled by shareholders and not influenced by a central authority.

**DAO Universe** - Community-based DAO Funds built on Aragon stack and aimed at profit maximization of assets under its management and social influence increase. There can be many DAO’s in DAO Universe ecosystem serving different purposes and investment strategies.

**Address** - URL of DAOs from DAO Universe such as https://mainnet.aragon.org/#/mars-dao.eth. Each DAO has its own ENS name.

**Participants** - Any person having tokens in possession of DAO Universe is a Participant

**Roles** - There are no specific management roles in DAO Universe, however any Participant may take an active role in DAO’s Governance and Investment activity. As a reward, such a Participant will earn R tokens and participate in Equity tokens (Q tokens) distribution.

**Rewards distribution** - Distribution of fees for management among Participants of the DAO proportionally to their Reputation (R tokens). This will incentivize Participants of the DAO to take an active role in governance of the DAO. 

**Contribution** - An amount contributed to the DAO in exchange for Q tokens.

**Redemption** - Q tokens can be sold on the secondary market or redeemed for any other liquid asset in possession of DAO at any time within setted timeframe executed by conducting a vote. Q Tokens may be sold using Continuous liquidity mechanism of Uniswap exchange (Uniswap.io) [a][b][c][d][e]according to available liquidity.

**Trade** - Q tokens can be freely traded via OTC or exchanges where available. R tokens are not tradable.

**DAO Shutdown** - Stopping of all activity and redemption of all Q tokens for Assets in DAO possession. Consensus of 75% Q Tokens need to approve that decision.

##Governance
Anyone can participate in the **DAO Universe** by contributing to one of its DAO’s. There is no minimum necessary contribution in the **DAO Universe**. 

DAOs in **DAO Universe** are governed by two types of tokens: **Q type** - tokens and **R type**. All decisions in DAO Universe are made through voting procedure executed on the Ethereum blockchain.

Any contributor to the DAO becomes **Participant** of this DAO and receives **Q tokens** of the DAO according to his/her contribution. All contributions should be done in DAI, ETH or in any other liquid ERC-20 stable coin. 

**Q token and R tokens** might be transferable or non-transferable ERC-20 tokens. 

Each DAO is setting governing rules of functioning and operating according to Internal Governance Proposal approved by **Q - tokens holders** Voting.
 
##Reputation
Reputation is a powerful mechanism to incentivize Participants to take an Active role in DAO’s Governance and investment activity. Participant, no matter if he has or doesn’t have Reputation, may earn Reputation for a following activity:

1. ***Voting***. Any **Participant** who takes part in Votings of the DAO earns 1 (one) Reputation token, before consensus has been reached. 

2. ***Proposals***. Any Participant who makes proposal regarding Governance or Investment proposal earns Reputation tokens if the proposal has been accepted or executed.
Participant may initiate a Vote in the DAO only if he owns minimum required Reputation (a certain amount of tokens) set by the Investment memorandum of this DAO. 
Reputation represents a right to take part in DAO’s fees distribution. Any Participant who owns a Reputation tokens will get a reward from DAO’s activity proportionally to the amount of his Reputation tokens stake.
Reputation injection - DAO Participants may arbitrary decide to mint new Reputation tokens for any account, rewarding contractors, active members or others by Reputation Voting. Reputation injection is limited to 5% of total supply of R Tokens.

##The Roles
Every Participant can attend both roles in **DAO Universe**.

####Active role. 
Any Participant may take an active role in DAO’s Governance and Investment activity. As a reward, such a Participant will earn R tokens tokens in the following situations:

1. For every vote in any ongoing votes, Participant has made before consensus has been reached.
2. For every accepted proposal, regarding Governance or Investments, Participant put on voting. 

####Passive role. 
Any Participant may choose Passive role benefiting only from activity of other Participants of a DAO. Participant may choose an Active role at any time just by taking a part in Voting process or by making an Investment proposal. 

##The Funds
In DAO Universe several DAO’s for different investment strategies will be created: high risk strategies (Asteroids), moderate risk strategies (Planets), low risk strategies (Stars).

All proposed financial strategies will be measured according to 5 basic parameters: 

* Expected return E(Rp)
* Strategy Risk, return volatility 𝞂p
* Sharpe ratio 
* Time horizon t
* Liquidity L

Strategies that don’t fit the risk profile/time horizon/liquidity of a particular DAO won’t be accepted. 

##The Assets
As DAO Universe investment benchmark is US Dollar, the DAOs can keep their part or all of their working capital in DAI as a stable currency. 
Any other position should be considered as an investment action, which may only be executed after DAO investment proposal voting process.
Any participant should contribute into DAO with ETH or any other liquid ERC-20 stablecoin (according to the list approved by Participants voting). Participant should accept that all contributions other then ERC-20 stablecoins will be automatically converted by the DAO using a market order at the time frame outlined in parts of the DAO Universe Investment Memorandum.
Since DAO Vault is based on Ethereum blockchain only ETH and ERC-20 tokens are supported for now.

##Technological stack
DAO Universe is built using AragonOS from Aragon Network (aragon.org).
Aragon stack consists of different Layers included in overall solution: DOM Layer (Client UI+App UI), JS layer (Aragon UI, Script, aragon.js server, aragon.js client), EVM layer (Kernel, ACL, EVM Scripts, Apps)
AragonUI uses iframes and provide consistent experience for users across Aragon apps.
Permissions in each DAO are set in Access Control List.
Each is DAO is deployed mainnet with initial pre-determined setup, and then permissions might be changed according to current Tokens majority rule. Majority rule and quorum can not be altered after deployment.
AragonPM registry includes a number of installed applications including APMRegistry, one ENSSubdomainRegistrar and Repo instances. Each repo has a human-readable names, such as voting.aragonpm.eth
Each Aragon APP may be upgraded with smart-contract modifiers with added initialized function.
For building additional apps we use AragonAPI, writing Javascript implementations to interact with AragonOS handling pathing, upgradeability and state of the contracts.
Each DAO comes with 2 token smart-contracts, governing each action, 2 Voting application, Agent Vault for transacting with third party Dapps.

##Investment Proposals 
Participants, owning R tokens, may submit Investment proposals for partially managing the Assets. The maximum amount of Assets, which can be provided to any participant (for management), depends on the amount of R tokens, held by Participant.

If R token voting approves the Investment proposal, the Participant, who submitted it, should act as a manager and execute the proposal:

* Complete transactions according to the terms, indicated in the Investment proposal (until the transaction will be executed by the code).
* Participant is entitled to receive, transfer the funds, conduct the deals and perform other actions for the purposes of the Investment proposal execution.
* If the deal cannot be executed on the terms, indicated in Investment proposal (market conditions got worse, etc.), Participant should transfer the received Assets to the Vault.
* Finalize the deal and return the Assets to the Vault.
* Provide the report on the finalized deal.


Investment proposal should comply with one of the investment strategies, introduced in DAO Universe, and match the implied Risk and Return parameters for the strategy.
In general, Investment proposals will contain the detailed information on the trading idea and the deal terms, which will help other DAO participants to make a sophisticated decision: deal type (long/short trade; stake, compound, lend, ??), trading pair, deal direction, amount of assets, entrance price, target price and return, duration, investment rationale, etc.


###Long / Short Trade Investment Proposal Template


| Parameter                     |   | Comments                        |
|-------------------------------|---|---------------------------------|
| Deal type                     |   | * spot trade * derivative trade |
	

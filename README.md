<center>
    <h1>Dala: A decentralized financial ecosystem for emerging markets</h1>
    <h2 id="abstract">Abstract</h2>
</center>
<div style="text-align: justify; width: 600px; margin: 0 auto;">
Dala is a cryptocurrency that can be used for payments of any size, nearly instantaneously, and at almost zero cost. It’s very nature of being a cryptocurrency means it is borderless, and thus facilitates remittance transactions by its very nature. But Dala is more than that. It is the cornerstone of a financial services platform that has been designed to help those in most need of it - the financially excluded. This platform is global; bridging the divide between investors and consumers; creating opportunities for philanthropists, lenders, insurers, and most importantly, the financially excluded consumers.
</div>

## Toa
> Toa means *give* in Swahili.

### Introduction<div id="toa-introduction">
Dala is bringing the best protocols and blockchains together to deliver the best platform. So what are we looking for right now? Firstly, we need a reliable payments platform capable of processing millions of transactions at very low cost; and secondly, a robust, well-adopted, and turing-complete smart contracting platform. At this point in time, we have identified two public blockchains that we will build upon - Stellar for payments and Ethereum for smart contract capability.

The overriding premise of allowing $DALA to operate across chains is to ensure that the total $DALA in circulation across all active chains should never exceed the total amount of $DALA that was minted on Ethereum during the token sale in December 2017 - 1 billion tokens.

It is important to note that this space continues to evolve rapidly and we will be monitoring the environment closely. Should new blockchains or changes in existing ones indicate change is required, Dala will move towards creating the necessary swaps and contracts on the new chains. This is a public roadmap and consensus from the community would determine the future direction.

### Stellar<div id="toa-stellar">
**What is Stellar?**<div id="toa-stellar-what-is">

Stellar has been designed from the ground up to connect banks, payments systems, and people in order to move value quickly and reliably at almost no cost. Stellar also provides a smart contract platform that is geared heavily towards financial use cases. The Stellar network is a worldwide collection of Stellar Cores, each maintained by different people and organizations. All of these Stellar Cores - the network of nodes - eventually agree on sets of transactions. Each transaction attracts a very small fee to disincentivize bad actors on the network.

**What is an asset on Stellar?**<div id="toa-stellar-what-is-an-asset">

A Stellar asset is simply a credit from a particular account on the network. If you were to trade US dollars on Stellar, you’re not actually trading US dollars - you would be trading US dollar assets that have been credited from a particular account. It is important that there is trust in the issuer that they can redeem the credit if necessary. In Stellar, trust is represented by a trustline, simply a declaration from an account that it trusts a particular asset. Trustlines can also limit the amount of the asset that is trusted from a particular issuer.

**$DALA on Stellar**<div id="toa-dala-on-stellar">

To create the $DALA asset on Stellar, Dala will create three unique accounts: 

* Source account - this is the account of the entity that is creating the asset.
* Issuing account - this account is created by the source account to create new tokens.
* Distribution account - this account is for distributing tokens to the public.

The issuing account will create 1 billion $DALA tokens and send them to the distribution account. The issuing account will then be locked by setting all weights and thresholds to zero, making all keys invalid. This prevents the issuing account from ever creating any more transactions, preventing the creation of additional tokens. It is imperative that this initial supply matches what was originally minted on Ethereum during the initial token issuance. 

**Stellar Distributed Exchange**<div id="toa-stellar-dex">

The Stellar network acts as a decentralized, distributed exchange of any type of asset that has been added to the network. Accounts can make offers to buy or sell assets. The foundation will issue $DALA from Ethereum to Stellar to seed the order book and facilitate liquidity in the network, in accordance with the overall token supply schedule. The Dala control account will be the custodian of these tokens and make the requisite sell orders on the exchange. The exchange also facilitates cross-asset payments (paths of asset conversion can contain up to 6 hops) but the whole payment is atomic.

Lastly, Dala will also act as a $DALA anchor. Anchors are entities that are trusted to hold deposits and issue credits into the Stellar network for those deposits. 

**Summary**<div id="toa-stellar-summary">

Stellar is a reputable, public blockchain and has been created for the exact use cases that Dala is tackling. For this reason, Stellar will replace the existing off-chain scaling solution that Dala uses. This removes Dala as the primary arbitrator and facilitator of transactions on the network, moving from the current centralized exchange-type architecture to a decentralized network.

### Ethereum<div id="toa-ethereum">
**What is Ethereum?**<div id="toa-ethereum-what-is">

Ethereum is a decentralized blockchain platform that runs applications called smart contracts. These smart contracts execute exactly as programmed without any possibility of downtime, censorship, fraud, or third-party interference. This distributed global infrastructure enables developers to create new markets, store registries of debts or promises, move funds in accordance with predefined, immutable rule sets, maintain a decentralized identity, and many more things that have not been invented yet; all without middlemen or counterparty risk.

Ethereum is more than just a promise and has delivered on this time and again. This is most apparent by looking at the developer adoption:

* There is an order of magnitude more developers building on Ethereum than any other blockchain platform, and that gap is only getting wider.
* The Ethereum code school from Loom, CryptoZombies, has had over 200,000 users since November 2017 and is growing consistently by more than 30,000 per month.
* Truffle, an Ethereum development framework, has had over 500,000 downloads and is growing at over 45,000 per month.
* Developer adoption is important - generally, in order to have applications worth using, you need to attract enough developers to build them.
* Ethereum also brings the best tools and infrastructure for the development of distributed applications. As developer infrastructure grows, the more enjoyable and easier it becomes for new developers to build, and this cycle continues.

Furthermore, Ethereum does not sacrifice decentralization. In blockchain technologies, you often hear of the scalability trilemma. The scalability trilemma states that blockchain systems can only possess two of the following properties:

* Decentralization - enables censorship resistance and permits anyone to participate in the ecosystem without prejudice.
* Scalability - the ability to process transactions quickly for many, many users concurrently.
* Security - immutability of the ledger and resistance to attacks (e.g. 51%, Sybil, or DDos)

Ethereum prioritizes decentralization and security; this limits its suitability as a micropayments transaction platform (due to cost and speed) but at the same time creates a permissionless and censorship-resistant platform that can be used by anyone, for any purpose. No one can stop you uploading your smart contract or dApp and no one can stop your users from using it.

**What is an ERC20 token?**<div id="toa-ethereum-what-is-erc20">

ERC20 is a technical standard used for smart contracts on the Ethereum blockchain for implementing tokens. ERC stands for Ethereum Request for Comment, and 20 is the number that was assigned to this request. The clear majority of tokens issued on the Ethereum blockchain are ERC20 compliant.

$DALA was issued as an ERC20 token on the Ethereum blockchain at the start of the token sale in December 2017 with a fixed supply of 1 billion tokens.

### Atomic Swaps<div id="toa-atomic-swaps">
The circulating supply across all supported chains will never exceed the total supply that was created during the initial token issuance event in December 2017 - 1 billion $DALA.

Token supply control can be trustlessly adhered to by using atomic swap smart contracts that control the issuance and lock-up of tokens across the supported chains. The caveat to all participating chains would be that they support custom tokens analogous to ERC20 on Ethereum, as well as smart contract capability to support atomic swaps.

**What is an atomic swap?**<div id="toa-atomic-swaps-what-is">

An atomic swap allows for the exchange of one cryptocurrency for another cryptocurrency without the need for a trusted third party. It is paramount that this is atomic - this means that either the entire swap occurs successfully or none of it does.

Most cross-chain atomic swaps use what is called a hashed timelock contract (HTLC). In practical terms, this means that recipients of a transaction have to acknowledge payment by generating cryptographic proof within a certain timeframe. Otherwise, the transaction does not take place. This is probably easier to explain with an example using Stellar and Ethereum:

* Let’s assume Bob would like to swap 10 $DALA on Ethereum for 10 $DALA on Stellar. Mary has 10 $DALA on Stellar and would like to swap them for 10 $DALA on Ethereum. Now that we have willing participants, the swap can take place.
* First, Mary generates 32 random bytes and calls this the preimage, then computes the SHA256 hash of this preimage which is called the hashlock. The preimage is not shared by Mary until every required transaction has been set up.
* Mary generates a new Stellar keypair and calls this the swap keys. This account will act as a cryptographic escrow that holds the funds until the swap setup is complete.
* Mary then submits a Stellar transaction that does four things:

    1. Creates the swap account by sending the minimum XLM reserve balance to it;
    2. Moves 10 $DALA into the swap account;
    3. Locks the swap account with the hashlock and Bob’s public key;
    4. Removes the swap account private key as a signer;


* Bob is watching Mary’s Stellar account for the transaction and sees the new swap account, inspects the transaction, and extracts the hashlock from it.
* Bob now sends his 10 $DALA to an Ethereum smart contract which locks it with Mary’s Ethereum address as well as the hashlock.
* Mary sees this transaction and confirms that Bob’s Ethereum address, $DALA amount, and the hashlock are valid.
* Mary then claims her 10 $DALA from the Ethereum smart contract using the preimage that she generated in step one. Because this occurs on-chain, the preimage is now public knowledge.
* Bob is watching the Ethereum contract and sees that Mary has claimed the $DALA using her preimage; Bob can now use this preimage to claim the $DALA.
* Bob submits a Stellar transaction that claims the $DALA funds in the swap account using this preimage.

**$DALA Atomic Swaps**<div id="toa-atomic-swaps-dala">

Dala will be launching **Toa**, which encompasses the smart contracts (on both the Ethereum and Stellar blockchains) as well as a dApp.

Dala will initially only support atomic swaps between Dala ERC20 tokens on Ethereum and $DALA assets on Stellar. $DALA assets issued by the Dala foundation on Stellar can only enter circulation when atomically swapped from Ethereum. 

### Architecture<div id="toa-architecture">
![](https://s3-us-west-2.amazonaws.com/dharma-assets/WhitepaperV2Architecture.png)

## Soko

## Kazi

## Kopa
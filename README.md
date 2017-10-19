# Awesome Smart Contracts [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Curated list of platforms to run Smart Contracts.

### What is Smart Contract?

```
"New institutions, and new ways to formalize the relationships that make up these institutions, are now 
made possible by the digital revolution. I call these new contracts "smart", because they are far more 
functional than their inanimate paper-based ancestors. No use of artificial intelligence is implied. 
A smart contract is a set of promises, specified in digital form, including protocols within which the 
parties perform on these promises."

-Nick Szabo, 1996
```

### License
This document is licensed [WTFPL](http://www.wtfpl.net/txt/copying/)

### Contribute!
Share your knowledge. [Contributing guide](CONTRIBUTING.md)


## Platforms list

| Platform name                          | Contract language                                           | Live? |Origin | Inc. in     | Est.  | Pub. rel.|
|----------------------------------------|:-----------------------------------------------------------:|------:|------:|------------:|------:|----------|
| [Ethereum](https://www.ethereum.org/)  |  Solidity                                                   | Yes   | CA    |Switzerland  |2014.04|2015.07   |
| [Ethereum Classic](https://ethereumclassic.github.io/)|  Solidity                                    | Yes   | ^^^   | no          | ^^^   | ^^^      |
| [Neo](https://neo.org/)                |  1st batch: dotNet; 2nd: Java,Kotlin; 3rd: C,C++,GO,Py,JS (TBD)| Yes| China | China       |2014.06|2016.10   |
| [Ubiq](http://www.ubiqsmart.com/)      |  Solidity                                                   | Yes   | CA    | CA ?        |       |2017.01   |
| [Nem](https://nem.io/)                 |  ?                                                          | ?     |
| [Exonum](https://exonum.com)           |  Rust. Java bindings TBD                                    | No    | UA    |Netherlands  |       |2017.07   |
| [Qtum](https://qtum.org/)              |  Solidity                                                   | Yes   |Singapore|Singapore  |2016   |2017.09   |
| [Tezos](https://www.tezos.com)         |  Michelson                                                  | no    |
| [EOS](https://eos.io/)                 |  Web Assembly (aka WASM) ?                                  | no    |    
| [Urbit](https://urbit.org/)            |  Hoon                                                       | Yes   |    
| [Waves](https://wavesplatform.com/)    |  _NA_                                                       | Yes   |RU     |  ?          |2016   |2016.11   |    
| NXT                                    |  ?                                                          | Yes   |    
| Counterparty                           |  ?                                                          | Yes   |    
| [BitShares](https://bitshares.org/)    |  ?                                                          | Yes   |    
| hyperledger                            |  ?                                                          | ?     |    
| quorum                                 |  ?                                                          | ?     |    
| [Rootstock](http://www.rsk.co/)        |  Solidity                                                   | no    |Argentina|Argentina  |2015.11|
|[Cardano](https://cardanofoundation.org)|  Plutus (Haskell inspired)                                  | no    |HK       |Switzerland|2015   |
| [Universa](https://www.universa.io/)   |
| OmniLayer                              |
|[Corda](https://www.corda.net/)         |







## Ethereum

Ethereum is a gold standard in smart contracts and has biggest capitalization among other platforms.
Majority of token sales go on Ethereum platform,  with recently standartized token format ERC-20.

Founded by son of russian expats in Canada Vitalik Buterin. Incorporated in Switzerland.

Docs:
  * [solidity.readthedocs.io](http://solidity.readthedocs.io)
  * [Awesome Ethereum list](https://github.com/void4/awesome-ethereum)

Contract examples: 
* https://github.com/fivedogit/solidity-baby-steps
* https://github.com/OpenZeppelin/zeppelin-solidity/tree/master/contracts
* https://github.com/ConsenSys/

## Ethereum Classic

Classic appeared as a fork of main Ethereum chain (right after famous DAO hack) by a community that disagreed to 
alter the blockchain to get back stolen funds.
ETC is still in search of its place in smart contracts world. Some engineering changes are still going under the hood
(like, changing the emission and difficulty retarget algo), and developer tools are being developed. 
No major token crowdsales were made yet, but the community is looking forward to it.

Not incorporated.


## Neo

NEO (formerly Antshares) is a Chinese answer to Ethereum. Neo is a major player in SmartContracts world and 
often compared to Ethereum.

First batch of supported languages is ready for production use. Second is partially ready, and third is planned.

Docs:
 * [docs.neo.org/en-us/sc/introduction.html](http://docs.neo.org/en-us/sc/introduction.html)
 
Contract examples:
 * https://github.com/neo-project/examples-csharp

## Ubiq

Ubiq functions as a fork of Ethereum codebase, with several adjustmens, fully compatible with EVM and Solidity.

Governed by Ubiq Technology Inc.

## Urbit

WTF is dis

Contract examples: 
* https://github.com/urbit/examples


## Rootstock

Rootstock is a Bitcoin sidechain, adding Turing-complete language (enabling smart contracts) and ability to
scale up to 20k transactions per second (eventually). Sidechain shall be secured by a merge-mining with regular Bitcoin pools.

Rootstock is very well received by community, and among all 2nd layer solutions for Bitcoin is considered to be 
one of the closest to completion.

Language used shall be Solidity, and RSK VM is fully compatible with Ethereum VM.

Docs:
 * https://faq.rsk.co/en/main/
 * https://github.com/rsksmart/rskj/wiki
 * http://media.rsk.co/
    
    

## Cardano

Cardano claims it is the first Blockchain to use a provably secure, proof of stake algorithm.
Cardano is designed in separate layers, where the 1st layer (aka Settlement Layer; PoS blockchain) is already live (as of 2017.10),
and internal currency (Ada) being added to exchanges.

Second (aka computational) layer will run smart contracts using a Haskell-inspired scripting language, called Plutus,
and is scheduled to release in first quarter 2018.

Governed by The Cardano Foundation, IOHK and Emurgo.

Docs:
  * https://whycardano.com/
  * https://cardanodocs.com/technical/plutus/introduction/  
    
Contract examples:
  * https://cardanodocs.com/technical/plutus/examples/


## Exonum

Exonum is an extensible open-source framework for creating blockchain applications. It is designed to 
allow you, your company or your government to build a tailor-cut private or permissioned blockchain.  
Thus, there's no public Exonum network or traded Exonum tokens.

Exonum is developed and supported by the Bitfury Group.

```
Services are the main extension point for the Exonum framework. By itself, Exonum provides building 
blocks for creating blockchains; it does not come with any concrete transaction processing rules. 
This is where services come into play. If you want to create an instance of the Exonum blockchain, 
services are the way to go.
```

```
Endpoints defined by services fulfill the same role as smart contracts in other blockchain platforms. 
They define business logic of the blockchain, allow to retrieve data from the blockchain, and can be 
reused across different projects. Partial analogies for this execution model are endpoints of RESTful 
web services and stored procedures for DBMSs.
```

Docs:
  * https://exonum.com/doc/architecture/services/
  * https://exonum.com/doc/get-started/design-overview/#smart-contracting
  
Contract examples:
  * https://exonum.com/doc/get-started/create-service/
  
  
## BitShares

BitShares 2.0 is the first application of Graphene technology.


## Qtum

Qtum is a hybrid blockchain application platform. Qtum’s core technology combines a fork of bitcoin core, 
an Account Abstraction Layer allowing for multiple Virtual Machines including the Ethereum Virtual Machine (EVM) and Proof-of-Stake consensus.

Qtum smart contracts aim to be compatible with existing Ethereum contracts.

Main selling points of Qtum is: lite mobile wallets that can execute smart contracts; compatibility with existing bitcoin infrastructure/tools
(since Qtum forked off bitcoin, and aims to adopt most of bitcoin BIPs).

Qtum started in 2016, in 2017.03 Qtum had a crowdsale distributng their tokens. Main net launched on 2017.10.



## Waves

Waves is a PoS blockchain specifically designed to issue tokens (and run ICOs). Some of the largest ICOs were run on Waves Platform. 
Users can also lease funds to miners o generate interest.  There's also a decentralized exchange (DEX) with front-run protection, 
and gateways to common fiat currencies.

Smart contracts are planned (as stated on website), but not yet supported. 

Docs:
  * https://github.com/wavesplatform/Waves/wiki/Waves-Node-REST-API
  * https://github.com/wavesplatform/Waves/wiki/Matcher

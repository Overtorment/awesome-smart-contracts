# Awesome Smart Contracts [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Curated list of platforms to run Smart Contracts.

This document is licensed [WTFPL](http://www.wtfpl.net/txt/copying/)


| Platform name                          | Contract language                                           | Released |Origin | Inc. in     | Est.  | Pub. release.|
|----------------------------------------|:-----------------------------------------------------------:|---------:|------:|------------:|------:|--------------|
| [Ethereum](https://www.ethereum.org/)  |  [Solidity](http://solidity.readthedocs.io)                 | Yes      |RU/CA  |Switzerland  |2014.04|2015.07       |
| [Ethereum Classic](https://ethereumclassic.github.io/)|  Solidity                                    | Yes      | ^^^   | no          | ^^^   | ^^^          |
| [Neo](https://neo.org/)                |  1st batch: dotNet; 2nd: Java,Kotlin; 3rd: C,C++,GO,Py,JS (TBD)| Yes   | China | China       |2014.06|2016.10       |
| [Nem](https://nem.io/)                 |  ?                                                          | ?        |
| Exonum                                 |  ?                                                          | Yes      |
| Qtum                                   |  ?                                                          | ?        |
| [Tezos](https://www.tezos.com)         |  Michelson                                                  | no       |
| [EOS](https://eos.io/)                 |  Web Assembly (aka WASM) ?                                  | no       |    
| [Urbit](https://urbit.org/)            |  Hoon                                                       | Yes      |    
| Waves                                  |  ?                                                          | Yes      |    
| NXT                                    |  ?                                                          | Yes      |    
| Counterparty                           |  ?                                                          | Yes      |    
| BitShares                              |  ?                                                          | Yes      |    
| hyperledger                            |  ?                                                          | ?        |    
| quorum                                 |  ?                                                          | ?        |    
| [Rootstock](http://www.rsk.co/)        |  Solidity                                                   | no       |Argentina|Argentina   |2015.11|
|[Cardano](https://cardanofoundation.org)|  Plutus (Haskell inspired)                                  | no       |HK       |Switzerland |2014.12|







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

First batch on supported languages is ready for production use. Second is partially ready, and third is planned.

Docs:
 * [docs.neo.org/en-us/sc/introduction.html](http://docs.neo.org/en-us/sc/introduction.html)
 
Contract examples:
 * https://github.com/neo-project/examples-csharp

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
Cardano is designed in separate layers, where the 1st layer (PoS blockchain) is already live (as of 2017.10),
and internal currency (Ada) being added to exchanges.

Second (aka computational) layer will run smart contracts using a Haskell-inspired scripting language, called Plutus,
and is scheduled to release in first quarter 2018.

Docs:
  * https://cardanodocs.com/technical/plutus/introduction/  
    
Contract examples:
  * https://cardanodocs.com/technical/plutus/examples/

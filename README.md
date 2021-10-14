# LACChain Wiki

## History

LACChain is the Global Alliance for the Development of the Blockchain Ecosystem in Latin America and the Caribbean. This Alliance was founded in 20219 by the Innovation Lab of the Inter-American Development Bank (the IDB Lab). As of October of 2021, there are more than 50 entities working with blockchain technology that have signed an MOU with the IDB Lab to contribute to the LACChain Alliance.

* [IDB](https://www.iadb.org/en/about-us/overview)
* [IDB Lab](https://bidlab.org/en)
* [LACChain Partners](https://www.lacchain.net/alliance)

## Purpose 

The LACChain Global Alliance was created with the vision that blockchain technology could have a transformative impact in different sectors and industries, but also under the impression that there were many silos in the ecosystem, scarcity of information, regulatory uncertaintly, very expensive costs related to the use of the technology, a very concerning carbon footprint, and thousands of blockchain networks that were not suitable for the scalability of government and enterprise use cases. In order to address this issues and enable the use of blockchain technology in Latin America and the Caribbean in a way that empowers governments, private sector, universities, multilaterals, and enterpreneurs, but mostly **people**. 

LACChain aims to enable the **Internet of Value**. The Internet, as a network to connect people and entities remotely, in its current form does not allow for 
transferring both digital (e.g., a digital certificate or a digital currency) and physical (e.g., a painting, a car, or a house) assets electronically with full trust between unknown parties unless there is a trusted third-party involved. We believe the combination of the current Internet with a new robust and reliable **blockchain layer** properly provided with **digital identity** and **digital money** platforms can achieve full trust between remote and unknown parties without intermediaries, leading to a new digital era of digital services and transactions, and constituting the Internet of Value.

## Frameworks

LACChain Frameworks are sets of recommendations that encompases standards, protocols, technology, rules, policies, and agreements to enable the three layers of the Internet of Value: permissioned public blockchain networks, digital identity, and digital money.

* [LACChain Framework for Permissioned Public Blockchain Networks]() - A set of recommendations to build neutral, secure, multipurpose, multiprotocol, regulatory compliant, and quantum-resistant blockchain networks. Presents and discusses the concepts of operation, orchestration, and governance. Addresses topology, routing and connections, block generation, publicness, permissioning, resource distribution, node signatures, quantum-resistance, scalability, monitoring and evaluation, decentralized storage, and private channels. It also tackles regulatory matters.

* [LACChain Framework for Blockchain-Based Self-Sovereign Identity]() - A set of recommendations to build multipurpose, scalable, interoperable, secure, and privacy-preserving digital credentials and wallets. Covers decentralized identifiers, verifiable credentials and presentations, digital wallets, public key directories, trusted lists, certificate revocation lists, regulation, and trust frameworks.

* [LACChain Framework for Leveraging Tokenized Money for Retail Transactions, Cross-Border Payments, and Settlement and Clearing processes]() - Work in progress.

## Infrastructure

LACChain has enabled regional permissoned public blockchain infrastructures that are open and accessible for any entity in the world. The LACChain infrastructure includes networks build on [Hyperledger Besu technology (an open-source Ethereum client)](https://www.hyperledger.org/use/besu) and networks build on [EOSIO technology](https://eos.io/). In order to access the networks, it is necessary to follow the permissioning process. This process vary depending if the network to join is a Testnet, a Pro-Testnet, or a Mainnet. 

### Accessing the Networks

For Testnets and Protestnets:

* [Permissioning process for LACChain Testnets and Protestnets](https://github.com/lacchain/wiki/blob/main/permissioning_process.md)
* [Registration agreement for LACChain Testnets and Protestnets](https://github.com/lacchain/wiki/blob/main/registration_agreement.md)
* [Terms and conditions for writer nodes in Testnets and Protesnets](https://github.com/lacchain/wiki/blob/main/terms_and_conditions_writer_testnets.md)
* [Terms and conditions for validator and boot nodes in Testnets and Protesnests](https://github.com/lacchain/wiki/blob/main/terms_and_conditions_validator_testnets.md) 

For mainnets (yet to be released):
 
* Permissioning process for LACChain Mainnets - Work in progress
* SLA for validator and boot nodes in Mainnets - Work in progress
* SLA for writer nodes in Mainnets - Work in progress

The technical team of LACChain verifies the registration agreement and process to permission the entity in the network. Once a node is permission, there is no hierarchy ammong entities. All the entities running nodes are equal, and play different roles according to the [Topology of the LACChain Networks](https://github.com/lacchain/wiki/blob/main/LACChain_topology.md). To know more about the governance go to Section [LACNet Underlying Orchestration Vehicle](##LACNet-Underlying-Orchestration-Vehicle).

### Networks and tools using Hyperledger Besu Technology

 The LACChain Networks available using Hyperldedger Besu technology are the following:

* [LACChain Mainnet Alfa powered by Hyperledger Besu](https://github.com/lacchain/besu-mainnet) - To be launched in 2022. Membership-based. Intended to serve any use case compliant with regulation that requires guarantees in terms of support, resilience, and liabilities.
* [LACChain Protestnet powered by Hyperledger Besu](https://github.com/lacchain/besu-pro-testnet) - Open. Completely free (zero tx fees and no membership fee). Intended to serve any use case compliant with regulation under a best efforts support scenario.
* [LACChain DAVID19 testnet powered by Hyperledger Besu](https://github.com/lacchain/besu-pro-testnet/tree/david19_network) - Open. Completely free (zero tx fees and zero membership costs). Intended to serve any use case compliant with regulation under a best efforts support scenario.

Additionally, there are several open-source resources and tools available:

* [LACChain Framework for Permissioned Public Blockchain Networks]()
* [Full list of repositories related to the blockchain layer](https://github.com/lacchain/wiki/blob/main/repository_index_blockchain_layer.md) 

### Networks and tools using EOSIO Technology

 The LACChain Networks available using Hyperldedger Besu technology are the following:

* [LACChain Testnet powered by EOSIO](https://github.com/lacchain/eosio-network) - Open. Completely free (zero tx fees and no membership fee). Intended to serve any use case compliant with regulation under a best efforts support scenario.

Additionally, there are several open-source resources and tools available:

* [LACChain Framework for Permissioned Public Blockchain Networks]()
* [Full list of repositories related to the blockchain layer](https://github.com/lacchain/wiki/blob/main/repository_index_blockchain_layer.md) 

### LACChain ID

LACChain ID is the blockchain-based SSI layer developed by the LACChain Global Alliance. The main pieces released on this layer are:

Two books explaining Self-Sovereign Identity for all audiences and covering the legal aspects related to it in Latin-America and the Caribbean.

* [The future of Identity: Self-sovereignty, digital wallets, and blockchain](https://publications.iadb.org/en/self-sovereign-identity-future-identity-self-sovereignity-digital-wallets-and-blockchain)
* [Regulacion de blockchain e identidad digital en America Latina](https://publications.iadb.org/es/regulacion-de-blockchain-e-identidad-digital-en-america-latina)

A framework consisting on a set of recommendations to build multipurpose, scalable, interoperable, secure, and privacy-preserving digital credentials and wallets.

* [LACChain ID Framework]()

A open-source full stack that allows to implement SSI solutions compliant with the LACChain ID Framework on top of Ethereum-based networks.

* [LACChain ID Open-Source Stack for Ethereum-based Networks](https://github.com/lacchain/besu-id) 
* [LACChain did:lac method](https://github.com/lacchain/lacchain-did-js)
* [LACChain Universal Resolver](https://github.com/lacchain/universal-resolver)
* [LACChain Mailbox](https://github.com/lacchain/id-mailbox) 
* [Electronic authentication based on DIDConnect](https://github.com/lacchain/service-authentication) 
* [On-chain Roots of Trust and Trusted Lists](https://github.com/lacchain/lacchain-pkd) 

Additional open-source resources:

* [Full list of repositories related to the SSI layer](https://github.com/lacchain/wiki/blob/main/repository_index_id_layer.md) 

### LACChain Tokenized Money

LACChain Tokenized Money is the blockchain-based Tokenized Money layer developed by the LACChain Global Alliance. This layer is still at an early stage. The main pieces released on this layer are paper presenting the PoC accomplished by the Inter-American Development Bank and Citi Bank to make cross border payments between the US and the Caribbean using money tokenized in the LACChain Network and the code related to the development.

* [Paper - Cross border payments with blockchain](https://publications.iadb.org/en/cross-border-payments-blockchain)
* [Code - PoC between IDB and Citi on cross border payments](https://github.com/lacchain/wiki/blob/main/poc_idb_citi_cross_border.md)

## LACNet - Underlying Orchestration Vehicle

LACChain has created a non-profit entity based in Uruguay to orchestrate the LACChain mainnets ensuring technical and financial sustainability. The founders of this entity are [LACNIC](https://www.lacnic.net/), [Red Clara](https://www.redclara.net/index.php/en/), and the [IDB Lab](https://bidlab.org/en) as neutral and regional entities. More information will be added soon. Mainnets will be launched in 2022.

## Academy

LACChain Academy provides open content to educate and raise awareness about blockchain and structures its content into:

* [Videos](https://www.lacchain.net/academic-videos)
* [Courses](https://www.lacchain.net/certifiable-courses)
* [Publications](https://www.lacchain.net/academic-publications)

## Ecosystem

There are many different ways to participate in the LACChain Ecosystem. You can:

* [Become a partner](https://www.lacchain.net/contact)
* [Announce a bidding](https://www.lacchain.net/contact)
* [Announce a finding opportunity](https://www.lacchain.net/contact)
* [Spread your community, entity or event](https://www.lacchain.net/contact)
* [Promote your project, platform, or application deployed on top of a LACChain Network](https://www.lacchain.net/contact)
* [Announce a blockchain event](https://www.lacchain.net/contact)

You can also see current communities, entities, and events related to blockchain technology in Latin America and the Caribbean.

* [Communities](https://www.lacchain.net/ecosystem)
* [Entities](https://www.lacchain.net/ecosystem)
* [Events](https://www.lacchain.net/ecosystem)
* [Projects](https://www.lacchain.net/use-cases)
* [Bidding offerings](https://www.lacchain.net/use-cases)
* [Investment opportunities](https://www.lacchain.net/entrepreneurship)

## Contact

LACChain is available through different channels, including website, social networks, and Github.
 
* [LACChain Website](https://www.lacchain.net/home)
* [LACChain Linkedin](https://github.com/lacchain)
* [LACChain Twitter](https://twitter.com/lacchain?lang=en)
* [LACChain Medium](https://lacchain.medium.com/)
* [LACChain Vimeo](https://vimeo.com/lacchain)
* [LACChain Github](https://github.com/lacchain)

## Copyright 2021 LACChain

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.


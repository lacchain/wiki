# LACChain WIKI

## Introduction 

This document lists and describes the LACChain network Git repositories. All the repositories of the LACChain Alliance are licensed with Apache license version 2.0.

## Repository guide 

The following section describes the LACChain Git repositories and their corresponding layers in the LACChain ecosystem.  

The different layers of the LACChain ecosystem are: 

**LACChain DLT:** public-permissioned networks, open, decentralized, multipurpose, multi-community, scalable, regulated, with identification, and transaction fee free. 

**LACChain ID:** self-sovereign identity, decentralized identifiers (DIDs), verifiable credentials (VCs), verifiable presentations, digital wallets, CAs, trust lists, regulation, data protection, trust frameworks.  

**LACChain TFM:** tokenized fiat money, minted by authorized financial institutions, regulatory compliant. KYC and AML process. E-money token standard.  

The layers are built as the figure describes: 

### 2.1 LACChain DLT repositories 

**Besu-Network** **-** [**LINK**](https://github.com/lacchain/besu-network)

Description: this repository contains all the information on how to deploy nodes on the LACChain Besu Network, including information about the network’s topology, the permissioning process, how to deploy smart contracts, how to deploy applications, and recommendations on decentralized applications architecture.  

Among the relevant content of this repository: 

* Apache license version 2.0.  

* LACChain network permissioning process. 

* LACChain network topology and architecture. 

* Terms and conditions for writer nodes. 

* Terms and conditions for validator nodes. 

* Registration agreement form for node deployment on the LACChain network. 

* Generic onboarding provides instructions for the deployment of a node on the LACChain Besu Network with any OS. 

* List of permissioned nodes. 

* Monitoring tools. 

* How to connect your application to the LACChain network, including how to deploy Smart Contracts, connect external applications and broadcast transactions to the LACChain Besu Network. 

* Recommendations for decentralized applications architecture. 

**LACChain Network Docker** [**https://github.com/lacchain/lacchain-docker**](https://github.com/lacchain/lacchain-docker)

Description: this repository contains the docker container setup of a four-node network with the Block Explorer and the LACChain Prometheus & Grafana dashboard to track the progress of the chain for a Proof-Of-Authority example, allowing a DApp developer to use a simple network as an experimental testing ground for proof-of-concepts. Docker container configuration allows to run services and the network in POA mode and using the IBFT2 consensus algorithm.

**Gas Relay Signer** [**https://github.com/lacchain/gas-relay-signer**](https://github.com/lacchain/gas-relay-signer)

Description: this repository contains the source code for the gas distribution model that enables quantum-safe multi-signatures and the three goals intended to achieve in the implementation: 1. To enable a dynamic, functional, and easy to adopt solution for the distribution of gas in the LACChain (Besu) network, 2. To track and establish liabilities for the nodes that broadcast transactions to the network, and to verify that only writer nodes that are permissioned are broadcasting transactions, 3. To make the network quantum-safe.

## Copyright 2020 LACChain

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.


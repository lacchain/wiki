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

**LACChain Network Docker** **-** [**https://github.com/lacchain/lacchain-docker**](https://github.com/lacchain/lacchain-docker)

Description: this repository contains the docker container setup of a four-node network with the Block Explorer and the LACChain Prometheus & Grafana dashboard to track the progress of the chain for a Proof-Of-Authority example, allowing a DApp developer to use a simple network as an experimental testing ground for proof-of-concepts. Docker container configuration allows to run services and the network in POA mode and using the IBFT2 consensus algorithm.

**Gas Relay Signer** **-** [**https://github.com/lacchain/gas-relay-signer**](https://github.com/lacchain/gas-relay-signer)

Description: this repository contains the source code for the gas distribution model that enables quantum-safe multi-signatures and the three goals intended to achieve in the implementation: 1. To enable a dynamic, functional, and easy to adopt solution for the distribution of gas in the LACChain (Besu) network, 2. To track and establish liabilities for the nodes that broadcast transactions to the network, and to verify that only writer nodes that are permissioned are broadcasting transactions, 3. To make the network quantum-safe.

**EOSIO/LatamLink Testnet Node installation** **-** [**https://github.com/lacchain/eosio-network**](https://github.com/lacchain/eosio-network)

Description: this repository contains the files to setup an EOSIO-based testnet. LatamLink is a voluntary regional alliance led by Latin American technology companies interested in the development of the LACChain network ecosystem.

**IronBridge OpenSSL Engine** **-** [**https://github.com/lacchain/openssl-pqe-engine**](https://github.com/lacchain/openssl-pqe-engine)

Description: this repository contains the docker compose images for a minimal installation and usage of CQC’s IronBridge post-quantum entropy engine for OpenSSL connections among nodes on the LACChain network.

**TLS connections encapsulating Hyperledger Besu RPLx communication** **-** [**https://github.com/lacchain/rlpx-tls-tunnel-poc**](https://github.com/lacchain/rlpx-tls-tunnel-poc)

Description: this repository contains the docker container images and the docker compose configuration file for a proof of concept to enable TLS encapsulation of the communication between two Hyperledger Besu nodes that are using the RPLx protocol.

**Open Quantum Safe OpenSSL Debian files** **-** [**https://github.com/lacchain/oqs-openssl-debian**](https://github.com/lacchain/oqs-openssl-debian)

Description: this repository contains the files for generating Debian distribution packages for the OpenSSL fork that adds quantum-safe key exchange and authentication algorithms.

**LibOQS Debian files** **-** [**https://github.com/lacchain/liboqs-debian**](https://github.com/lacchain/liboqs-debian)

Description: this repository contains the docker container images and files for generating Debian distribution packages with the LibOQS library. LibOQS is an open source C library for quantum-safe cryptographic algorithms.

**Besu Health Check** **-** [**https://github.com/lacchain/besu-healthcheck**](https://github.com/lacchain/besu-healthcheck)

Description: this repository contains the docker container images and the docker compose configuration files for the Besu node health check service the enables users to test interactions with a Besu node using the RPC protocol.

**Node Health Check** **-** [**https://github.com/lacchain/node-health-check**](https://github.com/lacchain/node-health-check)

Description: this repository contains the source code for the node-health-check service that supports guaranteeing the availability of the Orion transaction manager used in the LACChain Besu network by writer nodes that execute private transactions. The source code aims to work hand-in-hand with the operating system, if for some reason the Orion service crashes, the node-health-check service restarts it.

**LACChain CLI** **-** [**https://github.com/lacchain/lacchain-cli**](https://github.com/lacchain/lacchain-cli)

Description: this repository contains the source code for a command line client to operate a LACChain node in the LACChain Besu network.

**Transaction per second throughput in Besu network** **-** [**https://github.com/lacchain/Ethereum-Benchmark**](https://github.com/lacchain/Ethereum-Benchmark)

Description: this repository contains the source code, smart contracts, docker container images and docker compose configuration for stress test suite that enables determining: a) How many transactions (with and without data) can be stored on each block, b) Establish a relation between gas and data for each transaction, and c) Expose a network node to different scenarios with different transaction rate and different amount of gas used per transaction at some time interval.

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


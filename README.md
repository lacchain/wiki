# LACChain Wiki

## Introduction 

LACChain Wiki lists and describes the LACChain network Git repositories. All the repositories of the LACChain Alliance are licensed with Apache license version 2.0.

## Repository guide 

The following section describes the LACChain Git repositories and their corresponding layers in the LACChain ecosystem.  

The different layers of the LACChain ecosystem are: 

**LACChain DLT:** public-permissioned networks, open, decentralized, multipurpose, multi-community, scalable, regulated, with identification, and transaction fee free. 

**LACChain ID:** self-sovereign identity, decentralized identifiers (DIDs), verifiable credentials (VCs), verifiable presentations, digital wallets, CAs, trust lists, regulation, data protection, trust frameworks.  

**LACChain TFM:** tokenized fiat money, minted by authorized financial institutions, regulatory compliant. KYC and AML process. E-money token standard.  

The layers are built as the figure describes: 
![alt text](https://github.com/lacchain/lacchain-id/blob/master/Internet_of_value.png "Internet of Value")

### 2.1 LACChain DLT repositories 

**Besu-Network** **-** [**https://github.com/lacchain/besu-network**](https://github.com/lacchain/besu-network)

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

**Remote PostQuantum OpenSSL RNG Engine** **-** [**https://github.com/lacchain/openssl-pqe-engine**](https://github.com/lacchain/openssl-pqe-engine)

Description: this repository contains an OpenSSL engine to obtain entropy from a remote server through a post quantum safe protocol.

**HTTP PostQuantum Entropy server provider** **-** [**https://github.com/lacchain/pqe-rpc-server-ng**](https://github.com/lacchain/pqe-rpc-server-ng)

Description: this repository contains a server to deliver entropy according a post quantum safe protocol.

**Post Quantum Meta-Transactions relay signer** **-** [**https://github.com/lacchain/pq-relay-signer**](https://github.com/lacchain/pq-relay-signer)

Description: this repository contains an application that relays a transaction to a destination contract adding a Falcon-512 signature.

**Post Quantum permissioning setup** **-** [**https://github.com/lacchain/pq-permissioning-setup**](https://github.com/lacchain/pq-permissioning-setup)

Description: this repository contains a Truffle project to configure Post Quantum permissioning for a [permissioned Hyperledger Besu network](https://besu.hyperledger.org/en/stable/Tutorials/Permissioning/Getting-Started-Onchain-Permissioning/) and a dummy relay contract. 

**PoC for encapsulating Hyperledger Besu RPLx communication through PQ TLS connections** **-** [**https://github.com/lacchain/pq-tls-rlpx-tunnel-poc**](https://github.com/lacchain/pq-tls-rlpx-tunnel-poc)

Description: this repository contains the docker container images and the docker compose configuration file for a proof of concept to enable TLS encapsulation of the communication between two Hyperledger Besu nodes that are using the RPLx protocol.

**Open Quantum Safe OpenSSL Debian files** **-** [**https://github.com/lacchain/oqs-openssl-debian**](https://github.com/lacchain/oqs-openssl-debian)

Description: this repository contains the files for generating Debian distribution packages for the OpenSSL fork that adds quantum-safe key exchange and authentication algorithms.

**LibOQS Debian files** **-** [**https://github.com/lacchain/liboqs-debian**](https://github.com/lacchain/liboqs-debian)

Description: this repository contains the docker container images and files for generating Debian distribution packages with the LibOQS library. LibOQS is an open source C library for quantum-safe cryptographic algorithms.

**LibOQS Java bindings** **-** [**https://github.com/lacchain/liboqs-java/**](https://github.com/lacchain/liboqs-java/)

Description: this repository contains a fork of [open-quantum-safe/liboqs-java](https://github.com/open-quantum-safe/liboqs-java) for publishing Apache Maven packages.

**HyperLedger Besu fork** **-** [**https://github.com/lacchain/besu**](https://github.com/lacchain/besu)

Description: this repository containes a Hyperledger Besu 20.10.3 fork which adds a precompiled contract for validating Falcon-512 signatures.

**Besu Health Check** **-** [**https://github.com/lacchain/besu-healthcheck**](https://github.com/lacchain/besu-healthcheck)

Description: this repository contains the docker container images and the docker compose configuration files for the Besu node health check service the enables users to test interactions with a Besu node using the RPC protocol.

**Node Health Check** **-** [**https://github.com/lacchain/node-health-check**](https://github.com/lacchain/node-health-check)

Description: this repository contains the source code for the node-health-check service that supports guaranteeing the availability of the Orion transaction manager used in the LACChain Besu network by writer nodes that execute private transactions. The source code aims to work hand-in-hand with the operating system, if for some reason the Orion service crashes, the node-health-check service restarts it.

**LACChain CLI** **-** [**https://github.com/lacchain/lacchain-cli**](https://github.com/lacchain/lacchain-cli)

Description: this repository contains the source code for a command line client to operate a LACChain node in the LACChain Besu network.

**Transaction per second throughput in Besu network** **-** [**https://github.com/lacchain/Ethereum-Benchmark**](https://github.com/lacchain/Ethereum-Benchmark)

Description: this repository contains the source code, smart contracts, docker container images and docker compose configuration for stress test suite that enables determining: a) How many transactions (with and without data) can be stored on each block, b) Establish a relation between gas and data for each transaction, and c) Expose a network node to different scenarios with different transaction rate and different amount of gas used per transaction at some time interval.

**Permissioning smart contracts** **-** [**https://github.com/lacchain/permissioning-smart-contracts**](https://github.com/lacchain/permissioning-smart-contracts)

Description: this repository is a fork from PegaSysEng/permissioning-smart-contracts, and contains the source code, smart contracts audited by third-parties and docker container image for on-chain node permissioning.

**LACChain BNDES Network** **-** [**https://github.com/lacchain/bndes-network**](https://github.com/lacchain/bndes-network)

Description: this repository is created as part of the relationship between the LACChain Alliance and the Brazilian Development Bank - BNDES to deploy a Public-Permissioned Blockchain Network maintained by both parts in order to develop and execute a different type of projects.

### 2.2 LACChain ID repositories

**LACChain DID Registry** **-** [**https://github.com/lacchain/lacchain-did-registry**](https://github.com/lacchain/lacchain-did-registry)

Description: this repository contains the Smart Contracts for LACChain DID method, that is intended to use Ethereum addresses as fully self-managed Decentralized Identifiers (DIDs), it allows you to easily create and manage keys for these identities. 

**LACChain DID NodeJS Library** **-** [**https://github.com/lacchain/lacchain-did-js**](https://github.com/lacchain/lacchain-did-js)

Description: this repository contains an implementation of LACChain DID Method in NodeJS. It provides the necessary methods and functions to interact with a DID and resolve a DID Document without the need to directly call the smart contracts.

**LACChain Mailbox** **-** [**https://github.com/lacchain/mailbox**](https://github.com/lacchain/mailbox)

Description: this repository contains the LACChain Mailbox, which is a secure and private system for the exchange of messages, VCs, and VPs based on the DIDComm Messaging Specification. It is a controlled by a centralized server that allows entities identified by a DID to send and receive messages.

**LACChain Universal Resolver** **-** [**https://github.com/lacchain/universal-resolver**](https://github.com/lacchain/universal-resolver)

Description: this repository contains the Universal DID Resolver, which implements different DID methods to resolve de DID Document. This project is currently deployed in the https://resolver.lacchain.net, but also can be deployed using the Docker image.

**LACChain Verifiable Credentials Registry** **-** [**https://github.com/lacchain/vc-contracts**](https://github.com/lacchain/vc-contracts)

Description: this repository contains the smart contracts based on EIP-712 and EIP-1812 for Structured Data Types and Verifiable Claims respectively, to perform the registration and verification process of Verifiable Credentials on-chain.

**LACChain DNS** **-** [**https://github.com/lacchain/lacchain-dns**](https://github.com/lacchain/lacchain-dns)

Description: this repository contains a smart contract and a decentralized application for the LACChain DNS that acts as a Decentralized Name Service that helps to maintain a registry of verified entities through a set of certificates issued by Certification Authorities (CA) associated with a DID (ethr). Certificates will be used to register and validate the entity in an Ethereum Smart contract, which we called: DNSRegistry. The provided DApp controls the entities registered in the DNSRegistry (listing, registration, and revocation).

**Post-Quantum Certificates** **-** [**https://github.com/lacchain/pq-cert**](https://github.com/lacchain/pq-cert)

Description: this repository contains the source code and the docker container images for the process for the issuance of a DID through a certifying authority, making use of different X.509 certificates validated by a root CA. The applicant must previously have a valid certificate (usually SSL), and a set of Ethereum keys in order to generate a Certificate Signing Request (CSR). Optionally, you can add a Post-Quantum key pair in the certificate request. As a final step, the certificate issued will have embedded both: the certificate data (SSL), as well as the Ethereum and Post-Quantum keys (if applicable).

**LACChain ID** **-** [**https://github.com/lacchain/lacchain-id**](https://github.com/lacchain/lacchain-id)

Description: this repository contains the description of the second layer of the LACChain network which consists of the Self-Sovereign Identity, that complements the first layer of public-permissioned blockchain networks by enabling the authentication and identification of the entities (individuals, organizations, things and processes) using the infrastructure. Assigning proper identifiers, it allows, as a principal use, to establish the ownership of the digital assets and settle legal accountabilities and responsibilities. The repository contains a Credential Registry contract.

**David19** **-** [**https://github.com/lacchain/david19-taskforce**](https://github.com/lacchain/david19-taskforce)

Description: this repository contains the verifiable credentials, smart contracts, and ansible playbooks for node deployment for the LACChain DAVID-19PAct® network. The DAVID-19PAct® is a task force where different LACChain partners collaborate to lead a campaign to provide useful blockchain-based solutions to combat the spread of the Coronavirus. The goal is to:

* Propose a standard for the forms and the verifiable credentials that are generated by different digital wallets to notarize information about isolation periods, symptoms, infection, and recovery.

* Create a single smart contract that will register all the cryptographic proofs of the credentials so every app whitelisted can register the proofs on it, and everyone can verify them against it. The smart contract also records the anonymous data in a decentralize way, so no central back-end/server is necessary.

* Provide a map where pseudonymous information about citizens is displayed with different colors depending on if they are healthy (blue), with symptoms (yellow), affected (red), or recovered (green). Additionally, dashboards will show total numbers of engagement and other useful information. The only information that is collected is age, sex, location, and information to notarize.

**David19 API** **-** [**https://github.com/lacchain/david19-api-nodejs**](https://github.com/lacchain/david19-api-nodejs)

Description: this repository contains the source code and docker container images for the API that serves the map within the DAVID-19PAct®, providing pseudonymous information about citizens health and dashboard.

**Credential service** **-** [**https://github.com/lacchain/credential-server**](https://github.com/lacchain/credential-server)

Description: this repository contains the source code and the docker container images for the Credential Provider Server that can generate, sign, validate, update, and revoke credentials. The credentials follow the standard Verifiable Credentials (VC) by the W3C. Credentials can be used to contain information about anything. Also, they can be signed by the issuer, and refer to a subject. Therefore, if the issuer is trusted by a third party, this third party can trust information about the subject by verifying the validity of the credential, without having to ask the issuer. When the previous is leveraged, and the subject is in control of their credentials, we can build identity models that fall into the category of self-sovereign identity (SSI).

**Academy Credential Issuance** **-** [**https://github.com/lacchain/academy-vc**](https://github.com/lacchain/academy-vc)

Description: 
LACChain VC is a Proof-Of-Concept application that allow issuance and on-chain verification of Verifiable Credentials (VC) following the W3C data model, EIP-712 and EIP-1812 for credential signatures and on-chain claims verification respectively.

**Hashing service** **-** [**https://github.com/lacchain/hashing-service**](https://github.com/lacchain/hashing-service)

Description: this repository contains the source code for the LACChain Hashing service that can hash any type of file, from applications to documents and media. Hashing a file results in a unique and irreversible identifier. If this identifier is registered in an immutable network, as a blockchain ledger, the owner of the file can prove at any time afterwards that the file was not modified. This hashing service signs the hash to guarantee that the file was hashed by itself and sends it to https://github.com/lacchain/credential-server to write it down in the LACChain blockchain network.

### 2.3 LACChain TFM repositories

**Citi API Proxy** **-** [**https://github.com/lacchain/citi-api-proxy**](https://github.com/lacchain/citi-api-proxy)

Description: this repository contains the source code and the docker container image for the Cross-Border Payments Citi WorldLink API integration proxy, that provides transparent access to Citi Bank WorldLink APIs (W3C XML Digital Signatures and Encryption only).

**Cross-Border Front** **-** [**https://github.com/lacchain/cross-border-front**](https://github.com/lacchain/cross-border-front)

Description: this repository contains the source code for the front-end of the Cross-Border Payments application on the LACChain network. The front-end interacts with the application back-end enabling users to sign-up/sign-in and use the different functionalities for tokenized money transfers with different currencies.

**Cross-Border Management** **-** [**https://github.com/lacchain/cross-border-management**](https://github.com/lacchain/cross-border-management)

Description: this repository contains the back-end components for the Cross-Border Payments application that manages Users, Accounts and Movements for the different functionalities. The back-end comprises the docker compose image, an API, the Eventeum component that listens to the LACChain DLT events, the Java source code that powers the API, and a PostgreSQL database.

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


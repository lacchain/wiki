# LACChain Blockchain Layer Repositories 

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

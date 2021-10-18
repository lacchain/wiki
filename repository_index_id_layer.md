# LACChain ID Repositories

**LACChain DID Registry** **-** [**https://github.com/lacchain/lacchain-did-registry**](https://github.com/lacchain/lacchain-did-registry)

Description: this repository contains the Smart Contracts for LACChain DID method, that is intended to use Ethereum addresses as fully self-managed Decentralized Identifiers (DIDs), it allows you to easily create and manage keys for these identities. 

**LACChain DID NodeJS Library** **-** [**https://github.com/lacchain/lacchain-did-js**](https://github.com/lacchain/lacchain-did-js)

Description: this repository contains an implementation of LACChain DID Method in NodeJS. It provides the necessary methods and functions to interact with a DID and resolve a DID Document without the need to directly call the smart contracts.

**LACChain Verifiable Credentials On-Chain Verification** **-** [**https://github.com/lacchain/vc-contracts**](https://github.com/lacchain/vc-contracts)

 Description: this repository contains the smart contracts based on EIP-712 and EIP-1812 for Structured Data Types and Verifiable Claims respectively, to perform the registration and verification process of Verifiable Credentials on-chain.
 
 **LACChain On-Chain Public Key Directory** **-** [**https://github.com/lacchain/lacchain-pkd**](https://github.com/lacchain/lacchain-pkd)

 Description: this repository is an implementation of Root-of-Trust proposal of LACChain ID Stack. The smart contracts helps to build a Root of Trust structure, by deploying a Public Key Directory (PKD) and a subset of Trusted List (TL) recursively to establish a hierarchy of entities.
 
 **LACChain Services Authentication** **-** [**https://github.com/lacchain/service-authentication**](https://github.com/lacchain/service-authentication)

 Description: this repository is the LACChain service authentication methods that are based on the use of a DID as an identity verification mechanism, using the public keys of a DID document to prove the identity of the entity that is in control of that DID.

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

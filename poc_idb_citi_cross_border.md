# Repositories related to the PoC between IDB and Citi Bank for cross border payments

This markdown contains the list of repositories with the code of the PoC between the Inter-American Development Bank and Citi to accomplish cross border payments from the US to the Caribbean using money tokenized in the LACChain Network. For for information read the [technical note](https://publications.iadb.org/en/cross-border-payments-blockchain).

**Citi API Proxy** **-** [**https://github.com/lacchain/citi-api-proxy**](https://github.com/lacchain/citi-api-proxy)

Description: this repository contains the source code and the docker container image for the Cross-Border Payments Citi WorldLink API integration proxy, that provides transparent access to Citi Bank WorldLink APIs (W3C XML Digital Signatures and Encryption only).

**Cross-Border Front** **-** [**https://github.com/lacchain/cross-border-front**](https://github.com/lacchain/cross-border-front)

Description: this repository contains the source code for the front-end of the Cross-Border Payments application on the LACChain network. The front-end interacts with the application back-end enabling users to sign-up/sign-in and use the different functionalities for tokenized money transfers with different currencies.

**Cross-Border Management** **-** [**https://github.com/lacchain/cross-border-management**](https://github.com/lacchain/cross-border-management)

Description: this repository contains the back-end components for the Cross-Border Payments application that manages Users, Accounts and Movements for the different functionalities. The back-end comprises the docker compose image, an API, the Eventeum component that listens to the LACChain DLT events, the Java source code that powers the API, and a PostgreSQL database.

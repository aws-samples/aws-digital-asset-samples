# AWS Digital Asset Samples

Reference architectures for digital asset workflows on AWS.

Explore AWS sample implementations for financial messaging integration, settlement, tokenization, price feeds, proof of reserves, and stablecoin payments.

## Reference patterns

| Use case | Repo | Pattern | Related blog |
| --- | --- | --- | --- |
| Connect off-chain financial instructions to digital asset settlement workflows | [Bridging financial messaging systems to digital asset settlement](https://github.com/aws-samples/sample-offchain-to-onchain-settlement) | Ingest, validate, orchestrate, and execute settlement instructions for on-chain token actions, such as issuance or redemption. | [Read blog](https://aws.amazon.com/blogs/web3/bridging-financial-messaging-systems-to-digital-asset-settlement/) |
| Deliver price, reserve, or collateral data to smart contracts | [AWS CRE Price Feeds & Proof of Reserves](https://github.com/aws-samples/sample-cre-price-feed-proof-of-reserves) | Use AWS services and Chainlink Runtime Environment (CRE) to deliver offchain data to smart contracts. | — |
| Process stablecoin payments on AWS | [Serverless Digital Asset Payments](https://github.com/aws-samples/sample-serverless-digital-asset-payments) | Create payment requests, monitor blockchain activity, confirm payments, and sweep funds to treasury. | [Read blog](https://aws.amazon.com/blogs/web3/processing-digital-asset-payments-on-aws/) |
| Secure private key custody and transaction signing | [AWS KMS Ethereum Accounts](https://github.com/aws-samples/aws-kms-ethereum-accounts), [AWS Nitro Enclave Blockchain Wallet](https://github.com/aws-samples/aws-nitro-enclave-blockchain-wallet) | Generate or import private keys in a hardened environment (KMS or Nitro Enclaves), sign transactions without exposing key material, and restrict signing authority through key policies or enclave attestation. | — |

## Example implementations

| Use case | Repo | Builds on |
| --- | --- | --- |
| Settle tokenized securities atomically (Delivery versus Payment) | [Digital Asset DvP](https://github.com/aws-samples/sample-digital-asset-delivery-vs-payment) | — |
| Agentic commerce with autonomous stablecoin micropayments and refunds | [Agentic Serverless Payments](https://github.com/aws-samples/sample-agentic-serverless-payments) | — |
| Issue and redeem tokenized commercial bank deposits | Tokenized deposits (coming soon) | Bridging financial messaging systems |
| Issue tokenized equity backed by verifiable price and reserve data | Derived equities (coming soon) | CRE Price Feeds & Proof of Reserves |

## Who this is for

Builders exploring digital asset architectures on AWS, including developers, solutions architects, fintech teams, Web3 teams, and financial services organizations.

## Get started

Open the sample that matches your use case and follow the setup instructions in that repository.

If this collection is useful, star the repository so you can find it again later.

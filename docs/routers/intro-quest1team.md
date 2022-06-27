# Introduction

## What are Routers?

## Why do we need them in Connext

## Security Assumptions and Risks
- **Seqencer downtime** (Connext's team will improve soon)
  
  The seqencer is responsible for collect the attempted transactions (bids) from all routers and choose which router fullfill the request So, if seqencer downtime the system will be down.
- **Funds delayed**

  The connext use Optimistic system that use fraud proofs to verify funds tranfer one chain to another so there is 30 minute window. During this time anyone watching the chain can prove fraud on the origin chain and disconnect to the destination chain. So the router has to wait for their funds until the disputing watcher be resovled.
- **Compromised router private key**

  If somebody can access to router's private key they can withdraw the liquidity to their wallet.
## Business Model

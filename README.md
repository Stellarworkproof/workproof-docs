# WorkProof Docs

WorkProof is an on-chain labour completion escrow for informal skilled trades.

This repository holds the product framing around the system: what problem it solves, how the MVP is split across repos, and how to demo the first version clearly.

## Problem statement

Across many informal trade markets, work begins with a handshake:

- the client worries about paying and getting abandoned
- the artisan worries about finishing work and not getting paid

WorkProof uses low-fee on-chain escrow on Stellar to make that exchange verifiable without turning a small job into a high-fee platform transaction.

## Repository map

- `workproof-contract`: Soroban contract for locking, releasing, disputing, and resolving funds
- `workproof-web`: mobile-first interface for clients and artisans
- `workproof-docs`: product notes, architecture framing, and demo material

## MVP definition

- client creates a job and locks funds
- artisan can see that the money is already committed
- client can release payment when work is complete
- either party can open a dispute
- approved arbitrators can resolve the escrow outcome

## Suggested demo flow

1. Start with a `NGN 40,000` job.
2. Show the client locking funds.
3. Show the artisan-facing view confirming that money is in escrow.
4. Move the job to work started.
5. Release payment and show the final paid state.
6. Rewind and trigger dispute to show the arbitration hook.

## Contents

- [ARCHITECTURE.md](/home/mainnetforker/Desktop/Talent/Stellar/project4/workproof-docs/ARCHITECTURE.md): workspace and repo split

## Near-term next steps

- wire the web app to live Soroban calls
- define arbitrator selection and reward rules
- add deployment and testnet usage guides
- write contributor and issue templates once the product shape stabilizes

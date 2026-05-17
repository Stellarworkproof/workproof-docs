# WorkProof Architecture

The workspace is split into standalone repositories so the contract, UI, and product notes can move independently inside a GitHub organization or a user namespace.

## Repositories

- `workproof-contract`: Soroban escrow contract for job locking, release, dispute, and resolution.
- `workproof-web`: Mobile-first frontend for client and artisan flows.
- `workproof-docs`: Product notes, demo script, and rollout context.

## Notes

- Stablecoin escrow is the core on-chain primitive.
- The UI is intentionally simple enough for low-friction mobile use.
- Arbitration is stubbed at the UX layer while the contract exposes the hook.

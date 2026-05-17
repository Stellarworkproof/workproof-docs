# WorkProof

WorkProof is an on-chain labour completion escrow for informal skilled trades.

## Standalone repos

- `workproof-contract`: Soroban smart contract for stablecoin escrow, release, dispute, and arbitrator resolution.
- `workproof-web`: Responsive mobile-first React app for client and artisan flows.
- `workproof-docs`: Product, demo, and deployment notes for the GitHub organisation.

## MVP scope

- Client locks payment into the contract at job start.
- Artisan sees that funds are locked before showing up.
- Client releases payment after completion.
- Either party can open a dispute.
- Approved arbitrator can resolve disputed funds to the artisan or client.

## Demo script

1. Create a job for `NGN 40,000`.
2. Tap `Lock funds`.
3. Share the job link with the artisan.
4. Move the job into work started.
5. Release payment after completion.
6. Optional: tap the amber dispute action to show the dispute hook.

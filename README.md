Treasury Sweeper

Overview

**Treasury Sweeper** is a permissionless Clarity smart contract designed to automatically consolidate idle or excess STX funds into a designated treasury address. It enables DAOs, protocols, and on-chain systems to maintain efficient treasury management without relying on centralized operators.

The contract allows anyone to trigger a sweep action while enforcing strict on-chain rules to ensure funds are transferred safely, transparently, and deterministically.

---

Key Features

- Permissionless treasury sweeping
- Secure and deterministic STX transfer logic
- On-chain transparency via read-only functions
- DAO and protocol-friendly treasury automation
- Lightweight and audit-friendly Clarity design

---

Use Cases

- DAO treasury consolidation
- Protocol revenue aggregation
- Automated fund housekeeping
- Reduction of fragmented or idle balances
- Trustless treasury maintenance

---

Contract Architecture

 Core Concepts

- **Treasury Address**  
  The destination address where swept funds are consolidated.

- **Sweep Trigger**  
  Any user can initiate a sweep when contract conditions are met.

- **Eligibility Rules**  
  Prevent invalid, duplicate, or unauthorized sweep operations.

---

Public Functions

`sweep-treasury`
Triggers the sweeping of eligible STX funds into the treasury address.

```clarity
(sweep-treasury)

License
MIT License

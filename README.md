# Proof‑of‑Build Pings (Base)

Minimal on‑chain "build pings". Call `ping("msg")` → emits `Ping(user, msg, timestamp, total)` and tracks per‑user stats.

## Contract
- **Mainnet**: `0x382f71b8e65a4f1ba863fa4d8e258bbfcb55d4b1`
- **Testnet (Base Sepolia)**: `0xc5b29ce3c4de2953970eaa8585a5b959a2985953`

## Verify
- Compiler: `v0.8.24+commit.e11b9ed9`
- Optimization: `enabled`, runs `200`
- License: `MIT`
- Constructor: none

## Frontend
Open `index.html` locally or host via GitHub Pages / Cloudflare Pages.
Edit `CONTRACT_ADDRESS` if you deploy a new instance.

## ABI
See `abi/ProofOfBuildPings.json`.

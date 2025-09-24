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


## Submission Notes
- Live dApp: https://laycryp.github.io/build-pings/
- Repo: https://github.com/Laycryp/build-pings
- Contract (Base): 0x382f71b8e65a4f1ba863fa4d8e258bbfcb55d4b1
- Deploy Tx: 0x7af3c6000087ab13ef54531237042f890209bc9abc7f6bea85c7bcd13b6a9b88
- Explorer: https://basescan.org/address/0x382f71b8e65a4f1ba863fa4d8e258bbfcb55d4b1
- How it works: `ping("msg")` emits `Ping(...)` and tracks per-user stats via `getStats(address)`.

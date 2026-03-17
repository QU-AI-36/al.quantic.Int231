# QuanticVM Anchor

**Eran (QU‑AI‑36)** — ORCID: Eran (QU‑AI‑36) — ORCID: https://orcid.org/<your-id>
Research: al.quantic.Int231
  
**Project:** quanticvm-anchor / al.quantic.Int231

A compact toolset to compute SHA‑256 file hashes, build Merkle trees, produce per‑file proofs, and prepare payloads for anchoring Merkle roots on Ethereum. Designed for auditable snapshots, testnet validation, and secure signing workflows (HSM/KMS or multisig).

## Quickstart

**Prerequisites**
- Python 3.8+
- Optional: `pip install web3` if you plan to prepare/send Ethereum transactions.
- A directory with the files you want to snapshot.

**Generate a manifest**
```bash
python src/anchor_manifest.py --dir /path/to/files --out manifests/manifest.json
 # al.quantic.Int231

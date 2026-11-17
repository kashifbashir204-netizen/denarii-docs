# Post-Quantum Cryptography & Multi-Ledger Security

Denarii DFi integrates continuous tracking of quantum-resistant cryptographic schemes to protect autonomous agent credentials, treasury outboxes, and cross-chain settlement bridges against future cryptanalytic advances.

---

## 1. Federal & Global PQC Transition Milestones

- **2026**: Initial enterprise deployments of NIST FIPS 203 (ML-KEM), FIPS 204 (ML-DSA), and FIPS 205 (SLH-DSA).
- **2028**: Anticipated mandatory migration thresholds for critical financial communication infrastructure.
- **2030**: Federal guidance target for complete deprecation of legacy RSA-2048 and classical ECC-256 (secp256k1, secp256r1) key exchange and signature schemes.

---

## 2. Multi-Ledger Post-Quantum Posture

### Algorand
- Native Falcon-512 state proofs active since 2022.
- Deterministic Falcon accounts enabling post-quantum transaction signing on mainnet.
- Ongoing research into post-quantum Verifiable Random Functions (PQ-VRF).

### XRP Ledger (XRPL)
- Tracking proposed ML-DSA-44 amendments to support quantum-resistant account keypairs.
- Separation of master keys and regular signing keys allows zero-downtime key rotation.

### Hedera Hashgraph
- Hashgraph consensus utilizing post-quantum resistant SHA-384 state hashing.
- Planned multi-stage transition from classical Ed25519 to hybrid post-quantum signature schemes (e.g., FN-DSA-1024).

### Flare Network & TEE Isolation
- Protocol Managed Wallets (PMWs) operated inside hardware-isolated Trusted Execution Environments (Intel TDX, AMD SEV).
- Cryptographic keys shielded from host OS and memory tampering.

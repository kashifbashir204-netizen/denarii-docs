# Agentic Protocols: MCP & Google Agent2Agent (A2A)

Denarii DFi integrates standard, vendor-neutral protocols for autonomous tool discovery, inter-agent communication, and cross-framework orchestration.

---

## 1. Model Context Protocol (MCP)

Denarii DFi agents interface with tools, databases, and blockchain RPC providers via the Model Context Protocol (MCP):
- **Tool Catalog**: Dynamic registration of over 4,000+ API tools, filesystem utilities, and on-chain signing bridges.
- **Client-Side Execution**: Tools execute with least-privilege scoping within sandboxed browser or local daemon environments.

---

## 2. Google Agent2Agent (A2A) Protocol

Denarii DFi publishes a public Agent Card compliant with the Linux Foundation / Google Agent2Agent (A2A) specification:
- **Card Endpoint**: `https://denarii-orchestrator.netlify.app/.well-known/agent.json`
- **Capabilities**: Multi-chain settlement, PQC compliance verification, and C2PA media provenance attestation.
- **Decoupled Identity**: Agents operate using W3C Verifiable Credentials (VCDM 2.0) with verifiable task completion proofs.

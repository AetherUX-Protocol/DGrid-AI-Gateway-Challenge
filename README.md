![DGrid-AI-Gateway-Challenge](https://github.com/user-attachments/assets/f5a4db36-0360-4cbd-9296-e6bb07cc2922)



# 🌐 DGrid AI Gateway Challenge
**Description:** Leaderless P2P AI Gateway

The **DGrid AI Gateway** is a resilient, sovereign settlement layer built for the Vertex Swarm Challenge. It utilizes **Tashi P2P rails** to ensure that AI agents can coordinate, settle IOUs, and maintain state integrity during network blackouts without a central leader.

---

## 🎭 The Swarm Characters

### 1. Aether-Alpha (The Initiator)
* **Role:** Detects x402 settlement triggers.
* **Function:** Broadcasts state changes to the mesh for immediate reconciliation.

### 2. Aether-Beta (The Witness)
* **Role:** Validates the P2P sync.
* **Function:** Mirrors the ledger for redundancy and handles failover during blackouts.

### 3. Mesh Arbiter (The Consensus)
* **Role:** The Tashi-backed decentralized logic.
* **Function:** Prevents double-spends and manages real-time agent reputation scores.

---

## 🛠 Core Tech Stack
* **Vertex / Tashi:** P2P messaging and leaderless consensus.
* **x402 Intercepts:** Automated agentic fee redirection.
* **Stateful Handshake:** Sub-second P2P state replication for high-stakes "PayFi."

## 📂 Repository Structure
* **/agents/aether_agent.py** — The executable core of the "Stateful Handshake."
* **/docs/PLAYBOOK.md** — The governance and "Arbiter Role" specifications.
* **LICENSE** — MIT License.

## 🚀 Technical Audit: Quick-Start
To verify **Bounty #1338 (Stateful Handshake)** and **Bounty #1337 (Leaderless Coordination)**:

1. **Initialize Swarm:** Launch two instances of `aether_agent.py` from the `/agents` folder.
2. **Verify Handshake:** Observe the logs for "Handshake Successful" and "State Synchronized."
3. **Simulate Blackout:** Force-close one agent; observe the second agent maintaining IOU ledger integrity via the Mesh Arbiter.

---

### 📜 Licensing
This project is licensed under the **MIT License**.

**Contact:** [ramanarolla/AetherUX]  
*Sovereign Agentic Rails for the New Internet.*

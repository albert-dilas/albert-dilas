# Albert Dilas

**Software & AI Systems Engineer**

Designing and shipping production-focused software: autonomous AI workflows, local-first desktop architectures, and full-stack web applications engineered for speed, reliability, and data sovereignty.

---

### Core Engineering Areas

- **AI Systems & Autonomous Agents**: Multi-agent orchestration, local CPU/ONNX inference pipelines (`faster-whisper`, `U2NetP`), deterministic verification loops, and RAG architectures.
- **Local-First Desktop & Systems Architecture**: Self-contained native applications running over `127.0.0.1` with zero telemetry, cryptographic update verification (`SHA-256`), and hop-by-hop network security (`Anti-SSRF`).
- **Full-Stack & Native Packaging**: Python (`FastAPI`, `Pytest`), TypeScript (`Next.js`, Finite State Machines, WebGL / Three.js), and deterministic builds (`PyInstaller`, `Inno Setup`, `Playwright E2E`).

---

### Open-Source & Production Systems

| System | Domain & Stack | Status & Links |
| :--- | :--- | :--- |
| **[Tornio](https://github.com/albert-dilas/Tornio)** | **Local-First Media & Document Workbench** (`Python / FastAPI / Next.js / FFmpeg / ONNX`)<br>58 offline tools across 7 Studios (PDF, Video, Audio, Image, Archive/Crypto, Local CPU AI, Web Capture). | `v3.0.0` (Apache 2.0)<br>[Repository](https://github.com/albert-dilas/Tornio) · [Interactive 3D Site](https://albert-dilas.github.io/Tornio/) · [Latest Release](https://github.com/albert-dilas/Tornio/releases/tag/v3.0.0) |

*(Additional systems and developer utilities in active development)*

---

### Engineering Principles

1. **Privacy by Architecture**: User files and sensitive computation belong on the user's hardware whenever possible.
2. **Explicit State & Zero Silent Failures**: Finite state modeling on the frontend paired with strict boundary validation and end-to-end automated testing on the backend.
3. **Production-Ready Distribution**: Software should install cleanly without intrusive privileges and verify its own integrity automatically.

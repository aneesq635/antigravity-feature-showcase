# ⚡ Antigravity - Feature Showcase & Zero-G Physics Lab

An interactive web application demonstrating the core architecture, reactive execution loop, and capabilities of **Antigravity** (Google DeepMind's Advanced Agentic Coding Assistant), coupled with an interactive **Zero-G physics simulation**.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/environment-Debian%2012%20Linux%20VM-cyan.svg)
![Architecture](https://img.shields.io/badge/architecture-Google%20DeepMind-indigo.svg)

---

## 🚀 Key Highlights & Features

### 1. 🧠 Agentic Cognitive Engine Visualizer
- **Step-by-Step Simulation**: Simulates the full agentic loop across four realistic developer scenarios:
  1. *Async Auth & Microservice Refactor*
  2. *Multi-Agent Swarm (`/teamwork`)*
  3. *Generative UI & Sandbox Artifacts*
  4. *Linux Core Dump & CI Debugger*
- **Live Streamed Internal Log**: Visualizes chain-of-thought (`<thought>`), tool dispatch, subagent communication, and artifact generation.
- **Speed & Control**: Adjustable playback speeds (1x, 2x) and reset controls.

### 2. 🌌 Zero-G Anti-Gravity Physics Lab
- **Interactive Force Fields**: High-performance HTML5 Canvas physics engine simulating inverted gravity ($-1.0g$ levitation to $+1.0g$ downforce).
- **Quantum Nodes**: Interactive draggable celestial nodes representing Antigravity components:
  - *Subagent Swarm*
  - *Debian 12 VM*
  - *Generative UI*
  - *DeepMind Brain*
  - *Reactive Wakeup*
  - *Slash Commands (`/goal`)*
  - *Skills Engine*
- **Dynamic Controls**: Particle friction sliders, gravity vector controls, quantum vortex mode, and explosive force pulse shockwaves.
- **Synthesized Audio**: Dynamic audio feedback synthesized entirely via the Web Audio API without external audio files.

### 3. ⚡ Core Capabilities Matrix
- **Subagent Swarms**: Concurrent background agents (`research`, `self`, `teamwork`, and dynamic custom agents via `define_subagent`).
- **Debian 12 Linux VM**: Non-root sandboxed execution environment with pre-installed Node.js 24 LTS, `uv`, Python 3.11, and GitHub CLI (`gh`).
- **Zero-Polling Reactive Wakeup**: Event-driven agent reactivation upon task and message delivery.
- **Generative UI**: Direct `<agent-embed>` chat widgets and standalone HTML artifacts styled with Tailwind CSS.
- **Workspace Plugins & Credential Proxy**: Outbound HTTP/HTTPS proxy managing zero-credential GitHub and Google Workspace workflows.
- **Slash Commands**: `/goal` (long-running autonomous loops), `/plan` (hierarchical roadmaps), `/grill-me` (design interviews), `/teamwork` (squad orchestration).

### 4. 💻 Interactive Sandbox Terminal
- Terminal emulator simulating shell commands inside the Antigravity sandbox:
  - `skills`: Inspect active capabilities
  - `subagents`: View background agents
  - `git-status`: Inspect repo branch & remote configuration
  - `run-tests`: Simulate running pytest suites
  - `/goal [task]`: Simulate autonomous goal execution
  - `zero-g`: Jump to physics visualizer

---

## 🛠️ Project Structure

```text
├── index.html        # Main standalone interactive showcase application
├── widget.html       # Compact inline Generative UI widget
├── package.json      # Quick scripts to run a local dev server
└── README.md         # Documentation & guide
```

---

## 🏃 Quick Start / Local Running

You can run this project locally using any static web server:

### Option A: Python 3
```bash
python3 -m http.server 8080
```
Then open `http://localhost:8080` in your browser.

### Option B: Node.js (npx)
```bash
npx serve .
```

### Option C: Direct Browser Open
Simply double-click or open `index.html` directly in any modern web browser (Chrome, Firefox, Safari, Edge).

---

## 🛡️ License

MIT License. Built with ❤️ for exploring Google DeepMind's Antigravity Agentic Coding Assistant.

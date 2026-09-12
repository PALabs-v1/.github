<h1 align="center">PALabs</h1>

<p align="center">
  <b>An experimental AI engineering lab building local-first, personalized and autonomous intelligent systems.</b>
</p>

<p align="center">
  <a href="https://github.com/PALabs-v1/AI_friend/releases/latest"><img src="https://img.shields.io/github/v/release/PALabs-v1/AI_friend?label=Release&color=orange&logo=github" alt="Release" /></a>
  <a href="https://github.com/PALabs-v1/AI_friend/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License: MIT" /></a>
  <a href="https://github.com/PALabs-v1/AI_friend/actions/workflows/ci.yml"><img src="https://github.com/PALabs-v1/AI_friend/actions/workflows/ci.yml/badge.svg" alt="CI" /></a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.12+-3776AB?logo=python&logoColor=white" alt="Python" /></a>
  <a href="https://www.rust-lang.org/"><img src="https://img.shields.io/badge/Rust-workspace-orange?logo=rust&logoColor=white" alt="Rust" /></a>
  <a href="https://palabs.vercel.app/docs"><img src="https://img.shields.io/badge/Docs-palabs.vercel.app-6366f1?logo=vercel&logoColor=white" alt="Docs" /></a>
</p>

<p align="center">
  <img src="assets/ai-friend-preview.png" alt="AI Friend interface preview" width="100%" />
</p>

**[📖 Documentation](https://palabs.vercel.app/docs)** · **[🚀 Quickstart](https://palabs.vercel.app/docs/getting-started/installation)** · **[🌐 Live Website](https://palabs.vercel.app/)** · **[💬 Discussions](https://github.com/PALabs-v1/AI_friend/discussions)** · **[📦 Latest Release](https://github.com/PALabs-v1/AI_friend/releases/latest)**

---

## Projects

### AI Friend

A local-first AI companion built around persistent cognition, affect, memory,
voice, vision and user-authored identity. Runs entirely on your own machine —
no API key required for the local-model path.

#### Quick start

```bash
git clone https://github.com/PALabs-v1/AI_friend.git
cd AI_friend
cp .env.example .env   # fill in the secrets it asks for
./start.sh              # or: make start
```

**Linux/macOS installer:**
```bash
curl -fsSL https://raw.githubusercontent.com/PALabs-v1/AI_friend/main/scripts/install.sh | bash
```

**Windows (PowerShell):**
```powershell
irm https://raw.githubusercontent.com/PALabs-v1/AI_friend/main/scripts/install.ps1 | iex
```

Needs [Docker](https://docs.docker.com/get-docker/) and
[Ollama](https://ollama.com) (`ollama serve` running, host-native) on a
machine with at least ~16GB RAM. A GPU is optional.

---

## Ecosystem repositories

| Repository | Description |
|---|---|
| **[AI_friend](https://github.com/PALabs-v1/AI_friend)** | **Core:** Python + Rust cognitive/affect/memory architecture, voice and vision agents, frontend. |
| **[website](https://github.com/PALabs-v1/website)** | **Docs & Landing:** Official website, docs hub, and live playground demos. |
| **[.github](https://github.com/PALabs-v1/.github)** | **Community & Health:** This organization profile, issue templates, and shared health files. |

---

## Contributors

[![Contributors](https://contrib.rocks/image?repo=PALabs-v1/AI_friend)](https://github.com/PALabs-v1/AI_friend/graphs/contributors)

---

## Principles

- Local-first where practical
- User-owned identity and data
- Measurable systems over AI demos
- Open engineering and reproducible research
- Human-centered personalized intelligence

---

MIT Licensed. Created by **Aniket Saha** ([@Aniket-a14](https://github.com/Aniket-a14)).
Contributions welcome — see [CONTRIBUTING.md](https://github.com/PALabs-v1/AI_friend/blob/main/CONTRIBUTING.md)
to get involved.

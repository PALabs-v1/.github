<h1 align="center">PALabs</h1>

<p align="center">
  <b>An experimental AI engineering lab building local-first, personalized and autonomous intelligent systems.</b>
</p>

<p align="center">
  <a href="https://github.com/PALabs-v1/AI_friend/releases/latest"><img src="https://img.shields.io/github/v/release/PALabs-v1/AI_friend?label=Release&color=orange&logo=github" alt="Release" /></a>
  <a href="https://github.com/PALabs-v1/AI_friend/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License: MIT" /></a>
  <a href="https://github.com/PALabs-v1/AI_friend/actions/workflows/ci.yml"><img src="https://github.com/PALabs-v1/AI_friend/actions/workflows/ci.yml/badge.svg" alt="CI" /></a>
  <a href="https://github.com/PALabs-v1/AI_friend/commits/main"><img src="https://img.shields.io/github/last-commit/PALabs-v1/AI_friend?color=blue" alt="Last commit" /></a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.12+-3776AB?logo=python&logoColor=white" alt="Python" /></a>
  <a href="https://www.rust-lang.org/"><img src="https://img.shields.io/badge/Rust-workspace-orange?logo=rust&logoColor=white" alt="Rust" /></a>
  <a href="https://palabs.vercel.app/docs"><img src="https://img.shields.io/badge/Docs-palabs.vercel.app-6366f1?logo=vercel&logoColor=white" alt="Docs" /></a>
</p>

<p align="center">
  <a href="https://palabs.vercel.app/">Website</a> ·
  <a href="https://palabs.vercel.app/docs">Documentation</a> ·
  <a href="https://palabs.vercel.app/docs/getting-started/installation">Quickstart</a> ·
  <a href="https://github.com/PALabs-v1/AI_friend/discussions">Discussions</a> ·
  <a href="https://github.com/PALabs-v1/AI_friend/releases/latest">Latest release</a>
</p>

<br />

<p align="center">
  <img src="assets/ai-friend-preview.png" alt="AI Friend interface preview" width="100%" />
</p>

<br />

We build systems that run on the user's own hardware, keep their state under
their own control, and get judged by what they measurably do — not by how
convincing a demo looks. Our first project, **AI Friend**, is the proving
ground for that approach: a companion with real cognitive and affective
state, not a chat wrapper.

## Projects

<table>
<tr>
<td width="120" valign="top"><b>AI Friend</b></td>
<td>

A local-first AI companion built around persistent cognition, affect, memory,
voice, vision and user-authored identity. Runs entirely on your own
machine — no API key required for the local-model path.

**Quick start**

```bash
git clone https://github.com/PALabs-v1/AI_friend.git
cd AI_friend
cp .env.example .env   # fill in the secrets it asks for
./start.sh              # or: make start
```

**Installers** — Linux/macOS:
```bash
curl -fsSL https://raw.githubusercontent.com/PALabs-v1/AI_friend/main/scripts/install.sh | bash
```
Windows (PowerShell):
```powershell
irm https://raw.githubusercontent.com/PALabs-v1/AI_friend/main/scripts/install.ps1 | iex
```

Needs [Docker](https://docs.docker.com/get-docker/) and
[Ollama](https://ollama.com) (`ollama serve` running, host-native) on a
machine with at least ~16GB RAM. A GPU is optional.

</td>
</tr>
</table>

## Ecosystem

| Repository | What it is | Stack |
|---|---|---|
| **[AI_friend](https://github.com/PALabs-v1/AI_friend)** | Core: cognitive/affect/memory architecture, voice and vision agents, frontend | Python · Rust · Next.js |
| **[website](https://github.com/PALabs-v1/website)** | Official website, docs hub, and live playground demos | Next.js · TypeScript |
| **[.github](https://github.com/PALabs-v1/.github)** | This organization profile, issue templates, shared health files | — |

## How we work

| | |
|---|---|
| **Local-first** | Runs on the user's own hardware where practical, not a cloud dependency by default |
| **User-owned** | Identity, memory, and data stay under the user's control |
| **Measured, not demoed** | Every claim ties to a test, an eval, or a metric — not a curated screen recording |
| **Open engineering** | Reproducible research, documented trade-offs, an engineering ledger that stays honest about what's not built |
| **Human-centered** | Personalization serves the person using it, not engagement metrics |

## Contributors

[![Contributors](https://contrib.rocks/image?repo=PALabs-v1/AI_friend)](https://github.com/PALabs-v1/AI_friend/graphs/contributors)

---

<p align="center">
MIT Licensed · Created by <b>Aniket Saha</b> (<a href="https://github.com/Aniket-a14">@Aniket-a14</a>)<br/>
Contributions welcome — see <a href="https://github.com/PALabs-v1/AI_friend/blob/main/CONTRIBUTING.md">CONTRIBUTING.md</a> to get involved.
</p>

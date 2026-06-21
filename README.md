# TrueLink

**Self-hosted. Truly private. Truly yours.**

TrueLink is an open-source, self-hosted messaging platform designed to be **more powerful than WhatsApp** while giving you complete control over your data.

No Big Tech. No phone number required. Full end-to-end encryption by default. Built for individuals, families, communities, and organizations who want privacy without compromise.

## Why TrueLink?

- **True Ownership** — Run it on your own server (Docker one-click). Your data never leaves your infrastructure.
- **True Privacy** — End-to-end encryption (MLS / Signal Protocol) enabled by default. Minimal metadata. No tracking.
- **True Power** — Federation-ready (future Matrix compatibility), unlimited groups, advanced threading, AI-powered summaries, voice/video calls, seamless media, and more.
- **True Freedom** — Open source (AGPL-3.0), no vendor lock-in, customizable, and extensible.

## Key Features (Current + Roadmap)

### ✅ MVP (In Progress)
- Self-hosted Docker deployment (PostgreSQL + Redis + MinIO)
- User registration (email/username, no phone mandatory)
- E2EE 1:1 and group messaging
- Real-time delivery via WebSockets
- Basic web + mobile client support

### 🚀 Coming Soon
- Federation (talk to users on other TrueLink servers)
- Large communities & channels
- Voice & video calls (WebRTC)
- AI message summaries & smart search
- Disappearing messages, polls, reactions, threading
- Bridges to WhatsApp/Signal/Telegram (optional)
- Multi-device sync without a primary device
- Admin dashboard for self-hosters

## Quick Start

```bash
git clone https://github.com/YOURUSERNAME/truelink.git
cd truelink
cp .env.example .env
docker compose up -d

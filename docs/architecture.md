# TrueLink Architecture

## High-Level
- Clients → Caddy (HTTPS) → Backend (Go)
- Backend uses PostgreSQL for metadata, Redis for real-time, MinIO for media
- E2EE using MLS / libsignal

## Components
- Auth Service
- Message Service
- Real-time (WebSocket)
- etc.

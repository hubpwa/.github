
---
<div align="center">

hubpwa

Public distribution for the PWA self-hosted stack

Installer & container images — pullable without authentication.

</div>

---
🚀 Install

Quick install (always latest):

curl -fsSL https://install.hubpwa.com/bootstrap.sh | sudo bash

Pin a specific version:

curl -fsSL https://github.com/hubpwa/installer/releases/latest/download/bootstrap.sh | sudo bash

Supports Ubuntu 20.04+ · Debian 11 / 12 / 13 · x86_64 / aarch64.

📦 Container images

All images live under ghcr.io/hubpwa/* and pull anonymously:

┌────────────────────────┬──────────────────────────┐
│         Image          │         Purpose          │
├────────────────────────┼──────────────────────────┤
│ ghcr.io/hubpwa/core    │ Backend — HTTP + workers │
├────────────────────────┼──────────────────────────┤
│ ghcr.io/hubpwa/app     │ Admin frontend           │
├────────────────────────┼──────────────────────────┤
│ ghcr.io/hubpwa/client  │ Client frontend          │
├────────────────────────┼──────────────────────────┤
│ ghcr.io/hubpwa/tds     │ Traffic distribution     │
├────────────────────────┼──────────────────────────┤
│ ghcr.io/hubpwa/landing │ Landing pages            │
├────────────────────────┼──────────────────────────┤
│ ghcr.io/hubpwa/filter  │ Traffic filter           │
├────────────────────────┼──────────────────────────┤
│ ghcr.io/hubpwa/nginx   │ Reverse proxy            │
└────────────────────────┴──────────────────────────┘

🔗 Links

- 🌐 Install — https://install.hubpwa.com
- 📥 Releases — https://github.com/hubpwa/installer/releases

---

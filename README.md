# SEFM — Syrotech Enterprise File Manager

> A secure, multi-department file management system with smart search and intelligent file merging.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## What is SEFM?

SEFM is an internal file management tool that replaces scattered Excel files, pen drives, and shared folders with a single secure web app. Each department has its own private space. Department heads control access. Files can be searched globally and merged intelligently.

## Key Features

- **Department-based access control** — secure isolation per team
- **OTP-based authentication** — email + 6-digit OTP, login alerts on every signin
- **Smart file merging** — combine CSV/Excel files with mismatched headers
- **Full operation pipeline** — filter, sort, clean, aggregate, export
- **Global search** — find files across all accessible departments in <1 second
- **Audit log** — every action tracked

## Tech Stack

- **Frontend:** React, Vite, Tailwind CSS
- **Backend:** Node.js, Express
- **Merge engine:** Python, FastAPI, pandas
- **Database:** PostgreSQL
- **Cache:** Redis
- **Storage:** MinIO (S3-compatible)
- **Auth:** JWT + bcrypt + Nodemailer

## Quick Start

\`\`\`bash
git clone https://github.com/YOUR-USERNAME/syrotech-sefm.git
cd syrotech-sefm
cp .env.example .env
docker-compose up -d
npm install
npm run dev
\`\`\`

Open http://localhost:3000

## Documentation

- Architecture — coming soon
- API Reference — coming soon
- Deployment — coming soon

## Testing

\`\`\`bash
npm test
npm run test:cov
\`\`\`

## Project Status

🚧 **In active development.** Currently in Month 1: Foundation phase.

## License

MIT — see [LICENSE](LICENSE)
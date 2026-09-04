# TrustTag 🔐

A full-stack verification platform designed to issue, store, and securely verify corporate credentials and documents (such as offer letters and certificates) using unique digital verification links and QR codes.

---

```markdown
# 🏷️ TrustTag

> A secure, verifiable digital vault for authenticating corporate credentials, offer letters, and experience certificates via tamper-proof verification links and QR codes.

---

## 📌 Overview

**TrustTag** eliminates credential fraud by enabling issuers (companies, institutions) to generate verifiable, tamper-evident digital records. Recruiters and third-party verifiers can instantly validate documents via dedicated verification pages or scanned QR codes without manual background check delays.

---

## ✨ Features

- 🔐 **Cryptographic Verification:** Tamper-proof validation for certificates and letters.
- 📱 **QR Code Access:** Instant verification via scannable QR tags on documents.
- ⚡ **Real-time Lookup:** Rapid, reliable credential checks for recruiters.
- 🛡️ **Role-Based Access:** Secure management workflows for issuing and viewing credentials.

---

## 🛠️ Tech Stack

- **Frontend:** React, TypeScript, Tailwind CSS, Vite
- **Backend / Database:** Node.js, Supabase (PostgreSQL, Auth, Storage)
- **Deployment:** Vercel / Netlify

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or pnpm
- A Supabase account and active project

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Gnaneshwar-reddy883/trust-tag.git
   cd trust-tag
npm install
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
npm run dev
trust-tag/
├── backend/          # Backend logic & helper scripts
├── src/              # React frontend application
├── supabase/         # Supabase migrations, schemas, and configurations
├── public/           # Static assets
└── package.json      # Project dependencies and scripts

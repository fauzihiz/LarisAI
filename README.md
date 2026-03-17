# LarisAI 🚀
**Customer Support Automation for Indonesian MSMEs (UMKM)**

LarisAI adalah platform otomasi layanan pelanggan berbasis AI yang dirancang khusus untuk membantu UMKM di Indonesia. Dengan teknologi RAG (Retrieval-Augmented Generation), LarisAI memungkinkan pemilik usaha untuk mengunggah katalog produk atau dokumen FAQ, sehingga AI dapat menjawab pertanyaan pelanggan secara otomatis dengan gaya bahasa lokal yang natural dan akurat.

## 🛠 Tech Stack
- **Framework**: Next.js 16 (App Router)
- **Database & Vector Store**: Supabase (pgvector)
- **AI Engine**: Google Gemini 1.5 Flash
- **Embeddings**: text-embedding-004
- **Language**: TypeScript
- **Styling**: Tailwind CSS

## 🗺 Roadmap & Progress
Track pengerjaan fitur LarisAI langkah demi langkah:

- [x] **Phase 1: Setup & Data Storage**
  - [x] Inisialisasi Project Next.js
  - [ ] Konfigurasi Supabase Schema & Extension `pgvector`
- [ ] **Phase 2: PDF Processing & Embeddings**
  - [ ] Implementasi PDF parser
  - [ ] Logika chunking teks
  - [ ] Integrasi Gemini Embedding API (text-embedding-004)
- [ ] **Phase 3: RAG Engine & AI Integration**
  - [ ] Implementasi similarity search di Supabase
  - [ ] Integrasi Gemini 1.5 Flash untuk Chat Response
  - [ ] Prompt Engineering (Persona UMKM Indonesia yang ramah)
- [ ] **Phase 4: API & Frontend**
  - [ ] API Route untuk Handle Chat & Upload
  - [ ] Dashboard Admin (Upload Katalog)
  - [ ] Floating Chat Widget untuk Customer
- [ ] **Phase 5: Refinement**
  - [ ] Audit Token & Optimasi Biaya
  - [ ] Testing & Deployment ke Vercel

## 🚀 Getting Started
1. Clone repository
2. Install dependencies: `npm install` di dalam folder `larisai`
3. Setup `.env.local` dengan API Key Gemini & Supabase
4. Jalankan aplikasi: `npm run dev`

---
*Dibuat dengan ❤️ untuk UMKM Indonesia.*
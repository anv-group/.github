# anv-group / .github

> Repositori pusat konfigurasi, standar rekayasa perangkat lunak, dan instruksi AI coding agent untuk organisasi **ANV Group**.

---

## 🏛️ Tentang ANV Group
**ANV Group** adalah tim rekayasa perangkat lunak siswa dari SMKN 1 Jenangan, Indonesia, dengan semangat *"driven by curiosity and constructive chaos"*. Kami berfokus pada pengembangan aplikasi web modern berbasis ekosistem Laravel, PostgreSQL, Blade, dan TailwindCSS.

- **Website / Redirect Portal**: [anvgroup.my.id](https://anvgroup.my.id)
- **Organisasi GitHub**: [github.com/anv-group](https://github.com/anv-group)

---

## 👥 Anggota Tim & Pembagian Peran

| Developer | Peran Utama | Domain & Tanggung Jawab |
|---|---|---|
| [@aldenasf](https://github.com/aldenasf) | **Lead Backend & System Architect** | Skema database, migrasi, arsitektur model Eloquent, rute web/API, autentikasi Breeze, dan core business logic. |
| [@alfianRapa](https://github.com/alfianRapa) | **Backend Developer** | Controller logic, API endpoints, request validation, database seeders, dan automated testing (Pest/PHPUnit). |
| [@SaaMasy](https://github.com/SaaMasy) | **Frontend & UI/UX Developer** | Desain visual, reusable Blade components, tatanan halaman (*layout*), dan responsivitas TailwindCSS. |
| [@vypashaa](https://github.com/vypashaa) | **Frontend & UI/UX Developer** | Desain interaksi, modal forms, status indicators/widgets, reusable Blade components, dan TailwindCSS styling. |

---

## 📂 Struktur Berkas Instruksi AI

Repositori ini menyediakan konteks tunggal (*single source of truth*) yang dapat dibaca oleh berbagai AI coding agent:

* [**AGENTS.md**](AGENTS.md) — Panduan standar universal untuk AI agent (Cursor, Claude Code, Antigravity, Windsurf, Roo Code, Codex, Aider) yang mencakup latar belakang organisasi, pembagian tugas, dan prinsip pengembangan.
* [**.github/copilot-instructions.md**](.github/copilot-instructions.md) — Instruksi tingkat organisasi khusus untuk GitHub Copilot Chat di seluruh repositori ANV Group.

---

## ⚙️ Prinsip Pengembangan Kunci

1. **Decoupled Development (Blade Mocking)**: Frontend mendesain komponen Blade yang modular dan independen menggunakan \@props\ dengan *default fallback*, sehingga tim frontend tidak terblokir oleh endpoint backend yang sedang dibuat.
2. **Delegasi Tugas Presisi**: Seluruh *issue* dan tugas backend diarahkan ke @aldenasf dan @alfianRapa. Seluruh tugas tampilan dan komponen UI diarahkan ke @SaaMasy dan @vypashaa.
3. **Standar Kode & Pengujian**: Menggunakan *Conventional Commits* dan pengujian otomatis berbasis Pest PHP untuk memastikan keandalan rute dan logika aplikasi.

---

## 🚀 Repositori Terkait
* [**todo-app**](https://github.com/anv-group/todo-app): Aplikasi manajemen tugas kolaboratif berbasis Laravel & Blade.
* [**coming-soon**](https://github.com/anv-group/coming-soon): Landing page dan portal pengalihan menuju organisasi ANV Group.
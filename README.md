# Audit Competency Strategy Assessment
**Internal Audit Division · Asuransi Umum Indonesia**

Asesmen berbasis simulasi untuk Ketua Tim Audit & Anggota Tim Audit  
21 Kompetensi · 7 Skenario · Referensi: Global Internal Audit Standards (GIAS) IIA 2024

---

## Panduan Deploy ke GitHub Pages (Step by Step)

> Ikuti langkah berikut untuk mendapatkan link publik yang bisa diakses seluruh tim tanpa perlu instalasi apapun.

---

### TAHAP 1 — Buat Akun GitHub (lewati jika sudah punya)

1. Buka **[github.com](https://github.com)**
2. Klik tombol **"Sign up"** di pojok kanan atas
3. Isi email, password, dan username (contoh: `internal-audit-xyz`)
4. Verifikasi email yang masuk di inbox Anda
5. Pilih plan **Free** saat ditanya

---

### TAHAP 2 — Buat Repository Baru

1. Setelah login, klik tombol **"+"** di pojok kanan atas → pilih **"New repository"**
2. Isi form berikut:

   | Field | Nilai yang diisi |
   |---|---|
   | Repository name | `audit-competency-assessment` |
   | Description | Audit Competency Strategy Assessment — Internal Audit |
   | Visibility | **Public** *(wajib agar GitHub Pages bisa aktif)* |
   | Add a README | ✅ Centang ini |

3. Klik tombol **"Create repository"**

---

### TAHAP 3 — Upload File Asesmen

1. Di halaman repository yang baru dibuat, klik tombol **"Add file"** → pilih **"Upload files"**
2. Drag & drop atau pilih **dua file** berikut:
   - `index.html` ← **rename file `audit_competency_strategy_assessment.html` menjadi `index.html` sebelum upload**
   - `README.md` ← file panduan ini (opsional)
3. Di bagian bawah halaman, isi commit message: `"Add assessment files"`
4. Klik **"Commit changes"**

> ⚠️ **Penting:** File HTML **harus** diberi nama `index.html` agar GitHub Pages mengenalinya sebagai halaman utama.

---

### TAHAP 4 — Aktifkan GitHub Pages

1. Di halaman repository, klik tab **"Settings"** (ikon roda gigi)
2. Di menu kiri, scroll ke bawah dan klik **"Pages"**
3. Di bagian **"Source"**, pilih:
   - Branch: **`main`**
   - Folder: **`/ (root)`**
4. Klik **"Save"**
5. Tunggu 1–2 menit, lalu refresh halaman
6. GitHub akan menampilkan banner hijau dengan link:

   ```
   Your site is published at:
   https://[username].github.io/audit-competency-assessment/
   ```

7. **Salin link tersebut** — ini adalah link permanen yang bisa dibagikan ke seluruh tim

---

### TAHAP 5 — Bagikan ke Tim

Bagikan link GitHub Pages melalui:
- **WhatsApp/Telegram group** tim audit
- **Email blast** ke seluruh peserta
- **Kalender undangan** sebagai link sesi asesmen

Peserta tidak perlu akun GitHub atau instalasi apapun. Cukup buka link di browser (HP atau laptop).

---

## Cara Update Konten di Masa Depan

Jika ada perubahan skenario atau perbaikan:

1. Buka repository di GitHub
2. Klik file `index.html`
3. Klik ikon **pensil** (Edit) di pojok kanan
4. Lakukan perubahan langsung di browser
5. Klik **"Commit changes"**
6. Perubahan otomatis live dalam 1–2 menit tanpa perlu upload ulang

---

## Struktur File Repository

```
audit-competency-assessment/
├── index.html          ← File utama aplikasi asesmen
└── README.md           ← Panduan ini
```

---

## Referensi Standar

| Standar | Deskripsi |
|---|---|
| **GIAS IIA 2024 — Domain I** | Purpose of Internal Auditing |
| **GIAS IIA 2024 — Domain II** | Ethics & Professionalism |
| **GIAS IIA 2024 — Domain III** | Governing the Internal Audit Function |
| **GIAS IIA 2024 — Domain IV** | Managing the Internal Audit Function |
| **GIAS IIA 2024 — Domain V** | Performing Internal Audit Services |
| **IIA Std. 11.1** | Risk-Based Internal Audit Planning |
| **IIA Std. 13.1** | Sufficient, Reliable & Relevant Evidence |
| **IIA Std. 13.3** | Fraud Consideration in Internal Auditing |
| **IIA Std. 13.4** | Fraud & Irregularities |
| **IIA Std. 14.2** | Technology Risk in Internal Auditing |
| **IIA Std. 15.1** | Integrity & Objectivity |
| **IIA Std. 15.2** | Objectivity in Evidence |
| **IIA Std. 16.1** | Communicating Audit Results |
| **IIA Std. 16.2** | Regulatory Reporting |
| **POJK No. 73/POJK.05/2016** | Tata Kelola Perusahaan Asuransi |
| **POJK No. 11/2022** | Keamanan Data & Sistem Informasi |

---

*Audit Competency Strategy Assessment v2.0 · Konfidensial — Hanya untuk penggunaan internal*

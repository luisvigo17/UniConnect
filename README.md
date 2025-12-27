
# UniConnect 🎓🤝

> Satu platform untuk kebutuhan mahasiswa: **Marketplace barang bekas**, **Berbagi catatan kuliah**, dan **GoU (bantuan pindahan)**.

UniConnect adalah project MVP (Minimum Viable Product) yang dibuat untuk memvalidasi kebutuhan utama mahasiswa sesuai project charter: transaksi barang bekas antar mahasiswa, berbagi materi/catatan kuliah, serta pemesanan bantuan pindahan.

---

## ✨ Highlights
- 🛒 **Marketplace**: list barang, detail barang, ajukan transaksi
- 📘 **Catatan**: list catatan, detail catatan, download
- 🚚 **GoU**: form booking bantuan pindahan + status booking
- 🧑‍💻 **Dashboard**: pusat aktivitas user
- 🛡️ **Admin Panel (MVP)**: moderasi posting & manajemen user

---

## 🎯 Tujuan MVP
MVP UniConnect berfokus pada:
- Memvalidasi minat dan kebutuhan fitur inti
- Menguji alur pengguna dari onboarding → penggunaan fitur
- Menghasilkan feedback cepat untuk iterasi berikutnya

> Catatan: MVP **tidak** mengejar fitur lengkap, melainkan kecepatan validasi.

---

## ✅ Ruang Lingkup (Scope)
### Termasuk
- Landing Page
- Login & Registrasi
- Dashboard User
- Marketplace (List + Detail)
- Catatan (List + Detail)
- GoU (Booking + Status)
- Admin Panel (moderasi & user management)

### Tidak Termasuk (Non-Goals)
- Chat pribadi antar user
- Mobile app (fokus web-first/desktop)
- Integrasi email kampus (sementara input manual)
- Sistem pembayaran & escrow (di MVP hanya “ajukan transaksi”)

---

## 🧭 User Flow Singkat
1. User membuka Landing Page  
2. Klik **Daftar**  
3. Login → Dashboard  
4. Pilih fitur (Marketplace / Catatan / GoU)  
5. Melakukan aksi (ajukan transaksi / download / booking)

---

## 🧩 Modul / Fitur (Detail)
### 1) Marketplace
- Search & filter (kategori, harga)
- Card barang (foto, nama, harga, kampus penjual)
- Detail barang + CTA **Ajukan Transaksi**

### 2) Catatan
- Filter mata kuliah & kampus
- Card catatan (judul, mata kuliah, uploader)
- Detail catatan + preview singkat + tombol **Download**

### 3) GoU
- Form booking: lokasi asal, tujuan, tanggal, deskripsi barang
- Status: menunggu → diproses → selesai

### 4) Admin Panel (MVP)
- Moderasi posting marketplace
- Moderasi catatan
- Manajemen user

---

## 🎨 UI/UX Guidelines (MVP)
- Minimal & fungsional (tanpa animasi berat)
- Konsistensi warna, ikon, layout
- Web-first (desktop)

**Skema warna:**
- Primary: `#2563EB`
- Secondary: `#F3F4F6`
- Accent: `#22C55E`

Font: Poppins/Inter (heading), Inter/Roboto (body)

---

## 🛠️ Tech Stack

- Frontend: `React/Vite` atau `Next.js` atau `HTML/CSS/JS`
- Styling: `TailwindCSS / Bootstrap / CSS Modules`
- Backend (opsional): `Node.js/Express` atau `Laravel` atau `Firebase`
- Database (opsional): `PostgreSQL/MySQL/MongoDB`
- Auth (MVP): basic auth (email+password), tanpa verifikasi email kampus

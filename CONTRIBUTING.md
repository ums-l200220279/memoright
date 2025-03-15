# 📜 CONTRIBUTING.md - Panduan Kontribusi untuk Memoright

Terima kasih telah tertarik untuk berkontribusi ke Memoright! 🚀
Dokumen ini akan membantu Anda memahami bagaimana cara berkontribusi dengan efektif dan sesuai dengan standar proyek.

---

## 🛠 Setup Proyek

Sebelum mulai berkontribusi, pastikan Anda sudah memiliki:

- **Node.js** (versi terbaru disarankan)
- **pnpm atau npm** (menggunakan pnpm lebih disarankan)
- **Git** untuk version control

### 1️⃣ Clone Repository

```sh
git clone https://github.com/ums-L200220279/memoright.git
cd memoright
```

### 2️⃣ Instalasi Dependencies

Gunakan salah satu dari perintah berikut sesuai package manager yang digunakan:

```sh
pnpm install  # Disarankan
# atau
npm install
```

### 3️⃣ Menjalankan Project secara Lokal

```sh
pnpm dev
# atau
npm run dev
```

---

## 📌 Aturan Kontribusi

### 🔹 1. Membuka Issue

Sebelum membuat issue baru, pastikan belum ada issue serupa di tab **Issues**.
Jelaskan secara rinci bug, fitur baru, atau perbaikan yang diperlukan.

#### **Format Issue Baru:**

```md

### Deskripsi
Jelaskan masalah atau fitur yang ingin ditambahkan.

### Langkah Reproduksi (Jika Bug)
1. Buka halaman...
2. Klik tombol...
3. Terjadi error...

### Solusi yang Diusulkan
Bagaimana cara memperbaikinya?
```

### 🔹 2. Membuat Pull Request (PR)

1. **Fork** repository ke akun GitHub Anda.
2. Buat branch baru dengan format:

```sh
git checkout -b feature/nama-fitur
# atau
git checkout -b fix/nama-perbaikan
```

1. Pastikan kode Anda telah dites sebelum membuat PR.
2. Tambahkan deskripsi PR dengan format berikut:

#### **Format Pull Request:**

```md
### Ringkasan Perubahan
Jelaskan perubahan yang dibuat secara singkat.

### Perubahan yang Dilakukan
- [ ] ✨ Fitur baru: ...
- [ ] 🐛 Perbaikan bug: ...
- [ ] 📚 Update dokumentasi: ...

### Checklist
- [ ] Kode sudah diuji secara lokal
- [ ] Tidak ada error atau warning di console
- [ ] Sudah mengikuti standar kode (ESLint, Prettier)
```

---

## 🎨 Standar Kode

### 📌 Format & Linting

Sebelum commit, pastikan kode Anda sudah bersih dari error dan mengikuti format yang benar:

```sh
pnpm lint
# atau
npm run lint
```

### 🔹 Struktur Commit Message

Gunakan format **Conventional Commits** untuk penulisan commit message:

```sh
feat: Menambahkan fitur baru untuk dashboard
fix: Memperbaiki bug pada login
docs: Memperbarui dokumentasi API
style: Memperbaiki format kode tanpa mengubah fungsionalitas
```

---

## 🤝 Kolaborasi

Jika ingin aktif berkontribusi, silakan bergabung di **Discord/Forum/GitHub Discussions** kami untuk berdiskusi lebih lanjut! 🚀

Terima kasih atas kontribusinya! ❤️

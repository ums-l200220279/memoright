# Memoright

Memoright adalah aplikasi yang menggunakan **Emotion Recognition berbasis Deep Learning** untuk membantu pengguna meningkatkan kesehatan mental mereka melalui pendekatan **Soul Care**.

## 🚀 Fitur Utama

- **Emotion Recognition** → Menganalisis ekspresi pengguna untuk memahami emosi.
- **Rekomendasi Personalisasi** → Memberikan konten yang sesuai berdasarkan emosi pengguna.
- **Meditasi & Mindfulness** → Menyediakan latihan relaksasi untuk meningkatkan kesejahteraan jiwa.
- **Jurnal & Refleksi** → Tempat bagi pengguna untuk menuliskan perasaan mereka.

## 📂 Struktur Proyek

```
memoright/
│── public/                   # Aset publik (ikon, gambar, dll.)
│── src/                      # Folder utama untuk kode sumber
│   │── app/                  # Routing utama (Next.js App Router)
│   │── components/           # Komponen UI reusable
│   │── hooks/                # Custom React hooks
│   │── lib/                  # Helper functions
│   │── pages/                # Routing Next.js Pages Router (jika digunakan)
│   │── styles/               # Styling tambahan
│   │── utils/                # Fungsi utilitas
│── .gitignore                # File yang diabaikan oleh Git
│── next.config.mjs           # Konfigurasi utama Next.js
│── package.json              # Dependencies & scripts
│── postcss.config.mjs        # Konfigurasi PostCSS
│── tailwind.config.js        # Konfigurasi Tailwind CSS
│── tsconfig.json             # Konfigurasi TypeScript
│── README.md                 # Dokumentasi proyek
```

## 🛠️ Teknologi yang Digunakan

- **Next.js** (v15.2.2) → Framework React untuk aplikasi web.
- **React** (v19) → Library utama untuk UI.
- **TypeScript** → Superset JavaScript yang lebih aman.
- **Tailwind CSS** → Utility-first CSS framework.
- **Deep Learning (TensorFlow.js/PyTorch)** → Untuk analisis ekspresi wajah.

## 📌 Instalasi & Menjalankan Proyek

1. **Clone repository**

   ```sh
   git clone https://github.com/username/memoright.git
   cd memoright
   ```

2. **Instal dependencies**

   ```sh
   npm install
   ```

   atau jika menggunakan PNPM:

   ```sh
   pnpm install
   ```

3. **Menjalankan proyek dalam mode pengembangan**

   ```sh
   npm run dev
   ```

   atau

   ```sh
   pnpm dev
   ```

4. **Build untuk produksi**

   ```sh
   npm run build
   ```

5. **Menjalankan aplikasi setelah build**

   ```sh
   npm start
   ```

## 📌 Konfigurasi Environment

Buat file `.env.local` di root proyek untuk menyimpan variabel lingkungan seperti:

```
NEXT_PUBLIC_API_URL=https://api.memoright.com
NEXT_PUBLIC_DEEP_LEARNING_MODEL=/models/emotion_model.tflite
```

## ✅ Kontribusi

Jika ingin berkontribusi, silakan fork repository ini dan buat pull request! Jangan lupa baca **CONTRIBUTING.md** (jika ada).

## 📄 Lisensi

Proyek ini dilisensikan di bawah **MIT License** – silakan lihat file `LICENSE` untuk detail lebih lanjut.

=======
This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

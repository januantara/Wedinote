
<div align="center">

  <img src="./public/logo.svg" alt="Wedinote Logo" width="140" style="background-color: white; padding: 12px; border-radius: 8px;" />

  ### Digital Wedding Invitation Manager

  **Kelola dan kirim undangan pernikahan digital dengan mudah dan elegan**

  [![Next.js](https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
  [![Bun](https://img.shields.io/badge/Bun-latest-fbf0df?style=for-the-badge&logo=bun)](https://bun.sh/)
  [![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Neon-316192?style=for-the-badge&logo=postgresql)](https://neon.tech/)

  [Demo](#) • [Fitur](#-fitur-utama) • [Tech Stack](#-tech-stack) • [Getting Started](#-getting-started)

</div>

---

## 📸 Preview

<div align="center">
  <img src="./public/home.png" alt="Wedinote Dashboard" width="100%" style="border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);" />
</div>

---

## ✨ Tentang Wedinote

**Wedinote** adalah aplikasi web yang memudahkan pengelolaan dan penyebaran undangan pernikahan digital. Wedinote membantu kamu:

- 📝 Membuat template ucapan yang dapat dikustomisasi sesuai dengan nama tamu
- 👥 Mengelola daftar tamu dan menambahkannya secara batch
- 🎯 Melacak status undangan (sudah diundang / belum)
- 💬 Mengirim undangan langsung ke WhatsApp

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|-----------|
| **Framework** | [Next.js 15](https://nextjs.org/) |
| **Language** | [TypeScript](https://www.typescriptlang.org/) |
| **Runtime** | [Bun](https://bun.sh/) |
| **Database** | [Neon PostgreSQL](https://neon.tech/) |
| **ORM** | [Drizzle](https://orm.drizzle.team/) |
| **Authentication** | [Better Auth](https://www.better-auth.com/) |
| **Styling** | Tailwind CSS |

---

## ✅ Fitur

- [x] Buat, edit, hapus template ucapan undangan
- [x] Sisipkan variable dalam template (mis. {{nama}}, {{acara}}) untuk personalisasi pesan
- [x] Kelola daftar tamu (tambah / edit / hapus)
- [x] Tambah tamu secara batch menggunakan csv
- [x] Filter tamu berdasarkan status: "Diundang" / "Belum"
- [x] Mode tampilan daftar: grid / list
- [x] Pratinjau pesan untuk setiap tamu (render variable ke konten final)
- [x] Direct share ke WhatsApp — kirim pesan yang sudah dipersonalisasi langsung ke nomor tamu
- [x] Tombol copy/share cepat untuk setiap entri tamu

---

## 🤝 Contributing

1. Fork repository ini
2. Buat branch fitur (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

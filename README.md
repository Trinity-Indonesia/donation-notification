# 💸 Donation Notification Skript
**Donation Notification** adalah skrip sederhana untuk server Minecraft yang menggunakan plugin [Skript](https://github.com/SkriptLang/Skript). Skrip ini memungkinkan admin mengirim notifikasi top-up yang menarik dan interaktif ke semua pemain di server.

## 📦 Fitur
- 🔔 Menampilkan notifikasi top-up dengan **title**, **subtitle**, dan **chat broadcast**.
- 🔊 Efek suara dinamis untuk meningkatkan pengalaman pemain.
- ✅ Cek input otomatis untuk validasi nama dan jumlah top-up.
- ⚙️ Perintah dapat digunakan hanya oleh player dengan permission `trakteer.use`.

## 🧾 Contoh Penggunaan
Gunakan perintah berikut di dalam game:
`/topup <nama_pemain> <jumlah>`
Tidak ada TAB completion untuk nama pemain agar pemain Bedrock Edition dengan prefix bisa digunakan
Contoh:
`/topup Louis 100000`

## 🎉 Apa yang Terjadi?
Setelah perintah dijalankan:
- Semua pemain menerima notifikasi title seperti:
  > **Louis**  
  > telah topup sebesar 💎 100000!
- Chat broadcast muncul:
  > [!] Terimakasih, **Louis** telah topup sebesar 💎 100000! [/store]
- Efek suara:
  - `levelup`
  - `experience_orb.pickup`
  - `note_block.pling`

## 🔐 Permission
Untuk dapat menjalankan perintah ini, pemain harus memiliki permission:
`trakteer.use`

## 📂 Instalasi
1. Pastikan plugin **Skript** sudah terinstal di server kamu.
2. Salin skrip ini ke dalam file dengan ekstensi `.sk`, contoh: `donation.sk`.
3. Tempatkan file tersebut ke dalam folder `plugins/Skript/scripts/`.
4. Ubah command atau perintah ketika pemain melakukan donasi
5. Reload skrip dengan perintah: `/skript reload donation-notification.sk`

## 🧠 Catatan
- Skrip ini tidak benar-benar melakukan transaksi top-up. Ini hanya untuk notifikasi visual dan suara.
- Sangat cocok digunakan untuk server dengan sistem manual top-up atau integrasi pihak ketiga.

## 🤝 Kontribusi
Jika kamu punya ide atau ingin menambahkan fitur, feel free untuk buka pull request atau buat issue!

## 📜 Lisensi
Proyek ini dilisensikan di bawah [MIT License](LICENSE).


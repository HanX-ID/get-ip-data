
# Penjelasan Singkat

Ini adalah project sebuah code HTML sederhana yang saya buat, untuk secara otomatis mengambil dan mengumpulkan data pengunjung (seperti IP, lokasi, bahasa, baterai, resolusi layar, dll) dan mengirimkannya ke bot Telegram milik admin.

---

## Fitur

- Mengambil IP dan data lokasi menggunakan API `ip-api.com`
- Menangkap status baterai pengguna jika didukung browser
- Menyimpan resolusi layar, bahasa, dan zona waktu pengguna
- Mengirim semua data tersebut ke bot Telegram admin
- Interface simpel dengan gambar dan link redirect

---

## Edit Token & Admin ID 
   Buka file HTML dan ganti bagian berikut:
   ```js

   const token = '-'; // Ganti dengan bot token kamu
   const chat_id = '-'; // Ganti dengan ID Telegram kamu

```
**Author** [HanX](https://github.com/HanX-ID)

# 🔥 **Mengenal Perintah `gh config delete` di GitHub CLI** 🛠️

## 📚 **Apa Itu `gh config delete`?**

Pernah nggak sih lo lagi ngerjain proyek, terus butuh ngapus konfigurasi GitHub tertentu dari GitHub CLI? Nah, disinilah **`gh config delete`** masuk! Perintah ini gunanya buat **menghapus konfigurasi** yang ada di GitHub CLI. Mulai dari akun yang terautentikasi sampai settingan lain yang ada. Kapan harus pakai ini? Biasanya sih pas lo perlu bersih-bersih atau ganti pengaturan yang udah nggak sesuai. 🧹

---

## 🔑 **Fungsi & Kegunaan `gh config delete`**

### 1. **Apa yang Terjadi Saat Lo Jalankan `gh config delete`?**

Perintah ini **ngapus konfigurasi GitHub** yang udah disimpen di GitHub CLI. Jadi, misalnya lo punya pengaturan repositori atau akun yang terautentikasi, dan lo nggak butuh lagi, lo bisa pake perintah ini buat **ngapus semua itu**. 🔥

### 2. **Apa yang Dimaksud dengan "config" dalam GitHub CLI?**

"Config" itu singkatan dari **konfigurasi**—bisa meliputi akun GitHub yang terautentikasi, URL repositori, atau pengaturan lain yang lo atur sebelumnya. Semua settingan yang berkaitan dengan GitHub lo bisa disimpen di sini.

---

## 🤔 **Kapan Lo Harus Pakai `gh config delete`?**

Misalnya:

- **Ganti akun GitHub:** Lo nggak mau akun lama nempel di CLI dan cuma mau nyimpen akun baru.

- **Ngehapus konfigurasi yang rusak:** Kalau lo merasa ada masalah sama konfigurasi GitHub lo, bisa pake perintah ini buat hapus yang bermasalah.
- **Nggak butuh konfigurasi tertentu:** Kalo lo udah nggak butuh repo atau settingan yang ada, bisa langsung dibuang.

---

## 🖥️ **Contoh Penggunaan `gh config delete`**

Misalnya, lo mau hapus konfigurasi GitHub untuk akun **`github.com`**, tinggal pakai perintah ini:

```bash
gh config delete -h github.com
```

### 1. **Menghapus Konfigurasi untuk GitHub Enterprise**

Kalau lo pake **GitHub Enterprise**, lo bisa tambahin opsi **`--url`** buat ngapus konfigurasi di server GitHub Enterprise tertentu:

```bash
gh config delete -h <hostname> --url https://github.com/enterprise
```

### 2. **Menghapus Konfigurasi untuk Satu Akun GitHub**

Kalau lo punya banyak akun GitHub dan pengen ngapus salah satunya, tinggal pakai:

```bash
gh config delete -h github.com
```

---

## ⚠️ **Efek Setelah Lo Hapus Konfigurasi**

Setelah lo ngapus konfigurasi, GitHub CLI bakal ngelupain pengaturan yang dihapus. Misalnya:

- **Token otentikasi hilang?** Lo harus login lagi, soalnya GitHub CLI gak inget lagi siapa lo.
- **Repositori yang terkonfigurasi hilang?** Lo harus reconfigure repositori lo.

Tapi jangan khawatir, lo masih bisa lanjut pakai GitHub CLI, cuma perlu login ulang atau setel ulang beberapa konfigurasi. 🔄

---

## 🛠️ **Cara Menentukan Konfigurasi yang Akan Dihapus**

- **Global atau lokal?** Lo bisa pilih apakah mau ngapus konfigurasi di level global (semua repositori) atau cuma di repositori tertentu.
- **Pilih yang tepat!** Jangan asal hapus ya, karena kalau lo salah hapus, lo bisa kehilangan akses atau konfigurasi penting lainnya.

---

## ❓ **Troubleshooting & Solusi Masalah**

Kalau lo udah ngapus konfigurasi, tapi masih ada masalah:

1. **Periksa apakah konfigurasi beneran hilang:** Lo bisa cek dengan perintah `gh config list` buat liat konfigurasi yang masih ada.
2. **Masalah nggak terhapus?** Pastikan lo ngetik perintah dengan bener. Cek apakah URL yang lo masukkan udah benar.

---

## 🔒 **Keamanan & Praktik Terbaik**

### **Hati-Hati Sebelum Hapus!**

- Jangan sembarangan ngapus konfigurasi, karena itu bisa mempengaruhi akses lo ke repositori atau akun GitHub yang terautentikasi.
- Kalau lo hapus konfigurasi autentikasi, lo bakal diminta login ulang. Jadi, pastikan lo tahu akun mana yang harus lo masukin.

---

## 🔄 **Perbandingan: `gh config delete` vs `gh auth logout`**

- **`gh config delete`**: Ngehapus konfigurasi yang terkait dengan GitHub CLI, kayak akun atau repositori.
- **`gh auth logout`**: Ngehapus autentikasi atau login dari akun GitHub lo. Jadi lo bakal logout, dan kalau mau lanjut, lo harus login lagi.

Kapan pakai mana?

- Kalau lo cuma mau hapus **pengaturan atau akun tertentu** tanpa logout, pakai **`gh config delete`**.
- Kalau lo mau keluar dari semua akun GitHub dan logout, pakai **`gh auth logout`**.

---

## 🎯 **Latihan Praktis**

1. **Menghapus Konfigurasi Akun GitHub**
   Jalankan perintah ini buat ngecek konfigurasi yang ada di GitHub CLI:

   ```bash
   gh config list
   ```

   Lalu hapus konfigurasi akun GitHub yang nggak lo butuhin:

   ```bash
   gh config delete -h github.com
   ```

2. **Menghapus Konfigurasi untuk GitHub Enterprise**
   Kalau lo pake GitHub Enterprise, coba hapus konfigurasi untuk server tersebut:

   ```bash
   gh config delete -h <hostname> --url https://github.com/enterprise
   ```

---

## 📝 **Ringkasan**

- **`gh config delete`** adalah perintah buat ngapus konfigurasi GitHub di GitHub CLI.
- Lo bisa hapus konfigurasi terkait akun, repositori, atau pengaturan lainnya.
- Setelah ngapus, lo mungkin harus login ulang atau setel ulang beberapa konfigurasi.
- **Hati-hati saat ngapus!** Pastikan lo ngerti apa yang lo hapus, biar nggak salah setting.

---

🔗 **Bacaan Lanjut**:

- [Dokumentasi `gh config delete`](https://cli.github.com/manual/gh_config_delete)
- [Panduan GitHub CLI](https://cli.github.com/)

### Penjelasan:

- **`gh config delete`** berguna buat menghapus konfigurasi GitHub yang udah ada di GitHub CLI, termasuk akun, repositori, atau pengaturan lainnya.
- Lo bisa ngehapus konfigurasi **global** atau **lokal** sesuai kebutuhan.
- Jangan asal hapus! Pastikan lo paham apa yang lo hapus karena bisa berakibat pada akses ke repositori atau akun GitHub lo. 🔑

# 🚪 **Perintah `gh auth logout` - GitHub CLI** 🔐

Lo udah login pake **`gh auth login`**, tapi sekarang lo pengen keluar atau ganti akun GitHub? Gampang! Cukup pake perintah **`gh auth logout`** buat keluar dari akun GitHub yang udah lo login di GitHub CLI. 🔥

---

## Apa Itu `gh auth logout`?

**`gh auth logout`** adalah perintah buat **keluar dari akun GitHub** yang udah lo login di GitHub CLI. Setelah logout, lo nggak bisa lagi akses fitur GitHub lewat CLI sampai lo login lagi. Ini berguna banget kalau lo mau ganti akun atau cuma mau logout sementara. 👋

---

## Kapan Harus Digunakan?

- **Ganti akun**: Lo pengen login pake akun GitHub yang beda.
- **Sesi login udah selesai**: Lo selesai pake GitHub CLI dan pengen keluar dari akun.
- **Keamanan**: Lo mau logout dari akun GitHub di perangkat tertentu, biar lebih aman.

---

## Cara Menggunakan `gh auth logout`

1. Cukup ketik perintah berikut di terminal:

   ```bash
   gh auth logout
   ```

2. Lo akan diminta untuk pilih **GitHub.com** atau **GitHub Enterprise**. Pilih yang sesuai dengan yang lo gunakan.

3. Setelah itu, lo bakal diminta konfirmasi buat logout. Ketik **Y** (Yes) untuk konfirmasi dan keluar dari akun GitHub.

---

## Contoh Kasus

### 1. **Logout dari GitHub CLI**

Kalau lo udah selesai kerja dan mau logout, cukup ketik:

```bash
gh auth logout
```

- Lo bakal keluar dari akun GitHub yang udah login dan nggak bisa akses repositori atau fitur lainnya sampai login ulang.

### 2. **Ganti Akun GitHub**

Misalnya lo punya lebih dari satu akun GitHub (misal akun pribadi dan organisasi), lo bisa logout dari akun yang satu dan login dengan akun yang lain:

```bash
gh auth logout
```

- Pilih akun yang mau lo logout, dan login dengan akun yang baru.

---

## Kenapa `gh auth logout` Itu Penting?

- **Keamanan**: Logout setelah selesai pake GitHub CLI penting buat ngelindungin akun lo, apalagi kalau lo pake komputer atau server bersama.
- **Ganti Akun**: Kalau lo perlu login dengan akun GitHub yang berbeda, **logout dulu** sebelum login ke akun yang baru.
- **Bersihkan Sesi**: Logout juga bisa jadi cara buat **membersihkan sesi** login lo, apalagi kalau sesi login udah lama dan lo gak lagi butuh akses ke akun GitHub.

---

## Tips dan Trik

1. **Logout dari Repositori Pribadi**: Kalau lo sering kerja dengan repositori pribadi, logout setelah selesai penting buat menghindari akses yang nggak sah.
2. **Cek Status Login**: Sebelum logout, lo bisa cek status login lo dulu pake perintah ini:

   ```bash
   gh auth status
   ```

   Ini bakal kasih tau apakah lo udah login atau belum.

---

## Kesimpulan

**`gh auth logout`** adalah perintah yang simpel tapi penting buat keluar dari akun GitHub di GitHub CLI. Gunakan perintah ini buat ganti akun, logout untuk keamanan, atau sekedar selesai pake GitHub CLI. 🔑

Langsung aja praktekin kalau lo butuh logout dari akun GitHub lo! 👋

### Penjelasan

- **Kapan Harus Digunakan**: Gunakan **`gh auth logout`** saat lo perlu ganti akun GitHub, selesai menggunakan GitHub CLI, atau untuk alasan keamanan.
- **Cara Cepat Memahami Sintaks**: Cukup ketik **`gh auth logout`**, pilih akun yang akan logout, dan konfirmasi dengan **Y**.

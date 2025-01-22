# 📥 **Perintah `gh run download` - GitHub CLI** 🚀

Pernahkah Anda merasa seperti seorang **detektif digital** yang ingin mengunduh hasil atau laporan dari sebuah proses tertentu? Nah, **`gh run download`** adalah alat yang Anda butuhkan untuk mengunduh **artefak** atau **hasil** dari **run GitHub Actions** yang telah selesai. 🔍

Bayangkan Anda sudah menjalankan sebuah **workflow**, dan kini saatnya untuk mengambil hasilnya—entah itu berupa **file, log**, atau **artefak** lainnya yang dihasilkan selama proses.

---

## 🌟 **Apa Itu `gh run download`?**

Perintah **`gh run download`** memungkinkan Anda untuk **mengunduh artefak** dari **run GitHub Actions** yang telah selesai. Artefak ini bisa berupa file hasil build, laporan status, atau bahkan file yang dihasilkan selama proses workflow tersebut.

---

## 📋 **Perumpamaan Sehari-hari:**

### 🎁 **1. Menerima Hadiah yang Sudah Dikirim**

Bayangkan Anda baru saja menerima sebuah **paket** dari teman Anda yang sudah lama Anda tunggu. Setelah Anda mengirimkan permintaan, paket tersebut akhirnya sampai di tangan Anda, dan Anda siap untuk **membuka dan melihat isinya**. Nah, **`gh run download`** adalah cara Anda **mengambil paket (artefak)** yang dihasilkan oleh GitHub Actions.

**Perintah GitHub CLI:**
```bash
gh run download <run-id> --artifact <artifact-name>
```

**Perumpamaan Sehari-hari:**
- Ini seperti Anda **menerima paket** dari teman yang berisi **hasil pekerjaan** mereka. Anda ingin membuka **artefak** itu untuk melihat apa yang ada di dalamnya. 📦🎁

---

### 🛠️ **2. Mengunduh Hasil Kerja dari Pekerjaan yang Selesai**

Misalkan Anda seorang **tukang kayu** yang sudah menyelesaikan **proyek** dan kini Anda ingin mengambil hasilnya. Hasil tersebut sudah siap diambil dan Anda hanya perlu menunduhnya agar bisa digunakan di pekerjaan berikutnya.

**Perintah GitHub CLI:**
```bash
gh run download <run-id>
```

**Perumpamaan Sehari-hari:**
- Ini seperti **mengambil hasil kerja** Anda setelah selesai mengerjakan sesuatu, seperti **meja kayu** yang telah selesai dibuat dan sekarang siap digunakan. Anda mengunduhnya untuk keperluan selanjutnya! 🪑🔨

---

### 🏁 **3. Mengunduh Semua Hasil (Artefak) dari Satu Run**

Jika Anda ingin **mengunduh semua artefak** yang dihasilkan dalam satu run, Anda bisa melakukannya dengan mudah. Ini seperti Anda mengambil **semua barang** yang sudah selesai diantar sekaligus, tanpa harus memilih satu per satu.

**Perintah GitHub CLI:**
```bash
gh run download <run-id> --all
```

**Perumpamaan Sehari-hari:**
- Seperti ketika Anda **mendapatkan banyak paket** sekaligus—Anda bisa **mengambil semuanya** yang sudah disiapkan dan menggunakannya sesuai kebutuhan. 📦🎁

---

## 🚀 **Contoh Perintah Lengkap - Mengunduh Artefak dari Run GitHub Actions**

Sekarang, mari kita lihat beberapa contoh perintah lengkap yang bisa Anda gunakan untuk mengunduh **artefak** dari **run GitHub Actions** yang sudah selesai.

### 🎯 **1. Mengunduh Artefak dari Satu Run**
```bash
gh run download <run-id> --artifact <artifact-name>
```
- **Perumpamaan:** Seperti Anda **menerima paket** yang berisi hasil pekerjaan dari teman Anda. Anda tahu apa yang ada di dalamnya dan siap untuk digunakan! 🎁📦

---

### 🌍 **2. Mengunduh Semua Artefak dari Satu Run**
```bash
gh run download <run-id> --all
```
- **Perumpamaan:** Seperti **mengambil semua barang** yang dikirimkan tanpa harus memilih satu per satu. Semua hasil kerja Anda siap digunakan! 🛍️🎉

---

### 💻 **3. Mengunduh Artefak dari Repositori atau Run Tertentu**
```bash
gh run download <run-id> --repo <owner>/<repo>
```
- **Perumpamaan:** Ini seperti Anda **mengambil hasil pekerjaan** dari **project teman Anda** yang sudah siap dan ingin dipakai, tanpa harus bingung mencari satu per satu. 📂🔄

---

### 🔧 **4. Menambahkan Opsi untuk Menentukan Lokasi Unduhan**
```bash
gh run download <run-id> --artifact <artifact-name> --dir <directory-path>
```
- **Perumpamaan:** Anda tidak hanya menerima paket, tetapi juga bisa memilih untuk **meletakkannya di lokasi tertentu** dalam rumah Anda—di tempat yang sesuai dan mudah diakses. 🏠📂

---

## 💥 **Kenapa `gh run download` Itu Keren?**

- **Mudah Mengambil Hasil:** Anda bisa dengan mudah **mengambil artefak atau hasil workflow** GitHub Actions, tanpa harus repot-repot mencari di UI GitHub.
- **Fleksibilitas Unduhan:** Anda bisa **mengunduh satu artefak** atau bahkan **semua artefak** dalam satu waktu.
- **Menghemat Waktu:** Jika workflow Anda menghasilkan banyak file, Anda bisa langsung **mengunduhnya sekaligus** tanpa perlu mengambil satu per satu. 🕒💨

---

## 🏅 **Bacaan Lanjut dan Referensi** ✨

- [GitHub CLI Documentation](https://cli.github.com/manual/gh_run_download) 📘
- [GitHub Actions Documentation](https://docs.github.com/en/actions) 📚

---

## 🎉 **Kesimpulan**

Dengan **`gh run download`**, Anda dapat dengan mudah **mengunduh artefak** yang dihasilkan oleh **GitHub Actions** setelah sebuah run selesai. Ini sangat berguna saat Anda membutuhkan **file hasil build, laporan, atau hasil lain** dari workflow yang telah berjalan.

Jadi, jika Anda ingin **mengambil hasil pekerjaan** atau **artefak** dari proses GitHub Actions yang telah selesai, cukup gunakan perintah ini! 🎁💻

---

Semoga penjelasan ini lebih mudah dipahami dan **lebih menarik** untuk Anda! Ayo coba **mengunduh artefak** GitHub Actions Anda sekarang! 📦🚀
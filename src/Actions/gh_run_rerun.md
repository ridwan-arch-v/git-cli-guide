# 🔄 **Perintah `gh run rerun` - GitHub CLI** ⚡️

Pernahkah Anda menjalankan sebuah proyek dan tiba-tiba **prosesnya gagal**? Atau mungkin ada masalah yang tidak terduga dalam **workflow GitHub Actions** Anda? Nah, jangan khawatir! Dengan perintah **`gh run rerun`**, Anda bisa dengan mudah **menjalankan kembali** (rerun) proses GitHub Actions yang sebelumnya gagal atau berhenti di tengah jalan. 🎯

---

## 🌟 **Apa Itu `gh run rerun`?**

Perintah **`gh run rerun`** memungkinkan Anda untuk **menjalankan kembali (rerun)** workflow GitHub Actions yang sudah dijalankan sebelumnya. Ini sangat berguna ketika **run GitHub Actions gagal**, atau Anda ingin mengulangnya tanpa harus mengonfigurasi ulang semuanya.

---

## 📋 **Perumpamaan Sehari-hari:**

### 🛠 **1. Memperbaiki Kerusakan dengan Mengulangi Proses**

Bayangkan Anda sedang **membangun rak buku** di rumah, dan tiba-tiba **sebuah bagian rak gagal pasang**. Alih-alih membongkar semuanya dan memulai dari awal, Anda cukup **mengulang bagian yang gagal** tersebut untuk menyelesaikan pekerjaan Anda. Begitu juga dengan perintah **`gh run rerun`**, yang memungkinkan Anda **mengulang workflow** yang gagal tanpa memulai dari awal.

**Perintah GitHub CLI:**
```bash
gh run rerun <run-id>
```

**Perumpamaan Sehari-hari:**
- Seperti **memperbaiki bagian rak yang gagal dipasang** dengan hanya **mengulang langkah yang gagal**, tanpa perlu membongkar semuanya dan memulai dari nol. 🏗️📚

---

### 🎯 **2. Mengulangi Proses yang Gagal di Tengah Jalan**

Misalkan Anda sedang **memasak** dan tiba-tiba **kompor mati** di tengah-tengah masakan. Alih-alih memasak ulang dari awal, Anda hanya perlu **menghidupkan kembali kompor** dan melanjutkan masakan yang sudah hampir selesai. Inilah yang dilakukan oleh **`gh run rerun`**—menjalankan kembali run GitHub Actions yang sempat terhenti.

**Perintah GitHub CLI:**
```bash
gh run rerun <run-id> --job <job-name>
```

**Perumpamaan Sehari-hari:**
- Seperti **menyalakan kembali kompor yang mati** untuk melanjutkan memasak tanpa harus memulai dari awal. Anda hanya melanjutkan bagian yang terhenti. 🍳🔥

---

### 🏃 **3. Mengulangi Run untuk Proyek atau Repositori Tertentu**

Kadang Anda ingin mengulang **workflow** yang terjadi di **repositori tertentu** saja. Misalnya, Anda baru saja mengalami masalah dengan workflow di **proyek A** dan ingin hanya mengulang **workflow di proyek A**, bukan proyek lainnya. Perintah **`gh run rerun`** memungkinkan Anda untuk memilih **repositori tertentu** dan menjalankan kembali run yang sudah ada.

**Perintah GitHub CLI:**
```bash
gh run rerun <run-id> --repo <owner>/<repo>
```

**Perumpamaan Sehari-hari:**
- Seperti Anda **mengulang masakan di dapur tertentu**, bukan di seluruh rumah, karena masalah hanya ada di **satu dapur saja**. 🍽️👩‍🍳

---

## 🚀 **Contoh Perintah Lengkap - Menjalankan Kembali Workflow di GitHub Actions**

Sekarang, mari kita lihat beberapa contoh perintah lengkap yang dapat Anda gunakan untuk **mengulang run** di GitHub Actions.

### 🎯 **1. Mengulang Workflow yang Gagal**
```bash
gh run rerun <run-id>
```
- **Perumpamaan:** Seperti Anda **memperbaiki bagian rak** yang gagal dipasang tanpa perlu memulai dari awal. Anda cukup mengulang bagian yang bermasalah. 🛠️📚

---

### 🌍 **2. Mengulang Salah Satu Job dalam Workflow**
```bash
gh run rerun <run-id> --job <job-name>
```
- **Perumpamaan:** Seperti **menyelesaikan bagian masakan** yang terhenti karena kompor mati, tanpa perlu mengulang semua langkah dari awal. 🍳🔥

---

### 🏁 **3. Mengulang Run untuk Repositori Tertentu**
```bash
gh run rerun <run-id> --repo <owner>/<repo>
```
- **Perumpamaan:** Seperti Anda **hanya mengulang proses masak di satu dapur tertentu**, karena masalahnya ada di dapur itu, bukan di seluruh rumah. 🍽️🔄

---

### 🛠 **4. Menambahkan Opsi untuk Rerun dengan Variabel Lingkungan**
```bash
gh run rerun <run-id> --env VAR_NAME=value
```
- **Perumpamaan:** Seperti Anda **menambahkan bumbu baru** dalam masakan yang sedang dimasak ulang, untuk meningkatkan rasa dan hasilnya. Anda bisa mengatur **variabel** yang diperlukan untuk rerun agar berjalan dengan pengaturan yang baru. 🌶️🍽️

---

## 💥 **Kenapa `gh run rerun` Itu Keren?**

- **Mengulang Workflow Gagal:** Anda tidak perlu khawatir jika suatu **workflow gagal**. Anda bisa langsung **mengulangnya** tanpa harus memulai dari awal.
- **Menghemat Waktu:** Anda hanya perlu mengulang bagian yang **gagal** atau **terhenti**, tanpa membuang waktu untuk seluruh proses.
- **Fleksibilitas dalam Mengulang:** Anda bisa memilih **job tertentu** atau **repositori tertentu** yang ingin dijalankan kembali—lebih cepat dan lebih efisien!

---

## 🏅 **Bacaan Lanjut dan Referensi** ✨

- [GitHub CLI Documentation](https://cli.github.com/manual/gh_run_rerun) 📘
- [GitHub Actions Documentation](https://docs.github.com/en/actions) 📚

---

## 🎉 **Kesimpulan**

Dengan perintah **`gh run rerun`**, Anda bisa dengan mudah **mengulang workflow GitHub Actions** yang sebelumnya gagal atau terhenti. Ini sangat berguna jika Anda ingin **memperbaiki masalah kecil** tanpa harus menjalankan semuanya dari awal.

Jadi, jika Anda menghadapi **run yang gagal** atau hanya ingin mengulangi bagian tertentu dari workflow Anda, cukup gunakan perintah ini untuk **menghemat waktu dan usaha**! 🔄⏳

---

Semoga penjelasan ini membuat Anda semakin paham dan tertarik untuk menggunakan **`gh run rerun`** di proyek Anda! Selamat mencoba! 🚀👩‍💻
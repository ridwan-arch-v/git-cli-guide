# ❌ **Perintah `gh run cancel` - GitHub CLI** 🚀

Pernahkah Anda merasa perlu untuk **menghentikan sesuatu** yang sedang berjalan? Misalnya, sedang menunggu **film yang membosankan**, tapi setelah beberapa menit menonton, Anda sadar film tersebut tidak sesuai dengan yang Anda harapkan. Anda pun memutuskan untuk **membatalkan** dan memilih **menonton film lain**.

Nah, perintah **`gh run cancel`** dalam GitHub CLI berfungsi seperti itu! Saat ada **workflow** atau **run GitHub Actions** yang sedang berjalan, dan Anda merasa **tidak sesuai** atau **terlalu lama**, Anda bisa menghentikannya dengan perintah ini!

---

## 🌟 **Apa Itu `gh run cancel`?**

**`gh run cancel`** adalah perintah di GitHub CLI yang memungkinkan Anda untuk **membatalkan atau menghentikan** workflow yang sedang berjalan di GitHub Actions. Misalnya, jika Anda menjalankan sebuah workflow yang ternyata **membutuhkan waktu lebih lama** dari yang Anda harapkan atau jika ada **kesalahan** yang terjadi dan Anda ingin menghentikannya lebih cepat.

---

## 📋 **Perumpamaan Sehari-hari:**

### 🎬 **1. Menonton Film yang Membosankan**

Bayangkan Anda sedang **menonton film** yang sangat membosankan. Setelah beberapa menit, Anda mulai berpikir, "Ini nggak menarik, lebih baik saya hentikan saja dan cari film lain."

**Perintah GitHub CLI:**
```bash
gh run cancel <run-id>
```

**Perumpamaan Sehari-hari:**
- Ini seperti **menekan tombol stop** saat Anda sedang menonton film yang nggak menarik. Anda bisa memilih untuk **membatalkan** dan melanjutkan dengan hal lain yang lebih produktif! 🎥❌

---

### 🚗 **2. Menunggu di Antrean yang Panjang**

Pernahkah Anda **mengantri** untuk mendapatkan sesuatu dan kemudian merasa, "Antrenya terlalu lama, saya lebih baik pindah ke tempat lain." Anda bisa **membatalkan** antrian itu tanpa merasa rugi.

**Perintah GitHub CLI:**
```bash
gh run cancel <run-id>
```

**Perumpamaan Sehari-hari:**
- Bayangkan Anda sedang **mengantri di tempat parkir** dan merasa antrian terlalu panjang. Anda memutuskan untuk **membatalkan antrian** dan mencari tempat parkir lain yang lebih cepat. 🅿️🚗

---

### ⏳ **3. Menghentikan Proses yang Terlalu Lama**

Saat bekerja, Anda mungkin menjalankan **proses otomatis** yang memakan waktu terlalu lama. Misalnya, Anda sedang menunggu hasil pemrosesan data besar, tetapi Anda sadar bahwa prosesnya **terlalu lama** dan sepertinya ada yang salah. **`gh run cancel`** adalah cara Anda untuk menghentikan proses yang tidak berjalan dengan baik.

**Perintah GitHub CLI:**
```bash
gh run cancel <run-id>
```

**Perumpamaan Sehari-hari:**
- Ini seperti Anda sedang **memasak makan malam** dan tiba-tiba merasa bahwa resepnya terlalu rumit atau bahan-bahannya habis. Anda memutuskan untuk **menghentikan proses memasak** dan mencoba resep yang lebih sederhana. 🍳❌

---

## 🚀 **Contoh Perintah Lengkap - Menghentikan Run di GitHub Actions**

Berikut adalah beberapa contoh perintah yang bisa Anda gunakan untuk membatalkan atau menghentikan **run** di GitHub Actions menggunakan **`gh run cancel`**.

### 🎯 **1. Membatalkan Satu Run dengan ID Tertentu**
```bash
gh run cancel <run-id>
```
- **Perumpamaan:** Ini seperti **menekan tombol stop** pada sesuatu yang sedang berlangsung, seperti film yang membosankan atau antrian yang terlalu panjang. Anda bisa langsung menghentikan prosesnya! ⏹️

---

### 🌍 **2. Membatalkan Semua Run yang Sedang Berjalan**
```bash
gh run cancel --all
```
- **Perumpamaan:** Bayangkan Anda **mengantri di banyak tempat** sekaligus, dan Anda memutuskan untuk **menghentikan semua antrian** tersebut sekaligus. Anda bisa memutuskan untuk **melanjutkan hal lain** yang lebih penting! 🛑🚶‍♂️

---

### 🧑‍💻 **3. Membatalkan Run dengan Status Gagal**
```bash
gh run cancel --status failure
```
- **Perumpamaan:** Ini seperti Anda **menghentikan proses** yang sudah **terbukti gagal**—misalnya, makanan yang sudah terbakar atau film yang tidak menarik. Anda memutuskan untuk berhenti dan mencoba hal lain yang lebih baik. 🍽️💔

---

### 🔍 **4. Menambahkan Opsi Lain untuk Membatalkan Run**
```bash
gh run cancel --repo <owner>/<repo> <run-id>
```
- **Perumpamaan:** Bayangkan Anda ingin membatalkan antrian atau proses di **tempat tertentu** (misalnya restoran lain atau tempat parkir yang berbeda). Anda bisa melakukannya dengan mengarahkannya pada tempat yang tepat! 🏢🔀

---

## 💥 **Kenapa `gh run cancel` Itu Keren?**

- **Cepat Menghentikan Proses yang Mengganggu:** Jika ada workflow yang sudah berjalan terlalu lama atau ada **kesalahan**, Anda bisa langsung menghentikannya tanpa menunggu lama.
- **Fleksibilitas:** Anda bisa **membatalkan satu run tertentu**, atau jika perlu, **semua run** di repositori tersebut dengan perintah yang sangat mudah.
- **Sangat Berguna untuk Workflow yang Gagal:** Jika workflow Anda gagal, Anda bisa **menghentikan proses** dan segera memperbaikinya.

---

## 🏅 **Bacaan Lanjut dan Referensi** ✨

- [GitHub CLI Documentation](https://cli.github.com/manual/gh_run_cancel) 📘
- [GitHub Actions Documentation](https://docs.github.com/en/actions) 📚

---

## 🎉 **Kesimpulan**

Dengan **`gh run cancel`**, Anda bisa **menghentikan workflow** GitHub Actions yang sedang berjalan dengan mudah dan cepat. Seperti memilih untuk **menghentikan sesuatu** yang tidak sesuai dengan harapan, Anda bisa membatalkan proses yang terlalu lama atau yang gagal. Ini adalah cara yang tepat untuk mengelola alur kerja Anda dan memperbaiki masalah dengan **efisien**!

Jadi, jika ada sesuatu yang **terlalu lama** atau **gagal** saat menjalankan GitHub Actions, jangan ragu untuk menggunakan **`gh run cancel`**! Anda bisa menjadi **pengendali penuh** terhadap workflow Anda! 💪🎯

---

Semoga penjelasan ini lebih mudah dipahami dan **lebih menarik** untuk Anda! Ayo coba dan batalkan **run** yang tidak diinginkan sekarang juga! 🚀
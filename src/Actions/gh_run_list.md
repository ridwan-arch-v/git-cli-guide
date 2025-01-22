# 📜 **Perintah `gh run list` - GitHub CLI** 🚀

Bayangkan Anda bekerja dalam sebuah **perusahaan besar** di mana ada banyak **proyek berjalan** secara paralel. Terkadang, Anda perlu mengecek **daftar proyek** yang sedang aktif untuk melihat mana yang sedang berjalan, mana yang sudah selesai, dan mana yang gagal. Nah, perintah **`gh run list`** di GitHub CLI bekerja mirip dengan itu—memberi Anda **daftar lengkap dari semua run GitHub Actions** yang terjadi di repositori Anda! 📋💻

---

## 🌟 **Apa Itu `gh run list`?**

**`gh run list`** adalah perintah GitHub CLI yang memungkinkan Anda untuk **melihat daftar run** yang ada dalam **repositori GitHub Actions**. Run ini bisa berupa proses-proses yang sedang berjalan atau yang telah selesai. Anda dapat melihat **status** masing-masing run, apakah **berhasil**, **gagal**, atau **sedang berjalan**.

---

## 📋 **Perumpamaan Sehari-hari:**

### 🎬 **1. Melihat Daftar Film yang Sedang Tayang**

Pernahkah Anda pergi ke **bioskop** dan ingin tahu film apa saja yang sedang tayang? Anda akan melihat **daftar film** yang sedang diputar di layar bioskop. Begitu pula dengan **`gh run list`**, yang memungkinkan Anda untuk melihat **daftar run** GitHub Actions yang sedang berjalan, yang sudah selesai, atau bahkan yang gagal.

**Perintah GitHub CLI:**
```bash
gh run list
```

**Perumpamaan Sehari-hari:**
- Ini seperti Anda **melihat daftar film** yang sedang diputar di bioskop. Anda bisa memilih film yang ingin ditonton berdasarkan statusnya—apakah sedang diputar atau sudah selesai. 🎥🍿

---

### 📝 **2. Menyusun Daftar Tugas yang Harus Dikerjakan**

Misalnya, Anda memiliki **daftar tugas** yang perlu diselesaikan di pekerjaan. Anda perlu melihat **tugas mana yang sudah selesai** dan **mana yang masih pending**. **`gh run list`** memberi Anda kemampuan untuk **melihat run** mana yang sudah selesai, mana yang berhasil, dan mana yang gagal.

**Perintah GitHub CLI:**
```bash
gh run list --status completed
```

**Perumpamaan Sehari-hari:**
- Seperti Anda sedang **memeriksa daftar tugas** untuk melihat **mana yang sudah selesai** dan **mana yang belum selesai**. Anda bisa langsung mengetahui tugas mana yang selesai dengan status yang baik. ✅📋

---

### 🏁 **3. Menyaring Berdasarkan Status Run**

Kadang Anda hanya tertarik dengan **run yang gagal** atau **run yang sedang berjalan** saja. Dengan **`gh run list`**, Anda bisa **menyaring daftar run** berdasarkan status tertentu. Misalnya, Anda hanya ingin melihat **run yang gagal** untuk segera diperbaiki!

**Perintah GitHub CLI:**
```bash
gh run list --status failure
```

**Perumpamaan Sehari-hari:**
- Bayangkan Anda sedang **menyaring tugas-tugas yang gagal**, misalnya **melihat mana yang gagal dikerjakan** dan perlu diperbaiki segera. 🛠️❌

---

## 🚀 **Contoh Perintah Lengkap - Melihat Daftar Run di GitHub Actions**

Sekarang, mari kita lihat beberapa contoh perintah lengkap yang bisa Anda gunakan untuk melihat **daftar run** di **GitHub Actions**.

### 🎯 **1. Melihat Daftar Semua Run**
```bash
gh run list
```
- **Perumpamaan:** Ini seperti **melihat semua film** yang sedang diputar di bioskop—baik yang sudah selesai, yang sedang berjalan, maupun yang gagal. Anda bisa mendapatkan gambaran umum dari semuanya! 🎥✨

---

### 🌍 **2. Melihat Daftar Run dengan Status Tertentu**
```bash
gh run list --status success
```
- **Perumpamaan:** Seperti melihat **daftar tugas yang berhasil** diselesaikan tanpa ada masalah. Anda bisa langsung mengidentifikasi mana yang sudah **berhasil** dan siap untuk dilanjutkan. ✅🏅

---

### 🏃 **3. Melihat Run Berdasarkan Waktu Tertentu**
```bash
gh run list --created <date>
```
- **Perumpamaan:** Ini seperti Anda **mencari film berdasarkan tanggal rilis**—Anda hanya ingin melihat film yang **dirilis pada hari tertentu**. Begitu juga, Anda bisa memilih run berdasarkan **tanggal pembuatan** tertentu. 📅🎬

---

### 📍 **4. Menampilkan Daftar Run yang Terakhir**
```bash
gh run list --limit 5
```
- **Perumpamaan:** Seperti Anda **menyaring film terbaru** yang diputar di bioskop—hanya melihat film-film terbaru tanpa menampilkan film-film lama. Anda bisa memilih **5 run terakhir** yang terjadi di repositori Anda! 🎞️✨

---

### 🧑‍💻 **5. Menampilkan Run untuk Repositori Tertentu**
```bash
gh run list --repo <owner>/<repo>
```
- **Perumpamaan:** Ini seperti Anda **memilih untuk melihat daftar film** hanya dari **bioskop tertentu**. Anda ingin memfokuskan diri hanya pada run dari **repositori tertentu**. 🎥🔍

---

## 💥 **Kenapa `gh run list` Itu Keren?**

- **Mudah Melihat Daftar Run:** Anda bisa dengan mudah **melihat semua run** yang terjadi di GitHub Actions, apakah sudah selesai atau sedang berlangsung.
- **Fleksibilitas Penyaringan:** Anda bisa **menyaring berdasarkan status** run—mencari yang **berhasil**, **gagal**, atau **sedang berjalan**. Sangat berguna jika Anda ingin fokus pada satu hal saja!
- **Mengecek Run Terakhir:** Anda bisa dengan cepat melihat **5 run terakhir** atau bahkan run berdasarkan **tanggal tertentu**, yang sangat membantu dalam pengecekan cepat.

---

## 🏅 **Bacaan Lanjut dan Referensi** ✨

- [GitHub CLI Documentation](https://cli.github.com/manual/gh_run_list) 📘
- [GitHub Actions Documentation](https://docs.github.com/en/actions) 📚

---

## 🎉 **Kesimpulan**

Dengan perintah **`gh run list`**, Anda bisa dengan mudah **melihat daftar run** yang terjadi di repositori GitHub Actions. Baik itu run yang **berhasil**, **gagal**, atau **sedang berjalan**, Anda bisa mendapatkan **gambaran lengkap** tentang alur kerja di repositori Anda.

Jadi, jika Anda ingin **melihat status dari berbagai workflow**, **menyaring berdasarkan status** atau **mencari run yang terjadi pada waktu tertentu**, gunakanlah perintah ini untuk memudahkan pekerjaan Anda! 🎯💻

---

Semoga penjelasan ini bermanfaat dan lebih mudah dipahami! Ayo coba **melihat daftar run GitHub Actions** di repositori Anda sekarang! 📜🚀
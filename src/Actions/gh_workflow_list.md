# 📜 **Perintah `gh workflow list` - GitHub CLI** 📋

Pernahkah Anda ingin melihat semua **workflow** yang telah Anda buat di GitHub Actions, atau mungkin Anda ingin **memeriksa status workflow** yang ada? Dengan perintah **`gh workflow list`**, Anda bisa dengan mudah melihat **daftar semua workflow** yang ada di repositori GitHub Anda. 🔍

---

## 🌟 **Apa Itu `gh workflow list`?**

Perintah **`gh workflow list`** digunakan untuk **menampilkan semua workflow** yang ada di dalam repositori Anda. Ini sangat berguna jika Anda memiliki beberapa workflow dan ingin melihat **workflow mana yang aktif**, serta status dan informasi terkait lainnya. 🎯

---

## 📋 **Perumpamaan Sehari-hari:**

### 📚 **1. Melihat Daftar Buku di Perpustakaan**

Bayangkan Anda sedang berada di **perpustakaan** dan ingin tahu buku apa saja yang ada di rak. Anda akan melihat daftar **semua buku yang tersedia**, sehingga Anda bisa memilih yang ingin dibaca. **`gh workflow list`** adalah seperti melihat **daftar semua workflow** yang ada di repositori Anda, sehingga Anda bisa memilih workflow mana yang ingin diaktifkan atau dimodifikasi. 📚📖

**Perintah GitHub CLI:**
```bash
gh workflow list
```

**Perumpamaan Sehari-hari:**
- Seperti Anda **melihat daftar buku di perpustakaan** untuk mengetahui apa saja yang tersedia. 📚🔍

---

### 🔍 **2. Melihat Daftar Tugas yang Harus Dilakukan**

Bayangkan Anda punya **daftar tugas** atau **checklist** yang berisi hal-hal yang harus dikerjakan sepanjang hari. Anda bisa melihat **semua tugas yang perlu diselesaikan** dan memprioritaskan yang mana yang harus dikerjakan terlebih dahulu. **`gh workflow list`** bekerja dengan cara yang sama, memberi Anda **daftar semua workflow** yang telah dibuat di repositori Anda, sehingga Anda bisa memantau tugas mana yang sedang berjalan dan mana yang telah selesai. ✅📝

**Perintah GitHub CLI:**
```bash
gh workflow list --repo <owner>/<repo>
```

**Perumpamaan Sehari-hari:**
- Seperti Anda **melihat daftar tugas** harian untuk melihat apa yang perlu diselesaikan hari ini. 🗂️✔️

---

### 📅 **3. Mengetahui Jadwal Pekerjaan**

Bayangkan Anda sedang bekerja dengan **beberapa rekan** dalam sebuah tim dan ingin tahu **jadwal kerja masing-masing**. Anda bisa melihat daftar **semua pekerjaan yang harus dilakukan**, serta siapa yang bertanggung jawab atas pekerjaan tersebut. Dengan **`gh workflow list`**, Anda bisa melihat **workflow mana yang sedang aktif** dan siapa yang menjalankan tugas tersebut di repositori Anda. 🧑‍💻👥

**Perintah GitHub CLI:**
```bash
gh workflow list --filter <status>
```

**Perumpamaan Sehari-hari:**
- Seperti Anda **melihat jadwal pekerjaan** teman-teman untuk mengetahui siapa yang sedang mengerjakan apa. 🕑📅

---

## 🚀 **Contoh Perintah Lengkap - Menampilkan Daftar Workflow**

Berikut adalah beberapa contoh penggunaan **`gh workflow list`** yang bisa Anda coba:

### 🎯 **1. Melihat Semua Workflow dalam Repositori**
```bash
gh workflow list
```
- **Perumpamaan:** Seperti Anda **melihat daftar buku di perpustakaan** untuk mengetahui apa yang tersedia dan bisa dipilih. 📚🔍

---

### 🔧 **2. Melihat Semua Workflow di Repositori Tertentu**
```bash
gh workflow list --repo <owner>/<repo>
```
- **Perumpamaan:** Seperti Anda **melihat daftar tugas** yang harus dilakukan dalam proyek tertentu, bukan di proyek lain. 🗂️✔️

---

### ⚙️ **3. Menampilkan Daftar Workflow dengan Filter Status**
```bash
gh workflow list --filter <status>
```
- **Perumpamaan:** Seperti Anda hanya ingin **melihat tugas yang sedang dikerjakan** atau **yang sudah selesai**. Anda bisa menambahkan **filter** untuk menampilkan daftar dengan status tertentu. ✅❌

---

### 🔄 **4. Melihat Daftar Workflow Secara Tertentu**
```bash
gh workflow list --name <workflow-name>
```
- **Perumpamaan:** Seperti Anda hanya ingin **melihat satu buku tertentu** di perpustakaan, bukan seluruh koleksi. 📖🔍

---

## 💥 **Kenapa `gh workflow list` Itu Keren?**

- **Menghemat Waktu:** Anda tidak perlu **masuk ke antarmuka web GitHub** untuk melihat daftar workflow yang ada. Dengan satu perintah, Anda dapat melihat semuanya langsung di terminal.
- **Kontrol yang Lebih Baik:** Memberikan **kontrol lebih** untuk memonitor workflow dan melihat statusnya kapan saja Anda perlukan.
- **Memudahkan Pemeliharaan:** Ketika banyak workflow yang perlu dimonitor, perintah ini membantu Anda untuk melihat **semuanya dengan mudah** dan menentukan langkah berikutnya.

---

## 🏅 **Bacaan Lanjut dan Referensi** ✨

- [GitHub CLI Documentation](https://cli.github.com/manual/gh_workflow_list) 📘
- [GitHub Actions Documentation](https://docs.github.com/en/actions) 📚

---

## 🎉 **Kesimpulan**

Perintah **`gh workflow list`** sangat berguna ketika Anda ingin **melihat daftar semua workflow** yang ada di dalam repositori Anda. Ini memberi Anda gambaran menyeluruh tentang **workflow mana yang aktif** dan apa saja yang perlu dimonitor lebih lanjut. 

Dengan menggunakan perintah ini, Anda bisa **memantau workflow** dengan lebih mudah dan mengelola proyek Anda dengan lebih efisien. Jangan ragu untuk mencoba perintah **`gh workflow list`** dan temukan workflow yang Anda butuhkan! 🎯🚀

---

Semoga penjelasan ini memudahkan Anda memahami cara menggunakan **`gh workflow list`** di GitHub CLI. Selamat mencoba dan semoga produktivitas Anda semakin meningkat! 💻📈
# 💥 **Perintah `gh pr view --json` - GitHub CLI** 🚀

Pernah nggak sih kamu pengen tahu **informasi lengkap** tentang sebuah **pull request** (PR) di GitHub, tapi malas buka browser dan nyari-nyari sendiri? Nah, dengan perintah **`gh pr view --json`**, kamu bisa **lihat informasi PR** secara cepat dan langsung di terminal, cuma pakai satu perintah aja! Keren kan? 😎🎯

---

## 🤖 **Apa Itu `gh pr view --json`?**

Perintah **`gh pr view --json`** memungkinkan kamu untuk **melihat informasi terkait pull request** dalam bentuk **data JSON**. Jadi, kamu bisa dapet informasi **detail** tentang PR seperti **status**, **komentar**, **reviewers**, dan banyak lagi, langsung dari terminal tanpa perlu buka GitHub di browser.

JSON di sini tuh semacam format **data** yang terstruktur, yang gampang dibaca mesin. Jadi, kalo kamu suka ngolah data atau lagi ngerjain sesuatu yang butuh data **terstruktur**, perintah ini bakal sangat membantu! ⚡

---

## 💡 **Perumpamaan Sehari-hari:**

### 📑 **1. Melihat Detail Tugas yang Dikerjain Temen**
Misalnya nih kamu lagi **mau ngecek progres tugas** yang dikerjain temen, misalnya dia udah selesai atau masih ada yang harus dibenerin. Kalau cuma nanya lewat chat, jawabannya kadang nggak lengkap. Nah, pake **`gh pr view --json`** itu kayak kamu **dapat laporan lengkap** tentang status tugas, siapa yang ngerjain, dan apa aja yang udah diselesaikan, tapi tanpa perlu nanya satu-satu. 🎯

**Contoh Perintah GitHub CLI:**
```bash
gh pr view <pr-id> --json
```
- **Perumpamaan Sehari-hari:**
  - Seperti kamu cek **laporan detail tugas** temen yang udah dikerjain, dan kamu bisa lihat statusnya langsung. 📈

---

### 🔍 **2. Mengecek Ulasan atau Review dari Temen**
Bayangin kamu lagi nunggu **review** dari temen tentang PR yang kamu buat. Nah, dengan **`gh pr view --json`**, kamu bisa **cek siapa yang udah nge-review** dan apa aja yang mereka komentarin tanpa buka GitHub di browser. Semua data ada di terminal dalam bentuk JSON yang bisa langsung kamu baca. 📄

**Contoh Perintah GitHub CLI:**
```bash
gh pr view <pr-id> --json reviews
```
- **Perumpamaan Sehari-hari:**
  - Seperti kamu **cek feedback temen** yang udah ngasih review tentang tugas yang kamu buat, lengkap dengan komentar-komentar mereka. 📝

---

### 🔄 **3. Memeriksa Status dan History PR**
Kalau kamu lagi ngecek PR yang udah di-merge atau belum, kamu bisa lihat **status** dan **history-nya** menggunakan perintah ini. Jadi, kamu tahu apakah PR itu udah selesai di-review atau masih dalam proses. 🕒

**Contoh Perintah GitHub CLI:**
```bash
gh pr view <pr-id> --json state,createdAt,mergedAt
```
- **Perumpamaan Sehari-hari:**
  - Seperti kamu ngecek **status dan waktu selesai tugas**, apakah udah selesai atau masih dikerjain. ⏱️

---

## 🔥 **Contoh Penggunaan `gh pr view --json`**

Berikut adalah beberapa contoh perintah **`gh pr view --json`** yang bisa kamu coba:

### 🎯 **1. Melihat Informasi Lengkap PR dalam Format JSON**
```bash
gh pr view <pr-id> --json
```
- **Perumpamaan:** Kayak kamu **minta laporan lengkap** tentang tugas yang udah dikerjain temen. Kamu bisa lihat semuanya dalam satu tempat. 📑

---

### 📝 **2. Melihat Reviews dan Komentar PR**
```bash
gh pr view <pr-id> --json reviews
```
- **Perumpamaan:** Seperti kamu **cek feedback** dari temen-temen yang udah nge-review tugas kamu, apakah ada yang perlu diperbaiki atau nggak. 🗣️

---

### 🔄 **3. Mengecek Status PR (Apakah Sudah Di-merge)**
```bash
gh pr view <pr-id> --json state,createdAt,mergedAt
```
- **Perumpamaan:** Seperti kamu **cek status tugas** apakah udah selesai atau masih dikerjain. 🏁🔄

---

## 🎯 **Kenapa `gh pr view --json` Itu Keren?**

- **Lihat Detail PR Tanpa Repot:** Dengan **`gh pr view --json`**, kamu bisa langsung dapetin **informasi lengkap PR** tanpa perlu buka browser. Semua data yang dibutuhin ada di terminal. 🚀
- **Format JSON yang Mudah Diproses:** Data yang ditampilkan dalam **format JSON** memudahkan kamu buat ngecek dan ngolah informasi lebih lanjut. Kalo kamu suka ngoding, bisa langsung diproses pake skrip atau tools lain. 💻
- **Cepat dan Efisien:** Semua informasi yang kamu butuhin tentang PR langsung diakses cuma pake satu perintah, tanpa perlu cari-cari manual. ⏱️

---

## 📖 **Bacaan Lanjut dan Referensi**

- [GitHub CLI Documentation](https://cli.github.com/manual/gh_pr_view) 📘
- [GitHub Pull Requests Documentation](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests) 📚

---

## 🎉 **Kesimpulan**

Dengan menggunakan **`gh pr view --json`**, kamu bisa **melihat informasi lengkap** tentang **pull request** GitHub langsung di terminal dalam format **JSON**. Baik itu untuk ngecek status PR, lihat **reviewers**, atau sekedar **mencari tahu lebih detail** tentang PR tertentu, semuanya jadi lebih praktis dan efisien!

Kalau kamu sering kerja dengan PR dan butuh akses cepat ke data tersebut, perintah ini bakal sangat **ngebantu** dalam **mempercepat workflow** kamu! 🚀
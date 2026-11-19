# 📋 Lembar Kredensial Resmi Tim Customer Support & Super Admin
**Jagoan Search — Portal Solusi & Dokumentasi Teknis Jagoan Hosting**

> Dokumen ini memuat data akun resmi yang telah di-seed dan aktif pada database TiDB Cloud. Staf cukup memasukkan **Username** dan **Password** masing-masing (tanpa perlu mengetikkan email).

---

### 👑 Akun Super Admin
* **Akses & Hak Istimewa (Privilege)**:
  * Memiliki menu eksklusif **"Kelola Template"** di Navbar.
  * Memiliki akses eksklusif ke tab **"📊 Audit Log & Analitik Tutorial"** di `/admin` untuk melihat siapa saja CS yang membaca tutorial, artikel apa yang dibuka, dan frekuensinya secara *real-time*.

| Nama Akun | Username Login | Kata Sandi (Password) | Hak Akses |
| :--- | :--- | :--- | :---: |
| **Super Admin** | `admin` | `230403` | **Super Admin (Full Access & Audit)** |

---

### 🛡️ Akun 16 Staf Customer Support
* **Hak Akses**: Pencarian cerdas (Fuzzy Search dengan toleransi typo), Investigasi kendala Board Kasus (`/board`), AI Copilot diagnosa, dan Extension Chrome.
* Staf biasa **tidak dapat** melihat menu analitik admin maupun mengedit template alur investigasi.

| No | Nama Rekan CS | Username Login | Kata Sandi (Password) | Keterangan |
| :---: | :--- | :--- | :--- | :---: |
| 1 | **Annisa** | `annisa` | `Annis@JH73` | CS Agent |
| 2 | **Aulia** | `aulia` | `Auli@JH29` | CS Agent |
| 3 | **Bima** | `bima` | `Bim@JH81` | CS Agent |
| 4 | **Devita** | `devita` | `Devit@JH45` | CS Agent |
| 5 | **Ebik** | `ebik` | `Ebik#JH62` | CS Agent |
| 6 | **Efril** | `efril` | `Efril#JH38` | CS Agent |
| 7 | **Farras** | `farras` | `Farr@sJH91` | CS Agent |
| 8 | **Fikry** | `fikry` | `Fikry#JH17` | CS Agent |
| 9 | **Henry** | `henry` | `Henry#JH54` | CS Agent |
| 10 | **Hildan** | `hildan` | `Hild@nJH83` | CS Agent |
| 11 | **Rompis** | `rompis` | `Rompis#JH26` | CS Agent |
| 12 | **Shinta** | `shinta` | `Shint@JH67` | CS Agent |
| 13 | **Sielo** | `sielo` | `Sielo#JH92` | CS Agent |
| 14 | **Syamsul** | `syamsul` | `Sy@msulJH48` | CS Agent |
| 15 | **Yogi** | `yogi` | `Yogi#JH35` | CS Agent |
| 16 | **Yusuf** | `yusuf` | `Yusuf#JH76` | CS Agent |

---

### 💡 Fitur Kunci:
1. **Gatekeeper Login**: Pengunjung yang belum memasukkan akun tidak dapat melihat halaman pencarian maupun board kasus, dan otomatis diarahkan ke halaman login.
2. **Kunci Sesi Permanen**: Sesi staf terkunci aktif hingga **1 Tahun**. Browser dapat ditutup atau laptop dimatikan tanpa perlu login ulang.
3. **Quick Login**: Jika staf logout, halaman login menyediakan tombol *Quick Login* untuk akun yang terakhir digunakan pada perangkat tersebut.
4. **Pelacakan Audit Extension & Web**: Setiap kali agen membuka panduan dari portal web maupun Chrome Extension, sistem mencatat username dan judul artikel ke TiDB Cloud.

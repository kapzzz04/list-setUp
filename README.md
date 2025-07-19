Siap! Berikut ini versi yang sudah dirapikan dan disusun sebagai **tahapan setup environment** untuk dimasukkan ke file `README.md` di GitHub:

---

## 🔧 Setup Environment

### ✅ Rekomendasi Ekstensi Visual Studio Code

| Bahasa      | Ekstensi yang Direkomendasikan                                                                                      |
| ----------- | ------------------------------------------------------------------------------------------------------------------- |
| HTML/CSS/JS | `Live Server`, `Prettier - Code Formatter`, `ESLint`, `Auto Rename Tag`, `IntelliSense for CSS class names in HTML` |
| PHP         | `PHP Intelephense`, `PHP Server`, `PHP Debug`                                                                       |

---

### 📁 Persiapan Folder Lokal

1. **Buka Git Bash**

2. Masuk ke folder `Desktop/keyro`:

   ```bash
   cd /c/Users/Administrator/Desktop/keyro
   ```

3. Jika folder `keyro` belum ada, buat terlebih dahulu:

   ```bash
   mkdir -p /c/Users/Administrator/Desktop/keyro
   cd /c/Users/Administrator/Desktop/keyro
   ```

---

### ⬇️ Clone Repository dari GitHub

Clone repository yang dibutuhkan ke dalam folder `keyro`:

```bash
git clone https://github.com/username/nama-repo.git
```

> Gantilah `https://github.com/username/nama-repo.git` dengan URL repo kamu sendiri.

---

### 🔐 Login Git (Jika Diminta)

Saat melakukan clone pertama kali, Git akan meminta kamu untuk login. Gunakan akun GitHub kamu:

* Masukkan **username GitHub**
git config --global user.email "keyno569@gmail.com"
git config --global user.name "kapzzz04"
* Masukkan **personal access token** sebagai pengganti password (jika pakai HTTPS)

---
Setelah repo berhasil dibuat, GitHub akan menampilkan perintah untuk menambahkan remote origin. Biasanya seperti ini:

bash
Salin
Edit
git remote add origin https://github.com/username/nama-repo.git
Lalu dorong (push) isi folder ke GitHub:

bash
Salin
Edit
git push -u origin master


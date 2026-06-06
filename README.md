# Practice-git-status-branch
# Panduan Lengkap Git Branching

## 1. Persiapan Awal (Masuk ke "Markas" Proyek)

Sebelum melakukan apa pun, Ayah wajib berada di dalam folder proyek tersebut.

Lihat folder di sekitar:
```bash
ls
```

(Perintah ini untuk melihat daftar folder/file yang ada di posisi terminal saat ini).

Masuk ke dalam folder proyek:

```bash
cd nama-folder-proyek
```

(Ganti nama-folder-proyek dengan nama folder yang Ayah tuju).

2. Memulai Dunia Branching (Sistem Cabang)

Cek branch aktif:

```bash
git branch
```

(Tanda bintang * menunjukkan di mana Ayah sedang berada sekarang).

Membuat branch baru:

```bash
git branch nama-fitur-baru
```

(Ini seperti membuat ruang kerja baru yang terpisah dari main).

Pindah ke branch baru:

```bash
git checkout nama-fitur-baru
```

(Sekarang Ayah resmi pindah ke ruang kerja baru).

3. Bekerja di Dalam Branch

Membuat file baru:

```bash
touch nama-file.txt
```

Menulis isi di dalam file:

```bash
nano nama-file.txt
```

(Setelah menulis, tekan Ctrl + O lalu Enter untuk simpan, kemudian Ctrl + X untuk keluar).

Mengecek status perubahan:

```bash
git status
```

(Melihat file mana saja yang sudah diubah atau ditambah).

4. Menyimpan Progres (Commit)

Memasukkan file ke daftar tunggu:

```bash
git add .
```

(Titik . artinya semua file yang berubah langsung didaftarkan).

Menyimpan riwayat (Commit):

```bash
git commit -m "Catatan apa yang berubah di sini"
```

(Catatan ini sangat penting agar Ayah tidak lupa apa yang sudah dikerjakan).

5. Berpindah Antar Ruang (Switching)

Kembali ke main:

```bash
git checkout main
```

(File yang tadi dibuat di branch baru akan hilang dari pandangan, tapi sebenarnya tersimpan aman di branch tersebut).

Kembali lagi ke fitur:

```bash
git checkout nama-fitur-baru
```

(File akan muncul kembali secara ajaib!).

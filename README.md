# backend-5053241036

Repo tugas mata kuliah **Pengembangan Backend Dasar**, dibuat dari template [`webdev-if-its/backend-template`](https://github.com/webdev-if-its/backend-template). Ganti judul di atas jadi nama repo kalian sendiri (`backend-nrp`, contoh: `backend-5025201012`).

## Aturan Umum

- Tugas tiap pertemuan disimpan di folder `pertemuan-XX/` pada repo ini.
- Commit message wajib menyebut level yang dicapai: `pertemuan-XX: level N selesai`.
- Deadline push: sebelum pertemuan berikutnya dimulai.
- Semua level dicek otomatis lewat `go test` — baca `pertemuan-XX/SOAL.md` tiap minggu untuk detail levelnya.

## Mengambil Pertemuan Baru Tiap Minggu

Repo ini **tidak otomatis sinkron** dengan template dosen. Begitu ada pertemuan baru, jalankan (ganti `pertemuan-02` sesuai minggu berjalan):

```bash
git fetch https://github.com/webdev-if-its/backend-template.git main
git checkout FETCH_HEAD -- pertemuan-02
```

Perintah ini **aman dijalankan kapan pun** — tidak akan menimpa folder pertemuan lain yang sudah kalian kerjakan, karena hanya mengambil folder yang disebutkan. Setelah itu, commit folder barunya seperti biasa.

Kalau dosen memperbaiki sesuatu di pertemuan yang sudah dirilis (mis. ada bug di test), biasanya cukup ambil ulang file yang diperbaiki saja, bukan seluruh folder — akan diumumkan file mana yang berubah.

---

Bagian di bawah ini **isi bertahap** sesuai level yang sedang kalian kerjakan (lihat `pertemuan-01/SOAL.md`) — heading-nya dicek otomatis, jangan diganti namanya.

## Identitas
- Nama: Zahra Fidela Ramadhiani Tjahjono
- NRP: 5053241036
- Kelas: M (RPL)

## Commit vs Push
Commit adalah kegiatan menyimpan perubahan file, dan Push adalah kegiatan mengupload perubahan tadi ke github.
Contoh situasi : ketika sebuah tim teridiri dari 2 orang, satu mengerjakan fitur A, dan satunya lagi mengerjakan fitur B, dimana seharusnya fitur B ini bisa dikerjakan ketika fitur A selesai. Lalu orang fitur A sudah selesai mengerjakan, dia commit dengan message "fitur A done" tepat waktu. namun dia lupa belum push ke github, sehingga orang fitur B yang seharusnya sudah bisa langsung mengerjakan jadi terlambat karna dia belum bisa menerima hasil dari fitur A di repo mereka.
## Reproducibility
Jika satu tim memakai versi Go yang berbeda, itu tidak akan menjadi masalah besar dan bisa tetap berjalan asalkan fitur yang diapakai itu adalah fitur dasar. Namun itu akan menjadi masalah nyata ketika teman satu tim memakai fitur terbaru pada versi Go yang lebih baru, dan saya masih memakai Go versi lama. Di saat itulah versi Go yang lama tidak akan bisa menjalankan kode nya.

## Catatan Merge Conflict
(tulis di sini)

## Kenapa .gitignore Penting
(tulis di sini)

## Refleksi
(tulis di sini)

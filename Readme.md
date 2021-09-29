Nama: Muhammad Hanif Sudibyo
NIM: 162012133040
Prodi: Teknologi Sains Data

Langkah langkah dalam membuat dan commit pada GitHub:
1. Membuat folder pada directory lokal untuk repository lokal, disini saya namai sesuai nama repository pada GitHub, yaitu Tugas1-AlPro.
2. Lalu buat file bernama Readme.md untuk deskripsi utama dalam repository
3. Lalu kita buka Git bash pada folder ini untuk melakukan operasi Git
4. Lalu kita inisialisasi repository dengan **git init**
5. Setelah inisialisasi, kita track file Readme.md untuk proses staging dengan **git add Readme.md**
6. Lalu kita commit file Readme.md tadi ke repository lokal dengan **git commit**
7. Setelah itu kita buat repository remote pada GitHub, disini saya menamai repository dengan "Tugas1-AlPro", seperti pada repository lokal
8. Lalu kita add alamat repository remote tadi dengan **git remote add server-yeay [link repository GitHub]**, server-yeay disini merupakan nama alias untuk repository remote
9. Setelah itu dapat kita push file Readme.md kosong ini pada repository remote dengan **git push server-yeay master**, master adalah nama branch repository lokal kita
10. Setelah itu, file Readme.md kosong tadi akan terupload pada repository remote, lalu kita dapat mengedit file Readme.md dengan langkah-langkah dalam tugas 1 ini
11. Setelah itu dapat kita track lagi file Readme.md yang sudah diedit dengan **git add Readme.md**
12. Lalu kita commit file Readme.md tadi dengan **git commit**
13. Terakhir, kita dapat push file Readme.md tadi dengan **git push server-yeay master**
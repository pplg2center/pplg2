XI PPLG 2 - GitHub Pages

VERSI INI TIDAK MEMAKAI FIREBASE, STORAGE, ATAU PESAN ANONIM.
Tidak ada fitur admin di galeri. Foto ditambahkan dengan mengedit array PHOTOS di gallery.html.

FILE UTAMA:
- index.html       halaman pembuka
- class.html       halaman informasi kelas
- gallery.html     galeri statis
- secret-room.html halaman rahasia

CARA TAMBAH FOTO:
1. Taruh file gambar di folder yang sama dengan gallery.html, misalnya foto1.jpg.
2. Buka gallery.html.
3. Cari const PHOTOS.
4. Tambahkan: { gambar: 'foto1.jpg', judul: 'Judul', deskripsi: 'Keterangan', tanggal: '2026' }

GITHUB PAGES:
Settings -> Pages -> Deploy from a branch -> main -> / (root) -> Save.
Pastikan index.html ada di root repository.

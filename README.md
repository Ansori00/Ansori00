Nama : Ansori Rafik
NIM : 352310938
Kelas : IE.23.C.13
Mata Kuliah : Program Komputer + Praktek
Dosen : Agung Nugroho, S.Kom., M.Kom.
"Membuat program sederhana pada pyhton menggunakan "List" dan "Dictionary"
A. Algoritma Program
Algoritma Program Pengelolaan Nilai Mahasiswa

1, Mulai Program

2, Inisialisasi List Kosong

students = [] (untuk menyimpan data mahasiswa)
3, Tampilkan Menu Utama

o Pilihan:

Lihat Data (L)
Tambah Data (T)
Ubah Data (U)
Hapus Data (H)
Cari Data (C)
Keluar (K)
4, Pilih Menu

o Input pilihan pengguna.

Proses Berdasarkan Pilihan Menu
5, Jika Pilihan (L): Lihat Data

o Jika list students kosong:

Tampilkan pesan "Tidak Ada Data".
o Jika list tidak kosong:

Tampilkan semua data mahasiswa dalam format tabel.
6, Jika Pilihan (T): Tambah Data

o Input:

NIM
Nama
Nilai Tugas
Nilai UTS
Nilai UAS
o Hitung Nilai Akhir:

nilai_akhir = (tugas * 0.3) + (uts * 0.35) + (uas * 0.35)
o Tambahkan data ke dalam list students.

o Tampilkan pesan "Data Berhasil Ditambahkan".

7, Jika Pilihan (U): Ubah Data

o Tampilkan data mahasiswa.

o Input nomor data yang ingin diubah.

o Jika nomor valid:

Input data baru:
NIM, Nama, Tugas, UTS, UAS.
Hitung ulang nilai akhir.
Perbarui data dalam list.
Tampilkan pesan "Data Berhasil Diubah".
o Jika nomor tidak valid:

Tampilkan pesan "Nomor Data Tidak Valid".
8, Jika Pilihan (H): Hapus Data

o Tampilkan data mahasiswa.

o Input nomor data yang ingin dihapus.

o Jika nomor valid:

Hapus data dari list students.
Tampilkan pesan "Data Berhasil Dihapus".
o Jika nomor tidak valid:

Tampilkan pesan "Nomor Data Tidak Valid".
9, Jika Pilihan (C): Cari Data

o Input NIM mahasiswa yang ingin dicari.

o Cari data berdasarkan NIM dalam list students.

o Jika ditemukan:

Tampilkan data mahasiswa.
o Jika tidak ditemukan:

Tampilkan pesan "Data Tidak Ditemukan".
10, Jika Pilihan (K): Keluar

o Tampilkan pesan "Keluar dari Program".

o Hentikan program.

11, Jika Pilihan Tidak Valid

o Tampilkan pesan "Pilihan Tidak Valid".

o Kembali ke menu utama.

12, Ulangi dari Langkah 3 Hingga Pengguna Memilih Keluar (K).

13, Selesai

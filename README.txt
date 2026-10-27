UNDANGAN PERNIKAHAN - CARA PAKAI
1. Buka index.html di browser (klik dua kali), atau unggah folder ini ke hosting (Netlify, Vercel, GitHub Pages, dll).
2. LOGIN ADMIN: ikon gembok di header.
   - Di komputer sendiri (file/localhost) ikon gembok langsung tampil.
   - Di hosting, buka alamat dengan tambahan ?admin  (contoh: https://situs-anda.com/?admin).
   - Pertama kali: buat password admin (min. 8 karakter). Selanjutnya login dengan password itu.
   - Setelah login, ikon pensil (CMS) muncul. Klik gembok terbuka untuk keluar.
   - Ubah password: CMS > Keamanan.
3. Ubah teks/gambar, klik Simpan (tersimpan di browser Anda).
4. Agar semua pengunjung melihat perubahan DAN password berlaku di hosting:
   klik "Unduh content.json", lalu taruh file itu di folder yang sama dengan index.html di hosting.
5. Musik (ikon musik di header):
   - LAGU WAJIB (permanen, tampil untuk semua tamu): login admin > CMS > "Musik Wajib".
     Di hosting sendiri: salin file MP3 ke folder musik/ (di samping index.html), lalu di CMS pilih file yang sama
     (atau ketik jalur: musik/nama-lagu.mp3) > Tambah > Simpan > Unduh content.json dan unggah bersama folder musik/.
     Urutan bisa diatur dengan tombol panah; tamu tidak bisa menghapus lagu wajib.
   - LAGU TAMU: tombol "+ Tambah Lagu Saya" di menu musik. Tersimpan hanya di perangkat tamu tersebut
     (maks. 20 lagu, 15 MB per file), tidak terlihat tamu lain maupun admin, dan bisa dihapus tamu sendiri.
6. Nama tamu: tambahkan #Nama-Tamu di akhir alamat, contoh index.html#Bapak-Andi
7. Koordinat Google Maps: isi di CMS bagian Acara & Lokasi, format -5.1477,119.4327 atau alamat lengkap.

UNTUK BANYAK KLIEN
- Buat satu folder terpisah untuk setiap klien (salin index.html ke folder baru, mis. klien-rina-adi/, klien-budi-sari/).
- Tiap folder/situs punya penyimpanan sendiri, jadi klien baru SELALU mulai dari layar "Buat Password Admin",
  walaupun Anda sudah membuat password untuk klien lain di browser yang sama.
- Setelah klien membuat password dan mengisi data, unduh content.json dan unggah bersama index.html ke hosting klien tersebut.
- Jangan memakai content.json klien lain untuk klien baru (password dan isinya ikut terbawa).
- Lupa password / ingin mulai ulang: di jendela Login admin klik "Lupa password? Atur ulang di browser ini".
  Jika content.json di hosting sudah berisi password, hapus juga bagian "adm" di file tersebut lalu unggah ulang.
- Memindahkan folder ke lokasi lain di komputer dianggap situs baru (password lokal tidak ikut); password di content.json tetap ikut.

CATATAN KEAMANAN
Situs ini statis (tanpa server), jadi login hanya menyembunyikan editor. Yang benar-benar menentukan
siapa yang bisa mengubah situs adalah akses ke hosting Anda: perubahan baru tampil untuk pengunjung
setelah content.json diunggah ke hosting. Gunakan password yang kuat dan jaga akun hosting Anda.
8. Gulir otomatis: ikon panah-bawah di header. Klik untuk mulai/berhenti; chip 'Kecepatan' mengganti 1x/2x/3x. Berhenti otomatis saat Anda menyentuh/scroll atau tiba di bagian bawah.

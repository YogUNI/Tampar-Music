# Tampar-Music

Halo Semuanya, saya membuat suatu project dari python yang berisi suatu lagu dan lirik
Jadi ini sebuah permainan sederhena menggunakan Python dengan pygame yang menampilkan lirik lagu dengan efek hujan yang animatif.
Berikut Lebih detail mengenai setiap bagian dari kodenya serta cara menjalankan project ini:
1. Inisialisasi Pygame:
- pygame.init() digunakan untuk memulai modul Pygame.
- screen_width dan screen_height menentukan ukuran layar, dan screen adalah objek tampilan utama.

2. Judul Jendela dan Warna:
- Judul jendela diatur dengan pygame.display.set_caption().
- Warna putih dan biru digunakan untuk teks dan latar belakang.

3. Font dan Ukuran:
- Font diatur dengan pygame.font.SysFont(), dan digunakan untuk menampilkan teks lirik.

4. Lirik dan Waktu Jeda:
- lines menyimpan lirik lagu dengan waktu jeda antar karakter.
- delays adalah waktu jeda antara lirik yang berbeda.

5. Fungsi draw_text_centered:
- Fungsi ini digunakan untuk menampilkan teks di tengah layar.

6. Efek Hujan:
- Rain adalah kelas untuk membuat sprite hujan yang bergerak secara acak di layar.
- Gambar hujan, awan, dan karakter diinisialisasi dan digunakan dalam game.

7. Loop Utama:
- Loop utama mengatur logika permainan, seperti menggambar hujan, menampilkan lirik, dan menggerakkan karakter.
- Lirik akan ditampilkan satu per satu dengan efek mengetik, dan hujan akan terus turun sepanjang permainan.

8. Akhir Loop:
- Setelah semua lirik ditampilkan, teks "End of Lyrics" muncul di layar.

Bagaimana cara Run? (How To Run?)
1. Instalasi Pygame : `pip install pygame`
   
2. Pastikan Gambar Tersedia : Pastikan file gambar hujan.png, sapira.png, dan me.png tersedia di direktori yang sama dengan file Python ini. Jika tidak ada, program akan menghasilkan error saat mencoba memuat gambar.
   
3. Menjalankan Project : Simpan kode Python di file dengan ekstensi .py, misalnya tampar_lyrics.py.
Buka terminal atau command prompt, lalu arahkan ke direktori tempat file disimpan.
Jalankan program dengan perintah berikut: `python tampar_lyrics.py`

4. Interaksi : Program akan membuka jendela baru di mana efek hujan dan lirik lagu akan ditampilkan secara animatif.
Program akan berjalan hingga semua lirik selesai ditampilkan atau kamu menutup jendela tersebut.

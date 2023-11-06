Kode pada Class `GameMain` yang mewakili panel permainan dalam permainan Tic-Tac-Toe. 
fungsi masing-masing bagian dari kode tersebut:

1. `initGame()` metode untuk menginisialisasi isi papan permainan dan status permainan saat ini.Metode ini mengatur seluruh sel papan permainan menjadi kosong dan menentukan bahwa permainan siap dimainkan dengan pemain "CROSS" yang bergerak pertama.

2. `updateGame()` adalah metode yang memperbarui status permainan setelah pemain dengan "theSeed" telah memasang di posisi (baris, kolom).
   Metode ini memeriksa apakah ada pemain yang menang atau permainan berakhir imbang, dan memperbarui status permainan saat ini berdasarkan hasil tersebut.

3. `paintComponent(Graphics g)` adalah metode yang melakukan gambar kustom pada JPanel ini. Metode ini mengisi latar belakang panel, menggambar papan permainan, dan menampilkan pesan status pada status bar tergantung pada status permainan saat ini.




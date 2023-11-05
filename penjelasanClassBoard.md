Kode yang diberikan adalah bagian dari kelas `Board` yang mewakili papan permainan dalam permainan Tic-Tac-Toe. Berikut adalah fungsi masing-masing bagian dari kode tersebut:

1. `Board()` adalah konstruktor yang menginisialisasi papan permainan. Pada konstruktor ini, array 2D `cells` diinisialisasi dengan sel-sel permainan.

2. `init()` adalah metode yang menginisialisasi kembali papan permainan. Metode ini menghapus semua isi sel permainan.

3. `isDraw()` adalah metode yang memeriksa apakah permainan berakhir imbang (draw), yaitu ketika tidak ada sel kosong tersisa.

4. `hasWon()` adalah metode yang memeriksa apakah pemain dengan "seed" tertentu telah menang setelah menempatkan di posisi (seedRow, seedCol).

5. `paint(Graphics g)` adalah metode yang menggambar papan permainan dan sel-selnya di atas kanvas grafis.

Kelas `Board` berfungsi untuk mengelola seluruh papan permainan dan berisi metode-metode yang penting untuk mengelola status permainan dan menentukan apakah ada pemenang atau permainan berakhir imbang.

Kode dari class `Board` mewakili papan permainan dalam permainan Tic-Tac-Toe. 
fungsi masing-masing bagian dari kode tersebut:

1. `Board()`  menginisialisasi papan permainan. Pada konstruktor ini, array 2D `cells` diinisialisasi dengan sel-sel permainan.

2. `init()`  metode yang menginisialisasi kembali papan permainan. Metode ini menghapus semua isi sel permainan ketika permainan sudah selesai.

3. `isDraw()`  metode yang memeriksa apakah permainan berakhir imbang (draw), yaitu ketika tidak ada sel kosong tersisa.

4. `hasWon()` metode yang memeriksa apakah pemain dengan "seed" tertentu telah menang setelah menempatkan di posisi (seedRow, seedCol).
   yaitu ketika salah seorang pemain sudah menderetkan tanda meraka masing-masing baik secara vertikal, horizontal, atau 
diagonal.

5. `paint(Graphics g)`  menggambarkan papan permainan dan sel-selnya di atas kanvas grafis.


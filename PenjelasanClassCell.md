Kode yang diberikan adalah implementasi kelas `Cell` yang mewakili sel pada papan permainan dalam permainan Tic-Tac-Toe. Berikut adalah fungsi masing-masing bagian dari kode tersebut:

1. `clear()` adalah metode yang menghapus konten sel saat ini dan mengaturnya kembali ke `Seed.EMPTY`.

2. `paint(Graphics g)` adalah metode yang melukis sel itu sendiri pada kanvas grafis. Metode ini menggunakan `Graphics2D` yang memungkinkan kita untuk mengatur stroke pen. Metode ini menggambar simbol (CROSS atau NOUGHT) di dalam sel berdasarkan konten sel. Jika kontennya adalah `Seed.CROSS`, maka akan digambar silang (X) berwarna kuning. Jika kontennya adalah `Seed.NOUGHT`, maka akan digambar bulatan (O) berwarna biru. Penempatan dan ukuran simbol ditentukan berdasarkan ukuran sel dan konstanta terkait.

Kelas `Cell` bertanggung jawab untuk mengelola tampilan setiap sel pada papan permainan, termasuk menggambar simbol di dalam sel sesuai dengan konten sel saat ini.

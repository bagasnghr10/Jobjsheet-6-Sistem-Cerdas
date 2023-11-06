Kode pada  `Cell` yang mewakili sel pada papan permainan dalam permainan Tic-Tac-Toe. 
fungsi masing-masing bagian dari kode tersebut:

![image](https://github.com/bagasnghr10/Jobjsheet-6-Sistem-Cerdas/assets/143892102/2146aad9-935b-4b0f-b7c1-e62ac863747e)


1. `clear()` adalah metode yang menghapus konten sel saat ini dan mengaturnya kembali ke `Seed.EMPTY`.
2. `paint(Graphics g)` adalah metode untuk menggambar sel  pada kanvas grafis. Metode ini menggunakan `Graphics2D`  untuk mengatur stroke pen. Metode ini menggambar simbol (CROSS atau NOUGHT) di dalam sel berdasarkan konten sel. Jika kontennya adalah `Seed.CROSS`, maka akan digambar silang (X) berwarna hijau. Jika kontennya adalah `Seed.NOUGHT`, maka akan digambar bulatan (O) berwarna merah. 


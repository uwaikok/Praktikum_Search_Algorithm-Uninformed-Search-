# Praktikum_Search_Algorithm-Uninformed-Search-
2306144_Rifki ahmad Dzulfikri

1.UCS (Uniform Cost Search)

-UCS adalah algoritma pencarian yang memperhitungkan biaya dalam menemukan jalur terpendek dari titik awal ke tujuan.
-Algoritma ini menggunakan struktur antrian prioritas untuk selalu mengeksplorasi simpul dengan biaya terendah terlebih dahulu.
-Cocok digunakan untuk mencari jalur optimal dalam graf berbobot.

2.DFS (Depth-First Search)

-DFS adalah algoritma pencarian yang menjelajahi graf dengan menyelam sedalam mungkin sebelum kembali ke simpul sebelumnya.
-Menggunakan struktur stack (baik eksplisit maupun dengan rekursi).
-Tidak menjamin solusi optimal, tetapi efisien dalam penggunaan memori.
-Cocok untuk eksplorasi ruang besar dengan sedikit solusi atau saat mencari jalur yang lebih dalam lebih dulu.

3.BFS (Breadth-First Search)

-BFS adalah algoritma pencarian yang menjelajahi simpul tingkat demi tingkat sebelum melangkah ke tingkat lebih dalam.
-Menggunakan struktur queue untuk memastikan semua simpul pada tingkat yang sama dieksplorasi terlebih dahulu.
-Menjamin solusi optimal jika semua langkah memiliki bobot yang sama.
-Cocok untuk menemukan jalur terpendek dalam graf tak berbobot.


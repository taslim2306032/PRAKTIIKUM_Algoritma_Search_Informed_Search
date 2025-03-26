
# Implementasi Algoritma Pencarian Berbasis Informasi Tambahan (Informed Search)

Repositori ini merupakan kumpulan implementasi dari berbagai algoritma pencarian yang memanfaatkan informasi tambahan atau pendekatan heuristik (Informed Search), ditulis dalam bahasa pemrograman Python. Algoritma-algoritma ini dirancang untuk menavigasi graf dan menemukan jalur optimal secara efisien dengan menggunakan estimasi terhadap jarak ke tujuan sebagai panduan dalam proses pencarian.

---

## 🧠 Jenis Algoritma yang Diimplementasikan

Beberapa algoritma yang termasuk dalam kategori pencarian berbasis informasi tambahan dan telah diimplementasikan dalam proyek ini antara lain:

### 🔹 Greedy Best-First Search (GBFS)
- Algoritma ini bekerja dengan memilih node berdasarkan nilai heuristik yang menunjukkan estimasi jarak terpendek menuju node tujuan.
- Tidak mempertimbangkan total biaya perjalanan dari titik awal.
- Cocok untuk pencarian cepat meskipun tidak selalu menjamin jalur terpendek.

### 🔹 A* Tree Search
- Implementasi algoritma A* menggunakan pendekatan *tree search*.
- Tidak menyimpan daftar node yang telah dieksplorasi sebelumnya.
- Node yang sama dapat dikunjungi kembali melalui jalur berbeda.

### 🔹 A* Graph Search
- Varian algoritma A* dengan pendekatan *graph search*.
- Menyimpan node yang sudah dikunjungi agar tidak dieksplorasi ulang.
- Lebih efisien dan mencegah perulangan yang tidak diperlukan.

Seluruh algoritma ini digunakan untuk menyelesaikan permasalahan pencarian jalur dalam struktur graf dengan pendekatan berbasis heuristik guna meningkatkan efisiensi dan efektivitas proses pencarian.

---

## 📁 Struktur Repositori

```
repository-name/
│
├── greedy_best_first.py     # Implementasi algoritma Greedy Best-First Search
├── a_star_tree.py           # Implementasi algoritma A* (Tree Search)
├── a_star_graph.py          # Implementasi algoritma A* (Graph Search)
└── README.md                # Dokumentasi proyek
```

Setiap file tidak hanya berisi kode algoritma, tetapi juga telah dilengkapi dengan contoh kasus penggunaan yang bisa dijalankan secara langsung.

---

## 🚀 Cara Menjalankan Program

### 🔧 Menjalankan di Google Colab atau Komputer Lokal

1. **Kloning Repositori:**

```bash
git clone https://github.com/username/repository-name.git
cd repository-name
```

2. **Eksekusi File Python:**

```bash
python greedy_best_first.py
python a_star_tree.py
python a_star_graph.py
```

---

## 🎯 Tujuan Proyek

Tujuan dari proyek ini adalah untuk menyediakan implementasi praktis dari algoritma pencarian berbasis heuristik, yang umum digunakan dalam bidang kecerdasan buatan, pencarian jalur (pathfinding), dan teori graf. Proyek ini bertujuan membantu pembaca memahami perbedaan antara pendekatan pencarian yang satu dengan yang lain dari segi performa, akurasi, dan efisiensi.

---

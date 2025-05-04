# Summary Materi Sebelum UTS

Summary ini mencakup penggunaan **pandas**, **matplotlib**, serta algoritma **Naive Bayes** dan **Decision Tree**

## 1. Pandas

### Pengertian
library Python yang digunakan untuk memproses dan menganalisis data terstruktur, terutama data tabular.

### Struktur Data Pandas
`Series`, `DataFrame`

### Fungsi Penting Pandas
- `read_csv()`: Untuk membaca data dari file CSV.
- `concat()`: Untuk menggabungkan dua DataFrame secara vertikal atau horizontal.

## 2. Matplotlib 

### Pengertian
library Python yang sangat populer dan fleksibel untuk menciptakan visualisasi data, seperti plot grafik, diagram, dan banyak lagi.

### Jenis Plot Pada Matplotlib
- `Line Plot`: Menampilkan data sebagai garis, sering digunakan untuk melihat tren dari waktu ke waktu. 
- `Scatter Plot`: Menampilkan data sebagai titik-titik, sering digunakan untuk melihat hubungan antara dua variabel. 
- `Bar Plot`: Menampilkan data dalam bentuk batang, sering digunakan untuk membandingkan nilai antara berbagai kategori.

## 3. Naive Bayes

### Pengertian
Digunakan untuk klasifikasi probabilistik berdasarkan Teorema Bayes.

### Jenis Naive Bayes
- `GaussianNB`: untuk data numerik (distribusi normal).
- `MultinomialNB`: untuk data diskrit (frekuensi, seperti teks).
- `BernoulliNB`: untuk fitur biner (0/1).

## 4. Decision Tree

### Pengertian
Algoritma klasifikasi berbasis struktur pohon keputusan.

### Visualisasi Pohon
```python
from sklearn.tree import plot_tree  
plot_tree(model, filled=True)
```

---



<h1 align="center"><b>Tugas 6 Pemrosesan Citra Digital</b></h1>

Nama | Nim | Mata Kuliah | Dosen Pengampu
---|---|---|---
Adelia Erlyn N.C.P. | 2110131320010 | Pemrosesan Citra Digital | Dr. Harja Santanapurba, M.Kom / Novan Alkaf B. S. S.Kom., M.T

<hr><br>

<h1 align="center"><b> Spatial Frequency Domain </b></h1></p>

<hr><br>

```
Ada 2 metode untuk melakukan perbaikan kualitas citra (Image Enhancement), yaitu :
1. Image Enhancement ranah Spasial
2. Image Enhancement ranah Frekuensi
```

<h2><b> 1. Domain Spasial </b></h2>

<p align="justify">Domain Spasial adalah suatu citra dapat direpresentasikan dalam bentuk matriks 2D dimana setiap elemen matriks mewakili intensitas piksel. Keadaan matriks 2D yang menggambarkan distribusi intensitas suatu gambar.</p>

<p align="justify">Dapat direpresentasikan seperti yang ditunjukkan di bawah ini</p><br>

<p align="center"><img src="img/TUGAS6_F1.png" width="500px"></p><br>

<p align="justify">Untuk citra RGB, domain spasial direpresentasikan sebagai vektor 3D dari matriks 2D. Setiap matriks 2D berisi intensitas untuk satu warna seperti yang ditunjukkan di bawah ini</p><br>

<p align="center"><img src="img/TUGAS6_F2.png" width="500px"></p><br>

<p align="justify">Setiap intensitas piksel direpresentasikan sebagai I(x,y) di mana x,y adalah koordinat piksel dalam matriks 2D. Operasi yang berbeda dilakukan dalam nilai ini. Misalnya- operasi T(katakanlah, penambahan 5 ke semua piksel) dilakukan di I(x,y) yang berarti bahwa setiap nilai piksel bertambah 5. Ini dapat ditulis sebagai</p>

```
I’(x,y) = T[I(x,y)]
```

<p align="justify">di mana, I’(x,y) adalah intensitas baru setelah menambahkan 5 ke I(x,y).</p><br>

<h3 align="center"><b> NOTED </b></h3></p>


```
DOMAIN SPASIAL

- Konsep koordinat baris dsn kolom
- Pemrosesan piksel-per-piksel
- Komputasi lama (terutama citra dengn ukuran yang spasial tinggi)
```
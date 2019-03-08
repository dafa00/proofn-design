---
description: >-
  Grid System digunakan untuk penyusunan layout halaman dengan beberapa jenis
  baris dan kolom yang digunakan untuk meletakkan konten.
---

# Grid

Pada aplikasi Proofn, Proofn menggunakan repsonsive, Fluid grid system, lebih tepatnya memiliki skala sampai dengan 12 column.

### **Struktur Dasar**

Proofn memiliki Fixed Left-side panel yang hanya ada pada Proofn versi web. Dimana fixed left-side panel ini memiliki kegunaan sebagai navigasi, yang isinya mencakup kotak pesan, grup, dan kontak. Besarnya Fixed Left-side panel ini adalah 56px. Jadi, Grid dimulai setelah 56px dari Fixed Left-side panel ini.

![](.gitbook/assets/grid.png)

### Cara Bekerja

#### **Gutter**

Kolom memberikan Gutter \(jarak diantara kolom\). Untuk devices dengan screen yang memiliki lebar lebih dari 768px, memiliki Column Padding sebesar 20px. Dan, untuk Devices dengan screen lebar kurang dari 768px, memiliki Column Padding sebesar 12px.

**Column**

Proofn seharusnya memiliki 12 column, namun apabila designer dirasa perlu untuk mengurangi column di gridnya, designer dapat melebarkan grid yang dirasa perlu untuk dilebarkan.

**Margins**

Grid dengan 12 Column tidak memiliki maximum grid. Dengan kata lain, memiliki Grid sebesar 100% yang terdapat margin didalamnya yang dapat membuat padding diantara jumlah kolom dan edges viewport.

Contoh : Screen width 1028px 

22px kanan = 6% margins \(dIbulatkan dengan yang terdekat\)

22px kiri = 6% margins \(dIbulatkan dengan yang terdekat\)

### Grid skala besar

Proofn selalu menggunakan ukuran default dan tergantung oleh tipe konten dan kepadatan konten. Untuk ukuran layar yang besar, skalanya tetap harus konsisten dari setiap sesi dari product. Proofn menggunakan ukuran default dari grid skala besar ini karena agar setiap bentuk dan kepadatannya selalu konsisten dan dapat memberi kenyamanan kepada pengguna apabila pengguna menggunakan layar yang besar. Ukuran Fixed Left Panel akan ikut membesar, sesuai dengan persentase dari setiap ukuran layar, jika pada ukuran normal layar yaitu 1280px memiliki persentasi 4.5%, maka untuk ukuran yang lebih besar lagi, tetap memiliki 4.5% dari setiap ukurannya. 4.5% tidak berlaku jika ukurannya lebih kecil dari 1280px. Jika ukurannya lebih kecil, tetap menggunakan skala 56px lebar Fixed Left Panel. Untuk Column juga memiliki perubahan, yaitu dapat membesar lagi, sedangkan gutter nilainya tetap 24px.


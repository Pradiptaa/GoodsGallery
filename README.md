# GoodsGallery
---
## Pradipta Arya Pramudita - 2206083685
---
## ---Tugas 7---
---
### Apa perbedaan utama antara stateless dan stateful widget dalam konteks pengembangan aplikasi Flutter?
---
Stateless widget adalah widget yang tidak memiliki state internal dan tidak dapat diubah setelah dibuat. Penggunaan stateless widget hanya memerlukan definisi tampilan widget tersebut dalam method build, lalu Flutter akan render tampilan.
<br>
Stateful widget adalah widget yang dapat memiliki state internal dan dapat melakukan perubahan atau pembaruan data. Saat state internal berubah, perlu memanggil method setState untuk memicu perubahan tampilan.

### Sebutkan seluruh widget yang kamu gunakan untuk menyelesaikan tugas ini dan jelaskan fungsinya masing-masing.
---
* Material: Untuk mengatur latar belakang dan tampilan.
* InkWell: Untuk memberikan respons ketika user menyentuh tampilan.
* Container: Unutk mengelola tampilan dan memberikan margin dan padding.
* Column: Untuk mengatur tampilan secara vertikal dalam satu column
* Icon: Untuk menampilkan icon dengan warna dan ukuran tertentu.
* Text: Untuk menampilkan text.
* SnackBar: Untuk menampilkan pesan pop-up kecil saat user berinteraksi.
* Scaffold: Untuk mengatur kerangka dasar aplikasi.
* AppBar: Untuk membuat Bar dalam aplikasi.
* GridView: Untuk membuat tata letak berbasis grid.
* Padding: Untuk memberikan padding pada tampilan.

### Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas secara step-by-step (bukan hanya sekadar mengikuti tutorial)
---
Dimulai dengan membuat direktori baru dengan nama project yang diinginkan, lalu generate project flutter pada direktori tersebut. Dilanjut dengan memodifikasi file main.dart yang sudah ter-generate dengan import baru dan menghapus sebagian kode. Buat file baru bernama menu.dart pada folder yang sama dengan main.dart. Lalu import dari file main.dart.
<br>
Dilanjut dengan membuat stateless widget pada main.dart, dan membuat class yang extend stateless widget pada file menu.dart. Lengkapi file menu.dart dengan class yang diperlukan dan hal terakhir yang dilakukan adalah run project.
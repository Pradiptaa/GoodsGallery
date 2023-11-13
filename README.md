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

---
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

---
### Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas secara step-by-step (bukan hanya sekadar mengikuti tutorial)
---
Dimulai dengan membuat direktori baru dengan nama project yang diinginkan, lalu generate project flutter pada direktori tersebut. Dilanjut dengan memodifikasi file main.dart yang sudah ter-generate dengan import baru dan menghapus sebagian kode. Buat file baru bernama menu.dart pada folder yang sama dengan main.dart. Lalu import dari file main.dart.
<br>
Dilanjut dengan membuat stateless widget pada main.dart, dan membuat class yang extend stateless widget pada file menu.dart. Lengkapi file menu.dart dengan class yang diperlukan dan hal terakhir yang dilakukan adalah run project.

---
###  Jelaskan perbedaan antara Navigator.push() dan Navigator.pushReplacement(), disertai dengan contoh mengenai penggunaan kedua metode tersebut yang tepat!
---
* <strong>Navigator.push()</strong> digunakan untuk menambah rute baru ke tumpukan navigasi, yang berarti rute sebelumnya tetap ada di dalam tumpukan navigasi dan user dapat kembali ke rute sebelumnya. 
<br> Contoh:

~~~
Navigator.push(
    context,
    MaterialPageRoute(
    builder: (context) => ShopFormPage(),
    ));
~~~
* <strong>Navigator.pushReplacement()</strong> digunakan untuk menggantikan rute saat ini dengan rute baru, yang berarti rute sebelumnya akan dihapus dari tumpukan navigasi.
<br> Contoh:

~~~
Navigator.pushReplacement(
    context,
    MaterialPageRoute(
    builder: (context) => MyHomePage(),
    ));
~~~
---
###  Jelaskan masing-masing layout widget pada Flutter dan konteks penggunaannya masing-masing!
---
1. <strong>Container:</strong> Berguna untuk mengatur tata letak dan tampilan elemen.
2. <strong>Row & Column:</strong> Berguna untuk mengatur elemen dalam baris dan kolom (horizontal dan vertikal) secara berurutan.
3. <strong>ListView: </strong> Berguna untuk menampilkan daftar elemen yang rolling vertikal ataupun horizontal.
4. <strong>Card: </strong> Berguna untuk membuat kartu berisi konten seperti gambar, teks, ataupun tidakan.
5. <strong>Align: </strong> Berguna untuk mengatur elemen dalam tata letak dengan presisi berdasarkan lokasi dalam kotak yang lebih besar.
6. <strong>Flow: </strong> Berguna untuk mengatur elemen dalam aliran (flow) berdasarkan algoritma tata letak yang khusus.
7. <strong>SizedBox: </strong> Berguna untuk menambahkan spasi berdasarkan lebar dan tinggi tertentu.

---
###  Sebutkan apa saja elemen input pada form yang kamu pakai pada tugas kali ini dan jelaskan mengapa kamu menggunakan elemen input tersebut!
---

---
###  Bagaimana penerapan clean architecture pada aplikasi Flutter?
---

---
###  Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas secara step-by-step! (bukan hanya sekadar mengikuti tutorial)
---
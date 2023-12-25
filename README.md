# flutter_application_bimbingankonseling_ammar

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## widget mobile ammar

widget yang di pakai ialah

- main.dart
    
    `Pada kode yang Anda berikan, terdapat penggunaan beberapa widget dari paket flutter/material.dart. Berikut adalah widget yang digunakan:

MaterialApp: Merupakan widget yang mendefinisikan struktur dasar aplikasi menggunakan Material Design. Widget ini memiliki banyak properti yang dapat dikonfigurasi, seperti debugShowCheckedModeBanner, title, dan theme.

ThemeData: Widget ini digunakan untuk mengkonfigurasi tema aplikasi. Pada contoh kode, colorScheme diatur dengan warna dasar dari skema warna, dan useMaterial3 diatur sebagai true.

LoginPage: Merupakan custom widget yang digunakan sebagai halaman utama (home) pada aplikasi. Custom widget ini mungkin didefinisikan dalam file terpisah, yaitu login.dart. Namun, detail implementasi dari LoginPage tidak diberikan dalam potongan kode yang Anda berikan.

Selain itu, terdapat widget lain seperti Container, Column, Row, atau widget lainnya yang mungkin digunakan dalam implementasi LoginPage, tetapi detailnya tidak terlihat dalam potongan kode tersebut.`

- login.dart

    `Pada potongan kode LoginPage yang Anda berikan, terdapat penggunaan beberapa widget dari paket flutter/material.dart. Berikut adalah widget yang digunakan:

MaterialApp: Pada fungsi build di dalam kelas LoginPage, kembali digunakan widget MaterialApp. Perlu diingat bahwa sebaiknya hanya satu instance MaterialApp didefinisikan di seluruh aplikasi, biasanya pada bagian paling atas dari aplikasi.

Scaffold: Widget ini digunakan untuk membuat struktur dasar dari antarmuka pengguna Material. Pada potongan kode ini, Scaffold digunakan sebagai induk dari antarmuka halaman login.

Container: Digunakan untuk membuat kotak yang dapat dikonfigurasi, di mana widget lain dapat ditempatkan di dalamnya. Pada kode ini, Container digunakan untuk memberikan margin pada seluruh elemen yang berada di dalamnya.

Column: Merupakan widget yang mengatur anak-anaknya dalam satu kolom. Pada potongan kode ini, Column digunakan untuk mengatur tata letak vertikal dari elemen-elemen anak di dalam Container.

Text: Untuk menampilkan teks pada antarmuka pengguna. Digunakan untuk menampilkan pesan "Welcome Back" dan "Enter your credential to login, Bimbingan Konseling" pada fungsi _header.

TextField: Untuk mendapatkan input teks dari pengguna. Digunakan untuk membuat kolom input untuk alamat email dan kata sandi.

ElevatedButton: Digunakan untuk membuat tombol dengan efek naik ketika ditekan. Pada potongan kode ini, ElevatedButton digunakan sebagai tombol "Login".

Icon: Untuk menampilkan ikon. Digunakan pada prefixIcon pada TextField untuk menambahkan ikon di bagian depan input.

SizedBox: Digunakan untuk menambahkan spasi kosong di antara elemen-elemen di dalam Column.

TextButton: Digunakan untuk membuat tombol teks. Meskipun pada potongan kode ini tidak memiliki teks yang terlihat, mungkin diimplementasikan lebih lanjut pada bagian yang belum diisi (dengan teks dan fungsi yang sesuai).

Navigator: Digunakan untuk mengelola perpindahan antar halaman. Pada kode ini, digunakan untuk mengarahkan ke halaman HomeScreen saat tombol "Login" ditekan.

Itulah beberapa widget yang digunakan dalam potongan kode LoginPage yang Anda berikan.`

- profile.dart

    `Pada potongan kode yang Anda berikan, terdapat penggunaan beberapa widget dari paket flutter/material.dart. Berikut adalah widget yang digunakan:

Scaffold: Widget ini digunakan untuk membuat struktur dasar dari antarmuka pengguna Material. Pada potongan kode ini, Scaffold digunakan sebagai kerangka utama halaman profil.

AppBar: Merupakan widget yang menampilkan bilah aplikasi di bagian atas. Pada potongan kode ini, AppBar digunakan sebagai bilah aplikasi dengan judul "Profile" dan tombol kembali (IconButton).

IconButton: Digunakan untuk membuat tombol ikon. Pada potongan kode ini, IconButton digunakan sebagai tombol kembali di AppBar.

Column: Widget ini digunakan untuk menata anak-anaknya dalam satu kolom. Pada potongan kode ini, Column digunakan untuk mengatur tata letak vertikal dari elemen-elemen di dalam Scaffold.

Container: Widget ini digunakan untuk membuat kotak yang dapat dikonfigurasi. Pada potongan kode ini, Container digunakan untuk mengatur tata letak dan tampilan dari gambar profil.

Text: Digunakan untuk menampilkan teks pada antarmuka pengguna. Terdapat beberapa contoh penggunaan pada kode ini, seperti menampilkan nama ("Ammar"), status ("Siswa"), judul ("PROFILE"), dan informasi profil lainnya.

SizedBox: Digunakan untuk menambahkan spasi kosong. Pada potongan kode ini, SizedBox digunakan untuk memberikan spasi antara elemen-elemen.

Expanded: Widget ini digunakan untuk memberikan proporsi fleksibel pada elemen-elemen dalam Column. Pada potongan kode ini, Expanded digunakan untuk memberikan proporsi pada bagian atas dan bawah dari halaman profil.

Row: Widget ini digunakan untuk menata anak-anaknya dalam satu baris. Pada potongan kode ini, Row digunakan untuk menata ikon dan teks pada bagian bawah halaman profil.

ListView: Meskipun tidak terlihat dalam potongan kode yang diberikan, kemungkinan besar widget ini digunakan di beberapa bagian untuk membuat daftar item, seperti pada fungsi listProfile.

Icon: Digunakan untuk menampilkan ikon. Terdapat beberapa contoh penggunaan pada kode ini, seperti menampilkan ikon kembali di IconButton dan ikon pada fungsi listProfile.`

- home.dart

    `Pada potongan kode yang Anda berikan, terdapat penggunaan beberapa widget dari paket flutter/material.dart. Berikut adalah beberapa widget yang digunakan:

Scaffold: Widget ini digunakan untuk membuat struktur dasar dari antarmuka pengguna Material. Pada potongan kode ini, Scaffold digunakan sebagai kerangka utama halaman utama (HomeScreen).

AppBar: Merupakan widget yang menampilkan bilah aplikasi di bagian atas. Pada potongan kode ini, AppBar digunakan sebagai bilah aplikasi dengan judul "Home" dan menu aksi seperti menu profil dan log out.

PopupMenuButton: Widget ini membuat tombol yang menghasilkan menu pop-up ketika ditekan. Digunakan untuk menampilkan opsi "Profile" dan "Log Out" pada bagian kanan atas AppBar.

Column: Widget ini digunakan untuk menata anak-anaknya dalam satu kolom. Pada potongan kode ini, Column digunakan untuk mengatur tata letak vertikal dari elemen-elemen di dalam halaman.

Card: Digunakan untuk membuat kartu dengan bayangan dan bentuk bulat. Pada potongan kode ini, Card digunakan untuk membuat kartu yang berisi informasi waktu, informasi siswa, dan tombol absen.

ListTile: Digunakan untuk membuat elemen dalam daftar. Pada potongan kode ini, ListTile digunakan untuk menampilkan informasi waktu pada kartu pertama.

Container: Widget ini digunakan untuk membuat kotak yang dapat dikonfigurasi. Digunakan di beberapa tempat untuk mendefinisikan tata letak dan penataan visual.

Text: Digunakan untuk menampilkan teks pada antarmuka pengguna. Terdapat berbagai penggunaan pada potongan kode ini untuk menampilkan teks seperti judul, deskripsi, dan informasi lainnya.

SizedBox: Digunakan untuk menambahkan spasi kosong. Pada potongan kode ini, SizedBox digunakan untuk memberikan spasi antara elemen-elemen.

ElevatedButton: Digunakan untuk membuat tombol dengan efek naik ketika ditekan. Pada potongan kode ini, ElevatedButton digunakan sebagai tombol absen masuk, terlambat, dan pulang.

FloatingActionButton: Digunakan untuk menampilkan tombol aksi mengambang. Pada potongan kode ini, FloatingActionButton digunakan sebagai tombol untuk menambahkan formulir absen baru.

BottomAppBar: Digunakan untuk menempatkan aksi navigasi dan tindakan lainnya di bagian bawah antarmuka. Pada potongan kode ini, BottomAppBar digunakan sebagai bilah navigasi di bagian bawah halaman.

Icon: Digunakan untuk menampilkan ikon. Terdapat beberapa penggunaan pada potongan kode ini, seperti menampilkan ikon pada tombol aksi mengambang dan ikon pada bilah navigasi bawah.

InkWell: Digunakan untuk membuat efek klik pada widget. Pada potongan kode ini, InkWell digunakan pada ikon "Visi Dan Misi" pada bilah navigasi bawah.`

- about.dart

`Pada potongan kode VisiMisiScreen yang Anda berikan, terdapat penggunaan beberapa widget dari paket flutter/material.dart. Berikut adalah beberapa widget yang digunakan:

Scaffold: Widget ini digunakan untuk membuat struktur dasar dari antarmuka pengguna Material. Pada potongan kode ini, Scaffold digunakan sebagai kerangka utama halaman "Visi Misi Sekolah SMK Taruna Bhakti".

AppBar: Merupakan widget yang menampilkan bilah aplikasi di bagian atas. Pada potongan kode ini, AppBar digunakan sebagai bilah aplikasi dengan judul "Visi Misi Sekolah SMK Taruna Bhakti".

SingleChildScrollView: Widget ini digunakan untuk membuat widget dapat discroll ke atas dan ke bawah. Digunakan di dalam body untuk memastikan kontennya dapat diakses dengan baik, terutama jika konten lebih panjang dari layar.

Padding: Digunakan untuk memberikan jarak (padding) pada elemen-elemen di dalamnya. Pada potongan kode ini, Padding digunakan untuk memberikan jarak di sekitar Column.

Column: Widget ini digunakan untuk menata anak-anaknya dalam satu kolom. Pada potongan kode ini, Column digunakan untuk mengatur tata letak vertikal dari elemen-elemen dalam halaman.

Text: Digunakan untuk menampilkan teks pada antarmuka pengguna. Terdapat banyak penggunaan Text untuk menampilkan judul, teks visi, misi, dan informasi lainnya.

SizedBox: Digunakan untuk menambahkan spasi kosong. Pada potongan kode ini, SizedBox digunakan untuk memberikan spasi antara elemen-elemen.

Demikianlah beberapa widget yang digunakan dalam potongan kode VisiMisiScreen yang Anda berikan.`

- form.dart

    `Pada potongan kode FormScreen yang Anda berikan, terdapat penggunaan beberapa widget dari paket flutter/material.dart. Berikut adalah beberapa widget yang digunakan:

Scaffold: Widget ini digunakan untuk membuat struktur dasar dari antarmuka pengguna Material. Pada potongan kode ini, Scaffold digunakan sebagai kerangka utama halaman formulir.

AppBar: Merupakan widget yang menampilkan bilah aplikasi di bagian atas. Pada potongan kode ini, AppBar digunakan sebagai bilah aplikasi dengan judul "Question".

TextField: Digunakan untuk membuat input teks. Pada potongan kode ini, TextField digunakan untuk memasukkan keterangan siswa.

SizedBox: Digunakan untuk menambahkan spasi kosong. Pada potongan kode ini, SizedBox digunakan untuk memberikan jarak antara elemen-elemen.

Text: Digunakan untuk menampilkan teks pada antarmuka pengguna. Pada potongan kode ini, Text digunakan untuk menampilkan informasi bahwa keterangan telah direkap, jika _showText adalah true.

Container: Digunakan untuk membuat kontainer dengan penataan dan dekorasi tertentu. Pada potongan kode ini, Container digunakan untuk mengatur tata letak tombol submit.

ElevatedButton: Digunakan untuk membuat tombol dengan efek naik ketika ditekan. Pada potongan kode ini, ElevatedButton digunakan sebagai tombol submit.

setState(): Digunakan untuk memperbarui state widget. Pada potongan kode ini, setState() digunakan untuk mengubah nilai _showText menjadi true saat tombol submit ditekan.

Future.delayed(): Digunakan untuk menunda eksekusi kode selama beberapa waktu tertentu. Pada potongan kode ini, Future.delayed() digunakan untuk menunggu 2 detik sebelum pindah ke halaman beranda.

Navigator.push(): Digunakan untuk melakukan navigasi ke halaman baru. Pada potongan kode ini, Navigator.push() digunakan untuk pindah ke halaman beranda setelah mengisi formulir.

Demikianlah beberapa widget dan konsep yang digunakan dalam potongan kode FormScreen yang Anda berikan.`
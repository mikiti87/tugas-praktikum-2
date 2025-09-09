# flutter_application_1
Analasisa kode 
Kode ini adalah aplikasi Flutter sederhana dengan navigasi antar halaman.
Terdapat dua halaman: HomePage dan ItemPage.
Navigasi menggunakan routes pada MaterialApp.
Titik awal aplikasi adalah HomePage.

langkah langkah 
persiapan Project

Pastikan sudah menginstall Flutter dan VS Code.
Buat project baru Flutter:
flutter create nama_project

Salin kode main.dart ke folder lib.
Membuat Halaman

Buat dua file baru di folder lib/pages/:
home_page.dart
item_page.dart
Isi masing-masing file dengan widget sederhana (misal: Scaffold dengan judul).
Implementasi Navigasi

Pada HomePage, tambahkan tombol untuk pindah ke ItemPage:
ElevatedButton(
  onPressed: () {
    Navigator.pushNamed(context, '/item');
  },
  child: Text('Go to Item Page'),
)
Pastikan ItemPage menampilkan konten berbeda.

uji coba 
flutter run
Pastikan tombol di HomePage berfungsi dan berpindah ke ItemPage.

Modifikasi & Eksplorasi

Tambahkan fitur lain, misal: kembali ke HomePage dari ItemPage.
Ubah tampilan halaman sesuai kreativitas.


<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/068e98e6-06c0-4cb2-a9ed-1c6f696f172b" />

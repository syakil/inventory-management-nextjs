Inventory Management Dashboard - Next.js, Node.js, Redux & AWS

Deskripsi

Aplikasi ini dikembangkan mengikuti tutorial dari video YouTube Build Next.js Inventory Management Dashboard & Deploy on AWS. Aplikasi ini bertujuan untuk mempermudah pengelolaan inventaris, mencatat barang masuk/keluar, dan memantau stok dengan antarmuka yang modern dan user-friendly.

Fitur Utama

Manajemen Barang: Pencatatan barang masuk dan keluar.

Stock Opname: Laporan stok secara real-time.

Analisis Data: Grafik dan visualisasi data inventaris.

Pengaturan Pengguna: Manajemen user dengan role berbeda.

Deployment di AWS: Implementasi dan hosting aplikasi di AWS.

Instalasi

Clone repository ini:

git clone [URL_REPOSITORY]

Masuk ke direktori project:

cd inventory-management-dashboard

Instal dependensi:

npm install

Jalankan aplikasi:

npm run dev

Konfigurasi

Pastikan untuk mengatur file .env sesuai dengan kebutuhan aplikasi.

Contoh konfigurasi:

DATABASE_URL=[url_database]
PORT=3000
AWS_ACCESS_KEY_ID=[aws_access_key]
AWS_SECRET_ACCESS_KEY=[aws_secret_key]

Cara Penggunaan

Akses aplikasi melalui browser di http://localhost:3000.

Login menggunakan akun admin yang telah terdaftar.

Kelola inventaris dan pantau data stok secara langsung.

Teknologi yang Digunakan

Frontend: Next.js, React.js

Backend: Node.js, Express

State Management: Redux Toolkit

Database: MongoDB

Deployment: AWS (EC2, S3, Lambda)

Kontribusi

Kontribusi sangat diterima! Jika ingin berkontribusi:

Fork repository ini.

Buat branch fitur (git checkout -b feature/[nama_fitur]).

Commit perubahan (git commit -m 'Add [deskripsi fitur]').

Push ke branch (git push origin feature/[nama_fitur]).

Buat Pull Request.
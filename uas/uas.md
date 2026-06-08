# UAS: Deploy Web Static dan Docker di EC2

1. Membuat EC2 Instance

   ![Membuat EC2 Instance](./image-1.png)
   - Menyiapkan instance baru di AWS EC2 untuk menjalankan aplikasi.

2. Membuat Folder Project

   ![Membuat Folder Project](./image-2.png)
   - Membuat struktur folder proyek untuk menyimpan sumber daya dan file aplikasi.

3. Memindahkan project web static UTS ke dalam folder `stati-web`

   ![Memindahkan project web static](./image-3.png)
   - Menyalin dan mengatur ulang file web static ke folder proyek yang benar.

4. Membuat `dashboard.php`

   ![Membuat dashboard.php](./image-4.png)
   - Membuat halaman dashboard sederhana untuk menampilkan data atau kontrol aplikasi.

5. Menginstal Docker dan Docker Compose pada EC2

   ![Menginstal Docker dan Docker Compose](./image-5.png)
   - Mengonfigurasi lingkungan Docker pada instance EC2 untuk menjalankan kontainer.

6. Menambahkan GitHub Secrets

   ![Menambahkan GitHub Secrets](./image-6.png)
   - Menyimpan kredensial dan variabel lingkungan yang dibutuhkan untuk proses CI/CD.

7. Build dan Push Docker Image Otomatis

   ![Build dan Push Docker Image Otomatis](./image-7.png)
   - Menjalankan pipeline untuk membangun image Docker dan mengirimkannya ke registry.

8. Menampilkan Halaman Web Dinamis

   ![Menampilkan Halaman Web Dinamis 1](./image-8.png)
   ![Menampilkan Halaman Web Dinamis 2](./image-9.png)
   ![Menampilkan Halaman Web Dinamis 3](./image-10.png)

9. Tampilan Web Statis

   ![Tampilan Web Statis](./image-11.png)

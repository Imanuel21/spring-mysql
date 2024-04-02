Untuk turorialnya saya pakai dari https://spring.io/guides/gs/accessing-data-mysql

untuk melakukan get dan Post saya menggunakan postman dengan tutorial penggunaannya :

Ya, Anda dapat menggunakan Postman untuk mengirim permintaan yang setara dengan perintah `curl`. Berikut adalah langkah-langkahnya:

1. **Buka Postman**: Buka aplikasi Postman di komputer Anda.

2. **Buat Permintaan Baru**: Klik tombol "New" di sudut kiri atas untuk membuat permintaan baru.

3. **Atur Metode dan URL**: Di bilah alamat URL di atas area kerja, pilih metode HTTP yang sesuai (misalnya, POST) dan masukkan URL endpoint yang ingin Anda gunakan. Misalnya, `http://localhost:8080/demo/add`.

4. **Atur Headers**: Klik pada tab "Headers" di bawah bilah alamat URL. Tambahkan header dengan nama `Content-Type` dan nilai `application/x-www-form-urlencoded`. Ini akan menetapkan tipe konten permintaan sebagai `application/x-www-form-urlencoded`, sama seperti dalam perintah `curl`.

5. **Atur Body**: Klik pada tab "Body" di bawah bilah alamat URL. Pilih opsi "x-www-form-urlencoded" sebagai tipe data. Kemudian, tambahkan pasangan nilai kunci untuk data yang ingin Anda kirim. Misalnya, tambahkan pasangan `name` dan `email` dengan nilai yang sesuai.

6. **Kirim Permintaan**: Klik tombol "Send" di sebelah kanan bilah alamat URL untuk mengirim permintaan. Postman akan mengirimkan permintaan ke endpoint yang ditentukan dengan parameter yang Anda tentukan dalam langkah-langkah sebelumnya.

Dengan menggunakan Postman, Anda dapat membuat dan mengirim permintaan HTTP dengan lebih mudah dan visual daripada menuliskan perintah `curl` secara manual. Postman juga menyediakan fitur-fitur tambahan seperti manajemen permintaan yang lebih baik, pengaturan otentikasi, pengujian otomatis, dan banyak lagi.

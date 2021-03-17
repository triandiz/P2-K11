# Pagekit

## Sekilas Tentang:
Pagekit adalah aplikasi yang digunakan untuk mempermudah para penggunanya dalam membangun web baru. Pagekit sendiri memiliki beragam fitur yang bisa anda gunakan seperti membuat tampilan halaman baru untuk membuat blog dan personalisasi web. Aplikasi yang dibuat oleh @yoohotheme ini dibangun dengan teknologi modern dengan CMS modular dan ringan.

## Instalasi
Proses instalasi Pagekit cepat dan mudah serta hanya membutuhkan waktu beberapa menit.

- Langkah 1: Unduh dan buka Penginstal
  
  Pertama-tama, Anda perlu mengunduh paket Pagekit terbaru dan mengekstrak isinya ke server web Anda, anda bisa mengekstraknya ke direktori root web atau ke subfolder, contoh ```/pagekit```.
  
  NOTE: jika anda mengekstrak paket secara lokal sebelum mengunggah pastikan bahwa sertakan file ```.htaccess``` yang tersembunyi.
  
  Lalu open browser yang tadi sudah di ekstrak, lalu itulah tampilan pertama dari penginstalan web dan anda harus melihatnya.

- Langkah 2: Bahasa

  Selanjutnya anda harus memilih bahasa utama untuk situs tersebut. Ini akan menjadi bahasa default yang digunakan di panel admin dan frontend. Namun bahasa ini dapat diubah kapan saja.

- Langkah 3: Database

  Pada langkah ini anda diharuskn untuk menyambungkannya ke database. Secara default, Pagekit menggunakan SQLite untuk menyimpan data situs anda.  Di sini Anda perlu mengisi kolom Nama Database dan Awalan Tabel. Awalan default tabel adalah ```pk_```.
  
  Sebagai alternatif, Anda juga dapat memilih untuk menggunakan MySQL. Dalam hal ini, detail berikut perlu dimasukkan.
  
  <table>
    <tbody>
        <tr>
            <td>BIDANG System</td>
            <td>DESKRIPSI</td>
        </tr>
        <tr>
            <td>Driver</td>
            <td colspan=3 style="text-align:center">Maukkan database driver. Bergantung pada database yang digunakan</td>
        </tr>
        <tr>
            <td>Hostname</td>
            <td colspan=3 style="text-align:center">Masukkan host name dari database server kalian. Jika data base dan web server berada pada mesin yang sama, berarti berada pada localhost atau 127.0.0.1. </td>
        </tr>
        <tr>
            <td>User</td>
            <td colspan=3 style="text-align:center">Masukkan nama pengguna MySQL yang memiliki akses ke database.</td>
        </tr>
        <tr>
            <td>Password</td>
            <td colspan=3 style="text-align:center">Masukkan password Mysql</td>
        </tr>
      <tr>
            <td>Database Name</td>
            <td colspan=3 style="text-align:center">Masukkan nama database</td>
        </tr>
      <tr>
            <td>Table Prefix</td>
            <td colspan=3 style="text-align:center">Anda dapat mengubah prefiks yang digunakan untuk tabel database. Awalan default adalah pk_.</td>
        </tr>
    </tbody>
</table>

  CATATAN Pagekit akan mencoba membuat database selama instalasi. Anda juga dapat melakukan ini sendiri menggunakan alat seperti phpMyAdmin. Jangan ragu untuk menggunakan database yang sudah ada. Pagekit mengawali tabelnya untuk menghindari konflik.
 
- Langkah 4: Penyiapan situs

## Konfigurasi

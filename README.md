# srs-kelompok-3
<strong><em>Software Requirement  Specifications </em></strong>
<p>
  <strong>System Test Online</strong>
  </p>
<p>
disususn oleh : <br>
181022000010  Suwarjono<br>
181022000017  Susi  <br>
181022000063  Michael Raymond Ketty<br>
181022000015  Angelina Hadriani<br>
</p>
<p>
Mata Kuliah Rekayasa Perangkat Lunak
</p>
<p></p>

<p>&nbsp;</p>
<p><strong>1. Pendahuluan</strong> </p>
<p><strong>1.1 Tujuan</strong> </p>
<p>Tujuan pembuatan software ini adalah untuk mengotomatisasi proses ujian tengah semester atau ujian akhir  semester secara online. Sistem ini dikhususkan untuk dosen yang ingin  melakukan proses ujian secara online agar proses ujian dapat direkap dengan  baik dan hasil dari ujian dapat diketahui secara langsung oleh dosen selaku  pemilik sistem maupun mahasiswa sebagai user pada waktu ujian berlangsung.  Berbeda jika proses ujian di lakukan secara manual butuh waktu dalam proses  rekap hasil dari ujian mahasiswa. Dengan perkembangan teknologi informasi saat  ini khususnya internet dan smartphone maka sistem ini akan sangat membantu  dalam proses rekap hasil ujian mahasiswa dengan cepat dan&nbsp; mudah untuk di terapkan kapan saya dan dimana  saja selama terkoneksi dengan internet.</p>
<p>&nbsp;</p>
<p><strong>1.2 Ruang Lingkup</strong> </p>
<p>Adapun ruang lingkup pembuatan  software ini adalah aplikasi berbasis web yang memiliki beberapa  fasilitas yaitu:.</p>
<ol>
  <li>Memiliki fasilitas / menu untuk  pembuatan bank soal atau kumpulan soal-soal dan dapat menyisipkan file dalam  bentuk gambar.</li>
  <li>Memiliki fasilitas /menu untuk  pembuatan jadwal test online dan pilihan soal-soal yang akan ditestkan .</li>
  <li>Sistem&nbsp; &nbsp;mampu&nbsp;  &nbsp;menampilkan soal dengan urutan yang  berbeda-beda atau acak pada masing user </li>
  <li>Soal test ditampilkan persatu soal  dan akan menampilkan soal berikutnya setelah user menjawab soal yang  ditampilkan.</li>
  <li>Sistem mampu menampilkan keterangan jumlah soal yang telah dijawab  oleh user dan jumlah soal yang belum di jawab.</li>
  <li>Sistem&nbsp; akan menampilkan hasil dari test online saat  user telah menjawab semua soal dari test .</li>
  <li>Sistem mampu menampilkan hasil rekap test online semua user</li>
  <li>Sistem mampu melanjutkan test online  kembali dengan menampilkan soal yang belum dijawab jika tidak sengaja keluar  dari sistem .</li>
</ol>
<p>&nbsp;</p>
<p><strong>1.3&nbsp;  Definisi, Istilah, dan Singkatan</strong> </p>
<ol>
  <li>SRS &nbsp;: &nbsp;Software &nbsp;Requirement &nbsp;Specifications  &nbsp;(Spesifikasi  &nbsp;kebutuhan  perangkat lunak</li>
  <li>IEEE : <em>Institute of Electrical and Electronics Engineer</em></li>
</ol>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><strong>1.4&nbsp;  Referensi</strong> </p>
<ol>
  <li>Standar IEEE nomor ANSI / IEEE Std 1058.1-1987 <em>(reaffirmed </em>1993), 18 September 2004.</li>
</ol>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><strong>1.5&nbsp;  Gambaran Umum Dokumen</strong> </p>
<p>Penulisan dokumen ini dibagi menjadi  beberapa bab sebagai berikut:</p>
<ol>
  <li>Bab  1 : menjelaskan mengenai tujuan perangkat lunak, ruang lingkup, daftar definisi, istilah, dan singkatan, referensi  serta gambaran umum dokumen.</li>
  <li>Bab  2 : berisi tentang gambaran  umum mengenai perspektif produk, manfaat produk, karakteristik  user, batasan, &nbsp;asumsi, dan ketergantungan yang digunakan.</li>
  <li>Bab &nbsp;3 &nbsp;: &nbsp;menyediakan &nbsp;spesifikasi &nbsp;kebutuhan &nbsp;antarmuka,  &nbsp;kebutuhan  fungsional, kebutuhan non fungsional,  lingkungan operasi, dan batasan  perancangan.</li>
</ol>
<p>&nbsp;</p>
<p><strong>2. Deskripsi Umum</strong> </p>
<p><strong>2.1 Perspektif Produk</strong> </p>
<p>Produk ini akan  dijalankan oleh admin pemilik sistem  dan oleh user yang memiliki koneksi ke internet. Penggunaan sistem terbagi dua yaitu antar muka  untuk user sebagai mahasiswa  dan antar muka untuk admin sebagai dosen. Produk ini dapat  berjalan &nbsp;pada <em>platform </em>atau sistem operasi apa saja yang mendukung yang  memiliki aplikasi browser baik melalui komputer maupun smartphone</p>
<br clear="all" />
<p><strong>2.2 Manfaat Produk</strong> </p>
<p>Manfaat  yang didapat apabila menggunakan sistem ini antara lain adalah:</p>
<ol>
  <li>Menjaga kemandirian mahasiswa karna  soal ditampilkan dengan urutan berbeda untuk masing-masing user .</li>
  <li>Mempercepat informasi hasil dari test  karna dapat di ketahui saat setelah selesai menjawab semua soal</li>
  <li>Mempercepat pembuatan rekap nilai  mahasiswa hasil dari test online</li>
  <li>Memiliki bank soal yang dapat  digunakan bila diperlukan</li>
</ol>
<p>&nbsp;</p>
<p><strong>2.3 Karakteristik User</strong> </p>
<p>Dalam  sistem informasi ini, users yang terlibat adalah sebagai berikut:</p>
<p><strong>2.3.1 Admin</strong> </p>
<p>Admin adalah user yang digunakan oleh  Dosen yang memiliki fungsi, sebagai pengelola bank  soal, pengelola jadwal test dan soal-soal yang akan ditestkan, melihat dan  download rekap nilai hasil test dari semua user mahasiswa.<br />
    <strong>2.3.2 User </strong> </p>
<p>User &nbsp;adalah yang  digunakan oleh mahasiswa yang memiliki &nbsp;hak &nbsp;untuk melakukan test dan melihat hasil  test untuk dirinya saja.</p>
<p>Karekteristik pengguna  atau user dapat juga dijabarkan dalam table berikut ini.<br />
    <strong>Tabel 1 Karekteristik Pengguna</strong></p>
<table border="1" cellspacing="0" cellpadding="0" width="866">
  <tr align="center"  bgcolor="#EFEFEF">
    <td width="124" height="35"><p>Kategori Pengguna</p></td>
    <td width="283"><p>Tugas</p></td>
    <td width="228"><p>Hak Akses ke Aplikasi</p></td>
    <td width="221"><p>Kemampuan yang harus di miliki</p></td>
  </tr>
  <tr>
    <td width="124"><p><strong>Admin </strong></p></td>
    <td width="283"><ol>
      <li>Mengelola data soal atau bank soal</li>
      <li>Mengelola jadwal test</li>
      <li>Mengelola soal-soal yang akan ditestkan ke mahasiswa    sesuai jadwal</li>
      <li>Mengelola rekap nilai</li>
    </ol></td>
    <td width="228"><ol>
      <li>Akses data soal</li>
      <li>Akses data jadwal test</li>
      <li>Akses soal yang di akan ditestkan</li>
      <li>Akses rekap nilai test</li>
      <li>Akses download rekap nilai</li>
    </ol>
    <p>&nbsp;</p></td>
    <td width="221"><p>Memiliki Pengetahuan    pengunaan aplikasi berbasis web</p></td>
  </tr>
  <tr>
    <td width="124"><p><strong>User</strong></p></td>
    <td width="283"><ol>
      <li>Mengerjakan atau menjawab soal yang telah disediakan    sesuai jadwal test</li>
    </ol></td>
    <td width="228"><ol>
      <li>Akses jadwal    test</li>
      <li>Akses soal test</li>
    </ol></td>
    <td width="221"><p>Memiliki    pengetahuan aplikasi berbasis web.</p></td>
  </tr>
</table>

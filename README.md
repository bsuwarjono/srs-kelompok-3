# srs-kelompok-3
<strong><em>Software Requirement  Specifications </em></strong>
<p>
  <strong>System Test Online</strong>
  </p>
<p>
disususn oleh : <br>
181022000010  Suwarjono (bsuwarjono) <br>
181022000017  Susi (susi91) <br>
181022000063  Michael Raymond Ketty (rayrich-one) <br>
181022000015  Angelina Hadriani (AngelinaHadriani)<br>
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
<p>Manfaat yang didapat apabila menggunakan sistem ini antara lain adalah:</p>
<ol>
  <li>Menjaga kemandirian mahasiswa karna  soal ditampilkan dengan urutan berbeda untuk masing-masing user .</li>
  <li>Mempercepat informasi hasil dari test  karna dapat di ketahui saat setelah selesai menjawab semua soal</li>
  <li>Mempercepat pembuatan rekap nilai mahasiswa hasil dari test online</li>
  <li>Memiliki bank soal yang dapat digunakan bila diperlukan</li>
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

<p><strong>2.4 Batasan-batasan</strong> </p>
<ol>
  <li>Khusus untuk user hanya login saat  mengikuti test dengan memasukan Nim dan Nama Mahasiswa dengan password dan  waktu yang telah ditentukan oleh admin pada saat pembuatan jadwal test.</li>
  <li>Users yang berhak untuk mengakses  sistem ini adalah admin sebagai Dosen dan User sebagai Mahasiswa.</li>
  <li>Aplikasi ini hanya dapat diakses  melalui jaringan internet</li>
  <li>Aplikasi diakses dengan browser baik  yang ada dikomputer maupun smartphone</li>
  <li>Aplikasi diletakan diserver internet  atau hosting yang mendukung apache, php dan mysql</li>
</ol>
<p>&nbsp;</p>
<p><strong>2.5 Asumsi  dan Ketergantungan</strong> </p>
<ol>
  <li>User&nbsp;  &nbsp;pengguna&nbsp; &nbsp;sistem&nbsp;  &nbsp;informasi&nbsp; &nbsp;ini&nbsp;  &nbsp;minimal&nbsp;  &nbsp;tahu&nbsp;  &nbsp;dan&nbsp;  &nbsp;dapat mengoperasikan komputer terutama  untuk aplikasi berbasis <em>web</em>.</li>
  <li>Tersedia sarana web server atau  hosting dan internet untuk mengakses aplikasi ini</li>
</ol>
<p>&nbsp;</p>
<p><strong>3. Kebutuhan Spesifik</strong> </p>
<p><strong>3.1 Kebutuhan Fungsional</strong> </p>
<p>Kebutuhan fungsional sistem ini terdiri  atas beberapa fungsi utama yang saling  berhubungan dan mendukung satu sama lain, yang meliputi  fungsi- fungsi sebagai berikut:</p>
<ol>
  <li>Input data soal oleh <em>admin</em>.</li>
  <li>Pembuatan jadwal test dan soal yang  dipilih oleh <em>admin</em>.</li>
  <li>Menjawab soal test oleh <em>user</em></li>
  <li>Menampilkan hasil nilai dari test  pada masing-masing <em>user</em>.</li>
  <li>Menampilkan laporan rekap nilai hasil  dari test oleh <em>admin</em>.</li>
</ol>
<p>Untuk &nbsp;masing-masing  &nbsp;fungsi&nbsp; diatas &nbsp;akan &nbsp;dijelaskan &nbsp;secara &nbsp;mendetil  sebagai berikut:<br />
  1.&nbsp; Input data  soal : sistem menerima input data soal dari <em>admin</em>, dan dapat menyisipkan file  dalam bentuk gambar jika dibutuhkan.<br />
  2. Pembuatan  jadwal test dan soal yang dipilih &nbsp;dari &nbsp;<em>admin</em> &nbsp;:  &nbsp;sistem&nbsp; menyimpan waktu dimulainya test dan soal-soal  yang dipilih admin untuk dikerjakan oleh user.<br />
  3.  Menjawab soal test oleh <em>user</em> : user  menjawab soal yang ditampilkan secara acak oleh sistem.<br />
  4. Menampilkan  hasil nilai dari test pada masing-masing <em>user</em> : setelah user menjawab semua soal maka sistem akan menampilkan nilai yang  diperoleh dari perhitungan jumlah jawaban benar dibagi jumlah soal dan  dikalikan 100.<br />
  5. Menampilkan  laporan rekap nilai hasil dari test semua user  : sistem menampilkan hasil  rekap test semua user dengan menampilkan jawaban user di urutkan berdasarkan  urutan soal dan kunci jawaban serta menampilkan nilai akhir dan diurutkan  berdasarkan perinkingan serta dapat di simpan dalam bentuk file excel.</p>
<p><strong>3.1.1 Use Case Diagram</strong><br />
    <img  src="http://bausir.net/gambar/gbr1.jpeg" alt="testonline1.jpeg" /> </p>
<p>&nbsp;</p>
<p><strong>3.1.2 Activity Diagram</strong><br />
    <strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>A. Activity Login Admin<br />
    <img  src="http://bausir.net/gambar/gbr2.jpeg" alt="login dosen.jpeg" /> <br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; B. Activity Login User<br />
  <img  src="http://bausir.net/gambar/gbr3.jpeg" alt="loginmahasiswa2.jpeg" /> <br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; C. Activity Bank Soal<br />
  <img  src="http://bausir.net/gambar/gbr4.jpeg" alt="banksoal.jpeg" /> <br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; D. Activity Jadwal Test<br />
  <img  src="http://bausir.net/gambar/gbr5.jpeg" alt="jadwaltest2.jpeg" /> <br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; E. Activity Test User<br />
  <img  src="http://bausir.net/gambar/gbr6.jpeg" alt="testmahasiswa.jpeg" /> <br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; F. Activity Rekap Nilai<br />
  <img  src="http://bausir.net/gambar/gbr7.jpeg" alt="rekapnilai.jpeg" /> </p>
<p>&nbsp;</p>
<p><strong>3.1.2 Sequence Diagram</strong></p>
<ol>
  <li>Sequence Login Admin</li>
</ol>
<p><img  src="http://bausir.net/gambar/login.jpeg" alt="login.JPG" /> </p>
<ol>
  <li>Sequence Login User</li>
</ol>
<p><img  src="http://bausir.net/gambar/gbr8.png" alt="loginuser.JPG" /> </p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<ol>
  <li>Sequence Bank Soal</li>
</ol>
<p><img  src="http://bausir.net/gambar/gbr9.jpeg" alt="soal.jpeg" /> </p>
<ol>
  <li>Sequence Jadwal Test</li>
</ol>
<p><img  src="http://bausir.net/gambar/gbr10.jpeg" alt="jadwal.jpeg" /> </p>
<ol>
  
  <li>Sequence Test User</li>
  <p><img  src="http://bausir.net/gambar/test.jpeg" alt="jadwal.jpeg" /> </p>
  </ol>
  <ol>
  <li>Sequence Rekap Nilai</li>
  <p><img  src="http://bausir.net/gambar/rekapnilai.jpeg" alt="jadwal.jpeg" /> </p>
</ol>
<p><strong>3.2 Kebutuhan Non Fungsional</strong> </p>
<p>Dalam &nbsp;sistem &nbsp;test  online &nbsp;ini, &nbsp;kebutuhan &nbsp;yang &nbsp;mendukung  &nbsp;kelancaran  fungsi-fungsi utama dapat didefinisikan pada  Tabel 1.</p>
<p><strong>T</strong><strong>abel 2  Kebutuhan Non Fungsional</strong></p>
<table border="1" cellspacing="0" cellpadding="0" width="564">
  <tr>
    <td width="156" valign="top"><p><strong>Parameter</strong></p></td>
    <td width="408" valign="top"><p><strong>Requirement</strong></p></td>
  </tr>
  <tr>
    <td width="156"><p><em>Availability</em></p></td>
    <td width="408"><p>24 jam nonstop,    kecuali ada maintenance / perbaikan sistem.</p></td>
  </tr>
  <tr>
    <td width="156"><p><em>&nbsp;</em></p>
        <p><em>Reliability</em></p></td>
    <td width="408"><p>Kegagalan yang ditolerir sekitar 5%.</p></td>
  </tr>
  <tr>
    <td width="156"><p><em>Ergonomy</em></p></td>
    <td width="408"><p>Sistem test online    ini harus user friendly dengan tampilan&nbsp;    responsive</p></td>
  </tr>
  <tr>
    <td width="156"><p><em>Portability</em></p></td>
    <td width="408"><p>Sistem ini berjalan pada platform atau sistem    operasi apa saja yang memiliki browser untuk akses aplikasi</p></td>
  </tr>
  <tr>
    <td width="156"><p><em>Memory</em></p></td>
    <td width="408"><p>Minimum memory 128    MB</p></td>
  </tr>
  <tr>
    <td width="156"><p><em>Response Time</em></p></td>
    <td width="408"><p>Tidak lebih dari 15 detik</p></td>
  </tr>
  <tr>
    <td width="156"><p><em>Security</em></p></td>
    <td width="408"><p>Login&nbsp; users&nbsp;    dan&nbsp; validasi&nbsp; data&nbsp;    sangat&nbsp; penting</p></td>
  </tr>
  <tr>
    <td width="156"><p><em>Bahasa</em></p></td>
    <td width="408"><p>Menu dan tampilan bisa menggunakan&nbsp;&nbsp; bahasa&nbsp;&nbsp;    Inggris dan indonesia</p></td>
  </tr>
</table>
<p><strong>3.3 Kebutuhan AntarMuka</strong> </p>
<p>Kebutuhan antarmuka  dalam program ini antara lain adalah  kebutuhan perangkat&nbsp;&nbsp; keras&nbsp; &nbsp;berupa&nbsp;  &nbsp;<em>Personal&nbsp; &nbsp;Computer&nbsp; &nbsp;</em>(PC)&nbsp; &nbsp;berupa&nbsp;&nbsp; <em>Central Processing&nbsp; Unit &nbsp;</em>(CPU),  &nbsp;<em>mouse</em>,  &nbsp;<em>keyboard</em>,  &nbsp;<em>monitor</em>,  &nbsp;dimana&nbsp; perangkat PC  harus terhubung dengan jaringan  internet, untuk user bisa juga mengunakan  smartphone yang terhubung dengan internet. Sedangkan untuk kebutuhan perangkat lunak yang harus  disediakan adalah berupa sebuah  web <em>browser </em>seperti Google Chrome, Mozilla Firefox,  dan sebagainya untuk menjalankan aplikasi berbasis  web.</p>
<p>&nbsp;</p>
<p><strong>3.4 Lingkungan Operasi</strong> </p>
<p>Aplikasi &nbsp;perangkat lunak &nbsp;ini &nbsp;akan&nbsp;  berfungsi dengan&nbsp; spesifikasi &nbsp;seperti pada Tabel 2<br />
  Tabel 2 Lingkungan  Operasi</p>
<table border="1" cellspacing="0" cellpadding="0" width="522">
  <tr>
    <td width="240" valign="top"><p><strong>Jenis / Kegunaan</strong></p></td>
    <td width="282" valign="top"><p><strong>Perangkat Lunak yang    Digunakan </strong></p></td>
  </tr>
  <tr>
    <td width="240"><p><em>Sistem Operasi</em></p></td>
    <td width="282"><p>Linux/ hosting yang    memiliki Cpanel</p></td>
  </tr>
  <tr>
    <td width="240"><p><em>DataBase Management System    (DBMS)</em></p></td>
    <td width="282"><p>Mysql</p></td>
  </tr>
  <tr>
    <td width="240"><p><em>Pengolah Kata</em></p></td>
    <td width="282"><p>Microsoft Word</p></td>
  </tr>
  <tr>
    <td width="240"><p><em>Bahasa Pemrograman</em></p></td>
    <td width="282"><p>PHP, Javascript, HTML</p></td>
  </tr>
  <tr>
    <td width="240"><p><em>Presentasi</em></p></td>
    <td width="282"><p>Microsoft PowetPoint</p></td>
  </tr>
</table>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><strong>3.5&nbsp;  Batasan Perancangan</strong> </p>
<ol>
<ul>
  <li>Sistem ini hanya digunakan untuk test  online dan rekap nilai saja</li>
  <li>Kelompok users hanya dua saja yaitu  admin sebagai dosen dan user sebagai mahasiswa</li>
  <li>Data mahasiswa lengkap mahasiswa  tidak disimpan pada sistem ini kecuali NIM dan Namanya saat mengikuti test</li>
  <li>Download rekap nilai hanya dalam  bentuk file excel</li>
</ul>

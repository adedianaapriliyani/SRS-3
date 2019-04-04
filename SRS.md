<p><strong>SOFTWARE REQUIREMENTS SPECIFICATIONS</strong></p>
<p><strong>APLIKASI PENJUALAN </strong><strong>OLAHAN </strong></p>
<p><strong>BUAH MANGGA</strong> <strong>INDRAMAYU BERBASIS WEBSITE</strong></p>
<p><strong>TIKB2293 PROYEK II </strong></p>
<p>Diajukan untuk Memenuhi Persyaratan Mata Kuliah Proyek II</p>
<p>&nbsp;</p>
<p><strong>&nbsp;</strong></p>
<p>Disusun Oleh:</p>
<p>Ade Diana Apriliyani&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (1703072)</p>
<p>Fany Fahrurozi&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (1703060)</p>
<p>Fiqi Andri Reviansyah&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (1703064)</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><strong>D3 TEKNIK INFORMATIKA</strong></p>
<p><strong>POLITEKNIK NEGERI INDRAMAYU</strong></p>
<p><strong>&nbsp;</strong></p>
<p>Jl. Lohbener Lama No.08, Lohbener, Indramayu, Legok, Lohbener, Kabupaten Indramayu, Jawa Barat 45252, Indonesia</p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<h1>KATA PENGANTAR</h1>
<p>&nbsp;</p>
<p>Puji syukur kehadirat Allah swt yang telah melimpahkan rahmat-Nya sehingga aplikasi ini dapat diselesaikan tepat pada waktunya dengan judul &ldquo;Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Website &rdquo;. Aplikasi ini disusun demi memenuhi Tugas Mata Kuliah Proyek II Program Studi Teknik Informatika Diploma III Politeknik Negeri Indramayu.</p>
<p>Harapan kami, aplikasi ini menjadi salah satu media yang menarik untuk dikunjungi dan mudah dipahami oleh seluruh pengunjungnya. Akhirnya penyusun mengucapkan banyak terima kasih, khususnya kepada:</p>
<ol>
<li>Ibu Munengsih Sari Bunga, S.Kom., M.Eng selaku Ketua Jurusan Teknik Informatika Politeknik Negeri Indramayu.</li>
<li>Bapak Adi Suheryadi S.ST., M.Kom., selaku dosen wali kelas D3TI.2C dan dosen pembimbing I.</li>
<li>Bapak Eka Ismantohadi, S.Kom.,M.Eng selaku dosen pembimbing II.</li>
<li>Bapak Kurnia Adi Cahyanto, S.T.,M.Kom selaku dosen pembimbing III.</li>
<li>Orang tua dan keluarga yang selalu memberikan dukungan kepada saya baik itu moril maupun materil.</li>
<li>Rekan-rekan D3TI.2C, yang selalu memberikan keceriaan disetiap harinya sehingga saya tidak merasa terbebani dengan adanya tugas ini.</li>
</ol>
<p>Penyusun mengharapkan saran-saran dari para pembaca sebagai masukan yang berguna bagi penyempurnaan aplikasi ini. Semoga aplikasi ini bermanfaat bagi kita semua.</p>
<p><br /> <br /> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Indramayu, 10 Februari 2019<br /> <br /> <br /> <br /> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Penulis<br /> </p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>RINGKASAN </strong></p>
<p>Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Website (MANGOLINESHP) adalah salah satu jenis aplikasi perangkat lunak yang dapat digunakan untuk membantu proses penjualan olahan secara online. Selama ini pemasaran olahan mangga khas Indramayu dipasarkan secara konvensional yaitu dijual di toko sekitar Indramayu saja. Pemasaran olahan mangga Indramayu pun kurang berkembang karena pembeli harus datang ke toko. Oleh karena itu olahan mangga&nbsp; khas Indramayu pun yang mengenal hanya orang-orang yang singgah atau berwisata ke Indramayu saja. Sehingga kami berinisiatif untuk membuat sebuah wadah yang didalamnya terdapat lapak-lapak penjual olahan mangga dalam bentuk aplikasi berbasis website. Dibuatnya aplikasi ini kami bisa membantu pemasaran dari penjual olahan mangga Indramayu serta mempromosikan tentang keberagaman olahan mangga yang ada di Indramayu.</p>
<p>Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Website ini dibangun dengan menggunakan framework laravel dengan didukung basis data MYSQL.</p>
<p><strong>Kata kunci&nbsp;&nbsp;&nbsp;&nbsp; : </strong>Aplikasi Penjualan, framework laravel, MYSQL</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><strong><br /> </strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>BAB I</strong></p>
<p><strong>PENDAHULUAN</strong></p>
<p><strong>1.1 Tujuan</strong></p>
<p>Dokumen ini akan menyajikan deskripsi rinci tentang Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Website (MANGOLINESHP) yang akan dikembangkan. Dokumen akan menjelaskan mengenai spesifikasi pada aplikasi Mangolineshop seperti fitur sistem, antarmuka sistem, sistem apa yang akan dilakukan, apa saja kendala pada saat aplikasi beroperasi, dana bagaiman system akan bereaksi pada saat sedang digunakan oleh pemakai atau user.</p>
<p><strong>1.2&nbsp;Lingkup</strong></p>
<p>Dokumen ini menyediakan acuan untuk pengendalian tentang aplikasi Mangolineshop. Adapun ruang lingkup pembuatan aplikasi ini adalah berbasis website yang memilih beberapa fasilitas yang ada yaitu:</p>
<ol>
<li>Admin untuk mengelola data CRUD (Create, Read, Update, Delete) yang ada pada fitur- fitur aplikasi Mangolineshop seperti input produk olahan mangga, mendaftarkan akun kasir dan akun penjual, dan memonitoring laporan keuangan.</li>
<li>Kasir sebagai tempat perhitungan pada transaksi pembelian yang dilakukan oleh pelanggan dan dapat memonitoring hasil pendapatan pada hari ini.</li>
<li>Penjual sebagai wadah untuk produk olahan mangga yang di Mangolineshop tersebut agar pelanggan dapat memesan produk yang ada dan data yang dipesan akan di tampung pada chart pesanan yang akan dikonfirmasi jika jadi memesan dan dapat dibatalkan jika tidak jadi dipesan yang dilakukan oleh penjual.</li>
</ol>
<p><strong>BAB II</strong></p>
<p><strong>GAMBARAN UMUM</strong></p>

<p>Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Website (MANGOLINESHP) adalah salah satu jenis aplikasi perangkat lunak yang dapat digunakan untuk membantu proses penjualan olahan secara online. Selama ini pemasaran olahan mangga khas Indramayu dipasarkan secara konvensional yaitu dijual di toko sekitar Indramayu saja. Pemasaran olahan mangga Indramayu pun kurang berkembang karena pembeli harus datang ke toko. Oleh karena itu olahan mangga  khas Indramayu pun yang mengenal hanya orang-orang yang singgah atau berwisata ke Indramayu saja. Sehingga kami berinisiatif untuk membuat sebuah wadah yang didalamnya terdapat lapak-lapak penjual olahan mangga dalam bentuk aplikasi berbasis website. Dibuatnya aplikasi ini kami bisa membantu pemasaran dari penjual olahan mangga Indramayu serta mempromosikan tentang keberagaman olahan mangga yang ada di Indramayu.</p>
<p><strong>2.1	Perspektif produk</strong></p>
<p>Aplikasi Mangolineshop adalah aplikasi yang digunakan untuk memesan produk olahan mangga Indramayu melalui website yang sebelumnya menggunaka metode manual dengan membeli langsung pada toko. Kemudian aplikasi Mangolineshop juga dapat melakukan pencatatan transaksi.</p>
<p><strong>2.1.1	Antarmuka sistem</strong></p>
<p><strong>2.1.1.1	Use Cases Pembeli</strong></p>
 

<p align="center">Gambar 2.1.1.1 (Use Case Pembeli)</p>
<p><strong>2.1.1.2	Use Cases admin</strong></p>
 
<p align="center">Gambar 2.1.1.2 (Use Case Admin)</p>
<p><strong>2.1.1.3	Use Cases Reseller
 
<p align="center">Gambar 2.1.1.3 (Use Case Reseller)</p>



<p><strong>2.1.1.4	Use Cases Penjual</strong></p>
 
<p align="center">Gambar 2.1.1.4 (Use Case Penjual)</p>
<p><strong>2.1.2	Antarmuka pengguna</strong></p>
<p>Aplikasi Mangolineshop menggunakan antarmuka berbasis website. Dimana antarmuka website digunakan untuk admin dan pembeli. </p>
<p><strong>2.1.3	Antarmuka perangkat keras</strong></p>
<p>a.	Laptop</p>
<p>b.	Processor Core i3 or higher</p>
<p>c.	Penyimpanan (Hardisk) Minimal 4 GB free space</p>
<p>d.	Monitor resolusi 1240 x 768 colors 5</p>
<p>e.	Keyboard dan mouse compatible with windows</p>
<p><strong>2.1.4	Antarmuka perangkat lunak</strong></p>
<p>a.	Windows 10 or higher</p>
<p>b.	Laravel</p>
<p>c.	Code Igniter</p>
<p>d.	Corel Draw X7</p>
<p>e.	Database Mysql</p>
<p>f.	Adobe XD</p>
<p>g.	Sublime Text 3</p> 

<p><strong>2.1.5	Antarmuka komunikasi</strong></p>
<p>a.	Paket Data</p>
<p>b.	Wifi</p>
<p>c.	Modem</p>
<p>d.	Laptop</p>
<p><strong>2.1.6	Batasan Memori</strong></p>
<p>a.	RAM yang kami gunakan adalah minimal 4 gb.</p>
<p>b.	Memori yang dibutuhkan aplikasi minimal 50 mb.</p>
<p><strong>2.1.7	Operasi – operasi</strong></p>
<p>a.	Input data pembeli</p>
<p>b.	Input data penjual</p>
<p>c.	Input data produk olahan mangga Indramayu</p>
<p>d.	Input pesanan</p>
<p>e.	Update data pembeli</p>
<p>f.	Update data penjual</p>
<p>g.	Update data produk olahan mangga</p>
<p>h.	Tampilan hasil penjualan harian</p>
<p>i.	Laporan hasil penjualan</p>
<p><strong>2.1.8	Kebutuhan Adaptasi</strong></p>
<p>Kebutuhan adaptasi yang diperlukan pada saat pengembangan aplikasi dengan menggunakan fungsi update data agar memudahkan admin dalam mengkoreksi pengetikan yang salah.</p>

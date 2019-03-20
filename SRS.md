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
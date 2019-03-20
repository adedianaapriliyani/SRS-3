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
<p><strong>DAFTAR ISI</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>HALAMAN JUDUL............................................................................................... i</strong></p>
<p><strong>KATA PENGANTAR.................................................................................... </strong></p>
<p><strong>RINGKASAN......................................................................................................... ii</strong></p>
<p><strong>DAFTAR ISI.......................................................................................................... v</strong></p>
<p><strong>DAFTAR TABEL................................................................................................. vi</strong></p>
<p><strong>DAFTAR GAMBAR............................................................................................ vii</strong></p>
<p><strong>BAB I </strong><strong>PENDAHULUAN</strong></p>
<ul>
<li>Gambaran Proyek..............................................................................</li>
<li>Dokument-dokumen dalam proyek........................................................... 1</li>
</ul>
<p>1.3&nbsp;&nbsp; Evolusi SPMP........................................................................................... 1</p>
<p>1.4&nbsp;&nbsp; Material Acuan.......................................................................................... 2</p>
<p>1.5&nbsp;&nbsp; Definisi dan Akronim............................................................................... 2</p>
<p>&nbsp;</p>
<p><strong>BAB II </strong><strong>ORGANISASI PROYEK</strong></p>
<p>2.1&nbsp;&nbsp; Model Proses............................................................................................. 1</p>
<p>2.2&nbsp;&nbsp; Struktur Organisasi................................................................................... 2</p>
<p>2.3&nbsp;&nbsp; Batasan dan Antarmuka Organisasi.......................................................... 2</p>
<p>2.4&nbsp;&nbsp; Lingkungan Hidup.................................................................................... 1</p>
<p>&nbsp;</p>
<p><strong>BAB II</strong><strong>I</strong> <strong>PROSES MANAJERIAL</strong></p>
<p>3.1&nbsp;&nbsp; Tujuan dan prioritas manajemen............................................................... 1</p>
<p>3.2&nbsp;&nbsp; Asumsi-asumsi, ketergantungan/keterkaitan, dan batasan-batasan.......... 2</p>
<p>3.3&nbsp;&nbsp; Manajemen resiko..................................................................................... 2</p>
<p>3.4&nbsp;&nbsp; Mekanisme monitoring dan kontroling..................................................... 1</p>
<p>3.5&nbsp;&nbsp; Perencanaan staf........................................................................................ 1</p>
<p>&nbsp;</p>
<p><strong>BAB I</strong><strong>V</strong> <strong>PROSES TEKNIS</strong></p>
<p>4.1&nbsp;&nbsp; Metoda, tool, dan teknik........................................................................... 1</p>
<p>4.2&nbsp;&nbsp; Dokumentasi perangkat lunak................................................................... 2</p>
<p>4.3&nbsp;&nbsp; Fungsi-fungsi pendukung proyek............................................................. 2</p>
<p>&nbsp;</p>
<p><strong>BAB </strong><strong>V</strong> <strong>PAKET PEKERJAAN</strong></p>
<p>5.1&nbsp;&nbsp; Mekanisme Monitoring dan Kontroling......................................................... 1</p>
<p>5.2&nbsp;&nbsp; Ketergantungan dan Keterkaitan............................................................... 2</p>
<p>5.3&nbsp;&nbsp; Kebutuhan Sumber Daya.............................................................................. 2</p>
<p>5.4&nbsp;&nbsp; Alokasi budget dan sumber daya................................................................... 1</p>
<p>5.5&nbsp;&nbsp; Ketergantungan dan Keterkaitan............................................................... 2</p>
<p>5.3&nbsp;&nbsp; Jadwal........................................................................................................ 2</p>
<p><strong>BAB </strong><strong>VI</strong> <strong>PENUTUP</strong></p>
<p>6.1&nbsp;&nbsp; Kesimpulan................................................................................................. 1</p>
<p>6.2&nbsp;&nbsp; Saran......................................................................................................... 2</p>
<p><strong>BAB VII REFERNSI</strong></p>
<p><strong>BAB VIII LAMPIRAN</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p>&nbsp;</p>
<p><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>DAFTAR TABEL</strong></p>
<p><strong><br /> </strong></p>
<p><strong>DAFTAR GAMBAR</strong></p>
<p><strong><br /> </strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong><br /> </strong></p>
<p><strong>&nbsp;</strong></p>

<p><strong>BAB I</strong></p>
<p><strong>PENDAHULUAN</strong></p>
<p><strong>1.1 Tujuan</strong></p>
<p>Tujuan pembuatan SDD (Software Design Description) ini adalah untuk menjelaskan langkah langkah desain dan proses-proses dalam pembuatan sistem aplikasi yang akan diterapkan pada Aplikasi Mangolineshop (Aplikasi Penjualan Olahan Mangga Indramayu Berbasis Mobile), dan juga memberi definisi kebutuhan untuk sistem, spesifikasi kebutuhan fungsional.</p>
<p>Fungsi utama dari aplikasi Mangolineshop ini adalah mempermudah penjual olahan mangga dalam memberikan pelayanan terhadap pembeli, memudahkan penjual dalam rekap laporan keuangan, dan sebagai sarana untuk mempromosikan produk olahan mangga khas Kota Indramayu.</p>
<p>Secara ringkas, fungsi Aplikasi Mangolineshop dapat dituliskan sebagai berikut :</p>
<ol>
<li>Admin dapat menginputkan fitur kategori produk, akun penjual, dan akun pembeli yang nantinya akan digunakan oleh user dalam aplikasi tersebut.</li>
<li>Admin merekap laporan transaksi.</li>
<li>Aplikasi penjual harus mendaftar terlebih dahulu di admin Mangolineshop.</li>
<li>Aplikasi penjual dan admin login, kemudian memberikan detail produk olahan mangga pada pembeli.</li>
<li>Pembeli harus melakukan konfirmasi pembelian terlebih dahulu setelah memilih produk olahan mangga yang ingin dibeli pada aplikasi Manolineshop.</li>
<li>Pembeli melakukan pembayaran setelah konfirmasi pemesanan menu &ndash; menu yang dibeli di aplikasi kasir sebagai bukti pembayaran.</li>
<li>Aplikasi penjual dan admin login, kemudian melakukan proses perhitungan pembayaran untuk pembeli.</li>
<li>Setelah melakukan transaksi penjual dan admin dapat melihat laporan pendapatan terhadap pemesanan yang dilakukan oleh pembeli.</li>
</ol>
<p><strong>1.2&nbsp;Ruang Lingkup</strong></p>
<p>Hasil dari SDD ini adalah aplikasi yang berbasis mobile, yang digunakan untuk membantu pemasaran dan pengelolaan yang ada di UKM Kenanga Mandiri dalam hal :</p>
<ol>
<li>Mencatat produk olahan mangga Indramayu yang akan ditampilkan di aplikasi Mangolineshop.</li>
<li>Mencatat pemesanan produk olahan mangga terhadap pembeli di aplikasi Mangolineshop.</li>
<li>Menghitung transaksi terhadap pemesanan yang dilakukan oleh pembeli yang akan dilakukan pada aplikasi Admin dari aplikasi Mangolineshop.</li>
<li>Mencatat laporan transaksi yang akan ditampilkan di aplikasi penjual dan admin dari aplikasi Mangolineshop.</li>
</ol>
<p><strong>1.3&nbsp;Gambaran umum dokumen</strong></p>
<p>Penulisan dokumen ini dibagi menjadi beberapa bab sebagai berikut:</p>
<ol>
<li>Bab 1, adalah Pendahuluan yang menjelaskan mengenai tujuan perangkat lunak, ruang lingkup, serta gambaran umum dokumen.</li>
<li>Bab 2, adalah Deskripsi Umum, yang berisi tentang gambaran umum mengenai perspektif produk, manfaat produk, karakteristik user dan stakeholder, batasan, serta asumsi dan ketergantungan yang digunakan.</li>
<li>Bab 3, adalah Software Design, yang menyediakan spesifikasi, kebutuhan, antarmuka, kebutuhan fungsional dan nonfunctional, lingkungan operasi, dan batasan perancangan, permodelan proses, permodelan data, struktur data, spesifikasi program dan desain interface.</li>
</ol>
<p>&nbsp;</p>
<p><strong>BAB II</strong></p>
<p><strong>DESKRIPSI UMUM</strong></p>
<p><strong>&nbsp;</strong></p>
<p><strong>2.1 Perspektif Produk</strong></p>
<p>Produk dari SDD ini adalah sebuah aplikasi yang berbasis mobile, yang akan dijalankan dan berfungsi sebagai untuk mempermudah layanan penjualan olahan mangga, seperti yang telah dijelaskan pada Pendahuluan. Produk ini akan dapat diakses melalui smartphone.</p>
<p><strong>2.2 Manfaat Produk</strong></p>
<p>Manfaat yang didapat managemen dalam menggunakan sistem atau aplikasi Mangolineshop ini adalah:</p>
<ol>
<li>Memudahkan proses pemesanan produk olahan mangga Indramayu bagi pembeli.</li>
<li>Memudahkan admin dan penjual dalam melakukan perhitungan</li>
<li>Memudahkan penjual memantau penjualan pada aplikasi Mangolineshop.</li>
<li>Menyediakan informasi mengenai produk olahan mangga Indramayu kepada pembeli.</li>
</ol>
<p><strong>2.3 Karakteristik User dan Stakeholder User</strong></p>
<ol>
<li>Yang terlibat adalah sebagai berikut :</li>
<li>Admin</li>
<li>Penjual</li>
<li>Reseller</li>
<li>Pembeli</li>
<li>Stakeholder yang terkait dengan system ini:</li>
<li>Mitra Kenanga Mandiri.</li>
<li>Kelompok Aplikasi Mangolineshop.</li>
</ol>
<p><strong>2.4 Batasan &ndash; Batasan</strong></p>
<ol>
<li>Aplikasi ini mencakup sistem pada admin dan penjual saja</li>
<li>Transaksi pembayaran langsung dilakukan pembeli dan kasir, sistem hanya membantu menampilkan transaksi yang dilakukan</li>
</ol>
<p><strong>2.5&nbsp;Asumsi</strong></p>
<ol>
<li>Setiap pembeli dapat langsung memesan produk melalui smartphone yang ada pada aplikasi Mangolineshop.</li>
<li>Setiap penjual mempunyai username dan password yang diberikan oleh admin.</li>
</ol>
<p>Tersedia sarana koneksi ke internet, sarana jaringan komputer, dan sarana penunjang lainnya.</p>
<ol start="3">
<li><strong>SOFTWARE DESIGN</strong></li>
</ol>
<p><strong>&nbsp;</strong></p>
<ul>
<li><strong>Kebutuhan Fungsional</strong></li>
</ul>
<p>Kebutuhan fungsional (Functional Requirements) ini adalah kebutuhan utama yang diharapkan dari system ini, yang terkait langsung dengan system ini. Kebutuhan fungsional dari system ini adalah sebagai berikut :</p>
<ul>
<li>Pencatatan laporan penjualan</li>
<li>Manajemen produk olahan mangga</li>
<li>Transaksi</li>
<li></li>
<li></li>
<li></li>
</ul>
<p>&nbsp;</p>
<ul>
<li>Spesifikasi yang diharapkan dari laporan penjualan</li>
</ul>
<ul>
<li>System dapat menampilkan penjualan hari ini</li>
<li>System dapat menampilkan laporan penjualan dalam periode waktu tertentu</li>
</ul>
<p>&nbsp;</p>
<ul>
<li>Spesifikasi yang diharapkan pada Manajemen produk olahan mangga</li>
</ul>
<ul>
<li>Sistem harus dapat menghapus, dan menambah Manajemen produk olahan mangga</li>
<li>Sistem dapat menampilkan produk olahan mangga &nbsp;yang masih tersedia</li>
</ul>
<p>&nbsp;</p>
<ul>
<li>Transaksi</li>
</ul>
<ul>
<li>Sistem harus dapat menghitung harga yang harus dibayar konsumen</li>
<li>System dapat menampilkan uang kembalian pelanggan secara otomatis</li>
<li>System harus dapat menghitung data pesanan</li>
</ul>
<p>&nbsp;</p>
<ul>
<li><strong>Kebutuhan Non Fungsional</strong></li>
</ul>
<p>Kebutuhan yang mendukung kelancaran system ini didefnisikan sebagai berikut:</p>
<ul>
<li>Availability: online selama caf&eacute; buka, dengan asumsi koneksi internet dan jaringan berjalan normal</li>
<li>Reliability: system data reliabel berhubungan dengan stok produk olahan mangga dan juga reliabel berhubungan dengan laporan penjualan</li>
<li>Ergonomy: user friendly dengan memperhatikan hal yang berhubungan dengan Human Computer Interaction</li>
<li>Portability: dapat diakses dari mobile untuk beli serta diakses dari web mengenai transaksi dan laporan</li>
<li>Memory : minimum memory untuk server aplikasi 4 Gb</li>
<li>Response time: tidak terukur</li>
<li>Security: login dan validasi password</li>
</ul>
<p>&nbsp;</p>
<ul>
<li><strong>Kebutuhan Antarmuka (interface)</strong></li>
</ul>
<p>Antarmuka dalam penerapan aplikasi Mangoline dibagi menjadi dua, yaitu:</p>
<ol>
<li>Hardware Interface : adalah kebutuhan perangkat keras yang harus dipenuhi untuk implementasi system aplikasi Mangoline:</li>
</ol>
<ul>
<li>Mobile</li>
<li>Website</li>
</ul>
<ol start="2">
<li>Software Interface : kebutuhan software untuk implementasi system aplikasi Mangoline:</li>
</ol>
<ul>
<li>Apache</li>
<li>PHP</li>
<li>MYSQL</li>
</ul>
<p>&nbsp;</p>
<ul>
<li><strong>Lingkungan Operasi</strong></li>
</ul>
<p>Aplikasi aka berfungsi dengan lingkungan operasi sebagai berikut:</p>
<ul>
<li>Sistem Operasi : Windows dan android</li>
<li>DBMS : Berbasis SQL</li>
<li>Pemrograman : PHP, HTML, dan Java</li>
</ul>
<p>&nbsp;</p>
<ul>
<li><strong>Batasan Perancangan</strong></li>
</ul>
<p>Perancangan system aplikasi Mangolineini adalah berbasis web untuk admin dan kasirnya sedangan untuk pelayan berbasis mobile. Dan Bahasa pemrograman yang digunakan adalah PHP,HTML dan Java.</p>
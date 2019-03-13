*__Software Projects Management Plan (SPMP)__*
**1.** **Pendahuluan**<br>
    **1.1** **Gambaran Proyek** <br>
        <ol>Proyek yang sedang kami buat adalah Sistem Informasi Absensi dan Penggajian di Perusahaan Konveksi "Kafka". Kafka merupakan sebuah perusahaan konvenksi dengan karyawan yang cukup banyak. Oleh karena itu Sistem absen dan penggajian merupakan hal yang sangat pokok pada kegiatan financial sebuah perusahaan karena hal tersebut sangat berpengaruh kepada kinerja para pegawai yang setiap hari melakukan aktifitas. Sistem penggajian menyajikan cara-cara penggajian pegawai secara akurat, menghasilkan laporan-laporan yang diperlukan dan menyajikan kebutuhan informasi kepada manajemen. </ol><br>
        <ol>Adapun kendala yang dihadapi di Kafka konveksi yaitu absensi dan penggajian yang masih dilakukan secara manual masih berbentuk arsip sehingga memperlambat dalam proses pencarian, penghitungan dan proses pembuatan laporan penggajian. oleh karena itu akan dirancang sebuah sistem informasi absensi dan  penggajian, antara lain meliputi sistem absensi karyawan, sistem penghitungan gaji dan berbagai attributnya seperti lembur, cuti, potongan dan sebagainya secara terotomatisasi. Selain itu sistem juga mampu membuat berbagai laporan baik yang ditujukan untuk karyawan seperti slip gaji dan laporan yang ditujukan untuk direktur seperti laporan data karyawan, laporan absensi karyawan, dan laporan gaji karyawan secara terotomatisasi dimana system informasi tersebut dibuat dengan Framework Laravel dan Android.</ol><br>
        <ol>Tentunya dalam pembuatan Sistem Informasi Absensi dan Penggajian di Perusahaan Konveksi "Kafka" yang akan Kami buat butuh sebuah tim yang solid, tim yang terdiri dari Project Manager, Programmer, Data Analisis,Database Administrator. kami bermaksud membagi beberapa tugas sesuai kriteria kemampuan masing-masing, yang nantinya satu sama lain diharapkan dapat bekerja sama dan melengkapi satu sama lain, sehingga dapat membangun sistem yang baik sesuai yang produsen butuhkan. </ol>
    **1.2** **Dokumen-dokumen dalam Proyek** <br>
        <ol>Saat mengerjakan projek ini, pencatatan kegiatan yang telah dilakukan ditulis didalam log book kelompok, anggota yang telah mengerjakan tugas sesuai projek kegiatannya dicatat dalam log book, selain log book dokumen yang berkaitan dengan projek ini meliputi requirtments, penjadwalan, pembagian tugas, dan referensi-referensi yang berkaitan dengan pembuatan projek kami. Selain Log book ada juga Proposal serta laporan, Proposal mengenai daftar yang di butuhkan dalam penggarapan project serta laporan hasil project yang telah dibuat </ol><br>
    **1.3** **Evolusi SPMP**<br>
        <ol>Dokumen ini bersifat freeware, jadi siapa saja boleh untuk memanfaatkan dokumen ini untuk hal yang positif. Tentu ada hal-hal yang tidak boleh dilakukan dalam pemanfaatan dokumen ini, seperti menjualbelikan dokumen ini secara ilegal, ataupun mengubah dokumen tanpa dasar yang jelas.</ol><br>
    **1.4** **Material Acuan** <br>
        <ol>Materi yang menjadi acuan dalam pembuatan projek ini menggunakan standar IEEE, karena menyediakan kerangka kerja yang menggabungkan seluruh spektrum proses siklus hidup perangkat lunak. Dan juga standar IEEE untuk membentukmodel yang diakui secara internasional dari kehidupan perangkat lunak umum, siklus proses yang dapat direferensikan oleh industri perangkat lunak diseluruh dunia, untuk mempromosikan pemahaman diantara pihak bisnis dengan aplikasi umum serta mengakui proses, kegiatan dan tugas.</ol><br>
        <ol>IEEE adalah sebuah organisasi profesi nirlaba yang terdiri dari banyak ahli dibidang teknik yang mempromosikan pengembangan standar-standar dan bertindak sebagai pihak yang mempercepat teknologi- teknologi baru dalam semua aspek dalam industry dan rekayasa (engineering), yang mencakup telekomunikasi, jaringan komputer, kelistrikan, antariksa, dan elektronika. Tujuan inti IEEE adalah mendorong inovasi teknologi dan kesempurnaan untuk kepentingan kemanusiaan.Visi IEEE adalah akan menjadi penting untuk masyarakat teknis global dan professional teknis dimana-mana dan dikenal secara universal untuk kontribusi teknologi dan teknis yang professional dalam meningkatkan kondisi perkembangan global. Standar dalam IEEE adalah mengatur fungsi, kemampuan dan interoperabilitas dari berbagai macam produk dan layanan yang mengubah cara orang hidup, bekerja dan berkomunikasi.</ol><br>
    **1.5** **Definisi Akronim (Singkatan)** <br>
        <ol>Dalam penulisan dokumen pembuatan projek ini, ada beberapa kata yang mungkin akan sulit dipahami oleh orang awam berikut ini : <br>
        IEEE = The International Institute of Electronic and Electrical Engineers


**2.** **Organisasi Proyek**<br>
   **2.1** **Model proses**<br>
        <ol>Kami menggunakan model Incremental, dalam model Incremental ini proses pengerjaan perangkat lunak akan dilakukan perbagian sehingga bagian selanjutnya akan dikerjakan setelah bagian awal telah selesai dan selanjutnya sampai menghasilkan perangkat lunak yang lengkap dengan semua fungsi yang diperlukan dan pengerjaan perangkat lunak berakhir. Sebelum pengerjaan perangkat lunak akan dilakukan perancangan arsitektur software sebagai kerangka dalam pengerjaan perbagian. </ol><br>
        **2.1.1** **Kelebihan Model Incremental**<br>
        <ol><li>Resiko yang rendah pada pengembangan sistem.
        <li>Mengutamakan fungsi-fungsi pada sistem perangkat lunak sehingga kemudahan pemakaian sistem yang paling di utamakan.
        <li>Tahap awal adalan dasar dari pembuatan tahap berikutnya (dikerjakan secara terurut).
        <li>Cocok digunakan bila pembuat software tidak banyak/kekurangan pembuat.
        <li>Mampu mengakomodasi perubahan kebutuhan customer.
        <li>Mengurangi trauma karena perubahan sistem. Klien dibiasakan perlahan-lahan menggunakan produknya bagian per bagian.
        <li>Memaksimalkan pengembalian modal investasi konsumen.</ol><br>
        **2.1.2** **Kekurangan Model Incremental<br>**
        <ol><li>Hanya akan berhasil jika tidak ada staffing untuk penerapan secara menyeluruh.
        <li>Penambahan staf dilakukan jika hasil incremental akan dikembangkan lebih lanjut.
        <li>Hanya cocok untuk proyek dengan skala kecil.
        <li>kemungkinan tiap bagian tidak dapat diintegrasikan.</ol><br>
    **2.2** **Struktur Organisasi**<br>
        <ol>Project Manager         : Priliyandi<br>
        Programmer              : Riyanwar Setiadi<br>
        Database Administrator  : Setyo Sbiansah<br>
        Analisys Desain         : Uum Khumaeroh</ol><br>
    **2.3** **Batasan dan antarmuka organisasi**<br>
        <ol><li>Project manager dimana harus mejadi pengawas dari anggota – anggotanya bilamana saat anggota lalai dengan tugas – tugasnya, Ketua berhak menegur dan bagi anggota tidak berhak melawan jika ditegur, dan untuk Ketua sendiri tidak berhak semena-mena \dengan jabatanya.<br>
        <li>Programmer dimana dia bertanggung jawab untuk membuat dan menyempurnakan suatu program.<br>
        <li>Database administrator dimana dia bertanggung jawab merancang dan mengelola database<br>
        <li>Analis dimana dia bertugas memberikan gambaran project dan alur pengkoding pada programmer.</ol><br> 
    **2.4** **Lingkup tanggung jawab**<br>
        <ol><li>Manager adalah seseorang mempunyai tanggung jawab dan tugas yang besar dalam sebuah tim, tidak hanya terfokus pada hal-hal yang teknis sifatnya. Manager juga harus mampu memajemen tim dengan baik, agar target projek dapat tercapai. Selain itu memberi pengarahan, memonitoring kinerja tim, serta serta membagi tugas juga bagian tanggung jawab dari seorang manager.<br>
        <li>Programmer Dalam hal ini, seorang programer bertugas untuk mengimplementasikan dari sistem yang sudah dirancang didesain. Programmer dituntut dapat menuliskan code program dengan baik, dan efesien. Hal ini dimaksudakan untuk menghindari terjadinya banyak error dalam proses implementasinya.<br>
        <li>Database Administrator adalah seseorang yang bertanggung jawab terhadap pengaturan, pembuatan, dan rekam jejak segala jenis dokumen yang terlibat dalam proyek. Mulai dari proposal dan kontrak proyek, sampai dengan hasil sampling atau percobaan dalam proses pembangunan proyek. Disamping dokumen, hal-hal yang berkaitan dengan komunikasi antara anggota proyek dengan perusahaan dan vendors juga harus dikelola oleh Administrator. Agar segalanya berjalan dengan lancar, biasanya Administrator sudah memiliki standar dokumen dan prosedur yang harus diikuti oleh seluruh tim proyek, agar proses administrasi berjalan dengan efektif dan secara efisien. <br>
        <li>Analisys sistem, Banyak hal yang harus dilakukan oleh seorang sistem analis, terutama yang berkaitan dengan pemecahan masalah. Seorang sistem analis harus mampu menganalisa segala kemungkinan dari pemasalahan yang ada, dan dapat mengasilkan solusi yang tepat dari permasalahan tersebut. Menentukan sistem yang tepat merupakan bagian dari tugas seorang sistem analis, sehingga kinerja tim dapat berjalasan secara efesien.</ol> <br>

**3.** **Proses Manajerial**<br>
    **3.1** **Tujuan dan prioritas manajemen**<br>
        <li>Prioritas Jadwal <br>
            Prioritas jadwal yang dilakukan pada saat ini adalah membuat sistem yang akan dibuat, dokumen  projek, jadwal  kegiatan, struktur pembuatan projek dan organisasi<br>
        <li>Budget <br>
            Prioritas budget untuk project ini lebih ditekankan pada kualitas hardware dan requirtment proyek.  <br>
        <li>Kemampuan (Kualitas dan reusability)  <br>
            Projek yang kami buat saat ini mempunyai kelebihan dalam memanajemen pembuatan proyek, juga berbasis desktop yang membuat konsumen merasa lebih budah dalam interaksinya.<br>
    **3.2** **Asumsi-asumsi, ketergantungan/keterkaitan, dan batasan-batasan**<br>
        a. Asumsi <br>
            Adapun aplikasi yang sejenis aplikasi manajemen berbasis web dan mobile. <br>
        b. Keterkaitan dan Batasan  <br>
            Dalam projek yang kami buat adapun beberapa software desktop yang mendukungnya, seperti xampp sebagai perantara mysql database. Namun ada batasannya, yaitu tidak bisa digunakan secara online. <br>
    **3.3** **Manajemen resiko**<br>
|Resiko                                |Solusi                         |
|-------------------------------|-----------------------------|
|
 Kerusakan Teknologi dan bahan produk |Mengganti dengan teknologi yang baru dengan sistem yang sama|
|Estimasi biaya dan waktu yang tidak realistis|Membuat berapa biaya estimasi, desain untuk kerja, merekan dan menganalisa project yang akan dibuat|
|Pengembangannya terlalu sulit secara teknis|Analisis teknis, analisa biaya manfaat, analisa software, simulasi software|
    **3.4** **Mekanisme monitoring dan kontroling**<br>
        a. Pertemuan proyek II seminggu 3 kali<br>
        b. Repository bersama di Github<br>
    **3.5** **Perencanaan staf**<br>
        1.  Priliyandi (Project Manager)<br>
        2.  Riyanwar Setiadi (Programmer)<br>
        3. Setyo Abiansah (Database Administrator)<br>
        4.  Uum Khumaeroh (Analisis Desain))<br>
 **4.**  **Proses teknis**<br>
    **4.1** **Metoda, tool, dan teknik**<br>
        Proyek II ini akan menggunakan tools, metoda, dan teknologi yaitu :
            1. Android Studio
            2. Laravel
            3. laragon
            4. SubimeText3
            5. Bootstrap
    **4.2** **Dokumentasi perangkat lunak**<br>
        Dokumentasi peragkat lunak yang digunakan berdasarkan standar internasional IEEE, karena telah menyediakan kerangka kerja yang menghubungkan seluruh spektrum siklus hidup perangkat lunak.<br>
    **4.3** **Fungsi-fungsi pendukung proyek**<br>
        Semua pendukung proyek akan selesai secara bertahap<br>
**5.** **Paket pekerjaan, jadwal, dan budget**<br>
    **5.1** **Paket pekerjaan**<br>
         1. Riyanwar Setiadi sebagai progammer, memprogram aplikasi yang akan di buat  menjadi yang lebih baik lagi karena dia bisa membuat suatu aplikasi hanya dengan menjentikan jarinya saja. wow sekali ini<br>
         2. Priliyandi sebagai project manager, dia yang selalu memarahi anggotanya karena anggota nya selalu melebihi ekspetasinya, waw sekali kawan-kawan.<br>
         3. Setyo Abiansah sebagai database administrastor, serius tapi santai dalam mengerjakan tugas nya.<br>
         4. Uum Kumairoh sebagai analis, dia itu selalu ngomel-ngomel ngga jelas, marah-marah ngga jelas mungkin karena dia itu perempuan PMS<br>
    **5.2** **Ketergantungan/keterkaitan**<br>
        <ol>Dalam proses pengerjaan proyek yang kami buat ini, keterkaitan dari tugas masing-masing saling membantu agar terbentuknya ketelitian saat mengerjakan dan mendapatkan hasil yang bagus.
        1. Programmer berkaitan dengan Database administrator karena programmer mengambil datanya itu dari database yang sudah di buat oleh database administrator.<br>
        2. Programmer dengan analis, setelah program telah selesai dibuat oleh programmer selanjutnya akan di analisis oleh seorang analis yang nanti nya akan di koreksi, dan kalau ada kesalahan atau ada fitur yang belum memenuhi akan di tegur.<br>
        3. Project Manager dengan anggotanya, anggota akan bekergantungan dengan project manager nya karena project manager lah yang akan mengarahkan apa-apa yang harus di lakukan oleh anggotanya.</ol><br>
    **5.3** **Kebutuhan-kebutuhan sumber daya**<br>
        1. Personal : <br>
                - Priliyandi  Project Manager<br>
                - Riyanwar Setiadi aka Progammer <br>
                - Setyo Abiansah aka Database administrator <br>
                - Uum Kumaeroh aka Analis <br>
        2. Biaya : <br>
                - Transportasi   = Rp 1.000.000 <br>
                - Makan & Minum  = Rp 5.000.000 <br>
                - Tempat tinggal = Rp 10.000.000 <br>
        3. Perangkat Keras : 
                - Laptop<br>
                - Mouse<br>     
                - Keyboard<br>
                - Monitor<br>
                - Printer<br>
                - Kabel data USB<br>
        4. Perangkat Lunak : <br>
                - Windows 10
                - Android Studio<br>
                - PHP Myadmin<br>
                - Framework Laravel<br>
    **5.4** Alokasi budget dan sumber daya<br>
         Biaya Hardware :<br>
            1. 1 Komputer = Rp 7.000.000<br>
            2. 1 Mouse    = Rp 30.000<br>
            3. 1 Keyboard = Rp 50.000<br>
            4. Laptop     = Rp 4.500.000<br>
            5. Kabel USB  = Rp 25.000<br>
            6. Monitor    = Rp 1.400.000<br>
            7. Printer    = Rp 1.500.000<br>
        Biaya SOftware : <br>
            1. Windows 10       = Rp 1.500.000<br>
            2. Xampp            = Rp 450.000<br>
            3. Android Studio   = Rp -<br>
            4. Framework        = Rp -<br>
    **5.5** **Jadwal**<br>
<<<<<<< HEAD
    1. Persiapan 6-12 Februari<br>
    2. Requiment 14-29 Februari<br>
    3. Analis 1-14 Maret<br>
    4. Implementasi 15-30 Maret<br>
    5. Testing dan Pemeliharaan 1-10 April<br>
    6. Evaluasi 11-20 April<br>
>>>>>>> 327620f0d805144dd778d19a69c38291d5e887fc


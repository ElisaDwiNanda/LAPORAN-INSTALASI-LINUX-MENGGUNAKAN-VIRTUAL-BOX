# Laporan Instalasi Linux Ubuntu 24.04 menggunakan VirtualBox
## PENDAHULUAN

### Tujuan Praktikum
- Mahasiswa diharapkan mampu menggunakan sebuah sistem operasi berbasis Open Source (Linux).
- Mahasiswa mampu menginstall salah satu distro sistem operasi Linux, dalam hal ini dipilih Ubuntu.
- Mahasiswa familiar dengan Desktop Environment sistem operasi berbasis Linux.
- Mengerti kekurangan dan kelebihan Linux distro Ubuntu.
- Mengenal sejarah Linux dan Distronya.

### Alat yang Digunakan
1.	Laptop/PC
2.	Virtual Box
3.	Ubuntu 24.04 LTS

### Dasar Teori 
Pengerian linux adalah software sistem operasi open source yang gratis untuk disebarluaskan di bawah lisensi GNU. jadi anda diijinkan untuk menginstal pada komputer anda ataupun mengkopi dan menyebarluaskannya tanpa harus membayar. linux merupakan turunan dari unix dan dapat bekerja pada berbagai macam perangkat keras koputer mulai dari inter x86 sampai dengan RISC. Dengan lisensi GNU (Gnu Not Unix) Anda dapat memperoleh program, lengkap dengan kode sumbernya (source code). Tidak hanya itu, Anda diberikan hak untuk mengkopi sebanyak Anda mau, atau bahkan mengubah kode sumbernya.Dan itu semua legal dibawah lisensi. Meskipun gratis, lisensi GNU memperbolehkan pihak yang ingin menarik biaya untuk penggandaan maupun pengiriman program.

Kebebasan yang paling penting dari Linux, terutama bagi programmer dan administrator jaringan, adalah kebebasan untuk memperoleh kode sumber (source code) dan kebebasan untuk mengubahnya. Ini berimplikasi pada beberapa hal penting. Pertama keamanan, yang kedua dinamika.

### Sejarah Linux
Pada tahun 1969, Ken Thompson dan Dennis Ritchie (juga adalah developer bahasa C), para peneliti di AT&T Bell Laboratorium Amerika, membuat sistem operasi UNIX, cikal bakal dari Linux. UNIX mendapatkan perhatian besar karena merupakan sistem operasi pertama yang dibuat bukan oleh hardware maker. Selain itu juga karena seluruh source code-nya dibuat dengan bahasa C, sehingga mempermudah pemindahannya ke berbagai platform.

Dalam waktu singkat UNIX berkembang secara pesat dan terpecah dalam dua aliran: UNIX yang dikembangkan oleh Universitas Berkeley dan yang dikembangkan oleh AT&T. Setelah itu mulai banyak perusahaan yang melibatkan diri, dan terjadilah persaingan yang melibatkan banyak perusahaan untuk memegang kontrol dalam bidang sistem operasi. Persaingan ini menyebabkan perlu adanya standarisasi. Dari sini lahirlah proyek POSIX yang dimotori oleh IEEE (The Institute of Electrical and Electronics Engineers) yang bertujuan untuk menetapkan spesifikasi standar UNIX. Akan tetapi, standarisasi ini tidak meredakan persaingan. Sejak saat itu, muncul berbagai macam jenis UNIX.

Salah satu diantaranya adalah MINIX yang dibuat oleh A. S. Tanenbaum untuk tujuan pendidikan. Source code MINIX inilah yang oleh Linus Torvalds, seorang mahasiswa Universitas Helsinki pada waktu itu, kemudian dijadikan sebagai referensi untuk membuat sistem operasi baru yang gratis dan yang source codenya bisa diakses oleh umum. Sistem operasi ini kemudian diberi nama Linux. Dalam membangun Linux, Linus menggunakan tool-tool dari Free Foundation Software yang berlisensi GNU. Kemudian untuk menjadikan Linux sebuah sistem operasi yang utuh, dia memasukkan program-program yang juga berlisensi GNU.
 
Secara teknis dan singkat dapat dikatakan, Linux adalah suatu sistem operasi yang bersifat multi user dan multitasking, yang dapat berjalan di berbagai platform, termasuk prosesor INTEL 386 dan yang lebih tinggi. Sistem operasi ini mengimplementasikan standard POSIX. Linux dapat berinteroperasi secara baik dengan sistem operasi yang lain, termasuk Apple, Microsoft dan Novell.

Berawal dari sistem operasi Unix dikembangkan dan diimplementasikan pada tahun 1960-an dan pertama kali dirilis pada 1970. Faktor ketersediaannya dan kompatibilitasnya yang tinggi menyebabkannya dapat digunakan, disalin dan dimodifikasi secara luas oleh institusi-institusi akademis dan pada pebisnis.

Nama Linux sendiri diturunkan dari pencipta awalnya, LINUS TORVALDS, di Universitas Helsinki, Finlandia yang sebetulnya mengacu pada kernel dari suatu sistem operasi. Linux dulunya adalah proyek hobi yang dikerjakan oleh Linus Torvalds yang memperoleh inspirasi dariMinix. Minix adalah sistem UNIX kecil yang dikembangkan oleh Andy Tanenbaum pada tahun 1987. Minix pada saat itu merupakan suatu proyek pelajaran di kelasnya waktu itu yang menyerupai sistem UNIX.

Sejarah Linux berkaitan dengan GNU. Proyek GNU yang mulai pada 1984 memiliki tujuan untuk membuat sebuah sistem operasi yang kompatibel dengan Unix dan lengkap dan secara total terdiri atas perangkat lunak bebas. Tahun 1985, Richard Stallman mendirikan Yayasan Perangkat Lunak Bebas dan mengembangkan Lisensi Publik Umum GNU (GNU General Public License atau GNU GPL). Kebanyakan program yang dibutuhkan oleh sebuah sistem operasi (seperti pustaka, kompiler, penyunting teks, shell Unix dan sistem jendela) diselesaikan pada awal tahun 1990-an, walaupun elemen- elemen tingkat rendah seperti device driver, jurik dan kernel masih belum selesai pada saat itu.

Linux versi 0.01 dikerjakan sekitar bulan Agustus 1991. Kemudian pada bulan Oktober 1991 tanggal 5, Linus mengumumkan versi resmi Linux, yaitu 0.02 yang hanya dapat menjalankan bash (GNU Bourne Again Shell) dan gcc (GNU C Compiler).
 
Sekarang Linux adalah sistem UNIX yang lengkap, bisa digunakan untuk jaringan (networking), pengembangan software, dan bahkan untuk sehari-hari. Linux telah digunakan di berbagai domain, dari sistem benam sampai superkomputer, dan telah mempunyai posisi yang aman dalam instalasi server web dengan aplikasi LAMP-nya yang populer. Linux sekarang merupakan alternatif OS yang jauh lebih murah jika dibandingkan dengan OS komersial, dengan kemampuan Linux yang setara bahkan lebih Lingkungan sistem operasi ini termasuk :
- Ratusan program termasuk, kompiler, interpreter, editor dan utilitas
- Perangkat bantu yang mendukung konektifitas, Ethernet, SLIP dan PPP, dan interoperabilitas.
- Produk perangkat lunak yang reliabel, termasuk versi pengembangan terakhir.
- Kelompok pengembang yang tersebar di seluruh dunia yang telah bekerja dan menjadikan
Linux portabel ke suatu platform baru, begitu juga mendukung komunitas pengguna yang beragam kebutuhan dan lokasinya dan juga bertindak sebagai team pengembang sendiri.

Pengembangan kernel Linux masih dilanjutkan oleh Torvalds, sementara Stallman mengepalai Yayasan Perangkat Lunak Bebas yang mendukung pengembangan komponen GNU. Selain itu, banyak individu dan perusahaan yang mengembangkan komponen non-GNU. Komunitas Linux menggabungkan dan mendistribusikan kernel, komponen GNU dan non-GNU dengan perangkat lunak manajemen paket dalam bentuk distribusi Linux.

Tak seperti produk komersial yang lain, Linux tidak memiliki suatu logo yang terlihat hebat, hanyalah sebuah burung Penguin yang memperlihatkan sikap santai ketika berjalan. Logo ini mempunyai asal mula yang unik, awalnya tidak ada suatu logo yang menggambarkan trademark dari Linux sampai ketika Linus ( Sang Penemu ) berlibur ke daerah selatan dan bertemu dengan seekor linux kecil dan pendek yang secara tidak
 
sengaja menggigit jarinya. Hal ini membuatnya demam selama berhari-hari. Kejadian ini kemudian menginspirasi dirinya untuk memakai penguin sebagai logonya dengan harapan user menjadi demam menggunakan sistem operasi yang beliau ciptakan ini.

TUX, nama seekor pinguin yang menjadi logo maskot dari linux. TUX hasil karya seniman Larry Ewing pada waktu developer merasakan Linux harus mempunyai logo trademark ( 1996 ), dan atas usulan James Hughes dipilihlah nama TUX yang berarti Torvalds UniX. Lengkap sudah logo dari Linux, berupa penguin dengan nama TUX. Trademark ini segera didaftarkan untuk menghindari adanya pemalsuan. Linux terdaftar sebagai Program sistem operasi ( OS ).

Hingga sekarang logo Linux yaitu Tux sudah terkenal ke berbagai penjuru dunia. Orang lebih mudah mengenal segala produk yang berbau Linux hanya dengan melihat logo yang unik nan lucu hasil kerjasama seluruh komunitas Linux di seluruh dunia.

Jenis Distro Linux, Distro Linux adalah sebutan untuk sistem operasi dan aplikasinya, merupakan keluarga Unix yang menggunakan kernel Linux. Distribusi Linux bisa berupa perangkat lunak bebas dan bisa juga berupa perangkat lunak komersial seperti Red Hat Enterprise, SuSE, dan lain-lain.
Ada banyak distribusi atau distro Linux yang telah muncul. Beberapa bertahan dan perkembang besar, bahkan sampai menghasilkan distro turunan, contohnya adalah Distro Debian GNU/Linux. Distro ini telah menghasilkan puluhan distro anak, antara lain Ubuntu, Knoppix, Xandros, DSL, dan sebagainya.
Berikut ini kelompok Linux yang beredar berdasarkan karakternya:

1.	Slackware
Distro paling tua, dibuat oleh Patrick Volkerding. Ini mungkin distro linux yang paling mirip UNIX. Paket manager masih menggunakan dpkg dengan akhiran tgz. Rilis pada Juli 1993, versi terakhirnya 10.2 performa nya bagus untuk low end komputer, kurang cocok untuk pemula, cocok bagi yang sudah sangat terbiasa dengan unix. Turunannya ada vector, slax
 
2.	Debian
Distro paling lengkap, dibuat oleh Ian dan Debbie. Didukung oleh paling banyak hacker di dunia, paling banyak paket programnya. Paket managernya pake apt-get, paket file nya *.deb. Paling cepat update nya, tapi rilis stabilnya paling lamban rilis terakhir “sarge” versi 3r1. Sebanyak 14CD atau 2DVD, sourcenya sebanyak 15CD, 3DVD. Mendownload cd nya dengan jidgo, jidgo ini akan mendownload paket program dan membuat image cd nya di komputer kita. Target nya stabilitas distro, pemakai nya kebanyakan advance user, untuk pemula kurang tepat, banyak tool yang harus diakses dari konsol. Saat ini banyak turunan dari debian contoh terkenal adalah linux live cd knoppix, ubuntu.

3.	Redhat
Pelopor distro linux user frendly, dibuat oleh Alan Cox. redhat yang menciptakan paket manager rpm, saat ini ada paket manager yup, dan apt-get untuk redhat. Target nya untuk pemula sampai advance user. Redhat juga yang membuat proyek Gnome. Turunan nya banyak contoh nya adalah Mandriva, Fedora dll. Saat ini Redhat fokus untuk komersial untuk enterprise Linux, sedangkan untuk komunitas ada Fedora. Btw sebenarnya orang nya dia-dia juga. Paket source dari Redhat sebenarnya free, jadi banyak yang porting dari RPMS redhat menjadi Distro lain contoh nya adalah CentOS, Tao, Whitebox.

4.	SuSE/Novell
Distro ini dikembangkan di eropa, jerman tepatnya, target user nya pemula sampai advance, dulunya SuSE tidak menyediakan iso image untuk di download, jadi kalau mau install konek internet, download disket boot dan install langsung dari Internet, maklum aja di eropa jaringan internet nya udah kenceng sampe ke rumah. Saat ini SuSE dibeli oleh Novell, berkerja sama juga dengan Sun Microsystem, sehingga desktop default nya solaris 10 adalah gnome. Baru ini saja Suse mengeluarkan versi OpenSuSE yang bisa di download iso image nya.
 
5.	Mandriva
Distro paling user frendly ini dikembangkan di Prancis, Dahulu nama nya Mandrake tapi karena ada masalah lisensi nama, kemudian ganti nama menjadi mandriva  setelah mengakuisisi Conectiva. Memakai paket mamager RPM, dan oleh mandriva di kembangkan menjadi urpmi. Target user nya pemula sampai advance, banyak dipakai untuk desktop. Yang baru pemula sungguh dipermudah pada mandriva, karena instalasi nya mudah, pengenalan hardware nya bagus. Default dekstop nya adalah KDE.

6.	Gentoo
Distro ini menyediakan compile di tempat. Artinya anda bisa mengoptimalkan distro linux untuk pc anda, pembuat nya (sory lupa) pernah menjadi developer freebsd. Kemudian membuat paket manager yang mirip dengan freebsd untuk gentoo.

7.	Knoppix
Distro yang paling asik, soalnya tidak perlu install ke hardisk, cukup masukkan cdnya dan boot ke cd. Dikembangkan dari debian, sehingga paket debian bisa di install ke knoppix, bisa di install ke hardisk. Guna nya cukup banyak misalnya untuk demo program, sarana belajar linux dengan cepat. Bagi pemula yang takut install linux lebih baik belajar pake Knoppix. Yang pembuat nya dari Jerman Klaus Knopper.

8.	Ubuntu
Distro baik hati, bayangin dia bagi bagi CD gratis ke seluruh dunia. Pasti uang nya juga lumayan terutama ongkos kirim nya. dikembangkan dari debian & knoppix, ada  dua versi live cd atau install. paket debian bisa langsung di install di Ubuntu.

9.	Mepis & Xandros
		Ini distro yang mudah di install, menyertakan paket yang instant misalnya flash, java, acrobat reader, mplayer, quicktime, nvidia driver sudah include ada di sini. Fedora, Mandriva free download, opensuse, belum menyertakan paket tersebut. Dkembangkan dari debian.
 
10.	Turbo Linux
Turbo Linux merupakan salah satu distro Linux yang diminati oleh perusahaan dan perorangan di Jepang dan Asia. Produk berbasis Linux dengan kinerja tinggi ini dimanfaatkan untuk pasar workstation dan server terutama untuk penggunaan clustering dan orientasinya ke perusahaan. Beberapa produk-produknya: TurboLinux Workstation untuk dekstopnya, TurboLinux Server untuk backend server dengan kinerja tinggi terutama untuk penggunaan bisnis di perusahaan, e-commerce dan transaksi B2B (Business-to-Business).

### Sejarah Linux Ubuntu
Ubuntu pertama kali dirilis pada 20 Oktober 2004, versi-versi ubuntu akan dirilis stiap 6 bulan sekali agar dapat memperbaharui sistem keamanan dan update program. LTS (Long Term Support) rilis, yang terjadi setiap dua tahun, didukung untuk tiga tahun pada desktop dan server untuk lima tahun. Andy Fitzsimon merupakan pencipta logo dari ubuntu yang sampai pada saat ini tidak ada perubahan dalam logo tersebut. Default User Interfaceny menggunakan GNOME ( varian berbeda ). Ubuntu didasarkan pada paket- paket dari Debian yang tidak stabil keduanya menggunakan distro Debian’s deb format dan alat manajemen paket, APT dan Synaptic walaupun Debian dan Ubuntu merupakan paket-paket yang belum tentu ( biner kompatibel ) satu sama lain, dan mungkin perlu dibangun ulang dari sumber. Ubuntu dapat digunakan baik untuk desktop maupun server. Ubuntu saat ini mendukung berbagai arsitektur komputer seperti PC (Intel x86), PC 64- bita (AMD64), PowerPC (Apple iBook dan Powerbook, G4 dan G5), Sun UltraSPARC dan T1 (Sun Fire T1000 dan T2000), Playstation 3. Minimum sistem untuk instalasi desktop adalah 300 MHz prosesor x86, 64 MB RAM, 4 GB dari ruang hard drive, dan video yang mendukung kartu VGA pada resolusi 640×480. Disarankan sistem untuk instalasi desktop adalah 700 MHz prosesor x86, 384 MB RAM, 8 GB dari ruang hard drive, dan video yang mendukung kartu VGA di resolusi 1024 × 768. Server memerlukan instalasi x86 prosesor 300 MHz, 64 MB RAM, [61] dan video yang mendukung kartu VGA di 640 × 480. Komputer yang tidak memenuhi persyaratan minimum yang disarankan sistem yang disarankan untuk mencoba Xubuntu, berdasarkan Xfce.



### Instalasi Linux Ubuntu menggunakan VirtualBox
1. **Download VirtualBox**: Download VirtualBox dari situs resmi VirtualBox.
2. **Download Ubuntu**: Download ISO file Ubuntu 24.04 LTS dari situs resmi Ubuntu.
3. **Buat Virtual Machine**:
   - Buka VirtualBox dan klik tombol "New".
   - Beri nama virtual machine dan pilih "Linux" sebagai operasi sistem.
   - Pilih "Ubuntu (64-bit)" dan klik "Next".
   - Pilih "Create a virtual hard disk now" dan klik "Create".
   - Pilih "VDI" sebagai format file dan klik "Create".
4. **Mount ISO File**:
   - Klik kanan pada virtual machine yang baru dibuat dan pilih "Settings".
   - Klik tab "Storage" dan pilih "Add new storage controller".
   - Pilih "IDE Controller" dan klik "OK".
   - Klik tab "Storage" lagi dan pilih "Controller: IDE Secondary Master".
   - Klik tombol "Choose a disk file" dan pilih ISO file Ubuntu yang telah didownload.
5. **Start Virtual Machine**:
   - Klik tombol "Start" untuk memulai virtual machine.
   - Pilih bahasa dan klik "Continue".
   - Pilih opsi "Install Ubuntu" dan klik "Install Now".
6. **Konfigurasi Instalasi**:
   - Pilih lokasi waktu dan klik "Continue".
   - Pilih opsi "Normal" dan klik "Continue".
   - Pilih opsi "Erase disk and install Ubuntu" dan klik "Install Now".
7. **Konfigurasi Akhir**:
   - Tunggu proses instalasi selesai.
   - Setelah selesai, restart virtual machine.

## Kesimpulan
Dengan menggunakan VirtualBox, Anda dapat dengan mudah menginstall Linux Ubuntu 24.04 LTS di komputer Anda. Proses instalasi yang sederhana dan mudah membuatnya menjadi pilihan yang tepat bagi pengguna baru.

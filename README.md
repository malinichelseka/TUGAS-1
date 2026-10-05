# TUGAS-1

NAMA : MALINI CHELSEKA
NIM : 09011382530123
KELAS : SKU3A

1. Buatlah laporan proses instalasi di komputer mahasiswa dan tampilkan screenshot-nya
   

   
  <img width="871" height="569" alt="foto_halaman_1_1" src="https://github.com/user-attachments/assets/9e150912-1743-4d31-9cae-38a3dc54a867" />

  <img width="661" height="496" alt="foto_halaman_1_2" src="https://github.com/user-attachments/assets/dbb398f1-2617-4b46-bf62-01c5d8b37282" />

  <img width="790" height="603" alt="foto_halaman_2_1" src="https://github.com/user-attachments/assets/8b37dea8-8a36-48e1-a6f5-c6f207af3028" />


2. Analisislah pada gambar kenapa saat instalasi perlu dipilih “/” pada opsi Mount Point?
   

    Tanda “/” merupakan root directory, yaitu direktori paling utama dalam sistem file Linux. Semua folder penting dalam Linux, seperti /home, /etc, /usr, /var, dan /boot, berada di dalam struktur root /. Saat proses instalasi Linux, sebuah partisi perlu ditentukan sebagai mount point / agar installer mengetahui bahwa partisi tersebut akan menjadi tempat utama untuk memasang sistem operasi. Dengan begitu, berbagai file dan direktori yang dibutuhkan Linux dapat ditempatkan pada struktur filesystem yang benar. Dalam pengaturan partisi manual, opsi Something else dapat digunakan untuk menentukan partisi dan mount point secara langsung. Salah satu partisi kemudian dapat menggunakan filesystem Ext4 dan diberi mount point /. Jadi, mount point / berfungsi sebagai titik awal atau pusat filesystem Linux, tempat sistem operasi beserta direktori direktorinya disimpan


3. Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32,btrfs !


    a. Ext4

   Ext4 atau Fourth Extended Filesystem adalah filesystem yang banyak digunakan pada Linux. Ext4 merupakan penerus Ext3 dengan berbagai peningkatan dalam hal kinerja, kapasitas penyimpanan, dan pengelolaan file. Ext4 juga memiliki fitur journaling yang membantu menjaga konsistensi data apabila terjadi gangguan pada sistem.


    b. Ext3

   Ext3 atau Third Extended Filesystem merupakan filesystem Linux yang dikembangkan dari Ext2. Keunggulan utama Ext3 adalah adanya fitur journaling, yaitu pencatatan perubahan yang terjadi pada filesystem. Fitur ini membantu mengurangi Risiko kerusakan atau ketidakkonsistenan data ketika komputer mengalami mati mendadak atau gangguan sistem.


    c. Swap

   Swap adalah area penyimpanan yang digunakan Linux sebagai memori tambahan/virtual ketika RAM mulai tidak mencukupi. Data yang sementara tidak aktif dapat dipindahkan ke swap sehingga RAM dapat digunakan untuk kebutuhan lainnya. Swap dapat dibuat dalam bentuk partisi khusus atau file swap.


   d. NTFS

   NTFS (New Technology File System) adalah filesystem yang dikembangkan dan digunakan terutama oleh Windows. NTFS mendukung penyimpanan file dan partisi berukuran besar serta memiliki fitur seperti pengaturan hak akses dan journaling. Filesystem ini cocok digunakan apabila membutuhkan kompatibilitas dengan sistem operasi Windows.


    e. FAT32

   FAT32 (File Allocation Table 32) adalah filesystem yang memiliki tingkat kompatibilitas tinggi dan dapat digunakan oleh berbagai sistem operasi, seperti Windows dan Linux. FAT32 sering digunakan pada flashdisk, kartu memori, dan media penyimpanan eksternal. Kekurangannya adalah ukuran satu file tidak dapat melebihi sekitar 4 GB.


   f. Btrfs

   Btrfs (B-tree File System) merupakan filesystem modern yang dikembangkan untuk Linux. Btrfs memiliki fitur seperti snapshot, compression, checksum, dan pengelolaan volume yang lebih fleksibel. Filesystem ini dapat membantu dalam pengelolaan data serta pemulihan sistem melalui fitur snapshot

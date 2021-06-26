# PT. ADYAWINSA TELECOMMUNICATION & ELECTRICAL

#### KOMPONEN UTAMA TOWER BTS
- ODU (XMC)
- COUPLER / HYBRID COUPLER FOR XMC 5
- ANTENNA SECTORAL & MICROWAVE
- KABEL COAXIAL
- BTS : 
  - IDU (RTN)
  - RECTIFIER
  - FIBER
  - LAN
  - DCDU
  - BATRAI (Untuk backup, maks 3-4 Jam)

#### LANGKAH-LANGKAH POINTING & PERSIAPAN
- PERSIAPAN
  - APD
    - HELM
    - Body Harnes
  - ALAT & BAHAN
    - Microwave & ODU (Perhatikan high, low, polarisasi & frequensi)
    - Kabel & Konektor Coaxial
    - Cutter & Gunting
    - IF Board (Berfungsi Untuk kabel coaxial dari ODU ke IDU)
    - Kompas (Untuk Cek Azimuth)
    - Multimeter Digital (Untuk Cek RSL dBm To Volts)
    - Kunci Ring Pass (14, 16, 17, 19, 22, 24) & Universal 
 
- LANGKAH-LANGKAH
  - LINK BUDGET
    - Azimuth
    - Tinggi Tiang
    - Frequency (MHz)
    - Polarisasi (Vertical atau Hirizontal)
    - Antenna Model (High atau Low)
    - RX Signal (dBm)
    - TX power (dBm)
  - PEMASANGAN
    - Rakit ODU ke Microwave (Cek LB untuk polarisasi)
    - Pasang Microwave Ke Boom (Tiang)
    - Crimping Coaxial (Pasangkan di ODU & IDU (If board))
    - Pasang IF board (Pastikan dalam kondisi OFF)
    - Setelah kabel coaxial siap, pasangkan ke ODU & IDU (If board)
    - Setelah semua sudah siap, tinggal poiting
 
- POINTING
  - CEK INTERFERENCE
    - Salah satu site harus menonaktifkan ODU
    - Engineer scan frequensi, Di site yang ODU nyala harus -90dBm
    - Lakukan hal yang sama pada site lainya

#### PENGENALAN PERANGKAT IDU
- IDU (In Door Unit) merupakan perangkat transmisi yang berfungsi menerima data yang berasal dari ODU (Out Door Unit), Yang kemudian disalurkan kembali ke BSC (Base Station Controller) Atau sabaliknya.

- TIPE-TIPE IDU : 
  - RTN 620
  - RTN 605
  - RTN 910 (Untuk New Site)
  - RTN 950
  - RTN 950A
  - RTN 980

- SPEKSIFIKASI
  - RTN 910 : <br> 1U <br> Bisa Untuk 2 arah radio link <br> Memiliki fitur proteksi 1+1 (HSB/SD/FD) <br> Memiliki fitur 2+0 <br> Memiliki fitur XPIC
  - RTN 950 : <br> 2U <br> Bisa untuk 6 arah radio link <br> Memiliki fitur proteksi 1+1 (HSB/SD/FD) <br> Memiliki fitur N+0 (maks N adalah 5) <br> Memiliki fitur N+1 (maks N adalah 4) <br> Memiliki fitur XPIC
  - RTN 980 : <br> 5U <br> Bisa untuk 14 arah radio link <br> Memiliki fitur proteksi 1+1 (HSB/SD/FD) <br> Memiliki fitur 14+0 (maks N adalah 5) <br> Memiliki fitur 7+1 (maks N adalah 4) <br> Memiliki fitur XPIC

#### PENGENALAN PERANGKAT ODU
- ODU (Out Door Unit) adalah perangkat transmisi yang dipasang dibelakang antena (Microwave). Fungsi ODU untuk meneruskan data dari antena menuju ke IDU.

- TIPE-TIPE ODU :
  - XMC-2 
  - XMC-3/3W
  - XMC-3H
  - XMC-5D

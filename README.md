# Purwadhika_JCDSOL_Capstone2_DataAnalysis

# Capstone Project - Module 2 - Supermarket Customer

# Background story/context
Supermarket X ingin melakukan efisiensi penjualan agar dapat meningkatkan revenue toko di tahun depan. Supermarket ini memiliki data konsumen beserta pembeliannya dalam 2 tahun terakhir. Untuk dapat mencapai tersebut, Supermarket ini ingin menganalisa perilaku pembelian konsumennya. <br> <br>
Kamu diminta untuk menganalisa data pelanggan tersebut dan diharapkan memberikan saran strategis ke depan bagi Supermarket X.

# General Question
Pertanyaan bisnis utama: Bagaimana meningkatkan pemasukan Supermarket berdasarkan pola perilaku pembelian konsumen dalam 2 tahun terakhir?** <br> <br>

Pertanyaan riset yang perlu dijawab dari data:
1. Siapa dan bagaimana profil konsumen Supermarket X?<br>
1.2. Apa segmen pelanggan yang potensial dan perlu untuk ditarget lebih jauh?  <br>

2. Bagaimana menarget pelanggan potensial Supermarket X? <br>
2.1 Produk apa yang perlu ditawarkan untuk segmen pelanggan potensial? <br>
2.2 Channel mana yang efektif untuk segmen pelanggan potensial? <br>
2.3 Strategi marketing seperti apa yang efektif untuk segmen pelanggan potensial?<br>


# Datasource
Dalam melakukan analisa, data yang digunakan adalah data pelanggan Supermarket dalam 2 tahun terakhir. Data dapat diakses di [sini](https://drive.google.com/drive/folders/1WodnBbuYTvsF0-6HTuQABQ0KCS31lqbK)

# Detail data pelanggan Supermarket
Pada data pelanggan Supermarket yang digunakan terdapat beberapa datapoint seperti profil demografi, histori pembelian barang, histori tempat pembelian barang, dan histori aktivitas marketing/campaign. Secara lengkap, berikut adalah deskripsi seluruh kolom data yang terdapat dalam database: <br> <br>

| Kolom               | Deskripsi                                             |
|---------------------|-------------------------------------------------------|
| ID                  | Nomor ID unik pelanggan                           |
| Year_Birth          | Tahun kelahiran pelanggan                             |
| Education           | Tingkat pendidikan pelanggan                          |
| Marital_Status      | Status pernikahan pelanggan                           |
| Income              | Pendapatan tahunan rumah tangga pelanggan            |
| Kidhome             | Jumlah anak di rumah tangga pelanggan                |
| Teenhome            | Jumlah remaja di rumah tangga pelanggan              |
| Dt_Customer         | Tanggal pendaftaran pelanggan dengan perusahaan       |
| Recency             | Jumlah hari sejak pembelian terakhir pelanggan       |
| Complain            | Status aktivitas komplain pelanggan dalam 2 tahun terakhir (Y/N) |
| MntWines            | Jumlah pembelian anggur pelanggan dalam 2 tahun terakhir |
| MntFruits           | Jumlah pembelian buah pelanggan dalam 2 tahun terakhir |
| MntMeatProducts     | Jumlah pembelian daging pelanggan dalam 2 tahun terakhir |
| MntFishProducts     | Jumlah pembelian ikan pelanggan dalam 2 tahun terakhir |
| MntSweetProducts    | Jumlah pembelian permen pelanggan dalam 2 tahun terakhir |
| MntGoldProds        | Jumlah pembelian emas pelanggan dalam 2 tahun terakhir |
| NumDealsPurchases   | Jumlah pembelian dengan diskon                       |
| AcceptedCmp1        | 1 jika pelanggan menerima tawaran dalam kampanye pertama, 0 sebaliknya |
| AcceptedCmp2        | 1 jika pelanggan menerima tawaran dalam kampanye kedua, 0 sebaliknya |
| AcceptedCmp3        | 1 jika pelanggan menerima tawaran dalam kampanye ketiga, 0 sebaliknya |
| AcceptedCmp4        | 1 jika pelanggan menerima tawaran dalam kampanye keempat, 0 sebaliknya |
| AcceptedCmp5        | 1 jika pelanggan menerima tawaran dalam kampanye kelima, 0 sebaliknya |
| Response            | 1 jika pelanggan menerima tawaran dalam kampanye terakhir, 0 sebaliknya |
| NumWebPurchases     | Jumlah pembelian melalui situs web perusahaan        |
| NumCatalogPurchases | Jumlah pembelian menggunakan katalog                 |
| NumStorePurchases   | Jumlah pembelian langsung di toko                   |
| NumWebVisitsMonth   | Jumlah kunjungan ke website perusahaan dalam bulan terakhir |


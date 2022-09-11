# Proposal : MyWallet 💵👛
MyWallet adalah aplikasi berbasis web yang dapat membantu penggunanya untuk melakukan pengelolaan keuangan. MyWallet juga dapat membantu penggunanya untuk melakukan perancangan budget sehingga penggunanya dapat mengelola keuangannya dengan lebih baik.

## 💭 Permasalahan
* Kesulitan melakukan pengelolaan uang bulanan
* Kebutuhan untuk pengingat batas pengeluaran keuangan

## 💡Rancangan Solusi
* Membuat aplikasi yang dapat merekam data pemasukan dan pengeluaran
* Membuat aplikasi yang dapat memberikan notifikasi kepada penggunanya apabila pengeluaran telah melebihi anggaran budget yang telah ditentukan

## 📑 Use Case
* User dapat melakukan registrasi dan login
* User dapat memasukkan pemasukan per bulannya
* User dapat melakukan perencaan budget keuangan bulanan
* User dapat memasukkan pengeluaran harian
* User dapat melihat laporan keuangan per bulannya

## 📃 Struktur Data

### User
|  Atribut  |  Tipe Data  |  Contoh  |
|-----------|-------------|----------|
|id         |varchar      |user1     |
|username   |varchar      |12345     |

### Income
|  Atribut  |  Tipe Data  |  Contoh  |
|-----------|-------------|----------|
|id         |varchar      |inc1      |
|bulan      |varchar      |Januari   |
|nominal    |integer      |500000    |

### Kategori
|   Atribut   |  Tipe Data  |  Contoh  |
|-------------|-------------|----------|
|id           |varchar      |ctg1      |
|nama_kategori|varchar      |makan     |

### Outcome
|  Atribut  |  Tipe Data  |  Contoh  |
|-----------|-------------|----------|
|id         |varchar      |outc1     |
|id_kategori|varchar      |ctg1      |
|id_income  |varchar      |inc1      |
|tanggal    |date         |01-11-2022|
|nominal    |integer      |20000     |

### Budget
|  Atribut  |  Tipe Data  |  Contoh  |
|-----------|-------------|----------|
|id         |varchar      |bdg1      |
|id_kategori|varchar      |ctg1      |
|id_income  |varchar      |inc1      |
|nominal    |integer      |100000    |

## 💻 UX Wireframe
![MyWallet01](https://user-images.githubusercontent.com/112860202/189522797-957e5196-a4ac-465f-a3fa-f223760c63c9.jpg)

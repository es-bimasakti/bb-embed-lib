> Konten ini hanya untuk Integrasi Custom Direct, tidak berlaku untuk model default bb-embed

# JS Interface Data

*Daftar Item yang dikirimkan pada JS Interface

| Variabel      | Type           | Nilai Awal       | Deskripsi                                                    |
| ------------- | -------------- | ---------------- | ------------------------------------------------------------ |
| idtrx         | String Numeric | -                | Nomor Referensi                                              |
| client        | String         | "BB"             | App Client                                                   |
| idprodukubp   | String         | -                | Kode Produk                                                  |
| idpelanggan1  | String         | -                | Nomor Pelanggan/Bill Info                                    |
| idpelanggan2  | String         | -                | Nomor Pelanggan 2/Nomor Meter                                |
| nominal       | String Numeric | -                | Nominal                                                      |
| nominal_admin | String Numeric | -                | Biaya Admin                                                  |
| cashback      | String Numeric | -                | Cashback                                                     |
| phonenumber   | String         | Nomor HP Penjual | Pulsa & Game: Nomor HP Pembeli<br />Ticket: Nomor HP Pembeli/Penumpang |
| email         | String         | Email Penjual    | Ticket: Email Pembeli/Penumpang                              |
| customername  | String         | Nama Penjual     | Nama Pelanggan/Bill Info (Jika Tersedia)                     |
| userid        | String         | -                | ID Agent/ID Member                                           |
| note          | String         | -                | Keterangan, digunakan untuk menu transfer                    |
|               |                |                  |                                                              |

## Mandatory Header

| Variabel        | Type   | Keterangan                                           |
| --------------- | ------ | ---------------------------------------------------- |
| token           | String | Token yang diberikan saat pendaftaran integrasi      |
| x-forwarded-for | String | Identifier yang diberikan saat pendaftaran integrasi |


Client Item File Diff
==========

## DISCLAIMER
FILE DAN DOKUMENTASI PENGGUNAAN YANG TERTERA PADA FILE INI DITUJUKAN SEBAGAI ANTISIPASI BAGI PEMAIN UNTUK MENGHINDARI "DIBUG CRASH" OLEH PEMAIN LAIN (DENGAN CARA MENGGUNAKAN ITEM YANG MENYEBABKAN ERROR/CRASH RAGEXE KARENA FILE INFORMASI TENTANG ITEM TERSEBUT BELUM DITAMBAHKAN OLEH GRAVINDO SECARA OFISIAL). FILE YANG DISEDIAKAN DI SINI MERUPAKAN HASIL 'GENERATE' DARI FILE CLIENT YANG ADA DIGUNAKAN UNTUK SERVER KLASIK DAN RENEWAL SECARA TERPISAH (SILAHKAN BACA DI BAWAH). PENGGUNAAN FILE DAN PETUNJUK PEMAKAIAN YANG TIDAK SESUAI DENGAN ISI FILE README.MD INI BUKANLAH TANGGUNG JAWAB DARI SAYA. HAK CIPTA FILE CLIENT ADALAH MILIK GRAVINDO.


## Cara Pakai

File yang ada pada folder ini merupakan file tambahan untuk memodifikasi GRF agar tidak terjadi CRASH pada client RO (Ragexe.exe) ketika pemain *mencoba* membaca chat (whisper, public, dan broadcast) atau drop item yang tidak belum ada ditambahkan oleh Gravindo ke dalam patch **sedangkan** item tersebut sudah ada pada server-side. Hal ini sering digunakan oleh para cheater untuk membuat *crash* lawan agar *disconnect* ketika sedang bermain.

Tambahkan **isi dari** file-file berikut ke dalam masing-masing file di dalam data.grf yang digunakan (klasik/renewal). Letakkan di atas bagian awal dari file yang dimaksud. Bisa menggunakan tool GRF Editor untuk mengubah isi file yang ada di dalam data.grf. Untuk file data.grf pada client RO Klasik sudah dienkripsi sejak awal rilis, carilah sendiri bagaimana cara membuka file grf yang terenkripsi.

## Table of Contents
---
* klasik              				- Untuk item client server Klasik
  * add_idnum2displaynametable.txt	- Daftar display name yang tidak dimiliki server Klasik, tamb
  * add_idnum2itemdesctable.txt   	- Daftar deksripsi item yang tidak dimiliki server Klasik
  * add_idnum2itemresnametable.txt	- Daftar resource name yang tidak dimiliki server Klasik
* renewal						- Untuk item client server Renewal
  * add_idnum2displaynametable.txt	- Daftar display name yang tidak dimiliki server Renewal
  * add_idnum2itemdesctable.txt   	- Daftar deksripsi item yang tidak dimiliki server Renewal
  * add_idnum2itemresnametable.txt	- Daftar resource name yang tidak dimiliki server Renewal

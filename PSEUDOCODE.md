Algoritma: Harga_Bayar_23
{dibaca merk buku, jumlah halaman, harga barang, jumlah barang dan besaran diskon dari piranti masukan. Hitunglah jumlah diskon dan harga barang}
	
Deklarasi:
merk                            : String 
harga, jumlah, Halbuku          : int
dis, total, bayar, jmlDis       : double

//dis=0.1//
	
Deskripsi:
1. print "Masukan merk buku"                          - read merk
2. print "Masukan jumlah halaman"                     - read Halbuku
3. print "Masukkan harga barang yang dibeli"          - read harga 
4. print "Masukkan Jumlah jumlah barang yang dibeli”  - read jumlah
5. print "Masukan besaran diskon yang anda dapat"     - read dis
5. total  = harga *jumlah
6. jmlDis = total*dis
7. bayar  = total-jmlDis
8. print “Diskon yang anda dapatkan adalah”
9. print jmlDiskon
10. print "Jumlah yang harus dibayar adalah”
11. print bayar
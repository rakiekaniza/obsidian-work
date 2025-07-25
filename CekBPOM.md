- Termin 1 23 Juli 
## Pengembangan 2025
1. Penyempurnaan filter, pencarian dan tampilan detail produk 
	-  Tampilan data pabrik/ pemberi dan penerima kontrak (jika kontrak) / pengemas (jika dikemas kembali) pada komoditi Suplemen dan Obat Kuasi, Untuk Obat Tradisional sudah sesuai. Contoh NIE: QD256016141
	- Perbaikan filter: 
		- Daftar produk: nomor registrasi, 
		- Daftar user: user id (diganti menjadi nip), nama produk, kemasan (tidak bisa filter dengan isian tertentu, contoh: Botol, 7 mL)
		- Produk ditarik: nomor registrasi, status
		- Penjelasan Publik: NIE
		- Hari libur:
	- Semua filter tanggal dibuat menjadi range dengan date picker
	- NPWP, telp, fax pada daftar sarana dihilangkan
	- Detail produk sesuai data di db t_product_manufacturer
	- Dropdown produk ditarik, penjelasan publik, dan informasi sirop obat dipisah
	- 
2. Penyempurnaan dashboard 
3. Penyempurnaan aliran data dari aplikasi registrasi ke cekbpom 
4. Penyempurnaan aliran data label dari aplikasi registrasi ke cekbpom 
5. Penyempurnaan menu pada role administrator 
6. Penyempurnaan modul produk yang ditarik (recall produk) dan penjelasan publik (public warning)
7. Penyempurnaan penghitungan dan tampilan grace period produk
8. Penyempurnaan API CekBPOM
	- API daftar hari libur
9. Penyempurnaan manajemen user (integrasi data siasn)
## Data
- Data e-reg rba lebih update di db lama
- Data notifkos ada yang tidak terkirim
- Data manufacturer di new aero tidak terkirim
- Label data caption di masing-masing komoditi
-
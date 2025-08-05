- Termin 1 23 Juli 
## Pengembangan 2025
1. Penyempurnaan filter, pencarian dan tampilan detail produk 
	-  Tampilan data pabrik/ pemberi dan penerima kontrak (jika kontrak) / pengemas (jika dikemas kembali) pada komoditi Suplemen dan Obat Kuasi, Untuk Obat Tradisional sudah sesuai. Contoh NIE: QD256016141
	- Perbaikan filter: 
		- Daftar produk: nomor registrasi, nama produk, kemasan (tidak bisa filter dengan isian tertentu, contoh: Botol, 7 mL)
		- Produk ditarik: nomor registrasi, status
		- Penjelasan Publik: NIE
		- Daftar Sarana: alamat, provinsi, negara
		- Hari libur: tidak jalan sama sekali
		- Daftar user: user id (diganti menjadi nip), status diganti jadi dropdown
	- Semua filter tanggal dibuat menjadi range dengan date picker
	- NPWP, telp, fax pada daftar sarana dihilangkan
	- Detail produk sesuai data di db t_product_manufacturer
	- Dropdown produk ditarik, penjelasan publik, dan informasi sirop obat dipisah
2. Penyempurnaan dashboard 
	- Grafik Jumlah Produk teregistrasi yang masih berlaku pada halaman depan tidak sesuai untuk komoditas OTSK
	- Pemisahan obat kuasi dari suplemen kesehatan di dashboard
	- Data daftar produk paling sering dicari
	- 
3. Penyempurnaan aliran data dari aplikasi registrasi ke cekbpom 
	- Nama pendaftar tidak muncul pada detail produk komoditi pangan, pengecekan aliran dari e-reg
4. Penyempurnaan aliran data label dari aplikasi registrasi ke cekbpom 
5. Penyempurnaan menu pada role administrator 
6. Penyempurnaan modul produk yang ditarik (recall produk) dan penjelasan publik (public warning)
7. Penyempurnaan penghitungan dan tampilan grace period produk
8. Penyempurnaan API CekBPOM
	- API daftar hari libur
9. Penyempurnaan manajemen user (integrasi data siasn)

- Link aplikasi diganti ke bpom mobile
- Tahun diganti jadi 2025
- Input nie manual
- Logo dan teck cek bpom diganti jadi link ke home
- 
## Data
- Data e-reg rba lebih update di db lama
- Data notifkos ada yang tidak terkirim
- Data manufacturer di new aero tidak terkirim
- Label data caption di masing-masing komoditi
# Todos
- [ ] Kirim grace period ke pengembang
	- [ ] grace period produk renewal
- [ ] Konfirmasi url file label
- [ ] Konfirmasi kendala di produk recall
- [ ] 
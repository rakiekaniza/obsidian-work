Tags: [[Penindakan]]
Pembukaan
- Rapat pagi ini membahas progres perbaikan aplikasi penindakan dan penyesuaian nomenklatur unit yang berubah
Progres Implementasi Modul Cegah Tangkal dan Intelijen
- Untuk modul Cegah Tangkal dan Intelijen sudah dinaikkan ke production, tetapi ada kendala karena perubahan nama unit
- Devi CT: Hasil dari perbaikan belum ada kendala, hanya data yang tidak muncul di akun upt
- UPT yang double karena sinkronisasi dengan data siasn dan nama pada master data unit di adp berbeda dengan yang dari siasn
- Setiya Intel: Untuk user intelijen jika melihat laporan informasi dan laporan intelijen yang dientri oleh UPT seharusnya tampil 5w+1h UPT dan pusat. Sedangkan jika yang mengentri intelijen seharusnya yang muncul 5w+1h pusat saja.
- Untuk wilayah verifikasi sebaiknya dilock sesuai dengan UPT nya, agar UPT tidak bisa melihat data UPT lainnya
- UPT yang berubah nama nya sebaiknya dijadikan satu unit saja, karena jika berbeda UPT tidak bisa melihat data dari nama yang sebelumnya
- Data UPT sebelum perubahan nama akan dirubah data nya menjadi nama UPT yang baru
- Trigger perubahan nama UPT saat sinkronisasi data pegawai dengan SIASN
- Pada tabel UPT ditambahkan kolom untuk kode unit dari satudata
- Yang perlu diset wilayah verifikasi nya hanya user intelijen saja, untuk akun UPT terisi otomatis
Progres Perbaikan Modul Digital Forensik
- Kolom unit kerja sudah ditambahkan pada tabel manajemen permohonan bantuan forensik
- Untuk dokumen yang opsional label nya seharusnya Penetapan Sita Pengadilan
- Kolom total jumlah barang bukti dirapihkan per jenis perangkat
- Warna font tombol catatan di tabel  diganti menjadi merah
- Pada form tambah dokumen serah terima nik disebelah nama petugas diganti menjadi nip
- Pilihan petugas penyerahan UPT difilter berdasarkan unit nya
- Pada daftar barang bukti ditambahkan jumlah barang bukti pada masing-masing tab jenis barang bukti
- Jika permohonan sudah selesai History dokumen dilengkapi log perdokumennya
- Kode peralatan, nomor akuisisi, dan nomor analisis bisa dilihat semua user
- Secara bisnis proses modul digital forensik sudah sesuai
Progres Perbaikan Modul Patroli Siber
- Import data patroli siber kadang tidak bisa upload file, setelah diupload muncul error 403
- Untuk entri laporan bulanan tanggal laporan terisi 1 januari, tidak sesuai dengan yang diinputkan
- Karena tidak diperlukan fitur entri laporan bulanan dihilangkan saja
- Untuk bulan dan tahun laporan diambil dari modal import
Progres Perbaikan Modul Penyidikan
- Dashboard perbandingan 5 tahun ke belakang belum dibuat
- Kolom untuk mencari data SIPT berdasarkan nomor sample sudah ditambahkan
- Data SIPT ditampilkan dalam satu kolom saja
- Untuk penyerahan dan pemushanan masih belum selesai
- Tampilan klinik hukum juga belum diperbaiki
Tindaklanjut
- Penyesuaian master data unit ADP akan dicoba tanggal 23 april 2025 di luar jam kerja
- Untuk modul siber dan penyidikan akan dinaikkan ke production pada akhir minggu ke 3 bulan april
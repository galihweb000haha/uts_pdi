# uts_pdi

table dimensi
1. dim_karyawan
berisi data karyawan yang sudah join dengan table office sehingga dapat diketahui karyawan dan lokasi kantornya
2. dim_order
berisi data customer yang sudah join dengan table orderdetails sehingga dapat diketahui tanggal order dan harga belinya
3. dim_payment

dari skema diatas dibuatlah table fakta
fact_cusomer
yaitu table yang menghubungkan ketiga table dimensi berisi data customer dengan sk dari masing-masing table dimensi

# bootlazada
lazada Boot
Bot Flash Sale Lazada developed with Puppeeter JS by Fmanda

Proses FS

proses login
clear existing cart item, loop sampai cart habis
go to product url, loop smpai bisa ditambahkan ke TROLI
tambahkan ke TROLI & checkout, apabila ada error ulangi step dari no 3
pembayaran, sukses loop ke step no 2 sejumlah products array
Step

Install NodeJS & NPM
run npm install
Edit config.json / Buat baru file config , sesuaikan account, isi produk dan metode pembayaran yg dipilih
run "node index.js config.json"
Bisa dijalankan dengan beberapa config yg berbeda, parameter dibelakan index.js adalah nama file config, contoh : node index.js fmanda.json
Keterangan :

FS menggunakan login Lazada ,
bagi yg pakai account google, silahkan jalankan lupa password agar dibuatkan password utk login native Lazada
Belum di test dengan kondisi aktual flash sale (503 , delay traffic, dsb), Feel free to optimize this script :)
Sebaiknya gunakan akun cadangan bukan utama, menghindari ban / account locked karena terdeteksi menggunakan bot

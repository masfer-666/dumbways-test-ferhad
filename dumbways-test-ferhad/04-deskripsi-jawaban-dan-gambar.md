**CI/CD** menggunakan otomatisasi untuk memastikan bahwa kode aplikasi baru selalu diuji, aman, dan siap digunakan sehingga tim dapat mengirimkan ke bagian produksi tepat pada waktunya.

CI adalah proses pengujian dan pembuatan software secara otomatis setelah kode aplikasi yang baru terintegrasi ke dalam *repository *(tempat penyimpanan) bersama. Sedangkan CD adalah proses penyampaian aplikasi yang dibuat dalam proses CI ke bagian lingkungan produksi, yang dimasukkan melalui *automated test*.

*Automated test* memastikan fungsi aplikasi tersebut dapat sesuai dengan yang diharapkan ketika didorong ke lingkungan produksi hingga ke tangan pengguna yang sebenarnya (*real users*)

Berikut proses workflow ci/cd nya :

1. Developer akan menulis code yang akan dieksekusi melalui **Version Control **system (contohnya git, svn, dsb.)
2. Setelah itu, software tersebut akan memasuki tahap **Build**. Pada tahap ini, developer akan melanjutkan codenya, code tersebut akan dikembalikan ke **Version Control** untuk pembaruan. Code baru dan yang mula ditulis akan digabungkan, dan akan di-compile menggunakan Compiler.
3. Setelah tahap **Build** selesai, kamu akan memasuki tahap **Testing**. Pada tahap ini akan dilakukan berbagai jenis tes untuk menguji kelayakan dari software.
4. Setelah tahap **Testing** selesai, akan dimulai tahap **Deploy**. Pada tahap **Deploy**, kamu akan menjalankan software ke staging server atau test server. Staging server atau test server berlaku sebagai simulasi dan kamu bisa melihat code atau software melalui simulator tersebut.
5. Jika tahap **Deploy **berhasil, kamu akan berlanjut ke tahap **Auto Test**. Jika keseluruhan software yang dikembangkan sudah dapat berjalan baik, maka software kamu sudah dapat dijalankan ke produksi (**Deploy to Production**).
6. Dalam setiap tahap, jika ada error dan semacamnya, kamu bisa menghubungi tim developer untuk membenarkan software tersebut, ini disebut sebagai **Production Feedback**. Developer akan memperbarui versi melalui **Version Control**, dan setiap tahap di atas akan berulang kembali. Siklus tersebut akan berulang sebanyak mungkin hingga diperoleh code yang dapat dijalankan ke server produksi, di mana kita dapat mengukur dan memvalidasi code. (**Measure + Validate**).

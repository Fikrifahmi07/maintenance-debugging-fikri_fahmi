# maintenance-debugging-fikri_fahmi

Penjelasan bug:
bug pertama yaitu pada total = n, ini salah kaena pada perulangan nilai "total" akan ditimpa terus jadi yanag tersimpan cuma angka terakhir,bukan jumlah semuanya. seharusnya dijumlahkan total += n.
bug kedua yaitu pada print("kategori:", kategori_nilai) tidak memanggil fungsi dengan parameter "rata".seharusnya:print("Kategori:", kategori_nilai(rata)).

Jenis error (logic error/ runtime error):
bug pertama termasuk logic error karena ini kesalahan pada logika bukan kesalahan penulisan kode(syntax),dan untuk bag kedua juga bisa termasuk sebagai jenis logic error karena secara penulisan tidak ada kesalahan tapi maknanya yang akan berbeda.dan lebih tepatnya ini termasuk semantic error.

solusi:
jujur saya kurang paham maksud dari solusi disisni,tapi kalau solusi dari bug sudah saya sedikit jelaskan di penjelasan bug, sedikit lebih detail nya seperti ini:
solusi dari bug pertama yaitu menambahkan + sebelum = yang awalnya total = n,menjadi total += n.
solusi dari bug kedua yaitu panggil fungsi dengan parameter rata, yang awalnya  print("kategori:", kategori_nilai),menjadi print("Kategori:", kategori_nilai(rata)).

PERTANYAAN ANALISIS 
1.	Mengapa bug logika lebih berbahaya daripada syntax error? 
Bug logika atau logika error lebih berbahaya daripada syntax error, karena kalau syntax error jelas program tidak akan berjalan,dan Ketika program tidak berjalan akan diberitahu atau ada tanda bahwa ada kesalahan dalam penulisan kode.Tetapi Ketika logika error, program akan tetap berjalan dan tidak ada pemberitahuan bahwa ada kesalahan,tetapi logika atau tujuan akhirnya akan salah.ini  bahaya kalau prpgrammer tidak mengecek Kembali maka kesalahan tidak akan ditemukan atau terdeteksi. 
2.	Apa risiko jika debugging dilakukan tanpa pengujian ulang? 
Manfaat atau fungsi dari pengujian ulang yaitu untuk memastikan bahwa bug sudah benar benar diperbaiki,tidak muncul bug baru,dan memastikan bahwa program dapat berjalan sesuai kebutuhan atau sesuai keinginan.oleh karena itu, jika pengujian ulang tidak dilakukan saat debugging, resikonya yaitu bisa saja bug tidak bener benar hilang atau justru malah muncul bug baru,atau program mengasilkan output yang salah sehingga program tidak sesua kebutuhan atau keinginan.
3.	Bagaimana praktik version control membantu maintenance?
Dalam proses debagging  version control sangat membantu programmer. contoh disini kita menggunakan github sebagai version contolnya,nah di github kita bisa melihat Riwayat perubahan kode jadi kita bisa melihat kapan bug mulai muncul,selain itu juga kita bisa membandingkan kode sebelumnya dengan kode yang versi sudah diperbaiki,selain itu juga kita bisa melihat di baris mana yang dirubah,kode apa yang ditambahkan atau di hilangkan,disini kita juga bisa mengembalikan kode ke versi sebelumnya jika dirasa kode yang dirubah tidak memungkinkan untuk dilanjutkan,dan di sini kita juga akan lebih mudah jika pengerjaan debugging dilakukan dengan kelompok atau tim.

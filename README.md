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


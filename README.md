# maintenance-debugging-fikri_fahmi

Penjelasan bug:
bug pertama yaitu pada total = n, ini salah kaena pada perulangan nilai "total" akan ditimpa terus jadi yanag tersimpan cuma angka terakhir,bukan jumlah semuanya. seharusnya dijumlahkan total += n.
bug kedua yaitu pada print("kategori:", kategori_nilai) tidak memanggil fungsi dengan parameter "rata".seharusnya:print("Kategori:", kategori_nilai(rata))

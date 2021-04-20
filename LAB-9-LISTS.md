'''
Valensia Fernanda Ham Ayomi
71200561
Universitas Kristen Duta Wacana

===================================================

Buatlah program yang dapat menghitung
banyaknya kata yang terdapat dalam kalimat
seperti pada Microsoft Word.

==================================================

input   : kalimat

proses  :
         - kalimat diubah menjadi list menggunaka metode split
         - jumlahkan menggunakan metode len

output : jumlah kata dalam kalimat tersebut

'''
klmt = input('masukkan kalimat: ')
listt = klmt.split()
listt = len(listt)

print('jumlah kata dalam kalimat tersebut adalah ',listt)

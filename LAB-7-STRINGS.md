#Valensia Fernanda Ham Ayomi
#71200561
#Universitas Kristen Duta Wacana

'''
Buatlah sebuah program, dimana user akan menginputkan
kalimat setelah itu menginputkan salah satu huruf yang
ingin dihapus.

===================================================

input : - kalimat
        - huruf yang ingin dihapus

proses : - meminta inputan kalimat
         - meminta inputan huruf yang ingin
         - menggunakan replace untuk menghilang huruf

output : - kalimat dengan huruf yang sudah dihilang

'''

kalimat = input('Masukkan kalimat: ')
huruf = input('Masukkan huruf yang ingin dihapus: ')

hasil = kalimat.replace(huruf,'')

print(hasil)

#Valensia Fernanda Ham Ayomi
#71200561
#Universitas Kristen Duta Wacana

''' 
Beberapa hari lagi teman kamu akan ulang tahun.
Buatlah program ucapan selamat ulang tahun.
syarat:
1. Ucapan diikuti nama dan umur
2. Beri ucapan sebanyak umur (sekarang 2021)
'''

'''
input: nama; tahun lahir

proses: - 2021-tahun lahir
        - 1. selamat ulang tahun
          2. selamat ulang tahun
          ...

output: selamat ulang yang ke ... ...
'''

print("""===== It is a SURPRISE =====
Hai! Ada kejutan buat kamu di hari spesial kamu lohh
Masukkan nama dan tahun lahir yaa""")
nama = input('Nama : ')
tahun = int(input('Tahun lahir (yyyy) : '))
umur = 2021-tahun
for i in range(1,umur+1):
    print(i,"\b. Selamat ulang tahun yang ke",umur,nama)

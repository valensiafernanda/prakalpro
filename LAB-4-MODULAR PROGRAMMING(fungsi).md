#Valensia Fernanda Ham Ayomi
#71200561
#Universitas Kristen Duta Wacana

#https://math4junior.blogspot.com/2017/11/aplikasi-operasi-hitung-bilangan-bulat.html?m=0
''' 
Santi membeli selusin gelas dengan harga 
Rp 17.000 per gelas. Kemudian ia membeli 19 
gelas lagi dengan harga Rp 34.000 per gelas.
Berapakah uang yang harus dibayarkan untuk
gelas-gelas tersebut?
Buatlah fungsi yang dapat menyelesaikan kasus
tersebut.
'''

'''
input: 1. a = 17000, b = 12; 2. a = 34000, b = 19

proses: 1. x = a*b
		2. y = a*b
		3. x+y

output: total harga yang bayar

'''
def kali(a, b):
    hasil = a*b
    return hasil

x = kali(17000, 12)
y = kali(34000, 19)

tambah = lambda x, y: x + y
print(tambah(x, y))

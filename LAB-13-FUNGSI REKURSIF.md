# prakalpro
#Valensia Fernanda Ham Ayomi - 71200561
#Universitas Kristen Duta Wacana

'''
Buatlah program yang dapat menghasil output 
bintang (*) sebanyak yang diinginkan sampai habis atau kosong 
menggunakan fungsi rekursif.

input: n 

proses: * x n
        n x fungsi(n-1)

output:
5 *****
4 ****
3 ***
2 **
1 *
0

'''
def bintang(n):
    if n == 0:
        return 0
    else:
        print(n,'*'*n)
        return n*bintang(n-1)

print(bintang(10))

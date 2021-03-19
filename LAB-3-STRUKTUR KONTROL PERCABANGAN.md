#Nama: Valensia Fernanda Ham Ayomi
#NIM: 71200561
#Universitas Kristen Duta Wacana
#sumber soal: http://mahmudtajinan.blogspot.com/2011/10/contoh-soal-if-else.html
'''
Ada suatu kondisi dimana pada tempat fotokopi "GRAFITY Fotocopy"
apabila dia pelanggan pada tempat itu maka berapa lembar pun
banyaknya dia fotokopi di dapat harga Rp.75 dan jika fotokopi bolak-balik
maka harga naik menjadi Rp.100.
Tapi jika dia bukan pelanggan maka :
a. jika dia fotokopi kurang dari 100 lembar maka dapet harga Rp.150 
   dan jika fotokopi bolak balik maka harga naik menjadi Rp.200
b. jika fotokopi sebanyak 100-200 lembar dapet harga Rp.100 
   dan jika fotokopi bolak balik maka harga naik menjadi Rp.150
c. jika fotokopi lebih dari 200 lembar dia dapet harga Rp.80 
   dan jika fotokopi bolak balik harga naik menjadi Rp.120

'''
'''
input : - apakah user adalah pelangan atau bukan
        - banyaknya fotokopi
        - apakah ingin fotokopi bolak-balik
        
proses : - jika pelanggan dan tdk bolak balik maka 75*banyaknya fotokopi
         - jika pelanggan dan bolak balik maka 100*banyaknya fotokopi
         - jika bukan pelanggan, tidak bolak balik, dan fotokopi <100 lembar maka 150*banyaknya fotokopi
         - jika bukan pelanggan, bolak balik, dan fotokopi <100 lembar maka 200*banyaknya fotokopi
         
output : - harga perlembar
'''

pelanggan = input('apakah anda pelanggan? (ya/tidak) ')
jumlah = int(input('ingin fotokopi berapa lembar? '))

if pelanggan == 'ya':
    bolak = input('apakah ingin fotokopi bolak balik? (ya/tidak) ')
    if bolak == 'ya':
        print('Harga fotokopi perlembar = Rp.100')
        total1 = jumlah*100
        print('jumlah harga yang anda bayar adalah ',total1)
    else:
        print('Harga fotokopi perlembar = Rp.75')
        total2 = jumlah*75
        print('jumlah harga yang anda bayar adalah ',total2)
else:
    bolak = input('apakah ingin fotokopi bolak balik? (ya/tidak) ')
    if bolak == 'ya' and jumlah < 100:
        print('Harga fotokopi perlembar = Rp.200')
        total3 = jumlah*200
        print('jumlah harga yang harus anda bayar adalah ',total3)
    elif bolak == 'tidak' and jumlah < 100:
        print('Harga fotokopi perlembar = Rp.150')
        total4 = jumlah*150
        print('jumlah harga yang harus anda bayar adalah ',total4)
    elif bolak == 'ya' and jumlah >= 100 and jumlah <= 200:
        print('Harga fotokopi perlembar = Rp.150')
        total5 = jumlah*150
        print('jumlah harga yang harus anda bayar adalah ',total5)
    elif bolak == 'tidak' and jumlah >= 100 and jumlah <=200:
        print('Harga fotokopi perlembar = Rp.100')
        total6 = jumlah*100
        print('jumlah harga yang harus anda bayar adalah ',total6)
    elif bolak == 'ya' and jumlah > 200:
        print('Harga fotokopi perlembar = Rp.120')
        total7 = jumlah*120
        print('jumlah harga yang harus anda bayar adalah ',total7)
    elif bolak == 'tidak' and jumlah > 200:
        print('Harga fotokopi perlembar = Rp.80')
        total8 = jumlah*80
        print('jumlah harga yang harus anda bayar adalah ',total8)

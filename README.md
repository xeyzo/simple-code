# simple-code
I have talent in lenguage python


message = ('Hello World')

nama = ('Xeyzo')

usia = 7

lingkar_perut = 35,5

print(message)

print(nama)

print(usia)

print(lingkar_perut)


if usia <= 17:

    print('Jangan nonton film Dewasa')
    
    print('Masih Kecil')
    
else:

    print('Menuju Dewasa')


if lingkar_perut < 30:

    print('Kurus')
    
elif lingkar_perut < 40:

    print('Berisi')
    
else:

    print('Gendut')


for i in range(1,3):

    print(message)

while usia > 0:

    print('Usia saat ini %s' % usia)
    
    print('Masih Hidup')
    
    usia = usia - 1

daftar_nama =['Sandi','Agung']

print(daftar_nama)

daftar_nama.append('japs')

daftar_nama.append('sandul')

print(daftar_nama)

for dn in daftar_nama:

    print('nama lain kamu adalah %s,padahal nama asli kamu itu %s' % (dn,nama))

manusia = {}

manusia['nama'] = 'sandi'

manusia['sex'] = 'Lalaki'

manusia['status'] = 'Pelajar'

print(manusia)

manusia['nama'] = 'Sandi'

print(manusia)

manusia['alamat'] = 'Wonogiri'

print(manusia)

import json

print(json.dumps(manusia))


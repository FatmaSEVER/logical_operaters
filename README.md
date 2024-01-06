# logical_operaters

a = int(input('sayi: '))

result = a > 0 and a < 100

print(f'sayi 0-100 arasında mı: {result}')



result = a >0 and a%2 == 0 

print(f'sayı pozitif ve çift mi: {result}')


mail = 'sever.fatma111@gmail.com'

sifre = 'fateleka21'

ismail = input('mail: ')

issifre = input('sifre: ')

result = ismail == mail and issifre == sifre

print(f'giriş bilginizin doğruluğu: {result}')


a = int(input('a: '))
b = int(input('b: '))
c = int(input('c: '))

result = a > b and a > c

print(f'a en büyük sayıdır: {result}')

result = b > a and b > c

print(f'b en büyük sayıdır: {result}')

result = c > a and c > b

print(f'c en büyük sayıdır: {result}')


vize1 = int(input('vize1: '))

vize2 = int(input('vize2: '))

final = int(input('final: '))

ort = ((vize1+vize2)/2)*0.6 + final*0.4

result = (final >= 50 and ort >=50) or final >=70

print(f'{ort} ile geçme durumunuz: {result}')


mantıksal operatörler ile vücut kitle endeksi hesaplama:

ad = input('isim: ')

kilo = float(input('kilo: '))

boy = float(input('boy: '))

vki = kilo / (boy)**2

zayif = vki <= 18.4 

normal = vki > 18.4 and vki <= 24.9

kilolu = vki >= 25.0 and vki <= 29.9

obez = vki > 30

print(f'{ad}, {vki} indeksi ile zayıf: {zayif}, normal: {normal}, kilolu: {kilolu}, obez: {obez}')

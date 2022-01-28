# Python-2.dereceden denklemin köklerini bulma

print("Kök Bulma Programına Hoşgeldiniz.")

a=int(input("Birinci kat sayıyı giriniz: "))
b=int(input("İkinci kat sayıyı giriniz: "))
c=int(input("Üçüncü kat sayıyı giriniz: "))



delta=b*b-4*a*c
kok1= (-b+(delta**0.5))/(2*a)
kok2=(-b-(delta**0.5))/(2*a)

print("Your first root: {}\nYour second root: {}".format(kok1,kok2))

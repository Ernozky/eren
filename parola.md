import random




karakterler = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
parola_uzunlugu = int(input("parolanız kaç haneli olsun"))
parola = ""

for i in range (parola_uzunlugu):
    parola += random.choice(karakterler)
a = random.choice(karakterler)

print(parola)

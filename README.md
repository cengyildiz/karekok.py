# karekok.py

import math

def karekok():
    while True:
        try:
            sayi = float(input("Bir sayı gir: "))

            if sayi < 0:
                print("Negatif sayı olmaz ki :)")
                break

            sonuc = math.sqrt(sayi)
            print("Karekök:", round(sonuc, 2))
            break

        except ValueError:
            print("Geçersiz giriş yaptın, tekrar dene.")
karekok()



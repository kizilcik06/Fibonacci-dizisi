
nterms = int(input("Terim sayısını girin "))

n1, n2 = 0, 1 count = 0

girilen sayının gecerli olup olmadığını kontrol etmek için
if nterms <= 0: print("Lütfen pozitif bir terim girin")

sadece bir terim varsa , n1 dön
elif nterms == 1: print("Fibonacci dizisi kadar ",nterms,":") print(n1)

Fibonacci dizisini yaratmak için
else: print("Fibonacci dizisi:") while count < nterms: print(n1) nth = n1 + n2 #nth = belirli bir dizideki değeri tanımlar # verileri güncelle n1 = n2 n2 = nth count += 1

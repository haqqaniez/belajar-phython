# belajar-phython
mencoba menggunakan phython
```python
# Program untuk menghitung luas bangun datar

# Fungsi untuk menghitung luas persegi
def luas_persegi(sisi):
    return sisi * sisi

# Fungsi untuk menghitung luas lingkaran
import math
def luas_lingkaran(jari_jari):
    return math.pi * jari_jari * jari_jari

# Fungsi untuk menghitung luas segitiga
def luas_segitiga(alas, tinggi):
    return 0.5 * alas * tinggi

# Input dari pengguna
print("Pilih bangun datar yang ingin dihitung luasnya:")
print("1. Persegi")
print("2. Lingkaran")
print("3. Segitiga")

pilihan = int(input("Masukkan pilihan (1/2/3): "))

if pilihan == 1:
    sisi = float(input("Masukkan panjang sisi persegi: "))
    print(f"Luas persegi adalah: {luas_persegi(sisi)}")
elif pilihan == 2:
    jari_jari = float(input("Masukkan jari-jari lingkaran: "))
    print(f"Luas lingkaran adalah: {luas_lingkaran(jari_jari)}")
elif pilihan == 3:
    alas = float(input("Masukkan panjang alas segitiga: "))
    tinggi = float(input("Masukkan tinggi segitiga: "))
    print(f"Luas segitiga adalah: {luas_segitiga(alas, tinggi)}")
else:
    print("Pilihan tidak valid.")
```

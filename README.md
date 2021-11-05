# Tugas Pertemuan 7 - Praktikum 3 - p7_labpy03


Repository ini dibuat untuk memenuhi Tugas Bahasa Pemrograman - Pertemuan 7 - Praktikum 3


Pada pertemuan 7 ini saya diberi tugas oleh Dosen untuk mempelajari dan membuat program sederhana dengan Bahasa Pemrograman Python


Nama    : Bagas Ari Pradana

NIM     : 312110485

Kelas   : TI.21.C.5

# Tugas Latihan 1

* Pada tugas kali ini saya diminta dosen untuk mengerjakan tugas latihan1.py, seperti gambar dibawah ini :

![Gambar 1](ss/Tugas1.png)

* Saya membuat source code dari perintah diatas (sesuai gambar), seperti dibawah ini :
    ```` Python
        n=int(input("Masukkan Nilai N : "))

        import random

        for x in list(range(1, n+1, 1)):
            print(f"Data ke: {x} ->",random.uniform(0, 0.5))
    ````
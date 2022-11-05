1. Pemrograman terstruktur merupakan pola penyusunan  program  komputer hanya dengan menggunakan tiga struktur kontrol yaitu:    
1.  Sequence    
2.  Selection    
3.  Repetion
uraikan dengan contoh 

1. Sequence

• Sequence merupakan urutan pengerjaan dari
perintah/statement pertama sampai dengan
perintah/statement terakhir.
• Umumnya bahasa pemrograman mempunyai
sequence (urutan pengerjaan dari perintah /
statement ) mulai dari atas ke bawah dan dari kiri
ke kanan.
• Top-down

#Konversi celcius ke kelvin
def kelvin(celcius):
    kelvin = celcius + 273

    return kelvin

#function utama untuk menu utama
def main():
    print("===========Konversi Suhu============")
    suhu = int(input("Masukan Suhu Celcius : "))

    #cetak hasil
    print("...................................................")	
    print("Hasil Konversi Suhu", suhu, "C ke Kelvin adalah", kelvin(suhu), "K")

#menjalankan program
main()

Urutan pengerjaan adalah mulai dari urutan pertama sampai dengan urutan terakhir
jika suhu diisi dengan 20, maka jumlah yang tercetak adalah 293  


2. Selection
Struktur Kontrol Selection adalah penggambaran
sebuah kondisi dan pilihan diantara dua aksi.
• Statement Pertama akan dikerjakan jika kondisi
bernilai benar, jika tidak maka akan mengerjakan
perintah setelah keyword “else” (jika ada).

if hasil > gm:
    print("GM")
elif im <= hasil < gm:
    print("IM")
else:
    print("Error")

Penjelasan :
jika variabel hasil lebih besar dari variabel gm
cetak nilai string "GM" jika variabel hasil lebih kecil dari variabel im
tetapi lebih besar sama dengan variabel im cetak im
selain itu cetak string error


3. Repetition
Beberapa statement / perintah dapat diulang
dengan menggunakan struktur kontrol repetition.
• Statement / perintah akan tetap diulang selama
kondisi perulangan memenuhi (jika menggunakan
DOWHILE – ENDDO)

i = 1
while i <= 5:
  print(i)
  i += 1

Pertama kali variabel i akan diisi dengan 1, setelah itu isi dari variabel i akan dicetak jika variabel i kurang dari sama dengan 5 
lalu cetak nilai variabel i lalu variabel i ditambahkan dengan nilai 1
sehingga tampilannya akan sebagai berikut:   
1 
2 
3 
4
5

2.  Buat flowchart

a. menghitung luas persegi panjang


b. menampilkan luas dan keliling lingkaran


c. membaca data kemudian di lihat apakah data tersebut ganjil atau genap 


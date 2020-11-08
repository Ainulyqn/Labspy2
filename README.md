# **Modul Praktikum 2**

# Latihan 1: Membuat Program Menentukan nilai akhir

`nama = input('masukkan nama: ')` <br>
`uts = input('masukkan nilai uts: ')` <br>
`uas = input('masukkan nilai uas: ')` <br>
`tugas = input('masukkan nilai tugas: ')` <br>
`akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uts) * .4)M` <br>
`keterangan = ('TIDAK LULUS', 'LULUS')[akhir > 60.0]` <br>
`if akhir > 80:` <br>
`    huruf = 'A'` <br>
`elif akhir > 70:` <br>
`    huruf = 'B'` <br>
`elif akhir > 50:` <br>
`    huruf = 'C'` <br>
`elif akhir > 40:` <br>
`    huruf = 'D'` <br>
`else:` <br.>
`    huruf = 'E'`

`print("\nNama :",nama)` <br>
`print("Nilai UAS :",uas)` <br>
`print("Nilai UTS :",uts)` <br>
`print("Nilai Tugas :",tugas)` <br>
`print("Nilai akhir :",akhir)` <br>
`print("\nNilai huruf :",huruf)` <br>
`print("keterangan :",keterangan)`

**PENJELASAN**
* Masukkan nilai yang sudah di tentukan oleh variabel, seperti nama, uts, uas,tugas
* untuk akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uts) *.4)

Outpot : <br>
![gambar](Latihan1/Gambar1/gambar1.png)

# Latihan 2 : Membuat Program Menampilkan Status Gaji Karyawan

`gaji = int(input("Masukkan gaji:"))` <br>
`berkeluarga = (False, True)[input("Sudah berkeluarga? (Y/T)") == "Y"]` <br>
`punya_rumah = (False, True)[input("Punya rumah? (Y/T)") == "Y"]` <br>
`if gaji > 3000000:` <br>
` print ("Gaji sudah diatas UMR")` <br>
` if berkeluarga:` <br>
`     print ("Wajib ikutan asuransi dan menabung untuk pensiun")` <br>
` else:` <br>
`     print("Tidak perlu ikutan asuransi")` <br>
` if punya_rumah:` <br>
`     print("Wajib bayar pajak rumah")` <br>
` else:` <br>
`     print("tidak wajib bayar pajak rumah")` <br>
`else:` <br>
`    print("Gaji belum UMR")` <br>

**PENJELASAN** <br>
Output : <br>
![gambar](Latihan2/Gambar2/gambar1.png)

# Latihan 3: penggunaan kondisi OR program membandingkan 3 input bilangan, apabila penjumlahan 2 bilangan hasilnya sama dengan bilangan lainnya, maka cetak pernyataan “BENAR” <br>

`a = int(input('Masukkan bilangan A: '))` <br>
`b = int(input('Masukkan bilangan B: '))` <br>
`c = int(input('Masukkan bilangan C: '))` <br>
`if a+b == c or b+c == a or c+a == b:` <br>
`    print('benar')` <br>
`else: print('salah')`

**PENJELASAN** <br>
Output : <br>
![gambar](Latihan3/Gambar3/gambar1.png)

# Tugas Praktikum 2 <br>
![gambar](TugasPraktikum2/Gambar1/gambar1.png)

`A = int(input('Masukkan bilangan pertama: '))` <br>
`B = int(input('Masukkan bilangan kedua: '))` <br>
`C = int(input('Masukkan bilangan ketiga: '))` <br>

`if A > B and A > C:` <br>
`    print('Nilai', A, 'terbesar dari 3 bilangan yang di inputkan')` <br>
`elif B > A and B > C:` <br>
`    print('Nilai', B, 'terbesar dari 3 bilangan yang di inputkan')` <br>
`else:` <br>
`    print('Nilai', C, 'terbesar dari 3 bilangan yang di inputkan')`

**PENJELASAN** <br>
Output : <br>
![gambar](TugasPraktikum2/Gambar1/gambar2.png)

Flowchart <br>
![gambar](TugasPraktikum2/Gambar1/flowchart.png)

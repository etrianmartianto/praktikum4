# praktikum4


Latihan 1 (Perhitungan dengan kodisi diskon tertentu)

Alur Algoritma : 
-Mendeklarasikan awal: (yt) untuk rumus perulangan "pilihan di akhir" {cin>>yt; if(yt=='Y' || yt=='y') {goto awal;} if(yt=='T' || yt=='t') {goto selesai;} selesai:} 
-Menggunakan variable awal: (yt) untuk rumus perulangan "kode>4" pilihan menu if (kode>'4') { cin>>yt; if(yt=='Y' || yt=='y') {goto awal;} if(yt=='T' || yt=='t') {goto selesai;} selesai:} 
-Mendeklarasikan int jumlah, kode sebagai variable input 
-Mendeklarasikan int, diskon,total,GT,harga sebagai variable perhitungan 
-Menentukan rumus diskon dengan kondisi >=1jt(10%), >500k(5%), <500k(0%) if (total>=1000000) (diskon=total0.1); else if (total>=501000) (diskon=total0.05); else (diskon=total0); 
-Menggunakan rumus perhitungan dengan diskon yang telah di tentukan "Digunakan di setiap variable input" total=jumlahharga; if (total>=1000000) (diskon=total0.1); else if (total>=501000) (diskon=total0.05); else (diskon=total*0); GT=total-diskon;

Berikut Pseudo-Codenya :

    1.kode :....
    2.if kode>4 then goto no 1, else no 9
    3.jumlah : ....
    4.total=jumlah*harga
    5.if (total>=1000000) (diskon=total0.1) else if (total>=501000) (diskon=total0.05) else (diskon=total*0)
    6.GT=total-diskon;
    7.Pilihan?
    8.if (Y) then goto no 1, else (T) goto no 9
    9.selesai

Berikut Flow chartnya :
![alt text](https://github.com/etrianmartianto/praktikum4/blob/master/flowchart.png)


-Berikut hasil screenshotnya: 

1.Kode pilihan T-selesai:
![alt text](https://github.com/etrianmartianto/praktikum4/blob/master/Latihan1.1.png)

2.Kode pilihan Y-mulai:
![alt text](https://github.com/etrianmartianto/praktikum4/blob/master/Latihan1.2.png)

3.Kondisi diskon 5% (1):
![alt text](https://github.com/etrianmartianto/praktikum4/blob/master/Latihan1.3.png)

4.Kondisi diskon 5% (2):
![alt text](https://github.com/etrianmartianto/praktikum4/blob/master/Latihan1.4.png)

5.Kondisi diskon 10% (1):
![alt text](https://github.com/etrianmartianto/praktikum4/blob/master/Latihan1.5.png)

6.Kondisi diskon 10% (2):
![alt text](https://github.com/etrianmartianto/praktikum4/blob/master/Latihan1.6.png)

7.Kondisi pilihan menu tidak ada:
![alt text](https://github.com/etrianmartianto/praktikum4/blob/master/Latihan1.7.png)

8.Kondisi tanpa diskon (1):
![alt text](https://github.com/etrianmartianto/praktikum4/blob/master/Latihan1.8.png)

9.Kondisi tanpa diskon (2):
![alt text](https://github.com/etrianmartianto/praktikum4/blob/master/Latihan1.9.png)



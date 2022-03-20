# NCC-Third-Assignment-Danial-Farros

## Soal 1.a
Display Filter sehingga wireshark hanya mengambil paket yang berasal dari 192.168.1.158 : 
1. Proses Filtering Dilakukan dengan menggunakan `ip.src == 192.168.1.158`
![alt text](https://github.com/danial921/NCC-Third-Assignment-Danial-Farros/blob/main/Soal1/1a%20command.png)
2. Berikut adalah hasil yang didapatkan
![alt text](https://github.com/danial921/NCC-Third-Assignment-Danial-Farros/blob/main/Soal1/1a%20result.png)

## Soal 1.b
Display Filter sehingga wireshark hanya mengambil paket yang menuju ke 192.168.1.255 : 
1. Proses Filtering Dilakukan dengan `ip.dst == 192.168.1.225`
![alt text](https://github.com/danial921/NCC-Third-Assignment-Danial-Farros/blob/main/Soal1/1b%20command.png)
2. Berikut adalah hasil yang didapatkan
![alt text](https://github.com/danial921/NCC-Third-Assignment-Danial-Farros/blob/main/Soal1/1b%20result.png)

## Soal 2
Ann adalah seorang tersangka dalam sebuah tindak kejahatan. Setelah bebas dengan uang jaminan, Ann melarikan diri. Polisi mengatakan bahwa kemungkinan besar dia melarikan diri bersama pacarnya. Penyidik telah memonitor lalu lintas jaringan yang digunakan Ann. Dari file .pcap yang merupakan hasil capture lalu lintas jaringan, diharapkan investigator bisa mencari keberadaan Ann.

## Soal 2.a
Cari data user berupa email yang ada dalam .pcap
|Email yang didapat | Keterangan|
|---|---|
|sneakyg33k@aol.com|Email Aan|
|sec558@gmail.com|Email Rekan Aan|
|mistersecretx@aol.com|Email Kekasih Aan|

![alt text](https://github.com/danial921/NCC-Third-Assignment-Danial-Farros/blob/main/Soal2/2a-1.png)
![alt text](https://github.com/danial921/NCC-Third-Assignment-Danial-Farros/blob/main/Soal2/2a-2.png)

## Soal 2.b
Pada protokol imf terdapat 2 pesan. Cari 2 data pesan tersebut!
1. Proses Filtering Dilakukan dengan `imf`
![alt text](https://github.com/danial921/NCC-Third-Assignment-Danial-Farros/blob/main/Soal2/2b-3.png)
2. Melakukan Analisis Terhadap Pesan 1
![alt text](https://github.com/danial921/NCC-Third-Assignment-Danial-Farros/blob/main/Soal2/2b-1.png)
4. Melakukan Analisis Terhadap Pesan 2
![alt text](https://github.com/danial921/NCC-Third-Assignment-Danial-Farros/blob/main/Soal2/2b-2.png)

## Soal 2.c
Cari data file .docx yang dikirim Ann
![alr_text](https://github.com/danial921/NCC-Third-Assignment-Danial-Farros/blob/main/Soal2/2c.png)
didapatkan aan mengirim docx dengna nama file `secretrendezvous.docx`

## Soal 2.c
Cari lokasi meeting Ann
berdasarhasil penelusuran dari soal 2.c dilakukan proses decoding dengan menggunakan notebook++, proses decoding lakukan dengan `Base64 Decode` dan hasilnya dapat dilihat dengan menggunakan penampil dokumen
![alr_text](https://github.com/danial921/NCC-Third-Assignment-Danial-Farros/blob/main/Soal2/2d.png)

## Soal 3
Buat suatu display filter sehingga wireshark hanya mengambil paket yang mengandung port 21! (Hasil berupa display filter yang di demokan)
proses filtering dilakukan dengan `dst port 21 || src port 21`, sehingga didapatkan
![alr_text](https://github.com/danial921/NCC-Third-Assignment-Danial-Farros/blob/main/Soal3/3a.png)

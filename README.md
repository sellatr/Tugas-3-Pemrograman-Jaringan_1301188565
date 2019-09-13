# Tugas-3-Pemrograman-Jaringan_1301188565

<p align="center"
  <a><strong>  NAMA KELOMPOK :  </strong></a> 
</p>
<p align="center">
  <a>  I Putu Surya Baratha (1301188566)  </a> 
</p> 

<p align="center">
  <a>  Muhammad Risdham Nur A.P (1301188603)  </a> 
</p>

<p align="center">
  <a>  Sella Tresnasari  (1301188565)  </a> 
</p> 



#### HASIL RUNNUNG NOMOR 1 ####

[![Screen-Shot-2019-09-10-at-15-43-03.png](https://i.postimg.cc/hjn0W6X1/Screen-Shot-2019-09-10-at-15-43-03.png)](https://postimg.cc/8FyvLyB7)

Cara kerja menggunakan FSM :

[![1.png](https://i.postimg.cc/RZHQ7y4f/1.png)](https://postimg.cc/RWvH9P3V)

#### HASIL RUNNING NOMOR 2 ####

[![Screen-Shot-2019-09-10-at-16-14-35.png](https://i.postimg.cc/VkRt0vvn/Screen-Shot-2019-09-10-at-16-14-35.png)](https://postimg.cc/bZZrKzQw)

Cara kerja menggunakan FSM :

[![2.png](https://i.postimg.cc/Dyt1w6Lz/2.png)](https://postimg.cc/nCGXdvd8)

#### HASIL RUNNING NOMOR 3 ####

[![Screen-Shot-2019-09-10-at-16-29-48.png](https://i.postimg.cc/G3FmmNHs/Screen-Shot-2019-09-10-at-16-29-48.png)](https://postimg.cc/t7gjrBdX)

Cara kerja menggunakan FSM :

[![fsm.png](https://i.postimg.cc/NGZxKQwY/fsm.png)](https://postimg.cc/DmdGDkZY)

#### HASIL RUNNING NOMOR 4 ####

[![message-Image-1568359604198.jpg](https://i.postimg.cc/1Xs5dh1T/message-Image-1568359604198.jpg)](https://postimg.cc/MM3ScLTb)

Cara kerja :

Ping dengan menggunakan perintah echo dari protocol ICMP. Ini merupakan protocol dengan berorientasi byte yang dimana klien mengirim aliran byte ke host lain lalu host akan membalas. Formatnya adalah:
* Byte yang pertama adalah 8, untuk pesan echo
* Byte yang kedua adalah nol
* Byte yang ketiga dan keempat merupakan checksum untuk seluruh pesan
* Byte yang kelima dan keenam merupakan pengidentifikasi arbitrer
* Byte yang ketujuh dan kedelapan merupakan nomor urut yang sembarang
* Sisa paket merupakan data pengguna
Program tersebut akan menyiapkan koneksi IP dan mengirim permintaan untuk ping ke host serta mendapatkan balasan.

#### HASIL RUNNING NOMOR 5 ####

[![message-Image-1568111201501.jpg](https://i.postimg.cc/m2ZB2gv0/message-Image-1568111201501.jpg)](https://postimg.cc/xqZW6nTR)

Cara kerja :

Multi-threading merupakan salah satu teknik dalam pemrograman yang bertujuan untuk membuat proses berjalan secara bersamaan dalam satu waktu. Pada sebuah thread bagian program yang dapat berjalan mandiri, sehingga dua atau lebih thread dapat
berjalan bersamaan, tanpa yang satu harus menunggu selesainya yang lain.
1. Program dijalankan dengan melakukan koneksi ke telnet port 8080 dengan jumlah yang banyak dengan waktu yang bersamaan.
2. Pertama panggil “telnet 8080” lalu program akan melakukan koneksi ke IP yang ditemukan.
3. Program mengeluarkan statement bahwa tidak bias koneksi ke Remote Host.
4. Yang kedua juga sama melakukan konksi ke “telnet 8080)
5. Lalu dicoba kembali dengan koseksi telnet dengan menambahkan alamat IP lalu diikuti port
8080
6. Program akan menjalankan looping sampai terkoneksi ke localhost dengan port 8080
dan melakukan input berupa string

#### HASIL RUNNING NOMOR 6 ####

[![Screen-Shot-2019-09-12-at-18-49-38.png](https://i.postimg.cc/NMq5t0QP/Screen-Shot-2019-09-12-at-18-49-38.png)](https://postimg.cc/sBmV9sQp)

Cara kerja : 

Multi-threading merupakan salah satu teknik dalam pemrograman yang bertujuan untuk membuat proses berjalan secara bersamaan dalam satu waktu. Pada sebuah thread bagian program yang dapat berjalan mandiri, sehingga dua atau lebih thread dapat
berjalan bersamaan, tanpa yang satu harus menunggu selesainya yang lain. Namun pada kasus kali ini program akan melakukan proses menurut antrian.
Cara kerja:
1. Program terkoneksi ke localhost dengan melakukan telnet ke port 8080
2. Program memproses sesuai antrian
3. CPU melakukan proses selama 1 detik
4. Input data berupa stirng
5. Menampilkan kembali output
6. Melakukan telnet> cost agar keluar dari program

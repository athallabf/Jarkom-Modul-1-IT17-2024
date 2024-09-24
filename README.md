# Jarkom-Modul-1-IT17-2024

# Anggota Kelompok

| Nama                        | NRP        |
| --------------------------- | ---------- |
| Athalla Barka Fadhil        | 5027231018 |
| Jody Hezekiah Tanasa Sagala | 5027221050 |

## Pegawai Negeri

Untuk soal ini kita hanya perlu cari sesuai yang diinginkan, pake Display Filter "frame contains 'TEXT'"
Lalu selanjutnya tinggal find TEXT di kolom find aja
![alt text](assets/image-37.png)
![alt text](assets/image-38.png)
![alt text](assets/image-39.png)
![alt text](assets/image-40.png)
![alt text](assets/image-41.png)
![alt text](assets/image-42.png)

## Rizzset

Display Filter "dns"
lalu cari ip dibagian kanan domain (103.94.189.5)
Lalu pake algoritma JARM (jarm.py) buat ambil fingerprintnya
![alt text](assets/image-23.png)
![alt text](assets/image-30.png)

## Sanity

Display Filter "ame"
Karena cari nama, dan kenapa "ame" tidak "name" agar saya bisa dapet "Name" dan "name" jadi untuk antisipasi capital

lalu tinggal cari yang ada tulsian "found"
dan disitu follow tcp dan ada semua infonya tinggal ikutin
![alt text](assets/image-4.png)
![alt text](assets/image-5.png)
![alt text](assets/image-6.png)
![alt text](assets/image-7.png)
![alt text](assets/image-8.png)
![alt text](assets/image-9.png)
![alt text](assets/image-10.png)
![alt text](assets/image-11.png)

## Stegago

Ini kita export as objects lalu ambil FTP-DATA lalu itu diitung aja ada berapa file .png
setelah itu kita bikin script yang akan ambil text tersembunyi, dari situ kita tinggal isi aja pertanyaannya
![alt text](assets/image-12.png)
![alt text](assets/image-13.png)
![alt text](assets/image-14.png)
![alt text](assets/image-15.png)
![alt text](assets/image-16.png)

## Surprise

Display Filter "frame contains 'ogin'" agar antisipasi capital Login atau login jadi kita pilih 'ogin'
disitu tinggal cari yang successfull dan kita ambil informasi dari situ, kemudian kita download file g0tcha.cppnya lalu kita compile aja
![alt text](assets/image-17.png)
![alt text](assets/image-18.png)
![alt text](assets/image-19.png)
![alt text](assets/image-20.png)
![alt text](assets/image-21.png)
![alt text](assets/image-22.png)

## InneRCE

Display Filter "frame contains 'upload'" atau http.request.method === POST
lalu tinggal cari aja ketika ada tulisan "has been uploaded" trus ambil tanggalnya dan tinggal ikuti aja karena dari filternya sudah ada informasi banyak yaitu nama file ada di url lalu nama command juga ada di url, untuk pesan yang ingin disampaikan hacker ada di url juga
![alt text](assets/image-43.png)
![alt text](assets/image-44.png)
![alt text](assets/image-45.png)
![alt text](assets/image-46.png)
![alt text](assets/image-47.png)
![alt text](assets/image-48.png)
![alt text](assets/image-49.png)
![alt text](assets/image-50.png)
![alt text](assets/image-51.png)
![alt text](assets/image-52.png)

## Corporate Breach

Display Filter kita cari request method POST sama frame yang ada "name" dari situ dapet nama hackernya habistu kita cari yang http contains OK atau responsenya 200, nah disitu ada frame yang beda sendiri, dia gaada tulisan text/html, nah itu jawabannya
![alt text](assets/image-24.png)
![alt text](assets/image-25.png)
![alt text](assets/image-26.png)
![alt text](assets/image-27.png)
![alt text](assets/image-28.png)
![alt text](assets/image-29.png)

## EZ

Ini pilih aja salah satu frame trus kita follow, nah disitu ada jawabannya lalu untuk port tinggal liat di bagian frame information
![alt text](assets/image-56.png)
![alt text](assets/image-57.png)
![alt text](assets/image-58.png)

## FTP Login

Display filter frame contains "ogin"
cari yang success lalu ambil info disitu
![alt text](assets/image-53.png)
![alt text](assets/image-54.png)
![alt text](assets/image-55.png)

## Gajah Recon

Pertama langsung keliatan ada PGSQL yaitu PostgreSQL lalu kita filter TCP dan kita ambil aja satu frame trus kita follow, nah disitu udah ada banyak infonya, untuk password pas dicek di GPT itu dia dihash pake md5, yaudah kita decrypt dan submit
![alt text](assets/image-31.png)
![alt text](assets/image-32.png)
![alt text](assets/image-33.png)
![alt text](assets/image-34.png)
![alt text](assets/image-35.png)
![alt text](assets/image-36.png)

## Illegal Breakthrough

Display filter http lalu kita ambil IP addressnya pas kita follow itu udah ada sama portnya jg lalu untuk endpoint sudah keliatan yaitu /ww1.php
lalu display filter buat response code 302 dan disitu udah ada tools sama kredensialnya
![alt text](img/image-1.png)
![alt text](img/image-2.png)
![alt text](img/image-3.png)
![alt text](img/image-4.png)
![alt text](img/image-5.png)
![alt text](img/image-6.png)
![alt text](img/image-7.png)
![alt text](img/image-8.png)
![alt text](img/image-9.png)

## Revisi

https://youtu.be/uoTMRIlQb5k

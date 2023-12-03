Web server merupakan aplikasi yang memberikan layanan uuntuk memudahkan pengakses mendapatkan informasi yang diinginkan. Web server juga berfungsi untuk melakukan pemeriksaan terhadap security yang berasal dari permintaan dan menyediakan data yang dinginkan sesuai request
Cara kerja web server:

Permintaan (Request): Pengguna membuka browser dan mengetikkan alamat situs web

Pemrosesan Permintaan: Web server menerima permintaan, menerjemahkan request, kemudian mengeksekusi perintah tersebut. 

Pengiriman (Response): Setelah pemrosesan selesai, web server akan mengirimkan hasilnya kembali ke browser pengguna. 

Tampilan di Browser: Browser menerima respons dari server dan menampilkan halaman web sesuai dengan instruksi yang diberikan oleh server.

Reverse Proxy sebuah atau kumpulan server yang mengetengahi lalu lintas antara pengguna dan internet. Mudahnya ketika pengguna ingin mengakses sebuah website maka sebelum masuk ke internet maka terlebih dahulu melewati proxy server, sehingga yang berhubungan langsung dengan website adalah proxy bukan server pengguna.

sebuah atau kumpulan server yang mengetengahi lalu lintas antara pengguna dan internet. Mudahnya ketika pengguna ingin mengakses sebuah website maka sebelum masuk ke internet maka terlebih dahulu melewati proxy server, sehingga yang berhubungan langsung dengan website adalah proxy bukan server pengguna.

Cara melakukan reverse proxy sebagai berikut
1. install multipass
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2017-54-34.png?raw=true)

2. launch multipas
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2018-12-54.png?raw=true)
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2018-17-47.png?raw=true)

3. melakukan clonning
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2018-42-33.png?raw=true)

4. cek clonning file
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2018-45-19.png?raw=true)

5. instalasi vnm
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2019-07-25.png?raw=true)

6. instal npm
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2020-09-15.png?raw=true)
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2020-19-31.png?raw=true)

7. npm start
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2020-20-10.png?raw=true)

8. cek IP npm
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2020-22-24.png?raw=true)

9. tes awal untuk menjalankan aplikasi
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2020-27-28.png?raw=true)

10. hasilnya
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2020-27-41.png?raw=true)

11. install nginx
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2020-51-27.png?raw=true)

12. cek status nginx
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2020-52-20.png?raw=true)

13. ubah kepemilikan file agar dapat membuat dikerktori 
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2020-54-39.png?raw=true)

14. hasil perubahan kepemilikan file
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2020-56-20.png?raw=true)

15. hasil configuration proxy yang sudah dibuat 
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2021-06-52.png?raw=true)

16. configurasi local
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2021-11-29.png?raw=true)

![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2021-12-53.png?raw=true)

![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2021-22-52.png?raw=true)

17. reverse proxy berhasil di buat
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2021-25-03.png?raw=true)

18 melakukan clonning terhadap nvm
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2022-54-53.png?raw=true)

19. jalankan aplikasi
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2022-56-15.png?raw=true)

20. hasil
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_6/Screenshot%20from%202023-12-02%2022-56-25.png?raw=true)

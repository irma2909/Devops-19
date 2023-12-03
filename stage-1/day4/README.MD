Teks editor merupakan suatu program komputer yang digunakan untuk mengedit suatu file dan menyimpan file

Membuka teks editor nano
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2008-11-44.png?raw=true)

Ctrl o untuk mengedit, menyimpan suatu file tanpa keluar dari teks editor
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2008-30-26.png?raw=true)

Ctrl W untuk mencari suatu teks
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2008-45-54.png?raw=true)

Ctrl A untuk memilih teks
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2008-54-40.png?raw=true)

Alt 6 untuk mengcopy teks
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2008-58-07.png?raw=true)

Ctrl u untuk paste teks
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2008-58-07.png?raw=true)

Alt u dan Alt e untuk redo dan undo
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2009-00-55.png?raw=true)
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2009-03-01.png?raw=true)

Ctrl K untuk meng-cut teks
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2009-03-01.png?raw=true)

Ctrl A untuk di awal baris dan Ctrl e untuk di akhir baris
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2009-05-24.png?raw=true)
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2009-05-30.png?raw=true)

Ctrl R untuk memindahkan konten dari satu file ke file yang lain
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2009-11-06.png?raw=true)
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2009-11-41.png?raw=true)

Manipulasi teks pada Linux merupakan operasi yang dapat digunakan untuk mengedit teks tanpa harus masuk ke editor teks, seperti pencarian, penggantian, penyaringan, pengurutan, dan manipulasi lainnya.
cat: Menampilkan isi file ke layar
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2009-42-23.png?raw=true)
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2009-44-55.png?raw=true)

sed: Melakukan manipulasi teks, seperti pencarian dan penggantian
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2009-52-29.png?raw=true)

grep : digunakan untuk mengubah mencari, menghitung teks dalam file
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2009-57-13.png?raw=true)
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2009-59-10.png?raw=true)

echo : digunakan untuk mengganti dan menambahkan teks dalam file
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2010-07-04.png?raw=true)

Apa itu Network Firewall:

Firewall adalah suatu sistem yang digunakan untuk menjaga keamanan jaringan sertaa memantau dan mengontrol lalu lintas yang masuk dan keluar dari jaringan. Firewall ini akan membantu melindungi sistem dari ancaman dan serangan. 
Fungsi Firewall:

Filtering: Memfilter lalu lintas berdasarkan aturan tertentu.

Logging: Mencatat aktivitas lalu lintas untuk analisis keamanan.

Prevention: Mencegah akses yang tidak diinginkan masuk ke sistem.

ufw (Uncomplicated Firewall) pada Ubuntu:

1 install ufw dan aktifkan ufw 
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2011-32-59.png?raw=true)
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2011-35-52.png?raw=true)

2 sudo ufw deny untuk mengijinkan semua akses yang masuk 
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2011-42-59.png?raw=true)

3. Melarang semua akses untuk keluar
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2011-45-16.png?raw=true)

4. Mengijinkan akses untuk keluar
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2011-46-25.png?raw=true)

Tes ssh ufw allow 22
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2012-03-10.png?raw=true)

6. verbose cek status
![alt text](https://github.com/irma2909/Devops-19/blob/master/Tugas%20Day_4/Screenshot%20from%202023-12-02%2012-05-16.png?raw=true)

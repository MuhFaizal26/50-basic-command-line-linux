# 50-basic-command-line-linux

#  Muhammad Faizal Mirzah
# 09011382429122
# Sistem Operasi

1. **cd**  
   Berpindah direktori.
<img width="725" height="511" alt="Screenshot 2025-09-15 184935" src="https://github.com/user-attachments/assets/192d56f5-02b2-48e7-9e61-0350e7e136f4" />

2. **ls**  
   Melihat daftar file/direktori dalam folder.
<img width="1102" height="360" alt="Screenshot 2025-09-12 090706" src="https://github.com/user-attachments/assets/7cd53285-a89a-4771-867a-a0907613c6fb" />

3. **ifconfig**  
    Menampilkan atau mengkonfigurasi jaringan.
<img width="1095" height="507" alt="Screenshot 2025-09-12 090737" src="https://github.com/user-attachments/assets/19dce058-f43b-40a2-9fa7-887abf6fb165" />

4. **ip a**  
    Menampilkan informasi jaringan modern (pengganti ifconfig).
<img width="1102" height="443" alt="Screenshot 2025-09-12 090817" src="https://github.com/user-attachments/assets/7836b0d1-a677-4c90-b6cf-7f590ec2713e" />

5. **mkdir**  
   Membuat direktori baru.
<img width="1106" height="314" alt="Screenshot 2025-09-12 090857" src="https://github.com/user-attachments/assets/4e954f05-d701-4b14-b252-3eddc176a911" />

6. **sudo su**  
    Mengubah user saat ini menjadi **root** (superuser) dan tetap berada di dalam shell login root.  
    > Contoh: `sudo su` → masuk ke root shell dengan seluruh environment root.
<img width="1108" height="267" alt="Screenshot 2025-09-12 091348" src="https://github.com/user-attachments/assets/633bf9ec-f11d-4972-a6ec-25fe886e9449" />

7. **sudo -**  
    Masuk ke shell **root login penuh** seolah-olah login langsung sebagai root, dengan semua konfigurasi environment root.  
    > Contoh: `sudo -` → langsung berada di lingkungan root seperti saat login sebagai root. 
<img width="1105" height="252" alt="Screenshot 2025-09-12 091446" src="https://github.com/user-attachments/assets/ba97f6f3-8f8f-42de-a7c1-61a9effebddc" />

8. **date**  
    Menampilkan atau mengatur tanggal/waktu.
<img width="1103" height="259" alt="Screenshot 2025-09-12 091537" src="https://github.com/user-attachments/assets/0763f334-20e6-4fa0-941e-f9e7a8d9dd61" />

9. **uptime**  
    Menampilkan lama waktu sistem berjalan.
<img width="1097" height="244" alt="Screenshot 2025-09-12 091555" src="https://github.com/user-attachments/assets/281bb653-342b-4296-983c-0432c2839dd4" />

10. **whoami**  
    Menampilkan username pengguna saat ini.
<img width="1098" height="254" alt="Screenshot 2025-09-12 091704" src="https://github.com/user-attachments/assets/8703b9a7-ebee-4612-8890-42244af935db" />

11. **who**  
    Menampilkan daftar user yang sedang login di sistem.  
    > Contoh: `who` → hasilnya bisa berupa daftar username, terminal, dan waktu login.
<img width="1122" height="279" alt="Screenshot 2025-09-12 091927" src="https://github.com/user-attachments/assets/2e15d53e-f5fb-4857-a3ec-ebefb1c324f4" />

12. **w**  
    Menampilkan daftar user yang sedang login beserta aktivitas/proses yang sedang mereka jalankan.  
    > Contoh: `w`
<img width="1101" height="305" alt="Screenshot 2025-09-12 091941" src="https://github.com/user-attachments/assets/3db7adf7-6db6-45ab-aece-2ae777ab349c" />

13. **users**  
    Menampilkan username semua user yang sedang login (ringkas, tanpa detail waktu/aktivitas).  
    > Contoh: `users`
<img width="1096" height="260" alt="Screenshot 2025-09-12 092008" src="https://github.com/user-attachments/assets/71159626-730d-4df6-b02e-0949515f5c61" />

14. **rmdir**  
   Menghapus direktori kosong.
<img width="740" height="529" alt="Screenshot 2025-09-15 184811" src="https://github.com/user-attachments/assets/a737e059-5295-4e3a-82a2-3bc4dd244ac0" />

15. **nano**  
    Membuka text editor berbasis terminal untuk membuat atau mengedit file.  
    > Contoh: `nano file.txt` → membuka atau membuat file.txt di editor nano.
<img width="725" height="512" alt="Screenshot 2025-09-15 185037" src="https://github.com/user-attachments/assets/176cf3ec-2524-4fd1-a010-c133b8953567" />

16. **cat**  
   Menampilkan isi file.
<img width="726" height="506" alt="Screenshot 2025-09-15 185104" src="https://github.com/user-attachments/assets/5562a26d-e625-4ef5-a3ee-5d4a36ff0c56" />

17. **rm**  
    Menghapus file atau direktori.
<img width="734" height="504" alt="Screenshot 2025-09-15 185156" src="https://github.com/user-attachments/assets/bc470122-1a42-46d7-aa4f-a1f8337068dd" />

18. **cp**  
   Menyalin file atau direktori.
<img width="713" height="519" alt="Screenshot 2025-09-15 185439" src="https://github.com/user-attachments/assets/6d616c58-9b13-4cfc-93e9-59c88c69a25c" />

19. **mv**  
   Memindahkan atau mengganti nama file/direktori.
<img width="790" height="312" alt="Screenshot 2025-09-15 185706" src="https://github.com/user-attachments/assets/300deefd-b1ea-4fa4-b333-e59179742748" />

20. **rm -rf**
    
    Command ini digunakan untuk menghapus file maupun direktori **secara permanen** tanpa masuk     ke *trash* atau *recycle bin*.
<img width="759" height="255" alt="Screenshot 2025-09-15 185757" src="https://github.com/user-attachments/assets/199c3cb4-f720-47df-bc68-e40c55379b0a" />

21. **cd /home/student**
    
    Pindah ke /home/student (path absolut)
<img width="741" height="525" alt="Screenshot 2025-09-15 185935" src="https://github.com/user-attachments/assets/cb4c52f6-014a-4228-8e06-364f47e6144a" />

22. **pwd**  
   Menampilkan direktori kerja saat ini (print working directory).
<img width="749" height="513" alt="Screenshot 2025-09-15 190207" src="https://github.com/user-attachments/assets/d3dc2ede-cc4a-415d-9716-a6c00844e810" />

23. **clear**  
    Membersihkan tampilan terminal.
<img width="758" height="520" alt="Screenshot 2025-09-15 190430" src="https://github.com/user-attachments/assets/cee41163-cb36-49ab-9bb5-bc65e4c14d1e" />

24. **passwd**  
    Mengubah password user. Jika dijalankan tanpa opsi, maka akan mengubah password user yang sedang login.  
    > Contoh:  
    > - `passwd` → mengganti password user aktif.  
    > - `sudo passwd username` → mengganti password user lain (butuh hak akses root).

<img width="690" height="416" alt="Screenshot 2025-09-15 190627" src="https://github.com/user-attachments/assets/740cf6b3-5052-48d4-89fc-eb5739278a5f" />

25. **date && uptime**  
    Menjalankan dua perintah sekaligus: menampilkan tanggal/waktu saat ini lalu menampilkan lama sistem berjalan.  
    > Contoh: `date && uptime`
<img width="718" height="527" alt="Screenshot 2025-09-15 190841" src="https://github.com/user-attachments/assets/274ccd8d-5605-4998-9342-eb68eb703c60" />

26. **date +%S**  
    Menampilkan detik saat ini (0–59) dari waktu sistem.  
    > Contoh: `date +%S`
<img width="723" height="514" alt="Screenshot 2025-09-15 191716" src="https://github.com/user-attachments/assets/9826d27b-cb09-4842-aae6-df4dc7d86afa" />

27. **date +%F**  
    Menampilkan tanggal dengan format standar (YYYY-MM-DD).  
    > Contoh: `date +%F` → `2025-09-15`
<img width="706" height="506" alt="Screenshot 2025-09-15 191809" src="https://github.com/user-attachments/assets/8e6d691e-29a1-428e-89af-c84a4e8dae0d" />

28. **ls -l**  
    Menampilkan daftar file/direktori dalam format panjang (long listing), termasuk permission, owner, group, ukuran, dan waktu modifikasi.  
    > Contoh: `ls -l`
<img width="729" height="521" alt="Screenshot 2025-09-15 192254" src="https://github.com/user-attachments/assets/7b2ac8ce-bc1a-4379-9496-3a851fdb0caf" />

29. **chmod 777**  
    Mengatur permission file menjadi full akses (read, write, execute) untuk **owner, group, dan others**.  
    > Contoh: `chmod 777 file.txt`
<img width="743" height="516" alt="Screenshot 2025-09-15 192602" src="https://github.com/user-attachments/assets/a08fa79b-dc70-40b3-92e6-2e4918334055" />

30. **chmod 444**  
    Mengatur permission file menjadi read-only untuk semua user.  
    > Contoh: `chmod 444 file.txt`
<img width="723" height="509" alt="Screenshot 2025-09-15 192643" src="https://github.com/user-attachments/assets/11f371c7-f189-4c86-a2fb-979c03723e99" />

31. **chmod 555**  
    Mengatur permission file menjadi read & execute (tanpa write) untuk semua user.  
    > Contoh: `chmod 555 script.sh`
<img width="733" height="515" alt="Screenshot 2025-09-15 192720" src="https://github.com/user-attachments/assets/582f6659-6130-45b2-b3a9-8e42cf959d65" />

32. **tail**  
    Menampilkan beberapa baris akhir dari file.
<img width="744" height="524" alt="Screenshot 2025-09-15 193245" src="https://github.com/user-attachments/assets/7ddd9db8-9d1c-44ff-b53f-b98380e4ac4e" />

33. **head**  
    Menampilkan beberapa baris awal dari file.
<img width="750" height="543" alt="Screenshot 2025-09-15 194317" src="https://github.com/user-attachments/assets/26a76530-b4a3-487f-89d6-de32bd10e4a0" />

34. **uname**  
    Menampilkan informasi sistem operasi.
<img width="741" height="509" alt="Screenshot 2025-09-15 194332" src="https://github.com/user-attachments/assets/d8ac48b5-6f8e-4bbc-801b-d62326d9fb06" />

35. **uname -a**  
    Menampilkan informasi lengkap tentang sistem operasi, termasuk kernel name, hostname, release, versi, dan arsitek
<img width="757" height="525" alt="Screenshot 2025-09-15 194401" src="https://github.com/user-attachments/assets/111b1aa3-2194-4bc5-b9bf-562399ddd85a" />

36. **cat file | grep 4**  
    Menampilkan isi file lalu memfilter hanya baris yang mengandung angka/teks "4".  
    - `cat file` → membaca isi file.  
    - `grep 4` → mencari baris yang mengandung karakter "4".  
    > Contoh: `cat data.txt | grep 4` → hanya menampilkan baris dalam *data.txt* yang ada angka 4.
<img width="765" height="544" alt="Screenshot 2025-09-15 194553" src="https://github.com/user-attachments/assets/a631f09d-0689-4dcf-b142-e54803d90f25" />

37. **ping 8.8.8.8**  
    Mengecek konektivitas jaringan ke server DNS publik Google (8.8.8.8). Perintah ini juga menampilkan waktu respon (latency) dari host tujuan.  
    > Contoh: `ping 8.8.8.8`  
    Tekan `Ctrl + C` untuk menghentikan proses ping.
<img width="734" height="584" alt="Screenshot 2025-09-15 194641" src="https://github.com/user-attachments/assets/96b43860-7305-4780-8ab5-29613b544686" />

38. **free**  
    Menampilkan informasi penggunaan memori (RAM dan swap) pada sistem. Biasanya digunakan untuk memantau ketersediaan memori.  
    > Contoh:  
    > - `free` → menampilkan dalam satuan kilobyte.  
    > - `free -m` → menampilkan dalam satuan megabyte.  
    > - `free -h` → menampilkan dengan format human-readable.
<img width="748" height="509" alt="Screenshot 2025-09-15 195208" src="https://github.com/user-attachments/assets/550a8fa7-90cb-481b-ae32-57079743d6d9" />

39. **top**  
    Menampilkan proses yang sedang berjalan (real time).
<img width="771" height="502" alt="Screenshot 2025-09-15 195241" src="https://github.com/user-attachments/assets/8900bced-81f7-478e-9fa0-905895d7bed5" />

40. **du**  
    Menampilkan ukuran file/direktori.
<img width="731" height="519" alt="Screenshot 2025-09-15 195348" src="https://github.com/user-attachments/assets/78c2efc2-815f-48cc-9f0d-6bc43ef0ba38" />

<img width="741" height="524" alt="Screenshot 2025-09-15 195441" src="https://github.com/user-attachments/assets/7b275619-fdd8-4bff-97c5-08446bcf0b98" />

<img width="732" height="523" alt="Screenshot 2025-09-15 195535" src="https://github.com/user-attachments/assets/092b2e06-67b4-4b9b-a4bc-cec572c7121e" />

<img width="745" height="522" alt="Screenshot 2025-09-15 195641" src="https://github.com/user-attachments/assets/fdd848c0-f544-4f85-9d38-358f0fea6285" />

<img width="746" height="526" alt="Screenshot 2025-09-15 200049" src="https://github.com/user-attachments/assets/d84f78ea-392e-4d22-b3ff-9e2ce0929e71" />

<img width="742" height="517" alt="Screenshot 2025-09-15 200212" src="https://github.com/user-attachments/assets/e1f7a00e-10dd-4dce-9c6c-3886d08baaac" />

<img width="745" height="508" alt="Screenshot 2025-09-15 200256" src="https://github.com/user-attachments/assets/d7f87fbc-987c-4c90-a41b-a0cd66bef317" />

<img width="721" height="521" alt="Screenshot 2025-09-15 200328" src="https://github.com/user-attachments/assets/b74d92b0-8992-4306-9ccb-91c43ba829d1" />

<img width="721" height="516" alt="Screenshot 2025-09-15 200633" src="https://github.com/user-attachments/assets/38c4037a-02c6-477e-8e63-8a54618296e1" />

<img width="751" height="517" alt="Screenshot 2025-09-15 200705" src="https://github.com/user-attachments/assets/24bb5aa7-7e37-4d3c-8990-2140d5ca80ac" />









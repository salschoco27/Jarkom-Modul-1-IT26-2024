# Laporan Resmi Jarkom-Modul-1-IT26-2024
**Salsabila Rahmah (5027231005)**

**Rafael Ega Krisaditya (5027231025)**

## Pegawai Negeri Sebelah
1. Pertama saya run port nya yaitu dengan ```ncat 10.15.42.60 53000``` lalu diminta untuk mencari pemilik password tersebut.
![Cuplikan layar 2024-09-18 125357](https://github.com/user-attachments/assets/76a97beb-f98d-47d9-b38f-493dc5a26ebe)

3. Saya mencari menggunakan ``` tcp contains "nNn" ``` dimana *nNn* merupakan 3 huruf pertama dari password yg dicari.
![Cuplikan layar 2024-09-18 125657](https://github.com/user-attachments/assets/3cca95db-195a-4783-960c-0b3e364c1f6c)

4. Saya gunakan Follow > TCP Stream untuk melihat data full nya. Lalu mencari jawaban dari pertanyaan-pertanyaan yg ada.
![Cuplikan layar 2024-09-18 125728](https://github.com/user-attachments/assets/826f7619-d5a3-4d28-b53a-296da6f4eb14)
![Cuplikan layar 2024-09-18 125357](https://github.com/user-attachments/assets/76a97beb-f98d-47d9-b38f-493dc5a26ebe)


## EZ
1. ketika saya melihat isi dari masing-masing file, ada pesan panjang dalam satu file ini dan saya menemukan pesannya adalah **jawabannya jawaban**
   dan ada port nya yaitu 1234
![Cuplikan layar 2024-09-18 131448](https://github.com/user-attachments/assets/45ade05c-d254-43cf-87f7-f8afc7043b22)
![Cuplikan layar 2024-09-18 131431](https://github.com/user-attachments/assets/b0e063fc-1c7d-47ba-9da8-e22911729696)
![Cuplikan layar 2024-09-18 131509](https://github.com/user-attachments/assets/cbda89e6-1b9d-4299-ac02-e31906d5d37f)

## Rizzset
1. Pertanyaan pertama adalah domain dari dns query. Lalu saya melihat bahwa ada banyak yg menggunakan www.its.ac.id pada list dibawah ini.
![Cuplikan layar 2024-09-18 214520](https://github.com/user-attachments/assets/4f6f203a-ffba-4e37-a862-eff79e9754bd)

3. Setelah itu terdapat pertanyaan IP yg digunakan dan setelah saya coba-coba, IP nya adalah ```103.94.189.5```
![Cuplikan layar 2024-09-18 214437](https://github.com/user-attachments/assets/588561c9-161d-43a1-a62b-05462bbea25b)
![Cuplikan layar 2024-09-18 220915](https://github.com/user-attachments/assets/37ec85d6-21a4-4cc8-9dd5-5cf715bf5a9d)

4. Ditanyakan JARM finger nya dan saya menggunakan python untuk mencari JARM nya.
![Cuplikan layar 2024-09-18 222104](https://github.com/user-attachments/assets/cb859e14-9244-405b-b7bc-4e8df40b68de)
![Cuplikan layar 2024-09-18 222202](https://github.com/user-attachments/assets/a8750a5b-53a5-46d6-88e9-dfc67c414c19)
![Cuplikan layar 2024-09-18 222236](https://github.com/user-attachments/assets/f87d4371-08c7-4b08-8d07-e187857f42fb)

Dan ditemukan JARM fingerprintn nya
![Cuplikan layar 2024-09-18 222328](https://github.com/user-attachments/assets/d87d85c6-1a03-4807-8eda-cf24159a27de)
![Cuplikan layar 2024-09-18 222342](https://github.com/user-attachments/assets/05289e2e-387c-4f1e-9b9a-718c0fe06252)

## Gajah Terbang Server
1. Diminta untuk mencari DBMS yang digunakan.
![image](https://github.com/user-attachments/assets/6852a909-c61a-4cd7-a879-8cc2bfa42246)

2. Terlihat bahwa ada PGSQL atau PostgreSQL
![image](https://github.com/user-attachments/assets/91820317-6ed9-4861-8e92-20f3a9d590fa)

3. Ditanyakan port yg digunakan
![image](https://github.com/user-attachments/assets/aca896f5-2835-4695-a447-59de12a3d7eb)
![image](https://github.com/user-attachments/assets/43c1960b-5cd3-437d-b7c8-f608b898045c)
![image](https://github.com/user-attachments/assets/5fe63f4e-07a7-44c5-8a3b-631e06ab8668)

4. OS & credentials apa yg digunakan?
![image](https://github.com/user-attachments/assets/3b21d4e0-028d-46a1-9d06-c457d551069a)
![image](https://github.com/user-attachments/assets/34dfdb0f-37bd-4a1e-9b38-11f8ad18448c)

5. password crack
![image](https://github.com/user-attachments/assets/5295c9fd-0652-4c4b-9066-2fab06b4cfc1)
![image](https://github.com/user-attachments/assets/309ea24a-a2cc-4bd4-ad00-42d693bede09)


## Gajah Terbang Attacker
*Lanjutan dari Gajah Terbang Server*
![image](https://github.com/user-attachments/assets/b67a20dd-ea60-46d1-be11-2c65dd3193d2)
![Cuplikan layar 2024-09-18 235911](https://github.com/user-attachments/assets/847841c9-bbe9-4714-aeb0-d84b9339f452)

Jawaban diambil dari analisa data yang ada pada gambar pertama
![Cuplikan layar 2024-09-19 000547](https://github.com/user-attachments/assets/fcc36c00-8858-4c93-b655-8059c9cebfb4)

## Advance Sanity Check
![image](https://github.com/user-attachments/assets/32db71d0-006c-410d-b614-0b68486a3ebb)
1. Saya menggunakan `frame contains "username"` untuk display filter agar bisa mengetahui nama pengirim
![Screenshot 2024-09-19 000158](https://github.com/user-attachments/assets/519c8ad4-10d0-4987-adc2-f31a546baabb)

2. Untuk mengetahui file yang dikirim saya menggunakan `frame contains "upload"`
![Screenshot 2024-09-19 000454](https://github.com/user-attachments/assets/1ee5a92b-b80a-4249-829c-af0287d6b81f)

3. Dari petunjuk di stream follow, saya diminta mengecek peraturan soal shift jarkom yang berada di canva
![Screenshot 2024-09-19 000519](https://github.com/user-attachments/assets/fc3dd2cb-3b06-4e3c-9d6c-c1889ba2c732)

4. Dari canva saya mendapatkan pesan rahasia yang harus di decode dengan base64 terlebih dahulu
![Screenshot 2024-09-19 001145](https://github.com/user-attachments/assets/7bccada7-5b8d-4d6c-a968-51fbb3b2e51d)


## Illegal Breakthrough
![Screenshot 2024-09-19 002115](https://github.com/user-attachments/assets/047539c9-037b-487d-bd1c-32636fba895c)
Karena semua attempt gagal selalu mengembalikan pesan Not Found, maka saya scroll ke bagian paling bawah di mana saya menemui pesan Found yang berarti Login Berhasil dari sana saya mendapatkan informasi untuk IP, Port, Endpoint, Tools, dan kredensial yang digunakan untuk login
![Screenshot 2024-09-19 002254](https://github.com/user-attachments/assets/edca712e-ee7f-4d1a-8a12-1c09fa05cbe9)


## Packets Barrage
![Screenshot 2024-09-19 002741](https://github.com/user-attachments/assets/e7e5a406-78c9-471d-b433-124c21c570e0)

1. Dengan display filter saya menemui ada 1918 kali percobaan untuk login dengan percobaan terakhir yang berhasil menyisakan 1917 percobaan
![Screenshot 2024-09-19 002625](https://github.com/user-attachments/assets/3592b96e-4eb7-466c-a0df-ddced161f67b)

2. Dari percobaan terakhir yang berhasil nama file dan pesan rahasia yang dikirm ada di bagian paling bawah dari stream
![Screenshot 2024-09-19 002648](https://github.com/user-attachments/assets/73c06544-0717-4c79-a37a-bc9a13e8c460)


## FTP Login
![Screenshot 2024-09-19 003559](https://github.com/user-attachments/assets/ef74a335-a8a0-469b-b09b-b7e0b6bcb448)

Dengan display filter saya mencari upaya login berhasil yang mengandung kata "success" dari sana dapat diketahui kredensial yang digunakan untuk login
![Screenshot 2024-09-19 003500](https://github.com/user-attachments/assets/6783a398-80de-41db-9699-a0c5ec10a4c7)
![Screenshot 2024-09-19 003515](https://github.com/user-attachments/assets/525bc0b9-08b6-4876-9b07-c2df3d9e7ad2)


## Surprise
![Screenshot 2024-09-19 004048](https://github.com/user-attachments/assets/3642f17d-2b54-4145-aa61-aff103a86471)

1. Pada stream yang sama dengan soal sebelumnya, saya mendapatkan informasi tentang service yang digunakan dan file yang dikirim attacker
![Screenshot 2024-09-19 004142](https://github.com/user-attachments/assets/c662619c-27e0-4483-9a5d-a92c12aac3ff)

2. Kemudian saya mengeksport file tersebut dan membukanya di visual studio code untuk menjalankan program dan menemukan pesan rahasianya
![Screenshot 2024-09-19 003834](https://github.com/user-attachments/assets/9b5306c4-a2b0-45b3-883b-2bad661c0980)
![Screenshot 2024-09-19 003955](https://github.com/user-attachments/assets/1b240710-7711-4211-8a85-33acc5950409)


## Corporate Breach
![Screenshot 2024-09-19 004611](https://github.com/user-attachments/assets/77489707-7b5a-416f-be96-9f1f4d1b1d2e)

1. Dari TCP Stream pertama saya sudah mendapatkan nama penyerangnya
![Screenshot 2024-09-19 004413](https://github.com/user-attachments/assets/5d45fa10-a74d-41c4-b777-1fd9c0a33bf2)

2. Kemudian saya menggunakan display filter untuk setiap paket yang mengandung suffix gmail dan menemui kejanggalan dari sebuah paket dengan panjang 108 di antara banyak paket yang hanya 90an panjangnya, dari paket tersebut saya mendapatkan kredensial yang digunakan untuk login
![Screenshot 2024-09-19 004506](https://github.com/user-attachments/assets/88364e2b-3920-481a-bc06-d91a1ea4b2f5)
![Screenshot 2024-09-19 004529](https://github.com/user-attachments/assets/31f50028-39fb-4e91-b72e-8cd0ca901373)

## 22 Nightmare
1. Filter dengan format *.jpg* untuk mencari file yang dikirim.
![image](https://github.com/user-attachments/assets/24b1aab1-0ac7-407b-81fd-a93982766042)
![image](https://github.com/user-attachments/assets/ffa6a822-20df-4396-8a73-9135c1eb50f2)

2. Export object untuk mengetahui isi dari file yg dikirim
![image](https://github.com/user-attachments/assets/c0920fe4-e40e-4c96-a108-a279cb3b662c)
![image](https://github.com/user-attachments/assets/05b1c66a-b7ec-4146-9b97-746bb95409a3)

3. Mencari nama pengirim dalam file noko.py dan menggunakan metode XOR 
   ![image](https://github.com/user-attachments/assets/f22ddb47-a5de-4004-b4d0-a27b899c1f5b)
   ![image](https://github.com/user-attachments/assets/0643a535-d89c-43a9-a026-5904d6a41ceb)








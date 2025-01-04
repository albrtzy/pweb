# Digital Sign - Instalation and Deploy
## 1. Clone Repository
Langkah pertama yaitu nge clone repository kami. Clone dapat dilakukan di terminal anda. Berikut adalah link nya :
```
git clone https://github.com/aryarexsa/pweb.git
```
## 2. Install  Dependencies
Projek kita menggunakan Node.js dan npm untuk mengelola dependensi, apabila anda belum menginstal di komputer anda berikut adalah link untul menginstall Node.js nya :
```
https://nodejs.org/en
```
Setelah install jalankan perintah berikut untuk menginstall semua dependensi yang diperlukan oleh aplikasi:
```
npm install
```
Perintah diatas digunakan untuk mengunduh dan menginstal semua dependensi yang ada dalam file package.json.
```
npm start
```
setelah npm instal, anda di anjurkan ke npm start
## 3. Jalankan Aplikasi 
Setelah semua dependensi terinstall, Anda dapat menjalankan aplikasi diterminal dengan perintah berikut:
```
nodemon app.js
```
## 4. Install MongoDB
Anda dapat menginstal aplikasi mongodb di browser anda. berikut link dibawah ini:
```
https://www.mongodb.com/lp/cloud/atlas/try4-reg?utm_source=google&utm_campaign=search_gs_pl_evergreen_atlas_core_prosp-brand_gic-null_apac-id_ps-all_desktop_eng_lead&utm_term=mongodb&utm_medium=cpc_paid_search&utm_ad=e&utm_ad_campaign_id=12212624350&adgroup=115749709863&cq_cmp=12212624350&gad_source=1&gclid=CjwKCAiA1eO7BhATEiwAm0Ee-C-cfSaArQxNkcm9OhOng-xoFWHiBE5odIuAb7xQiupKUhS7fyZwkBoCjtIQAvD_BwE
```
Aplikasi akan berjalan di http://localhost:3000 secara default. Anda dapat membuka aplikasi di browser dengan mengunjungi URL tersebut.
## 5. Struktur Projek Kami

## 6. Deploy ke Onrender
Apabila anda belum memiliki akun onrender, anda harus daftar di <a href="https://render.com/">OnRender</a>
### 6.1 Buat New Web Service di OnRender
1.Login ke akun OnRender.

2.Pilih New Web Service.

3.Pilih Deploy from GitHub.

4.Hubungkan akun GitHub Anda dengan OnRender jika belum terhubung.

5.Pilih repositori "fpweb".
### 6.2 Konfigurasi Deployment
Build Command: Biarkan saja kosongan biar Render mendeteksi secara otomatis.
Start Command: Gunakan perintah dibawah ini untuk menjalankan aplikasi:
```
npm start
```
### 6.3 Pilih Region dan Deploy
Pilih region terdekat untuk performa optimal.

Tekan tombol "Create Web Service" untuk memulai proses deploynya.
### 6.4 Gunakan Aplikasi yg sudah di deploy
Setelah selesai deploy, OnRender akan memberikan URL untuk aplikasi dan anda dapat mengakses aplikasi tersebut
## 7. Menggunakan Postman untuk Menguji API
File hasil export Postman telah tersedia di dalam repositori GitHub. Anda dapat menggunakannya untuk menguji endpoint API yang ada. Berikut adalah langkah-langkahnya pengerjaannya:
#### 1 Download dan Install Postman
Jika anda belum mengunduh postman, anda dapat mengunduh di link berikut <a href="https://www.postman.com/downloads/">Website Postman</a>
#### 2 Import Collection Postman
Buka Postman dan pilih menu "Import".

Pilih file export Postman yang tersedia di dalam repositori ....
#### 3 Gunakan Collection untuk Menguji API
1.Setelah di-import, Anda akan melihat daftar endpoint yang sudah dikonfigurasi.

2.Sesuaikan variabel lingkungan (base URL, token, atau lainnya) sesuai dengan aplikasi Anda.

3.Klik salah satu endpoint, sesuaikan parameter jika diperlukan, lalu tekan tombol Send untuk mengirimkan permintaan ke server.
## 8.Aplikasi yang kami gunakan
Node.js: Untuk server-side scripting.

Express.js: Framework untuk membangun server.

MongoDB: Database untuk menyimpan data.

EJS: Template engine untuk rendering halaman HTML.
## 9.Troubleshooting
1.Apabila mengalami kendala dalam hal" diatas dapat diperhatikan dibawah ini: 

2.Pastikan semua dependensi sudah terinstall.

3.Periksa kembali konfigurasi database Anda.

4.Periksa log aplikasi di terminal atau dashboard OnRender.

5.Kunjungi bagian Issues di repositori GitHub untuk mencari solusi atau membuka issue baru.


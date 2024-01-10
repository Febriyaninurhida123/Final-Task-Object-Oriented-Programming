<h1>Final Project: Ujian Akhir Semester</h1>

```bash
Kelompok 2      : - Akram Farasanto  (312210222)
                  - Febriyani Nurhida  (312210222)      
                  - Thoriq Azhar Fauzan (312210107)
                  - Kumara Davin Valerian (312210192)

Judul Project   : Sistem Polling Online
Kelas           : TI. 22. A2
Mata Kuliah     : Object Oriented Programming
Dosen Pengampu  : Dr. Ir. Ananto Tri Sasongko, M.Sc.,
# Polling Online

Polling Online adalah aplikasi web yang dibangun dengan Django, memungkinkan pengguna untuk melakukan vote/polling secara online

## Fitur 

- **Tampilan utama Home:** pilih polling yang tersedia
- **Tampilan Vote:** Pengguna dapat melakukan polling dan menyimpan suaranya.
- **View Result:** User dapat melihat jumlah polling sementara


## Teknologi yang Digunakan

- **Django:** Kerangka web yang digunakan untuk membangun aplikasi.
    - File `settings.py` yang telah disediakan berisi konfigurasi dasar untuk proyek Django.
    - File `__init__.py`  adalah file khusus dalam direktori atau package Python yang menandakan bahwa direktori tersebut adalah sebuah package.
    - File `manage.py` adalah skrip Python yang digunakan untuk menjalankan berbagai tugas administratif dan perintah manajemen dalam proyek Django


- **Database:** ( database yang digunakan SQLite).


## Installation

1. Clone repository:

   ```bash
  
   ```

2. Jalankan development server:

   ```bash
   python manage.py runserver
   ```

5. Akses aplikasi di ` http://127.0.0.1:8000/` di web browser anda.

==================================================================

# Online Polling

## Daftar Isi <br>

| No  | Description             | Link                                                    |
| --- | ----------------------- | ------------------------------------------------------- |
| 1   | Introduction            | [Click Here](#introduction)                             |
| 2   | Fitur-Fitur Website     | [Click Here](#website-ini-memiliki-fitur-fitur-berikut) |
| 3   | Which Is Use            | [Click Here](#which-is-used)                            |
| 4   | How To Run This Project | [Click Here](#how-to-run-this-project)                  |

### Introduction
**Website Online Polling adalah sebuah sistem untuk melakukan vote atau polling yang juga bisa di kelola oleh admin.** Dengan online voting diharap bisa mempermudah kegiatan polling atau voting.


Website Online Polling yang dibuat dengan **Python**, **Django**, dan **sqlite** memiliki beberapa kelebihan, yaitu :
> Tampilan website yang mudah dipahami

> Fleksibilitas polling

> Lebih cepat dan efisien

> Interaktif 


Website ini menggunakan database **db.sqlite3** yaitu sebuah file database yang umumnya digunakan oleh aplikasi berbasis Python yang menggunakan SQLite sebagai sistem manajemen basis data (DBMS). SQLite adalah library C yang memberikan fungsi lengkap sebuah basis data SQL tanpa memerlukan server terpisah dan pengaturan konfigurasi yang kompleks. SQLite adalah DBMS self-contained yang dapat digunakan dengan mudah dan ringan. Dalam konteks Django sebuah framework web Python, **db.sqlite3** biasanya muncul sebagai file database default ketika kita membuat proyek baru. Django menggunakan SQLite sebagai database default karena kemudahan konfigurasi dan kecocokan dengan banyak proyek kecil hingga menengah. 


### Website ini memiliki fitur-fitur berikut:

> **Admin**

- admin dapat melakukan login untuk mengakses sistem.

- Admin dapat mengelola pertanyaan.

- Admin dapat memperbarui, melihat, menyetujui, menolak, menghapus dan mengelola pertanyaan.

- Admin dapat membuat, melihat, dan menghapus polling.


### Which Is Used

1. **Django**
   
   Django adalah sebuah framework web berbasis Python yang dirancang untuk mempermudah pengembangan aplikasi web. Django menyediakan sejumlah alat dan fitur bawaan untuk mempercepat pembuatan aplikasi web dengan
   menyederhanakan tugas-tugas umum.

   Dalam sistem OnlineQuiz, Django digunakan untuk membuat struktur aplikasi web, membuat model database dan mempermudah penggunaan aplikasi web.


2. **Python**

    Python adalah bahasa pemrograman tingkat tinggi yang sangat populer, dirancang untuk menyediakan sintaksis yang jelas dan mudah dibaca. Dalam sistem OnlineQuiz, Python digunakan sebagai bahasa pemrograman utama untuk membuat aplikasi web.


3. **SQLite**
   
   
   SQLite adalah sistem manajemen basis data (DBMS) yang bersifat serverless, self-contained, dan bersifat transaksional. Ini berarti SQLite tidak memerlukan server terpisah untuk mengelola basis data, dan seluruh basis
   data disimpan dalam satu file tunggal yang dapat diakses langsung dari program aplikasi.

   Dalam sistem OnlineQuiz, SQLite digunakan sebagai database untuk menyimpan data pengguna, jumlah course/exam, jumlah pertanyaaan, dan data nilai siswa.


4. **VSCode**


   Untuk mengedit code, kami menggunakan Visual Studio Code (VSCode). Visual Studio Code (VSCode) adalah editor kode sumber sumber terbuka dan ringan yang dikembangkan oleh Microsoft. Visual Studio Code sering digunakan oleh para pengembang perangkat lunak untuk proyek-proyek pengembangan perangkat lunak, pemrograman web, dan pengembangan aplikasi lintas platform. Kelebihan dalam ekstensibilitas dan ekosistem ekstensi yang kaya menjadikannya pilihan populer di komunitas pengembangan perangkat lunak.




### How To Run This Project?

1. **Instalasi Python**

- Unduh Python dari situs resminya : https://www.python.org/downloads/

- Saat instalasi, pastikan untuk memberi centang pada kotak "Add Python to PATH". Ini akan memudahkan kita dalam menjalankan Python melalui perintah di terminal.

3. **Mengunduh dan menyiapkan project**
   ```
   https://github.com/syifaaurellia/OnlineQuiz.git
   ```

- Silahkan clone repository di atas atau download ZIP, kemudian extract file ZIP tersebut ke sebuah folder.

4. **Install dependencies**

- Buka terminal atau command prompt anda. (Jangan lupa untuk masuk ke folder yang kita extract sebelumnya)

- Ketik perintah berikut untuk menginstall dependencies :

```
pip install -r requirements.txt
```
   
5. **Jalankan migrasi database**

```
python manage.py migrate
```

6. **Membuat superuser**

```
python manage.py createsuperuser
```

- Pada bagian ini kita akan diarahkan untuk membuat username, mengisi akun email dan membuat password untuk akun kita di web nanti ketika sudah berhasil di run.

7. **Jalankan server**

```
python manage.py runserver
```

8. **Mengakses project di browser**

- Buka browser di pc anda (Chrome, Firefox, Edge dan lain-lain)

- Masukkan alamat berikut pada address bar browser :

  http://127.0.0.1:8000/

- Setelah itu web tampilan project django sudah berjalan dan tampil pada browser anda.


## Semoga Bermanfaat, Terima Kasih 












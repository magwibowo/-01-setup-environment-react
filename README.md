**LAPORAN PRAKTIKUM** <br>

==========<br>

NPM     : 2440107027001<br>
NAMA    : M. AGUNG WIBOWO<br>
KELAS   : TI - 4K RPL<br>

==========<br>

**1. Praktikum 1 : Menyiapkan Lingkungan Pengembangan** <br>
**a. Jelaskan kegunaan masing-masing dari Git, VS Code dan NodeJS yang telah Anda install pada sesi praktikum ini!** <br>

_Jawaban :_ <br>
Git berfungsi sebagai wadah penyimpanan setiap _project_, sehingga bisa diakses oleh orang lain ataupun grup dalam melakukan Kerjasama dalam mengerjakan _project_, agar memudahkan kolaborasi.<br>
Visual Studio Code sebagai text editor untuk mengerjakan _project_ yang dapat di-_install plugin_ atau ekstensi untuk memudahkan proses pengerjaan project.<br>
NodeJs sebagai _runtime environment_ untuk menjalankan kode Javascript, dan bisa juga berfungsi untuk membangun _backend_ seperti _server_ web, API, dan layanan _real-time_ lainnya.<br>

**b.	Buktikan dengan screenshoot yang menunjukkan bahwa masing-masing tools tersebut telah berhasil terinstall di perangkat Anda!**  <br>
_Jawaban :_  <br>
![image](https://github.com/user-attachments/assets/6a189c1e-0147-4793-8702-3cc196cc0505) <br>
Pada gambar diatas, terdapat informasi versi Git 2.47.1, versi vscode 1.96.4, versi nodejs v22.13.1 dan versi npm 10.9.2 yang semuanya sudah terinstall pada device saya.<br>

**2.	Praktikum 2 : Membuat Proyek Pertama React Menggunakan Next.js**  <br>
**a.	Pada Langkah ke-2, setelah membuat proyek baru menggunakan Next.js, terdapat beberapa istilah yang muncul. Jelaskan istilah tersebut, TypeScript, ESLint, Tailwind CSS, App Router, Import alias dan Turbopack!**  <br>
_Jawaban :_  <br>
-TypeScript adalah bahasa pemrograman yang merupakan superset dari JavaScript. Ini menambahkan fitur static typing (penulisan tipe data) ke JavaScript, membantu mendeteksi error lebih awal dan membuat code lebih mudah dimaintain.<br>
-ESLint adalah tools untuk analisis kode statis yang membantu menemukan dan memperbaiki masalah dalam kode JavaScript/TypeScript.<br>
-Tailwind CSS adalah framework CSS yang memungkinkan untuk membangun desain dengan menggabungkan class-class utilitas langsung dalam HTML. <br>
-App Router adalah fitur baru di Next.js 13+ yang menggunakan pendekatan file-system based routing dengan konvensi folder. <br>
-Import alias adalah cara untuk membuat shortcut dalam import path. <br>
-Turbopack adalah bundler JavaScript yang diklaim 10x lebih cepat dari Webpack<br>

**b.	Apa saja kegunaan folder dan file yang ada pada struktur proyek React yang tampil pada gambar pada tahap percobaan ke-3!**  <br>
_Jawaban :_  <br>

| **Nama Folder/File**        | **Keterangan**                                      |
|----------------------------|---------------------------------------------------|
| `/hello-world`             | Root folder proyek                                |
| `/next`                    | Folder yang berisi file-file build Next.js       |
| `/node_modules`            | Berisi semua package/dependencies yang diinstal  |
| `/public`                  | Folder untuk menyimpan asset statis              |
| `/src/app`                 | Folder utama aplikasi yang menggunakan App Router Next.js |
| `file.svg`                 | Asset SVG untuk icon file                        |
| `globe.svg`                | Asset SVG untuk icon globe/dunia                 |
| `next.svg`                 | Logo Next.js                                     |
| `vercel.svg`               | Logo Vercel                                      |
| `window.svg`               | Asset SVG untuk icon window                      |
| `.gitignore`               | Mengatur file/folder yang tidak perlu di-track Git |
| `eslint.config.mjs`        | Konfigurasi ESLint untuk linting kode            |
| `next-env.d.ts`            | Deklarasi tipe TypeScript untuk Next.js          |
| `next.config.ts`           | Konfigurasi Next.js                              |
| `package-lock.json`        | Lock file untuk versi dependencies npm           |
| `package.json`             | Manifest proyek & daftar dependencies           |
| `postcss.config.mjs`       | Konfigurasi PostCSS (digunakan Tailwind)         |
| `tailwind.config.ts`       | Konfigurasi Tailwind CSS                         |
| `tsconfig.json`            | Konfigurasi TypeScript                           |
| `favicon.ico`              | Icon website yang muncul di tab browser         |
| `globals.css`              | CSS global aplikasi                             |
| `layout.tsx`               | Layout utama aplikasi Next.js                   |
| `page.tsx`                 | Halaman utama/root aplikasi                     |

**c.	Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan!**  <br>
_Jawaban :_  <br>
Proses create project :   <br>
![image](https://github.com/user-attachments/assets/de67787d-4c8d-4a41-a494-a6c50672994d) <br>
Running : <br>
![image](https://github.com/user-attachments/assets/c4178b1b-466f-4441-801d-faec2e845be9) <br>
Hasil : <br>
![image](https://github.com/user-attachments/assets/9b83556e-e808-4672-b1b1-4ce7e95e0a74) <br>


**3.	Praktikum 3 : Menambahkan Komponen React (Button)**  <br>
**a.	Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan!**  <br>
_Jawaban :_  <br>

Create : <br>
![image](https://github.com/user-attachments/assets/8489d3b7-fb23-4f51-9aa8-b505d92d2387) <br>
![image](https://github.com/user-attachments/assets/ae2cb53d-557d-4740-b8fb-c3023bcd7a0f) <br>
![image](https://github.com/user-attachments/assets/0b52ec9a-76b7-4b65-b7be-27ddd3864e86) <br>

**4.	Praktikum 4 : Menulis Markup dengan JSX  <br>
a.	Untuk apakah kegunaan sintaks user.imageUrl?**  <br>
_Jawaban :_  <br>
untuk mengakses properti imageUrl pada sebuah objek user  <br>

**b.	Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan!**  <br>
_Jawaban :_  <br>
![image](https://github.com/user-attachments/assets/492379d0-bd47-4a3d-989c-7cdb30e8eb2f) <br>
![image](https://github.com/user-attachments/assets/92b25668-5d47-4ae8-9fd0-dd5dcb61a2f1) <br>
![image](https://github.com/user-attachments/assets/db1577d7-3894-42e3-895d-8079a9cb982c) <br>







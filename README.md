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
![image](https://github.com/user-attachments/assets/6fab8e3d-a7fe-4a9d-8f44-bd212870c39b)<br>
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
![image](https://github.com/user-attachments/assets/58543ba7-acfc-455b-b865-5212272cf948) <br>
Running : <br>
![image](https://github.com/user-attachments/assets/346f6400-f779-4907-b3e5-06618d1dcfde) <br>
Hasil : <br>
![image](https://github.com/user-attachments/assets/0c1e649c-ce1f-4ea2-b0a0-d252de8004c9) <br>


**3.	Praktikum 3 : Menambahkan Komponen React (Button)**  <br>
**a.	Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan!**  <br>
_Jawaban :_  <br>

Create : <br>
![image](https://github.com/user-attachments/assets/8163e877-e6bc-47d0-a529-0a4c9102a38d)
 <br>
![image](https://github.com/user-attachments/assets/a88a1054-2e77-4fb8-a0b1-14d380f238a3)
 <br>
![image](https://github.com/user-attachments/assets/23c2135d-80af-4725-87d9-96dc198cd291)
 <br>

**4.	Praktikum 4 : Menulis Markup dengan JSX  <br>
a.	Untuk apakah kegunaan sintaks user.imageUrl?**  <br>
_Jawaban :_  <br>
untuk mengakses properti imageUrl pada sebuah objek user  <br>

**b.	Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan!**  <br>
_Jawaban :_  <br>
![image](https://github.com/user-attachments/assets/5c4b8415-127e-488b-98c1-0ab609169b98)
 <br>
![image](https://github.com/user-attachments/assets/3dba36c9-aaaf-4615-9d14-641a51593283)
 <br>
![image](https://github.com/user-attachments/assets/610d6dbf-1aa8-4648-aaa8-0422d6c079f1)
 <br>







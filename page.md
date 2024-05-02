# Page

### ADMIN

**`/perguruan-tinggi`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/)
2. Masuk ke dalam menu dashboard&#x20;
3. Pilih navigasi admin (DIKTI),
4. Pilih opsi Perguruan Tinggi pada dropdown

`[PERMISSION]`&#x20;

perguruan-tinggi-menu

`[REDIRECT]`&#x20;

/perguruan-tinggi/{pt} (Detail Perguruan Tinggi)



**`2./perguruan-tinggi/{pt}`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/)
2. Masuk ke dalam menu dashboard&#x20;
3. Pilih navigasi admin (DIKTI),
4. Pilih opsi Perguruan Tinggi pada dropdown
5. Pilih Perguruan Tinggi yang dituju

`[PERMISSION]`&#x20;

perguruan-tinggi.show-menu

`[REDIRECT]`&#x20;

/pengusul/{id\_proposal} (Detail Proposal)



3. **`/pendaftaran-pt`**&#x20;

`[CARA AKSES]`&#x20;

1. Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/)
2. Masuk ke dalam menu dashboard&#x20;
3. Pilih navigasi admin (DIKTI)
4. Pilih opsi Daftar Pengajuan Unit Pengelola pada dropdown

`[PERMISSION]`&#x20;

pendaftaran-pt-menu

`[REDIRECT]`&#x20;

/pendaftaran-pt/{pt}



`/pendaftaran-pt/{pt}`&#x20;

`[CARA AKSES]`&#x20;

1. Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/)
2. Masuk ke dalam menu dashboard&#x20;
3. Pilih navigasi admin (DIKTI)
4. Pilih opsi Daftar Pengajuan Unit Pengelola pada dropdown
5. Pilih Detail Pendaftaran Pengelola MF yang dituju dengan mengetuk ikon pencarian "searchbar".

`[PERMISSION]`&#x20;

pendaftaran-pt-show-menu

`[REDIRECT]`&#x20;

\-



**`/pengusul`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/)
2. Masuk ke dalam menu dashboard&#x20;
3. Pilih navigasi admin (DIKTI)
4. Pilih opsi ProposalMF2023 pada dropdown.

`[PERMISSION]`&#x20;

pengusul-menu

`[REDIRECT]`&#x20;

/pengusul/{id\_proposal},&#x20;



**`/pengusul/{id_proposal}`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/)
2. Masuk ke dalam menu dashboard&#x20;
3. Pilih navigasi admin (DIKTI)
4. Pilih opsi ProposalMF2023 pada dropdown.
5. Pilih proposal yang dituju

`[PERMISSION]`&#x20;

pengusul.show-menu

`[REDIRECT]`&#x20;

\-

\


**`/kontrak`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/)
2. Masuk ke dalam menu dashboard&#x20;
3. Pilih navigasi admin (DIKTI)
4. Pilih opsi KontrakMF2023 pada dropdown.

`[PERMISSION]`&#x20;

kontrak-menu

`[REDIRECT]`&#x20;

kontrak/{id\_kontrak}



**`/diksi-kontrak (skip dulu)`**

\[CARA AKSES] \


\[PERMISSION]&#x20;

diksi-kontrak-menu

\[REDIRECT]&#x20;



**`/kontrak/merge-dokumen-kontrak`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/)
2. Masuk ke dalam menu dashboard&#x20;
3. Pilih navigasi admin (DIKTI)
4. Pilih opsi Merge Dokumen Kontrak pada dropdown.

`[PERMISSION]`&#x20;

kontrak.merge-dokumen-kontrak

`[REDIRECT]`&#x20;

\-

\


**`/kontrak/{id_kontrak}`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Kontrak MF 2023 pada dropdown.
5. Pilih detail kontrak yang dituju dengan mengetuk ikon pencarian "searchbar".

`[PERMISSION]`&#x20;

kontrak.show-menu

`[REDIRECT]`&#x20;

\-



**`/kontrak/{kontrak_id}/upload/{kategori_berkas_id} (ini juga skip dulu)`**

`[CARA AKSES]`&#x20;



`[PERMISSION]`&#x20;

kontrak.show-menu

`[REDIRECT]`&#x20;

\


**`/kontrak/{kontrak_id}/verifikasi/{kategori_berkas_id}  (ini juga skip dulu)`**

`[CARA AKSES]`&#x20;



`[PERMISSION]`&#x20;

kontrak.show-menu

`[REDIRECT]`&#x20;

\


**`/kontrak/{kontrak_id}/preview/{kategori_berkas_id} (ini juga skip dulu)`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

kontrak.show-menu

`[REDIRECT]`&#x20;

\
\


`/mitra (On Going)`

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Mitra pada dropdown.

\


`[PERMISSION]`&#x20;

mitra-menu

`[REDIRECT]`&#x20;

\-

\


`/reviewer`

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi reviewer pada dropdown.

`[PERMISSION]`&#x20;

reviewer-menu

`[REDIRECT]`&#x20;

admin/reviewer/{id}



**`/reviewer/{id}`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Reviewer pada dropdown.
5. Pilih detail kontrak yang dituju dengan mengetuk ikon pencarian "searchbar".
6. Pilih opsi View pada menu ikon yang tercantum pada bagian Aksi.

`[PERMISSION]`&#x20;

reviewer-show-menu

`[REDIRECT]`&#x20;

admin/pegusul/{id\_proposal}



**`/user-management`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi User Management pada dropdown.

`[PERMISSION]`&#x20;

user-management-menu

`[REDIRECT]`&#x20;

\-



**`/manajemen-pengumuman`**

**\[CARA AKSES]**&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Manajemen Pengumuman pada dropdown.

`[PERMISSION]`&#x20;

Manajemen-pengumuman &#x20;

`[REDIRECT]`&#x20;

\-

\


**`/statistik (Skip dulu)`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Statistik pada dropdown.

`[PERMISSION]`&#x20;

akses-statistik

`[REDIRECT]`&#x20;

\-



**`/statistik-2024 (Skip dulu)`**

`[CARA AKSES]`&#x20;



`[PERMISSION]`&#x20;

akses-statistik-2024

`[REDIRECT]`&#x20;

\-



**`/monitoring`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Papan Monitoring VK pada dropdown.

`[PERMISSION]`&#x20;

\-

`[REDIRECT]`&#x20;

\-

\


`/pusatbantuan (Skip dulu)`

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Papan Monitoring VK pada dropdown.

`[PERMISSION]`&#x20;

\-

`[REDIRECT]`&#x20;

\-



**`/export`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Export pada dropdown.

`[PERMISSION]`&#x20;

export-document

`[REDIRECT]`&#x20;

\-



**`/seminar-hasil-2022-dikti`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Seminar Hasil DIKTI 2022 pada dropdown.

`[PERMISSION]`&#x20;

seminar-admin

`[REDIRECT]`&#x20;

/seminar-hasil-2022-dikti/{id\_proposal}

\


**`/seminar-hasil-2022-dikti/{id_proposal}`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Seminar Hasil DIKTI 2022 pada dropdown.
5. Pilih proposal yang dituju dengan mengetuk ikon pencarian "searchbar".

`[PERMISSION]`&#x20;

seminar-admin

`[REDIRECT]`&#x20;

\-



**`seminar-hasil-diksi/2022`**&#x20;

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKSI).
4. Pilih opsi Seminar Hasil DIKSI 2022 pada dropdown.

`[PERMISSION]`&#x20;

seminar-admin-diksi

`[REDIRECT]`&#x20;

/seminar-hasil-diksi/{fiscal\_year}/{id\_proposal}

\-

\


**`seminar-hasil-diksi/2023 (Skip Dulu)`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKSI).
4. Pilih opsi Seminar Hasil DIKSI 2023 pada dropdown.

`[PERMISSION]`&#x20;

seminar-admin-diksi

`[REDIRECT]`&#x20;

\-



**`/seminar-hasil-diksi/{fiscal_year}/{id_proposal}`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKSI).
4. Pilih opsi Seminar Hasil DIKSI 2023 pada dropdown.
5. Pilih proposal yang dituju dengan mengetuk ikon pencarian "searchbar".

`[PERMISSION]`&#x20;

seminar-admin-diksi

`[REDIRECT]`&#x20;

\-



**`/pencairan`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Daftar Pencairan pada dropdown.

`[PERMISSION]`&#x20;

pencairan-admin-index

`[REDIRECT]`&#x20;

/pencairan/{id}



**`/pencairan/{id}`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Daftar Pencairan pada dropdown.

\[PERMISSION]&#x20;

pencairan-admin-index

`[REDIRECT]`&#x20;

\-



**`/kontrak/{id_kontrak}/pencairan-tahap-2`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Kontrak PDP 2024 pada dropdown.
5. Pilih Kontrak yang dituju dengan mengetuk ikon pencarian "searchbar".

`[PERMISSION]`&#x20;

pencairan-tahap-2

`[REDIRECT]`&#x20;

\-



**`/kontrak/{pencairan_id}/unggah-berkas-tahap-2 (Skip Dulu)`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

\-

`[REDIRECT]`&#x20;

\-



`/kontrak/{pencairan_id}/tanda-tangan-berkas-tahap-2 (Skip Dulu)`

`[CARA AKSES]`&#x20;



`[PERMISSION]`&#x20;

\-

`[REDIRECT]`&#x20;

\-

\
\


**`/kontrak/{pencairan_id}/kelengkapan-berkas-tahap-2(Skip Dulu)`**

`[CARA AKSES]`&#x20;



`[PERMISSION]`&#x20;

\-

`[REDIRECT]`&#x20;

\-

\


**`/izin-impor`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Izin Import pada dropdown.

`[PERMISSION]`&#x20;

izin-impor

`[REDIRECT]`&#x20;

/izin-impor/buat, /izin-impor/{id\_izin\_impor},



**`/izin-impor/buat`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Izin Import pada dropdown.
5. Pilih button “Buat Pengajuan”

`[PERMISSION]`&#x20;

izin-impor

`[REDIRECT]`&#x20;





**`/izin-impor/{id_izin_impor}`**

`[CARA AKSES]`&#x20;

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Izin Import pada dropdown.
5. Pilih Daftar Pengajuan Izin Impor yang dituju dengan mengetuk ikon pencarian "searchbar".

`[PERMISSION]`&#x20;

izin-impor

`[REDIRECT]`&#x20;

\-



### ADMIN VOLUNTEER

**`/pengusul`**

`[CARA AKSES]`&#x20;



`[PERMISSION]`&#x20;

volunteer-pengusul-menu

`[REDIRECT]`&#x20;

\


**`/pengusul/{id_proposal}`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

volunteer-show-pengusul-menu

`[REDIRECT]`&#x20;



### REVIEWER

**`reviewer/`**

`[CARA AKSES]`&#x20;

1. Login sebagai reviewer ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).

`[PERMISSION]`&#x20;

index-tugas-menu

`[REDIRECT]`&#x20;

reviewer/evaluasi-proposal/{id-proposal}, reviewer/presentasi-proposal/{id-proposal},&#x20;

\


**`/tugas/{tugas}`**

`[CARA AKSES]`&#x20;



`[PERMISSION]`&#x20;

show-tugas-menu

`[REDIRECT]`&#x20;

\


**`/tugas-semhas/{fiscal_year}/{tugas}`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

show-tugas-menu

`[REDIRECT]`&#x20;

\


**`/tugas-monev-2023/{tugas}`**

`[CARA AKSES]`&#x20;



`[PERMISSION]`&#x20;

show-tugas-menu

`[REDIRECT]`&#x20;



**`/evaluasi-proposal/{tugas}`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

\-

`[REDIRECT]`&#x20;

\


**`/presentasi-proposal/{tugas}`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

\-

`[REDIRECT]`&#x20;

\-

**`/veka/{tugas}`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

\-

`[REDIRECT]`&#x20;

\-



### UNIT PENGELOLA

**`/pengusul`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

up-index-proposal-menu

`[REDIRECT]`&#x20;



**`/pengusul/{id_proposal}`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

up-show-proposal-menu

`[REDIRECT]`&#x20;



**`/kontrak`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

up-index-kontrak-menu

`[REDIRECT]`&#x20;



**`/kontrak/create`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

up-index-kontrak-menu

`[REDIRECT]`&#x20;



**`/kontrak/{id_kontrak}`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

up-show-kontrak-menu

`[REDIRECT]`&#x20;



**`/kontrak/{kontrak_id}/verifikasi/{kategori_berkas_id}`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

up-show-kontrak-menu

`[REDIRECT]`&#x20;

\
\


**`/izin-impor`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

up-izin-impor

`[REDIRECT]`&#x20;





**`/izin-impor/buat`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

up-izin-impor

`[REDIRECT]`&#x20;



**`/izin-impor/{id_izin_impor}`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

up-izin-impor

`[REDIRECT]`&#x20;

\
\


**`/laporan`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

\-

`[REDIRECT]`



### OPERATOR

**`/pendaftaran-pt`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

\-

`[REDIRECT]`&#x20;



**`/edit-pt`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

operator-daftar-up-menu

`[REDIRECT]`&#x20;



### FRONT OFFICE

**`status-proposal`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

system-status-proposal

`[REDIRECT]`&#x20;

\


**`status-proposal/{fund_id}`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

system-status-proposal

`[REDIRECT]`&#x20;



**`deskripsi-proposal`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

\-

`[REDIRECT]`&#x20;



**`deskripsi-proposal/`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

system-description-proposal

`[REDIRECT]`&#x20;



**`/{description_id}`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

system-description-proposal

`[REDIRECT]`&#x20;



### PENGUSUL

**`pengusul/`**

`[CARA AKSES]`

1. Login sebagai pengusul ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Izin Import pada dropdown.
5. Pilih Daftar Pengajuan Izin Impor yang dituju dengan mengetuk ikon pencarian "searchbar".

`[PERMISSION]`&#x20;

pengusul-dashboard

`[REDIRECT]`&#x20;

/pengusul/proposal/{id\_proposal

\


**`/proposal/{proposal}`**

`[CARA AKSES]`&#x20;

`[PERMISSION]`&#x20;

pengusul-show-proposal

`[REDIRECT]`&#x20;



**`/pengajuan-proposal`**

**`[CARA AKSES]`**&#x20;

**`[PERMISSION]`**&#x20;

pengusul-pengajuan

\[REDIRECT]&#x20;

\


**`/usulan/{id_proposal}`**

\[CARA AKSES]&#x20;

\[PERMISSION]&#x20;

pengusul-show-proposal

\[REDIRECT]

\


\


\


\


\


\
\


\


| Document Owner    | Dimas Ahmad, M. Hilmy, M. Zulkifli, Rian A.P, Husein Alhafiz                                             |
| ----------------- | -------------------------------------------------------------------------------------------------------- |
| Designer          | Novita Rahmadhani                                                                                        |
| Developers        | Ahmad Jalu F. N. H, Anreas Nugroho, Bintang Rahmatullah, Michael Mervin R, Reza Irvando, Umar Hadi Mukti |
| Quality Assurance | M. Fadly Febrian, M. Ibnu Al Hanif                                                                       |
| Delivery Date     | -                                                                                                        |
| Sign off Date     | -                                                                                                        |

#### Riwayat Revisi

| Author              | Revision Notes                                                           |
| ------------------- | ------------------------------------------------------------------------ |
| Andreas Nugroho     | Deploy commit Profil Mitra                                               |
| Andreas Nugroho     | Fitur Release Listing Mitra                                              |
| Umar Hadi Mukti     | Fitur Release Profil Mitra dan Listing Proposal                          |
| M. Reza Irvando     | Fitur Release Detail Inovator (sidebar dan daftar proposal)              |
| Michael Mervin R    | Fitur Release Show Jumlah Proposal dan Pendanaan diajukan dan ditetapkan |
| Bintang Rahmatullah | Fitur Release                                                            |
| Michael Mervin R    | Fitur Release                                                            |

#### Petunjuk Instalasi

**Laravel Project Setup Guide**

This guide will walk you through the steps required to set up a Laravel project on your local machine. Laravel is a popular PHP framework for building web applications.

Prerequisites\
Before you begin, make sure you have the following installed on your machine:\
\- required PHP v8.0 or greater\
\- required Composer v2.5.8 or greater\
\- required Node.js v18 (with npm or yarn) or greater\
\- required Git v2.34.1 or greater\
\- optional Docker v25.0.2 or greater

Getting Started

1\. Clone the repository

sh\
git clone "link repository

2\. Navigate to the project directory

sh\
cd "project directory"

3\. Install PHP dependencies using composer

sh\
cd composer install

4\. Copy .env.example to .env

sh\
cp .env.example .env

5\. Generate application key

sh\
php artisan key:generate

6\. Install javascript using npm or yarn

sh\
npm install\
or\
yarn install

7\. Compile assets

sh\
for local development\
npm run dev\
or\
yarn dev

8\. Setup your database configuration file. If your are using docker, you can skip this step.

sh\
DB\_CONNECTION=mysql\
DB\_HOST=127.0.0.1\
DB\_PORT=3306\
DB\_DATABASE=your\_database\_name\
DB\_USERNAME=your\_database\_username\
DB\_PASSWORD=your\_database\_password\


9\. Migrate the database

sh\
php artisan migrate

10\. Serve application

sh\
php artisan serve

Additional Configuration

\- Environment Configuration: Update the .env file as per your environment settings (e.g., APP\_DEBUG, APP\_URL, etc.).\
\- Database Configuration: Modify the database configuration in the .env file according to your requirements.\
\- Cache Configuration: You can configure caching options in the .env file.\
\- Queue Configuration: If your application uses queues, configure the queue driver in the .env file.\


Run Using Docker

For those of u who prefer using docker when serving the application, please follow these steps below:

1\. Follow the prior step until you are at step \[7]\(#7)\
2\. Start the docker container\


sh\
\# run usign docker\
docker compose up -d\
\# or using docker-compose\
docker-compose up -d\


3\. Migrate the database using sail

sh\
./sail artisan migrate

### 2. LATAR BELAKANG

Sebagai bagian dari kerangka kebijakan Merdeka Belajar Kampus Merdeka (MBKM), Kementerian Pendidikan, Kebudayaan, Riset dan Teknologi mengimplementasikan berbagai program untuk membangun ekosistem yang mendorong peningkatan mutu dan relevansi pendidikan tinggi di Indonesia. Termasuk diantaranya adalah penawaran berbagai program pendanaan berbasis kompetisi.

Berbagai data dan informasi di lapangan menunjukkan bahwa sejumlah penelitian yang diselenggarakan di perguruan tinggi telah menghasilkan luaran yang memiliki potensi untuk diterapkan sebagai solusi dari berbagai persoalan di masyarakat atau dikembangkan untuk komersialisasi yang dapat meningkatkan produktivitas dan daya saing nasional. Selain itu, sejumlah perguruan tinggi juga memiliki kepakaran yang mumpuni untuk menjawab berbagai persoalan yang dihadapi sektor swasta maupun Pemerintah yang pada gilirannya akan mendorong peningkatan kinerja dan daya saing nasional

### 3. TUJUAN

Tujuan utama Program Backoffice Kedaireka adalah untuk mendorong terjadinya kerjasama yang saling menguntungkan dan berkelanjutan antara dosen sebagai pihak pengusul dengan dengan mitra sesuai dengan deskripsi masing-masing skema.

### 4. AKTOR

| No | User Category                            | User Main Activity                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| -- | ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1  | Admin                                    | <p>• Mengakses seluruh fitur pengusul.show-menu<br>• Mengakses seluruh fitur pengusul-menu<br>• Mengakses seluruh fitur perguruan-tinggi.show-menu<br>• Mengakses seluruh fitur perguruan-tinggi-menu<br>• Mengakses seluruh fitur action-verifikasi<br>• Mengakses seluruh fitur action-revert-status-verifikasi<br>• Mengakses seluruh fitur kontrak.show-menu<br>• Mengakses seluruh fitur seminar-admin-dksi</p>                                                     |
| 2  | Pengusul                                 | <p>• Mengakses seluruh fitur pengusul-dashboard<br>• Mengakses seluruh fitur pengusul-pengajuan<br>• Mengakses seluruh fitur pengusul-show-proposal<br>• Mengakses seluruh fitur pengusul-ajukan-proposal</p>                                                                                                                                                                                                                                                            |
| 3  | Tim Reviewer                             | <p>• Mengakses seluruh fitur index-tugas-menu<br>• Mengakses seluruh fitur show-tugas-menu</p>                                                                                                                                                                                                                                                                                                                                                                           |
| 4  | Unit Pengelola (KUP) di Perguruan Tinggi | <p>• Mengakses seluruh fitur action-verifikasi<br>• Mengakses seluruh fitur action-revert-status-verifikasi<br>• Mengakses seluruh fitur index-tugas-menu<br>• Mengakses seluruh fitur show-tugas-menu<br>• Mengakses seluruh fitur up-index-proposal-menu<br>• Mengakses seluruh fitur up-show-proposal-menu<br>• Mengakses seluruh fitur up-index-kontrak-menu<br>• Mengakses seluruh fitur up-show-kontrak-menu<br>• Mengakses seluruh fitur up-verif-pra-kontrak</p> |

### 5. FITUR YANG DIKEMBANGKAN

| No   | Epic             | Feature                                                                                                                          |                                                                                                                                                            |
| ---- | ---------------- | -------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| User | Admin            |                                                                                                                                  |                                                                                                                                                            |
| 1    | Perguruan Tinggi | <p>Profiling oleh Admin<br>- Daftar Pengusul<br>- Daftar Industri<br>- Total Kolaborasi dengan Industri<br>- Total Pendanaan</p> | -                                                                                                                                                          |
| 2    | Mitra            | <p>Login<br>- Daftar Pengusul<br>- Daftar Proposal<br>- Status Pendanaan<br></p>                                                 | <p>Profiling oleh Admin<br>- Daftar Pengusul<br>- Daftar Proposal<br>- Daftar Mitra<br>- Total Kolaborasi dengan Perguruan Tinggi<br>- Total Pendanaan</p> |
| 3    | Pengusul         | <p>Login<br>- Daftar Proposal<br>- Status Pendanaan<br></p>                                                                      | <p>Profiling oleh Admin<br>- Daftar Proposal<br>- Status Pendanaan<br></p>                                                                                 |

### 6. DETAIL FITUR

#### 1. LISTING MITRA

**Informasi Singkat**

| Target Release    | 1.0                                                                                                   |
| ----------------- | ----------------------------------------------------------------------------------------------------- |
| Epic              | Pengusul                                                                                              |
| Short Explanation | Fitur yang digunakan oleh pengusul setelah login supaya dapat melihat Daftar Proposal yang diinginkan |
| Document Status   | Draft                                                                                                 |

\


#### REQUIREMENT

| No | User Story                                                                                             | Priority  | Notes                                                                                                                       |
| -- | ------------------------------------------------------------------------------------------------------ | --------- | --------------------------------------------------------------------------------------------------------------------------- |
| 1  | <p>As a Mitra<br>I Want Search category as user<br>So I Can search and acces every Mitra features</p>  | Must Have | <p>Form filter mitra sebagai berikut<br>1. Filter kategori Mitra*<br>2. Filter Bidang*<br>3. Filter Pengajuan Proposal*</p> |
| 2  | <p>As a Admin<br>I Want Search category as Admin<br>So I Can search and acces every Admin features</p> | Must Have | <p>Form filter mitra sebagai berikut<br>1. Filter kategori Mitra*<br>2. Filter Bidang*<br>3. Filter Pengajuan Proposal*</p> |

#### SCENARIO

| No | Scenario                                                                                                               | Type    | Description                                                               | Validation |
| -- | ---------------------------------------------------------------------------------------------------------------------- | ------- | ------------------------------------------------------------------------- | ---------- |
| 1  | <p>As a Mitra Ikomerz Ilmu Komputer IPB<br>I want login as mitra<br>So i can search and acces every mitra features</p> | Postive | Mitra Ikomerz Ilmu Komputer IPB mendapatkan hasil pencarian sesuai filter | content    |

#### USER INTERFACE & DESIGN

| Description | Login                    |
| ----------- | ------------------------ |
| Login Page  | Image                    |
| Link figma  | ini ceritanya link figma |
|             |                          |

#### 2. PROFIL MITRA dan LISTING PROPOSAL

**Informasi Singkat**

| Target Release    | 1.0                                                                                   |
| ----------------- | ------------------------------------------------------------------------------------- |
| Epic              | Mitra                                                                                 |
| Short Explanation | Fitur untuk user/mitra dapat melakukan pencarian berdasarkan kriteria yang diinginkan |
| Document Status   | Draft                                                                                 |

#### REQUIREMENT

| No | User Story                                                                                             | Priority  | Notes                                                                                                                       |
| -- | ------------------------------------------------------------------------------------------------------ | --------- | --------------------------------------------------------------------------------------------------------------------------- |
| 1  | <p>As a Mitra<br>I Want Search category as user<br>So I Can search and acces every Mitra features</p>  | Must Have | <p>Form filter mitra sebagai berikut<br>1. Filter kategori Mitra*<br>2. Filter Bidang*<br>3. Filter Pengajuan Proposal*</p> |
| 2  | <p>As a Admin<br>I Want Search category as Admin<br>So I Can search and acces every Admin features</p> | Must Have | <p>Form filter mitra sebagai berikut<br>1. Filter kategori Mitra*<br>2. Filter Bidang*<br>3. Filter Pengajuan Proposal*</p> |

#### SCENARIO

| No | Scenario                                                                                                               | Type    | Description                                                               | Validation |
| -- | ---------------------------------------------------------------------------------------------------------------------- | ------- | ------------------------------------------------------------------------- | ---------- |
| 1  | <p>As a Mitra Ikomerz Ilmu Komputer IPB<br>I want login as mitra<br>So i can search and acces every mitra features</p> | Postive | Mitra Ikomerz Ilmu Komputer IPB mendapatkan hasil pencarian sesuai filter | content    |

#### USER INTERFACE & DESIGN

| Description | Login                    |
| ----------- | ------------------------ |
| Login Page  | Image                    |
| Link figma  | ini ceritanya link figma |

\

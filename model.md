# Model

### TkaiUser

**`[Deskripsi]`**

**Berisi data user yang mendaftar didalam kedaireka**

`[`**`Struktur`**`]`

<table><thead><tr><th width="70">No</th><th width="127">Tipe Data</th><th width="113">Deskripsi</th><th>Nama Kolom</th></tr></thead><tbody><tr><td>1</td><td>user_id</td><td>integer</td><td>Berfungsi untuk memberikan id untUk user</td></tr><tr><td>2</td><td>email</td><td>string</td><td>Berfungsi untuk menyimpan alamat email pengguna</td></tr><tr><td>3</td><td>phone</td><td>string</td><td>Berfungsi untuk menyimpan nomor telepon pengguna</td></tr><tr><td>4</td><td>password</td><td>string</td><td>Berfungsi untuk menyimpan kata sandi pengguna</td></tr><tr><td>5</td><td>type</td><td>integer</td><td>Berfungsi untuk menyimpan jenis atau kategori</td></tr><tr><td>6</td><td>is_active</td><td>string</td><td>Berfungsi untuk menunjukkan status aktif</td></tr><tr><td>7</td><td>created_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu.pembuatan data</td></tr><tr><td>8</td><td>created_by</td><td>string</td><td>Berfungsi untuk menyimpan nama pengguna pembuat data</td></tr><tr><td>9</td><td>updated_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir kali perubahan data</td></tr><tr><td>10</td><td>updated_by</td><td>string</td><td>Berfungsi untuk menyimpan nama pengguna yang melakukan perubahan data</td></tr><tr><td>11</td><td>name</td><td>string</td><td>Berfungsi untuk menyimpan nama dari pengguna</td></tr><tr><td>12</td><td>deleted_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir data dihapus</td></tr><tr><td>13</td><td>deleted_by</td><td>string</td><td>Berfungsi untuk meyimpan nama pengguna yang melakukan penhapusan data</td></tr></tbody></table>

`[`**`Relasi`**`]`

tkaiI\_profile\_innovator, tkai\_profile\_industry, tkai\_bo\_user



### TkaiBoUser

**`[Deskripsi]`**

berisi seluruh data user backoffice yang terelasi dengan tabel tkai\_user

`[`**`Struktur`**`]`

<table><thead><tr><th width="66">No</th><th width="127">Tipe Data</th><th width="113">Deskripsi</th><th>Nama Kolom</th></tr></thead><tbody><tr><td>1</td><td>id</td><td>integer</td><td>Berfungsi untuk id utama TkaiBouser</td></tr><tr><td>2</td><td>email</td><td>string</td><td>Berfungsi untuk menyimpan alamat email pengguna</td></tr><tr><td>3</td><td>auth_key</td><td>string</td><td>Berfungsi untuk memberikan token kepada user sebagai login session</td></tr><tr><td>4</td><td>password</td><td>string</td><td>Berfungsi untuk menyimpan kata sandi pengguna</td></tr><tr><td>5</td><td>role</td><td>integer</td><td></td></tr><tr><td>6</td><td>name</td><td>string</td><td></td></tr><tr><td>7</td><td>org_name</td><td>string</td><td></td></tr><tr><td>8</td><td>phone</td><td>string</td><td></td></tr><tr><td>9</td><td>education type</td><td>integer</td><td></td></tr><tr><td>10</td><td>created_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu.pembuatan data</td></tr><tr><td>11</td><td>updated_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir kali perubahan data</td></tr><tr><td>12</td><td>email_verified_at</td><td>timestamp</td><td></td></tr><tr><td>13</td><td>remember_token</td><td>string</td><td></td></tr><tr><td>14</td><td>current_team_id</td><td>int</td><td></td></tr><tr><td>15</td><td>profile_photo_path</td><td>string</td><td></td></tr><tr><td>16</td><td>userable_type</td><td>string</td><td></td></tr><tr><td>17</td><td>userable_id</td><td>int</td><td></td></tr><tr><td>18</td><td>type</td><td>int</td><td></td></tr><tr><td>19</td><td>tkai_id</td><td>int</td><td></td></tr></tbody></table>

`[`**`Relasi`**`]`

tkai\_user, keuangan\_reviewer, status\_kepegawaian, backoffice\_unit\_pengelola, tkai\_profile\_innovator, tkai\_profile\_industry, mf\_proposals.





### TkaiProfileInnovator

**`[Deskripsi]`**

berisi data user yang mendaftar didalam kedaireka dengan role pengusul atau innovator.

`[`**`Struktur`**`]`

<table><thead><tr><th width="68">No</th><th width="127">Tipe Data</th><th width="113">Deskripsi</th><th>Nama Kolom</th></tr></thead><tbody><tr><td>1</td><td>id</td><td>integer</td><td>Berfungsi untuk id utama TkaiProfileInnovator</td></tr><tr><td>2</td><td>profile_id</td><td>integer</td><td>Berfungsi untuk memberikan id untk profile</td></tr><tr><td>3</td><td>user_id</td><td>integer</td><td>Berfungsi untuk memberikan id untuk user</td></tr><tr><td>4</td><td>nik</td><td>string</td><td></td></tr><tr><td>5</td><td>passport_no</td><td>string</td><td></td></tr><tr><td>6</td><td>nationally_id</td><td>string</td><td></td></tr><tr><td>7</td><td>nidn</td><td>string</td><td></td></tr><tr><td>8</td><td>id_sp</td><td>string</td><td></td></tr><tr><td>9</td><td>organisation_name</td><td>string</td><td></td></tr><tr><td>10</td><td>organsation_type</td><td>string</td><td></td></tr><tr><td>11</td><td>keywords</td><td>string</td><td></td></tr><tr><td>12</td><td>document_ids</td><td>string</td><td></td></tr><tr><td>13</td><td>created_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu.pembuatan data</td></tr><tr><td>14</td><td>created_by</td><td>string</td><td>Berfungsi untuk menyimpan nama pengguna pembuat data</td></tr><tr><td>15</td><td>updated_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir kali perubahan data</td></tr><tr><td>16</td><td>updated_by</td><td>string</td><td>Berfungsi untuk menyimpan nama pengguna yang melakukan perubahan data</td></tr><tr><td>17</td><td>description</td><td>string</td><td></td></tr><tr><td>18</td><td>categories</td><td>string</td><td></td></tr><tr><td>19</td><td>deleted_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir data dihapus</td></tr><tr><td>20</td><td>deleted_by</td><td>string</td><td>Berfungsi untuk meyimpan nama pengguna yang melakukan penhapusan data</td></tr><tr><td>21</td><td>date_of_birth</td><td>string</td><td></td></tr><tr><td>22</td><td>flag _dikti</td><td>string</td><td></td></tr></tbody></table>

**`[Relasi]`**

user\_id -> tkai\_user, profile\_id -> proposal, profile\_id -> proposal2024,

### TkaiProfileIndustry

**`[Deskripsi]`**



`[`**`Struktur`**`]`

<table><thead><tr><th width="68">No</th><th width="127">Tipe Data</th><th width="113">Deskripsi</th><th>Nama Kolom</th></tr></thead><tbody><tr><td>1</td><td>id</td><td>integer</td><td>Berfungsi untuk id utama TkaiProfileInnovator</td></tr><tr><td>2</td><td>profile_id</td><td>integer</td><td>Berfungsi untuk memberikan id untk profile</td></tr><tr><td>3</td><td>user_id</td><td>integer</td><td>Berfungsi untuk memberikan id untuk user</td></tr><tr><td>4</td><td>nik</td><td>string</td><td></td></tr><tr><td>5</td><td>nationally_id</td><td>string</td><td>Berfungsi untuk memberikan id untuk nationally</td></tr><tr><td>6</td><td>passport_no</td><td>string</td><td></td></tr><tr><td>7</td><td>company_name</td><td>string</td><td></td></tr><tr><td>8</td><td>company_type</td><td>string</td><td></td></tr><tr><td>9</td><td>keywoard</td><td>string</td><td></td></tr><tr><td>10</td><td>document_ids</td><td>string</td><td></td></tr><tr><td>11</td><td>created_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu.pembuatan data</td></tr><tr><td>12</td><td>created_by</td><td>string</td><td>Berfungsi untuk menyimpan nama pengguna pembuat data</td></tr><tr><td>13</td><td>updated_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir kali perubahan data</td></tr><tr><td>14</td><td>updated_by</td><td>timestamp</td><td>Berfungsi untuk menyimpan nama pengguna yang melakukan perubahan data</td></tr><tr><td>15</td><td>description</td><td>string</td><td></td></tr><tr><td>16</td><td>is_hide</td><td>string</td><td></td></tr><tr><td>17</td><td>categories</td><td>string</td><td></td></tr><tr><td>18</td><td>delete_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir data dihapus</td></tr><tr><td>19</td><td>delete_by</td><td>string</td><td>Berfungsi untuk meyimpan nama pengguna yang melakukan penhapusan data</td></tr><tr><td>20</td><td>adress</td><td>string</td><td></td></tr><tr><td>21</td><td>total_employee</td><td>string</td><td></td></tr><tr><td>22</td><td>npwp</td><td>string</td><td></td></tr><tr><td>23</td><td>additional_documents_ids</td><td>string</td><td></td></tr></tbody></table>

**`[Relasi]`**

user\_id -> tkai\_user



### MfProposal2024

**`[Deskripsi]`**

Berisi data proposal 2024 yang berelasi dengan banyak tabel

`[`**`Struktur`**`]`

<table><thead><tr><th width="68">No</th><th width="145">Tipe Data</th><th width="113">Deskripsi</th><th>Nama Kolom</th></tr></thead><tbody><tr><td>1</td><td>id</td><td>integer</td><td>Berfungsi untuk id utama MFProposal</td></tr><tr><td>2</td><td>innovator_id</td><td>integer</td><td>Berfungsi untuk mencantumkan id pengusul yang berkontribusi pada proposal</td></tr><tr><td>3</td><td>judul</td><td>string</td><td>Berfungsi untuk memberikan judul proposal</td></tr><tr><td>4</td><td>batch_id</td><td>integer</td><td>Berfungsi untuk memberikan id untk batch</td></tr><tr><td>5</td><td>tema_id</td><td>integer</td><td>Berfungsi untuk memberikan id untuk tema proposal</td></tr><tr><td>6</td><td>skema_id</td><td>integer</td><td>Berfungsi untuk memberikan id untuk skema proposal</td></tr><tr><td>7</td><td>komposisi_luar</td><td>string</td><td>-</td></tr><tr><td>8</td><td>jenis_mitra</td><td>string</td><td>-</td></tr><tr><td>9</td><td>created_at</td><td>string</td><td>Berfungsi untuk menyimpan tanggal dan waktu.pembuatan data</td></tr><tr><td>10</td><td>updated_at</td><td>string</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir kali perubahan data</td></tr><tr><td>11</td><td>is_submitted</td><td>string</td><td></td></tr><tr><td>12</td><td>industry_id</td><td>string</td><td>Berfungsi untuk memberikan id untuk industri</td></tr><tr><td>13</td><td>bidable_type</td><td>string</td><td>Berfungsi untuk mendefinisikan bidable</td></tr><tr><td>14</td><td>direktorat</td><td>string</td><td></td></tr><tr><td>15</td><td>is_active</td><td>string</td><td>Berfungsi untuk menunjukkan status aktif</td></tr><tr><td>16</td><td>deleted_at</td><td>string</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir data dihapus</td></tr></tbody></table>

**`[Relasi]`**

_skema\_id_ -> mfSkema, _tema\_id_ -> mfTema, _batch\_id_ -> mfBatch, _peneliti\_Dosen_ -> Mf\_Proposal\_Anggota, _peneliti\_Non\_Dosen_ -> Mf\_Proposal\_Anggota, _innovator\_id_ -> Tkai\_Innovator, _industry\_id_ -> tkai\_industry, _boI\_nnovator_ -> Tkai\_Profile\_Innovator, _bo\_Industri_ -> tkai\_Profile\_Industry, _bidable\_id_ -> , _berkas\_id_ -> berkas, _status\_id_ -> Mf\_Proposal\_Status, _props\_id_ -> Mf\_Proposal\_Property, _reviewer\_id_ -> Review\_Penugasan, _tag\_id_ -> Tagging, _jadwal\_seleksi_ -> Proposal\_Jadwal\_Seleksi, _jadwal\_Seleksi\_EvaluasiProposal_ -> jadwal\_Seleksi, _pembanding\_id_ -> Mf\_Proposal\_Similarity, _anggarans\_id_ -> Mf\_Proposal\_Anggaran, _luarans\_id_ -> Mf\_Proposal\_Luaran, _penetapan\_id_ -> Mf\_Proposal\_Penetapan, _get\_Jadwal\_Evaluasi\_Proposal Attribute_ -> penyaluran\_id -> Mf\_Proposal\_Penyaluran\_Dana



### PerguruanTinggi

**`[Deskripsi]`**

Berisi data proposal 2024 yang berelasi dengan banyak tabel

`[`**`Struktur`**`]`

<table><thead><tr><th width="70">No</th><th width="127">Tipe Data</th><th width="113">Deskripsi</th><th>Nama Kolom</th></tr></thead><tbody><tr><td>1</td><td>kode_pt</td><td>string</td><td>Berfungsi untuk menyimpan kode identifikasi unik untuk institusi pendidikan</td></tr><tr><td>2</td><td>id_pt</td><td>string</td><td></td></tr><tr><td>3</td><td>nama_pt</td><td>string</td><td></td></tr><tr><td>4</td><td>nama_singkatan</td><td>string</td><td></td></tr><tr><td>5</td><td>kode_satker</td><td>integer</td><td></td></tr><tr><td>6</td><td>bentuk_pendidikan</td><td>string</td><td></td></tr><tr><td>7</td><td>pembina</td><td>timestamp</td><td></td></tr><tr><td>8</td><td>status_milik</td><td>string</td><td></td></tr><tr><td>9</td><td>kab_kota</td><td>timestamp</td><td></td></tr><tr><td>10</td><td>propinsi</td><td>string</td><td></td></tr><tr><td>11</td><td>status</td><td>string</td><td></td></tr><tr><td>12</td><td>is_negeri</td><td>boolean</td><td></td></tr><tr><td>13</td><td>created_at</td><td>timestamp</td><td></td></tr><tr><td>14</td><td>updated_at</td><td>timestamp</td><td></td></tr><tr><td>15</td><td>alamat</td><td>string</td><td></td></tr></tbody></table>

**`[Relasi]`**

penanggung\_jawab\_id -> penanggung\_jawab, rekening\_Kontrak\_id -> rekening\_kontrak, catatan\_monev\_id -> catatan\_monev, kontraks\_id -> tx\_kontrak, kontrak\_id -> kontrak, berkas\_id -> berkas

















#### 1. SHOW INNOVATOR (ADMIN)

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

| Description | Login                                                                                                                                                      |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Login Page  |                                                                                                                                                            |
| Link figma  | [Link Figma Show Innovator](https://www.figma.com/file/xtAQWc0KNI8uM0HXVNphgV/Backoffice?type=design\&node-id=200-3127\&mode=design\&t=Hg19uEuXSFjxZ86T-0) |

\


#### 2. DETAIL INOVATOR (ADMIN)

**Informasi Singkat**

| Target Release    | 1.0                                                                                                |
| ----------------- | -------------------------------------------------------------------------------------------------- |
| Epic              | Innovator                                                                                          |
| Short Explanation | Fitur untuk admin yang digunakan untuk menampilkan detail dari innnovator yang mengajukan proposal |
| Document Status   | Draft                                                                                              |

\


#### REQUIREMENT

<table><thead><tr><th>No</th><th width="160">User Story</th><th>Priority</th><th>Notes</th></tr></thead><tbody><tr><td>1</td><td>As a Mitra<br>I Want Search category as user<br>So I Can search and acces every Mitra features</td><td>Must Have</td><td>Form filter mitra sebagai berikut<br>1. Filter kategori Mitra*<br>2. Filter Bidang*<br>3. Filter Pengajuan Proposal*</td></tr><tr><td>2</td><td>As a Admin<br>I Want Search category as Admin<br>So I Can search and acces every Admin features</td><td>Must Have</td><td>Form filter mitra sebagai berikut<br>1. Filter kategori Mitra*<br>2. Filter Bidang*<br>3. Filter Pengajuan Proposal*</td></tr></tbody></table>

#### SCENARIO

| No | Scenario                                                                                                               | Type    | Description                                                               | Validation |
| -- | ---------------------------------------------------------------------------------------------------------------------- | ------- | ------------------------------------------------------------------------- | ---------- |
| 1  | <p>As a Mitra Ikomerz Ilmu Komputer IPB<br>I want login as mitra<br>So i can search and acces every mitra features</p> | Postive | Mitra Ikomerz Ilmu Komputer IPB mendapatkan hasil pencarian sesuai filter | content    |

#### USER INTERFACE & DESIGN

<figure><img src=".gitbook/assets/Detail Innovator.jpg" alt=""><figcaption></figcaption></figure>

| Description | Login                                                                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Login Page  |                                                                                                                                                              |
| Link figma  | [Link Figma Detail Innovator](https://www.figma.com/file/xtAQWc0KNI8uM0HXVNphgV/Backoffice?type=design\&node-id=200-3127\&mode=design\&t=Hg19uEuXSFjxZ86T-0) |
|             |                                                                                                                                                              |

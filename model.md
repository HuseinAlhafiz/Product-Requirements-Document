# Model

## TkaiUser

***

#### **Deskripsi**

TkaiUser berisi data yang mendaftar didalam kedaireka

#### **Struktur**

<table><thead><tr><th width="70">No</th><th width="143">Nama Kolom</th><th width="113">Tipe Data</th><th>Nama Kolom</th></tr></thead><tbody><tr><td>1</td><td>user_id</td><td>integer</td><td>Berfungsi untuk memberikan id untuk user</td></tr><tr><td>2</td><td>email</td><td>string</td><td>Berfungsi untuk menyimpan alamat email pengguna</td></tr><tr><td>3</td><td>phone</td><td>string</td><td>Berfungsi untuk menyimpan nomor telepon pengguna</td></tr><tr><td>4</td><td>password</td><td>string</td><td>Berfungsi untuk menyimpan kata sandi pengguna</td></tr><tr><td>5</td><td>type</td><td>integer</td><td>Berfungsi untuk menyimpan jenis atau kategori</td></tr><tr><td>6</td><td>is_active</td><td>string</td><td>Berfungsi untuk menunjukkan status aktif</td></tr><tr><td>7</td><td>created_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu.pembuatan data</td></tr><tr><td>8</td><td>created_by</td><td>string</td><td>Berfungsi untuk menyimpan nama pengguna pembuat data</td></tr><tr><td>9</td><td>updated_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir kali perubahan data</td></tr><tr><td>10</td><td>updated_by</td><td>string</td><td>Berfungsi untuk menyimpan nama pengguna yang melakukan perubahan data</td></tr><tr><td>11</td><td>name</td><td>string</td><td>Berfungsi untuk menyimpan nama dari pengguna</td></tr><tr><td>12</td><td>deleted_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir data dihapus</td></tr><tr><td>13</td><td>deleted_by</td><td>string</td><td>Berfungsi untuk meyimpan nama pengguna yang melakukan penhapusan data</td></tr></tbody></table>

#### **Relasi**

[tkaiI\_profile\_innovator](model.md#tkaiprofileinnovator), [tkai\_profile\_industry](model.md#tkaiprofileindustry), [tkai\_bo\_user](model.md#tkaibouser)

## TkaiBoUser

***

#### **Deskripsi**

TkaiBoUser Berisi seluruh data user backoffice yang terelasi dengan tabel tkai\_user

#### Struktur

<table><thead><tr><th width="73">No</th><th width="175">Nama Kolom</th><th width="122">Tipe Data</th><th>Deskripsi</th></tr></thead><tbody><tr><td>1</td><td>id</td><td>integer</td><td>Berfungsi untuk id utama TkaiBouser</td></tr><tr><td>2</td><td>email</td><td>string</td><td>Berfungsi untuk menyimpan alamat email pengguna</td></tr><tr><td>3</td><td>auth_key</td><td>string</td><td>Berfungsi untuk memberikan token kepada user sebagai login session</td></tr><tr><td>4</td><td>password</td><td>string</td><td>Berfungsi untuk menyimpan kata sandi pengguna</td></tr><tr><td>5</td><td>role</td><td>integer</td><td>Berfungsi untuk menyimpan role / peran pengguna</td></tr><tr><td>6</td><td>name</td><td>string</td><td>Berfungsi untuk menyimpan nama pengguna</td></tr><tr><td>7</td><td>org_name</td><td>string</td><td>Berfungsi untuk menyimpan nama organisasi pengguna</td></tr><tr><td>8</td><td>phone</td><td>string</td><td>Berfungsi untuk menyimpan nomor telepon pengguna</td></tr><tr><td>9</td><td>education type</td><td>integer</td><td>Berfungsi untuk menyimpan informasi jenis pendidikan</td></tr><tr><td>10</td><td>created_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu.pembuatan data</td></tr><tr><td>11</td><td>updated_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir kali perubahan data</td></tr><tr><td>12</td><td>email_verified_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan timestamp ketika email pengguna di verifikasi</td></tr><tr><td>13</td><td>remember_token</td><td>string</td><td>Berfungsi untuk otentikasi dan penggunaan "remember me" pada proses autentikasi pengguna</td></tr><tr><td>14</td><td>current_team_id</td><td>int</td><td>Berfungsi untuk menyimpan ID tim saat ini yang terkait dengan pengguna</td></tr><tr><td>15</td><td>profile_photo_path</td><td>string</td><td>Berfungsi untuk menyimpan path atau URL dari foto profil pengguna</td></tr><tr><td>16</td><td>userable_type</td><td>string</td><td>Berfungsi untuk menyimpan</td></tr><tr><td>17</td><td>userable_id</td><td>int</td><td>Berfungsi untuk memberikan ID entitas pengguna yang diberikan oleh userable_type</td></tr><tr><td>18</td><td>type</td><td>int</td><td></td></tr><tr><td>19</td><td>tkai_id</td><td>int</td><td>Berfungsi untuk memberikan id untuk tkai</td></tr></tbody></table>

**`Relasi`**

[tkai\_user](model.md#tkaiuser), keuangan\_reviewer, status\_kepegawaian, backoffice\_unit\_pengelola, [tkai\_profile\_innovator](model.md#tkaiprofileinnovator), [tkai\_profile\_industry](model.md#tkaiprofileindustry), [mf\_proposals.](model.md#mfproposal2024)

## TkaiProfileInnovator

***

#### **Deskripsi**

TkaiProfileInnovator berisi data user yang mendaftar didalam kedaireka dengan role pengusul atau innovator.

#### **Struktur**

<table><thead><tr><th width="68">No</th><th width="127">Nama Kolom</th><th width="113">Tipe Data</th><th>Deskripsi</th></tr></thead><tbody><tr><td>1</td><td>id</td><td>integer</td><td>Berfungsi untuk id utama TkaiProfileInnovator</td></tr><tr><td>2</td><td>profile_id</td><td>integer</td><td>Berfungsi untuk memberikan id untk profile</td></tr><tr><td>3</td><td>user_id</td><td>integer</td><td>Berfungsi untuk memberikan id untuk user</td></tr><tr><td>4</td><td>nik</td><td>string</td><td>Berfungsi untuk menyimpan Nomor Induk Kependudukan User</td></tr><tr><td>5</td><td>passport_no</td><td>string</td><td>Berfungsi untuk menyimpan nomor pasport user</td></tr><tr><td>6</td><td>nationally_id</td><td>string</td><td><p>Berfungsi untuk memberikan id untuk nationally </p><p>(1 = Indo, 2 = US, 999 = non indonesia)</p></td></tr><tr><td>7</td><td>nidn</td><td>string</td><td>Berfungsi untuk menyimpan Nomor Induk Dosen Nasional </td></tr><tr><td>8</td><td>id_sp</td><td>string</td><td>Befungsi untuk</td></tr><tr><td>9</td><td>organisation_name</td><td>string</td><td>Befungsi untuk</td></tr><tr><td>10</td><td>organsation_type</td><td>string</td><td>Berfungsi untuk </td></tr><tr><td>11</td><td>keywords</td><td>string</td><td>Berfungsi untuk memberikan istilah yang digunakan untuk mengidentifikasi saat melakukan pencarian</td></tr><tr><td>12</td><td>document_ids</td><td>string</td><td>Berfungsi untuk memberikan id untuk dokumen-dokumen</td></tr><tr><td>13</td><td>created_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu.pembuatan data</td></tr><tr><td>14</td><td>created_by</td><td>string</td><td>Berfungsi untuk menyimpan nama pengguna pembuat data</td></tr><tr><td>15</td><td>updated_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir kali perubahan data</td></tr><tr><td>16</td><td>updated_by</td><td>string</td><td>Berfungsi untuk menyimpan nama pengguna yang melakukan perubahan data</td></tr><tr><td>17</td><td>description</td><td>string</td><td>Berfungsi untuk menyimpan teks dan informasi deskriptif</td></tr><tr><td>18</td><td>categories</td><td>string</td><td></td></tr><tr><td>19</td><td>deleted_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir data dihapus</td></tr><tr><td>20</td><td>deleted_by</td><td>string</td><td>Berfungsi untuk meyimpan nama pengguna yang melakukan penhapusan data</td></tr><tr><td>21</td><td>date_of_birth</td><td>string</td><td>Befungsi untuk menyimpan informasi tanggal lahir pengguna</td></tr><tr><td>22</td><td>flag _dikti</td><td>string</td><td>Befungsi untuk menandai status kategori pendidikan (-1 = d1, d2, d3; 0 = s1, s2, s3; 1 = str, s2tr)</td></tr></tbody></table>

#### **Relasi**

<table><thead><tr><th width="219">profile_id</th><th width="149">Relasi</th><th>tkai_user</th></tr></thead><tbody><tr><td>profile_id </td><td>Relasi</td><td>proposal</td></tr><tr><td>catatan_monev_id</td><td>Relasi</td><td>catatan_monev</td></tr><tr><td>kontraks_id </td><td>Relasi</td><td>tx_kontrak</td></tr><tr><td>kontrak_id </td><td>Relasi</td><td>kontrak</td></tr><tr><td>berkas_id</td><td>Relasi</td><td>berkas</td></tr></tbody></table>

user\_id -> [tkai\_user,](model.md#tkaiuser) profile\_id -> proposal, profile\_id -> [proposal2024](model.md#mfproposal2024)

## TkaiProfileIndustry

***

#### Deskripsi

TkaiProfileIndustry berisi seluruh data mitra yang mendaftar didalam kedaireka dengan role mitra

#### Struktur

<table><thead><tr><th width="68">No</th><th width="149">Nama Kolom</th><th width="113">Tipe Data</th><th>Deskripsi</th></tr></thead><tbody><tr><td>1</td><td>id</td><td>integer</td><td>Berfungsi untuk id utama TkaiProfileInnovator</td></tr><tr><td>2</td><td>profile_id</td><td>integer</td><td>Berfungsi untuk memberikan id untk profile</td></tr><tr><td>3</td><td>user_id</td><td>integer</td><td>Berfungsi untuk memberikan id untuk user</td></tr><tr><td>4</td><td>nik</td><td>string</td><td>Berfungsi untuk menyimpan Nomor Induk Kependudukan User</td></tr><tr><td>5</td><td>nationally_id</td><td>string</td><td><p>Berfungsi untuk memberikan id untuk nationally </p><p>(1 = Indo, 2 = US, 999 = non indonesia)</p></td></tr><tr><td>6</td><td>passport_no</td><td>string</td><td>Berfungsi untuk menyimpan nomor pasport user</td></tr><tr><td>7</td><td>company_name</td><td>string</td><td></td></tr><tr><td>8</td><td>company_type</td><td>string</td><td></td></tr><tr><td>9</td><td>keywoard</td><td>string</td><td></td></tr><tr><td>10</td><td>document_ids</td><td>string</td><td>Berfungsi untuk memberikan id untuk dokumen-dokumen</td></tr><tr><td>11</td><td>created_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu.pembuatan data</td></tr><tr><td>12</td><td>created_by</td><td>string</td><td>Berfungsi untuk menyimpan nama pengguna pembuat data</td></tr><tr><td>13</td><td>updated_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir kali perubahan data</td></tr><tr><td>14</td><td>updated_by</td><td>timestamp</td><td>Berfungsi untuk menyimpan nama pengguna yang melakukan perubahan data</td></tr><tr><td>15</td><td>description</td><td>string</td><td>Berfungsi untuk menyimpan teks dan informasi deskriptif</td></tr><tr><td>16</td><td>is_hide</td><td>string</td><td>Berfungsi untuk menentukan suatu elemen disembunyikan atau ditampilkan</td></tr><tr><td>17</td><td>categories</td><td>string</td><td></td></tr><tr><td>18</td><td>delete_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir data dihapus</td></tr><tr><td>19</td><td>delete_by</td><td>string</td><td>Berfungsi untuk meyimpan nama pengguna yang melakukan penhapusan data</td></tr><tr><td>20</td><td>adress</td><td>string</td><td>Befungsi untuk menyimpan informasi alamat pengguna</td></tr><tr><td>21</td><td>total_employee</td><td>string</td><td>Befungsi untuk menyimpan informasi jumlah pengguna</td></tr><tr><td>22</td><td>npwp</td><td>string</td><td>Befungsi untuk menyimpan informasi Nomor Pokok Wajib Pajak (NPWP) pengguna</td></tr><tr><td>23</td><td>additional_documents_ids</td><td>string</td><td>Befungsi untuk menyimpan dokumen tambahan dari pengguna</td></tr></tbody></table>

#### **Relasi**

|   |   |   |
| - | - | - |
|   |   |   |
|   |   |   |
|   |   |   |

user\_id -> [tkai\_user](model.md#tkaiuser)

## MfProposal2024

***

#### **Deskripsi**

MfProposal berisi data proposal 2024 yang berelasi dengan banyak tabel

#### Struktur

<table><thead><tr><th width="68">No</th><th width="145">Nama Kolom</th><th width="113">Tipe Data </th><th>Deskripsi</th></tr></thead><tbody><tr><td>1</td><td>id</td><td>integer</td><td>Berfungsi untuk id utama MFProposal</td></tr><tr><td>2</td><td>innovator_id</td><td>integer</td><td>Berfungsi untuk mencantumkan id pengusul yang berkontribusi pada proposal</td></tr><tr><td>3</td><td>judul</td><td>string</td><td>Berfungsi untuk memberikan judul proposal</td></tr><tr><td>4</td><td>batch_id</td><td>integer</td><td>Berfungsi untuk memberikan id untk batch</td></tr><tr><td>5</td><td>tema_id</td><td>integer</td><td>Berfungsi untuk memberikan id untuk tema proposal</td></tr><tr><td>6</td><td>skema_id</td><td>integer</td><td>Berfungsi untuk memberikan id untuk skema proposal</td></tr><tr><td>7</td><td>komposisi_luar</td><td>string</td><td>-</td></tr><tr><td>8</td><td>jenis_mitra</td><td>string</td><td>-</td></tr><tr><td>9</td><td>created_at</td><td>string</td><td>Berfungsi untuk menyimpan tanggal dan waktu.pembuatan data</td></tr><tr><td>10</td><td>updated_at</td><td>string</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir kali perubahan data</td></tr><tr><td>11</td><td>is_submitted</td><td>string</td><td>Berfungsi sebagai penanda status dalam formulir</td></tr><tr><td>12</td><td>industry_id</td><td>string</td><td>Berfungsi untuk memberikan id untuk industri</td></tr><tr><td>13</td><td>bidable_type</td><td>string</td><td>Berfungsi untuk mendefinisikan bidable</td></tr><tr><td>14</td><td>direktorat</td><td>string</td><td></td></tr><tr><td>15</td><td>is_active</td><td>string</td><td>Berfungsi untuk menunjukkan status aktif</td></tr><tr><td>16</td><td>deleted_at</td><td>string</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir data dihapus</td></tr></tbody></table>

#### Relasi

<table><thead><tr><th width="226">skema_id </th><th width="149">Relasi</th><th>mfSkema</th></tr></thead><tbody><tr><td>rekening_Kontrak_id </td><td>Relasi</td><td>rekening_kontrak</td></tr><tr><td><em>tema_id</em></td><td>Relasi</td><td>mfTema</td></tr><tr><td><em>batch_id</em></td><td>Relasi</td><td>mfBatch,</td></tr><tr><td><em>peneliti_Dosen</em> </td><td>Relasi</td><td>Mf_Proposal_Anggota</td></tr><tr><td><em>peneliti_Non_Dosen</em> </td><td>Relasi</td><td>Mf_Proposal_Anggota</td></tr><tr><td><em>innovator_id</em> </td><td>Relasi</td><td>Tkai_Innovator</td></tr><tr><td><em>industry_id</em> </td><td>Relasi</td><td>tkai_industry</td></tr><tr><td><em>boI_nnovator</em> </td><td>Relasi</td><td>Tkai_Profile_Innovator</td></tr><tr><td><em>bo_Industri</em> </td><td>Relasi</td><td>tkai_Profile_Industry</td></tr><tr><td><em>bidable_id</em> </td><td>Relasi</td><td></td></tr><tr><td><em>status_id</em> </td><td>Relasi</td><td>Mf_Proposal_Status</td></tr><tr><td><em>props_id</em> </td><td>Relasi</td><td>Mf_Proposal_Property</td></tr><tr><td><em>reviewer_id</em> </td><td>Relasi</td><td>Review_Penugasan</td></tr><tr><td><em>tag_id</em></td><td>Relasi</td><td>Tagging</td></tr><tr><td><em>jadwal_seleksi</em></td><td>Relasi</td><td>Proposal_Jadwal_Seleksi</td></tr><tr><td><em>jadwal_Seleksi_EvaluasiProposal</em></td><td>Relasi</td><td>jadwal_Seleksi</td></tr><tr><td><em>pembanding_id</em></td><td>Relasi</td><td>Mf_Proposal_Similarity</td></tr><tr><td><em>anggarans_id</em></td><td>Relasi</td><td>Mf_Proposal_Anggaran</td></tr><tr><td><em>luarans_id</em></td><td>Relasi</td><td>Mf_Proposal_Luaran</td></tr><tr><td><em>penetapan_id</em></td><td>Relasi</td><td>Mf_Proposal_Penetapan</td></tr><tr><td>penyaluran_id -</td><td>Relasi</td><td>Mf_Proposal_Penyaluran_Dana</td></tr></tbody></table>



## PerguruanTinggi

***

#### **Deskripsi**

Perguruan Tinggi Berisi data proposal 2024 yang berelasi dengan banyak tabel

#### **Struktur**

<table><thead><tr><th width="70">No</th><th width="127">Nama Kolom</th><th width="113">Deskripsi</th><th>Nama Kolom</th></tr></thead><tbody><tr><td>1</td><td>kode_pt</td><td>string</td><td>Berfungsi untuk menyimpan kode identifikasi unik untuk institusi Perguruan Tinggi</td></tr><tr><td>2</td><td>id_pt</td><td>string</td><td>Berfungsi untuk memberikan id untuk Perguruan Tinggi</td></tr><tr><td>3</td><td>nama_pt</td><td>string</td><td>Berfungsi untuk memberkan nama untuk Perguruan Tinggi</td></tr><tr><td>4</td><td>nama_singkatan</td><td>string</td><td>Berfungsi untuk menyimpan singkatan dari setiap Perguruan Tinggi</td></tr><tr><td>5</td><td>kode_satker</td><td>integer</td><td>Berfungsi untuk menyimpan kode Satuan Kerja untuk Perguruan Tinggi </td></tr><tr><td>6</td><td>bentuk_pendidikan</td><td>string</td><td>Berfungsi untuk menyimpan informasi tentang bentuk pendidikan yang diselenggarakan.</td></tr><tr><td>7</td><td>pembina</td><td>timestamp</td><td>Berfungsi untuk menyimpan informasi pembina yang bertanggung jawab </td></tr><tr><td>8</td><td>status_milik</td><td>string</td><td>Berfungsi untuk menyimpan status kepemilikan Perguruan Tinggi</td></tr><tr><td>9</td><td>kab_kota</td><td>timestamp</td><td>Berfungsi untuk menyimpan nama kabupaten atau kota Perguruan Tinggi</td></tr><tr><td>10</td><td>propinsi</td><td>string</td><td>Berfungsi untuk menyimpan nama provinsi Perguruan Tinggi</td></tr><tr><td>11</td><td>status</td><td>string</td><td></td></tr><tr><td>12</td><td>is_negeri</td><td>boolean</td><td>Berfungsi sebagai penanda untuk menunjukkan Perguruan Tinggi Negeri</td></tr><tr><td>13</td><td>created_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu.pembuatan data</td></tr><tr><td>14</td><td>updated_at</td><td>timestamp</td><td>Berfungsi untuk menyimpan tanggal dan waktu terakhir kali perubahan data</td></tr><tr><td>15</td><td>alamat</td><td>string</td><td>Berfungsi untuk menyimpan alamat Perguruan Tinggi</td></tr></tbody></table>

#### Relasi

<table><thead><tr><th width="219">penanggung_jawab_id</th><th width="149">Relasi</th><th>penanggung_jawab</th></tr></thead><tbody><tr><td>rekening_Kontrak_id </td><td>Relasi</td><td>rekening_kontrak</td></tr><tr><td>catatan_monev_id</td><td>Relasi</td><td>catatan_monev</td></tr><tr><td>kontraks_id </td><td>Relasi</td><td>tx_kontrak</td></tr><tr><td>kontrak_id </td><td>Relasi</td><td>kontrak</td></tr><tr><td>berkas_id</td><td>Relasi</td><td>berkas</td></tr></tbody></table>



penanggung\_jawab\_id -> penanggung\_jawab,&#x20;

rekening\_Kontrak\_id -> rekening\_kontrak,&#x20;

catatan\_monev\_id -> catatan\_monev,&#x20;

kontraks\_id -> tx\_kontrak,&#x20;

kontrak\_id -> kontrak,&#x20;

berkas\_id -> berkas


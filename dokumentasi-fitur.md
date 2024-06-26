# Dokumentasi Fitur

## INNOVATOR

***

### List Innovator

<figure><img src=".gitbook/assets/mervin1.png" alt=""><figcaption><p>Tampilan List Innovator</p></figcaption></figure>

<figure><img src=".gitbook/assets/mervin2.png" alt=""><figcaption><p>Tampilan Detail Innovator</p></figcaption></figure>

<figure><img src=".gitbook/assets/mervin 6.png" alt=""><figcaption><p>Filter Perguruan Tinggi</p></figcaption></figure>

<figure><img src=".gitbook/assets/mervin7.png" alt=""><figcaption><p>Filter Direktorat</p></figcaption></figure>

<figure><img src=".gitbook/assets/mervin4.png" alt=""><figcaption><p>Filter Innovator</p></figcaption></figure>

<figure><img src=".gitbook/assets/mervin5.png" alt=""><figcaption><p>Multiple Filter</p></figcaption></figure>

<figure><img src=".gitbook/assets/TampilanResponsive.jpeg" alt="" width="195"><figcaption><p>UI Responsive</p></figcaption></figure>

#### Keterangan

<table><thead><tr><th width="196">Fitur</th><th width="211">Deskripsi </th><th width="165">Latar Belakang</th><th>Tujuan</th></tr></thead><tbody><tr><td>List Innovator</td><td>Fitur ini berisi Daftar Innovator yang mengajukan proposal.</td><td>karena fitur tersebut belum ada sebelumnya.</td><td>Berfungsi untuk menampilkan Innovator  yang mengajukan proposal.</td></tr><tr><td><p>Filter </p><p>(Perguruan Tinggi, Direktorat, dan Innovator, dan Multiple Filter)</p></td><td>Fitur ini berisi Filter  berdasarkan Perguruan Tinggi, Direktorat, dan Innovator yang dituju</td><td>User kesulitan untuk mencari proposal yang dituju</td><td>Berfungsi untuk mempermudah pencarian berdasarkan Perguruan Tinggi, Direktorat, dan Innovator</td></tr><tr><td><p>Search </p><p>(nama, direktorat, perguruan tinggi, profile id)</p></td><td>Fitur ini berisi search berdasarkan nama, direktorat, perguruan tinggi, dan profile id)</td><td>User kesulitan untuk mencari proposal yang dituju</td><td>Berfungsi untuk mempermudah pencarian berdasarkan nama, direktorat, perguruan tinggi, profile id</td></tr><tr><td>Tampilan antarmuka (UI) Responsive </td><td>Fitur ini berisi Tampilan Antarmuka (UI) yang telah dilakukan pada 3 device berbeda (Iphone xr, ipad air, laptop)</td><td>User memiliki tampilan antarmuka yang tidak responsive pada device yang berbeda </td><td>Berfungsi untuk menciptakan tampilan antarmuka pengguna (UI) yang responsif pada berbagai perangkat.</td></tr></tbody></table>

#### **Model**

<table><thead><tr><th width="75">No</th><th width="288">Model</th><th width="401">Nama Tabel</th></tr></thead><tbody><tr><td>1</td><td>TkaiInnovator</td><td>tkai_profile_innovator(tkai)</td></tr><tr><td>2</td><td>MfProposal (24)</td><td>mf_proposals</td></tr><tr><td>3</td><td>MfProposalPenetapan (24)</td><td>mf_proposal_penetapans</td></tr><tr><td>4</td><td>TkaiProposal(23)</td><td>tkai_matching_fund</td></tr><tr><td>5</td><td>ProposalDitetapkan</td><td>proposal_ditetapkans</td></tr><tr><td>6</td><td>TkaiPerguruanTinggi</td><td>tkai_master_pt</td></tr></tbody></table>

#### **Relasi**

<table><thead><tr><th width="212">Model / Tabel</th><th width="163">Relasi</th><th>Model/Tabel</th></tr></thead><tbody><tr><td>tkai_profile_innovator </td><td>belongs to </td><td>tkai_user</td></tr><tr><td>tkai_profile_innovator  </td><td>has many </td><td>mf_proposals </td></tr><tr><td>mf_proposals</td><td> has one  </td><td>mf_proposal_penetapans</td></tr><tr><td>mf_proposals</td><td>has many</td><td>Mf_Proposal_anggotas (Anggota2024)</td></tr><tr><td>tkai_matching_fund </td><td></td><td><ul><li>anggaran_bahan_prototype</li><li>anggaran_bantuan_insentif_mahasiswa</li><li>anggaran_biaya_perjalanan</li><li>anggaran_fgd, anggaran_honorerium</li><li>anggaran_pendaftaran_hki</li><li>anggaran_pendampingan</li><li>anggaran_pengelolaan_program</li><li>anggaran_pengujian_produk</li><li>anggaran_pendukung</li><li>anggaran_produk_skala_terbatas</li><li>anggaran_survey,(Anggaran2023)</li></ul><p></p></td></tr><tr><td>tkai_matching_fund</td><td>has one</td><td>proposal_ditetapkans</td></tr></tbody></table>

#### Nama Komponen

<table><thead><tr><th width="79">No</th><th width="288">Nama Folder</th><th>Nama File</th></tr></thead><tbody><tr><td>1</td><td>innovator</td><td>index</td></tr></tbody></table>

#### **Keanggotaan Proposal**

<figure><img src=".gitbook/assets/Keanggotaan Proposal.jpeg" alt=""><figcaption><p>Keanggotaan Proposal</p></figcaption></figure>

#### Model

<table><thead><tr><th width="87">No</th><th width="288">Model</th><th>Nama Tabel</th></tr></thead><tbody><tr><td>1</td><td>MfProposal</td><td>mf_proposals</td></tr></tbody></table>

#### **Relasi**

<table><thead><tr><th width="187">Model / Tabel</th><th width="163">Relasi</th><th>Model/Tabel</th></tr></thead><tbody><tr><td>tkai_profile_innovator </td><td>belongs To </td><td>TkaiUser</td></tr><tr><td>mf_proposal </td><td>belongs to many </td><td>tkai_profile_innovator</td></tr><tr><td>mf_proposals</td><td>belong to </td><td>tkai_profile_industry</td></tr><tr><td>mf_proposals</td><td>has many</td><td>Mf_Proposal_anggotas (Anggota2024)</td></tr></tbody></table>

#### Nama Komponen

<table><thead><tr><th width="79">No</th><th width="288">Nama Folder</th><th>Nama File</th></tr></thead><tbody><tr><td>1</td><td>pengusul2024</td><td>keanggotaan-proposal</td></tr></tbody></table>



### Detail Innovator

<figure><img src=".gitbook/assets/reza1.jpeg" alt=""><figcaption><p>List Proposal 2024</p></figcaption></figure>

<figure><img src=".gitbook/assets/detailProposal.jpeg" alt=""><figcaption><p>Detail Proposal</p></figcaption></figure>

<figure><img src=".gitbook/assets/FilterSearch.jpeg" alt=""><figcaption><p>Filter dan Search</p></figcaption></figure>

<figure><img src=".gitbook/assets/responsivereja.jpeg" alt="" width="203"><figcaption><p>UI Responsive</p></figcaption></figure>



#### Keterangan

<table><thead><tr><th width="169">Fitur</th><th width="190">Deskripsi </th><th width="187">Latar Belakang</th><th>Tujuan</th></tr></thead><tbody><tr><td><p>List Innovator</p><p>2023, 2024</p></td><td>Fitur ini berisi Daftar Proposal yang akan diajukan dan diterima</td><td>karena fitur tersebut belum ada sebelumnya.</td><td>Berfungsi untuk menampilkan Innovator yang mengajukan proposal.</td></tr><tr><td>Detail Innovator 2023, 2024</td><td>Fitur ini berisi Daftar Proposal yang akan diajukan dan diterima</td><td>karena fitur tersebut belum ada sebelumnya.</td><td>Berfungsi untuk menampilkan Detail Innovator yang mengajukan proposal</td></tr><tr><td>Data profile Innovator</td><td>Fitur ini berisi untuk menampilkan data </td><td>karena fitur tersebut belum ada sebelumnya.</td><td>Berfungsi untuk menampilkan Data Profile Innovator</td></tr><tr><td>Daftar Kolaborasi</td><td>Fitur ini berfungsi untuk mengetahui peran Innovator </td><td>karena fitur tersebut belum ada sebelumnya.</td><td>Berfungsi untuk mengetahui peran yang diemban oleh Innovator serta di mana ia berkontribusi dalam proposal tersebut.</td></tr><tr><td>Filter (Id dan Judul) pada daftar kolaborasi</td><td>Fitur ini berisi Filter  berdasarkan ID dan Judul yang dituju</td><td>User kesulitan untuk mencari proposal yang dituju</td><td>Berfungsi untuk mempermudah pencarian berdasarkan ID dan Judul</td></tr><tr><td><p>Search </p><p>(Jenis Kolaborasi dan Tahun) pada daftar kolaborasi</p></td><td>Fitur ini berisi search berdasarkan Jenis Kolaborasi dan Tahun</td><td>User kesulitan untuk mencari proposal yang dituju</td><td>Berfungsi untuk mempermudah pencarian berdasarkan Jenis Kolaborasi dan Tahun</td></tr><tr><td>Search Universal</td><td>Fitur ini berisi search berdasarkan ID dan Judul untuk Proposal atau Kolaborasi</td><td>User kesulitan untuk mencari proposal atau kolaborasi yang dituju</td><td>Berfungsi untuk mencari proposal ataupun kolaborasi berdasarkan id dan judul</td></tr><tr><td>Tampilan antarmuka (UI) Responsive pada Detail Innovator dan Detail Proposal 2023</td><td>Fitur ini berisi Tampilan Antarmuka (UI) yang telah dilakukan pada 3 device berbeda (Iphone xr, ipad air, laptop)</td><td>User memiliki tampilan antarmuka yang tidak responsive pada device yang berbeda </td><td>Berfungsi untuk menciptakan tampilan antarmuka pengguna (UI) yang responsif pada berbagai perangkat.</td></tr></tbody></table>

#### **Model**

2023

<table><thead><tr><th width="75">No</th><th width="288">Model</th><th>Nama Tabel</th></tr></thead><tbody><tr><td>1</td><td>TkaiInnovator</td><td>tkai_profile_innovator</td></tr><tr><td>2</td><td>MfProposal(24)</td><td>mf_proposals</td></tr><tr><td></td><td>MfProposalStatus(24)</td><td>mf_proposal_statuses</td></tr><tr><td>3</td><td>TkaiProposal</td><td>tkai_matching_fund</td></tr><tr><td></td><td>TxProposalStatus</td><td>tx_proposal_status</td></tr><tr><td>4</td><td>TkaiInnovation</td><td>tkai_innovation</td></tr><tr><td>5</td><td>TkaiBusinessCase </td><td>tkai_business_case</td></tr></tbody></table>

2024

<table><thead><tr><th width="79">No</th><th width="288">Model</th><th>Nama Tabel</th></tr></thead><tbody><tr><td>1</td><td>MfProposal</td><td></td></tr></tbody></table>

#### **Relasi**

<table><thead><tr><th width="187">Model / Tabel</th><th width="163">Relasi</th><th>Model/Tabel</th></tr></thead><tbody><tr><td>TkaiInnovator</td><td>belongs to</td><td>TkaiUser</td></tr><tr><td>MfProposal</td><td>belongs to</td><td><ul><li>MfSkema </li><li>MfTema </li><li>MfBatch</li><li>TkaiIndustry</li></ul></td></tr><tr><td>TkaiProposal</td><td>has one </td><td>ProposalDitetapkan</td></tr><tr><td>TkaiProposal</td><td> has many </td><td>TkaiIndustry</td></tr><tr><td>TkaiBusinessCase</td><td>has many </td><td>TkaiBusinessBid</td></tr><tr><td>TkaiBusinessCase </td><td>belongs to</td><td>TkaiIndustry</td></tr><tr><td>TkaiInnovation</td><td>has many </td><td>TkaiInnovationBid</td></tr><tr><td>TkaiInnovation</td><td>belongs to</td><td>TkaiInnovator</td></tr><tr><td>MfProposalStatus</td><td>belongs to</td><td>MfProposal</td></tr><tr><td>TxProposalStatus</td><td>belongs to</td><td>TkaiProposal</td></tr></tbody></table>

#### NAMA KOMPONEN

<table><thead><tr><th width="79">No</th><th width="288">Nama Folder</th><th>Nama File</th></tr></thead><tbody><tr><td>1</td><td>Innovator</td><td>Dashboard.php</td></tr><tr><td>2</td><td>Innovator</td><td>Sidebar.php</td></tr><tr><td>3</td><td>Komponen/Innovator</td><td>DaftarKolaborasi.php, DaftarProposal.php, Kolaborasi.php, Proposal2023.php</td></tr><tr><td>4</td><td>Komponen/Proposal2023</td><td>Status2023.php</td></tr></tbody></table>

## MITRA

***

### &#x20;User Mitra

<figure><img src=".gitbook/assets/umar1.jpeg" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/umar2.jpeg" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/umar3.jpeg" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/FilterProposal.jpeg" alt=""><figcaption><p>Filter Proposal</p></figcaption></figure>

<figure><img src=".gitbook/assets/SearchProposal.jpeg" alt=""><figcaption><p>search proposal</p></figcaption></figure>

#### **Keterangan**

<table><thead><tr><th width="150">Fitur</th><th width="217">Deskripsi </th><th width="195">Latar Belakang</th><th>Tujuan</th></tr></thead><tbody><tr><td>Profile Mitra</td><td>Profil Mitra meliputi Nama, Bidang Usaha, Jumlah Karyawan, Provinsi, Alamat Lengkap, dan Kontak.</td><td>User tidak memiliki halaman profil masing-masing</td><td>Berfungsi untuk mendeskripsikan detail dari masing-masing mitra </td></tr><tr><td>Pendanaan Proposal</td><td>Fitur ini memungkinkan untuk memantau total proposal yang diajukan dan diterima, serta total pendanaan yang diajukan dan diterima.</td><td>User tidak mengetahui pendanaan proposal yang diterima dan diajukan</td><td>Berfungsi untuk total proposal yang diajukan dan diterima, pendanaan yang diajukan dan diterima</td></tr><tr><td>List Proposal 2021-2024</td><td>Fitur ini memungkinkan pengguna untuk melihat daftar lengkap proposal yang diajukan dan diterima dalam periode 2023/2024</td><td>User belum memiliki daftar proposal yang merujuk kepada innovator</td><td>Berfungsi untuk mengetahui Daftar Proposal yang diajukan dan diterima </td></tr><tr><td>Detail Proposal 2023/2024</td><td>Fitur ini memberikan akses untuk melihat detail lengkap dari setiap proposal yang dipilih untuk periode 2023/2024.</td><td>User belum memiliki detail informasi proposal yang tersedia</td><td>berfungsi untuk menampilkan informasi lengkap mengenai proposal yang dipilih oleh pengguna.</td></tr><tr><td>Filter Proposal (Tema)</td><td>Fitur ini berisi Filter  berdasarkan Tema</td><td>User kesulitan untuk mencari proposal yang dituju</td><td>Berfungsi untuk mempermudah pencarian berdasarkan Tema</td></tr><tr><td>Search Proposal (ID, Tittle, dan Organisation Name)</td><td>Fitur ini berisi search berdasarkan ID, Tittle, dan Organisation Name</td><td>User kesulitan untuk mencari proposal yang dituju</td><td>Berfungsi untuk mempermudah pencarian berdasarkan ID, Tittle, dan Organisation Name</td></tr></tbody></table>

#### **Model**

<table><thead><tr><th width="79">No</th><th width="288">Model</th><th width="379">Nama Tabel</th></tr></thead><tbody><tr><td>1</td><td>TkaiUser</td><td>tkai_user</td></tr><tr><td>2</td><td>User</td><td>tkai_bo_user</td></tr><tr><td>3</td><td>TkaiIndustry</td><td>tkai_profile_industry</td></tr><tr><td>4</td><td>TkaiInnovator</td><td>tkai_profile_innovator</td></tr><tr><td>5</td><td>TkaiProposal</td><td>tkai_matching_fund</td></tr><tr><td>6</td><td>ProposalDitetapkan</td><td>proposal_ditetapkans</td></tr><tr><td>7</td><td>MfProposal</td><td>mf_proposals</td></tr><tr><td></td><td>MfTemas</td><td>mf_temas</td></tr><tr><td>8</td><td>TxProposalStatus</td><td>tx_proposal_status</td></tr><tr><td>9</td><td>MfProposalAnggaran</td><td>mf_proposal_anggarans</td></tr><tr><td>10</td><td>MfProposalPenetapan</td><td>mf_proposal_penetapans</td></tr><tr><td>11</td><td>AnggaranHonorarium</td><td>anggaran_honorarium</td></tr><tr><td>12</td><td>AnggaranPeralatanPendukung</td><td>anggaran_peralatan_pendukung</td></tr><tr><td>13</td><td>AnggaranBahanPrototype</td><td>anggaran_bahan_prototype</td></tr><tr><td>14</td><td>AnggaranPendampingan</td><td>anggaran_pendampingan</td></tr><tr><td>15</td><td>AnggaranFGD</td><td>anggaran_fgd</td></tr><tr><td>16</td><td>AnggaranSurvey</td><td>anggaran_survey</td></tr><tr><td>17</td><td>AnggaranPengujianProduk</td><td>anggaran_pengujian_produk</td></tr><tr><td>18</td><td>AnggaranPendaftaranHKI</td><td>anggaran_pendaftaran_hki</td></tr><tr><td>19</td><td>AnggaranBiayaPerjalananDinas</td><td>anggaran_biaya_perjalanan</td></tr><tr><td>20</td><td>AnggaranBantuanInsentifMahasiswa</td><td>anggaran_bantuan_insentif_mahasiswa</td></tr><tr><td>21</td><td>AnggaranProdukSkalaTerbatas</td><td>anggaran_produk_skala_terbatas</td></tr><tr><td>22</td><td>AnggaranPengelolaanProgram</td><td>anggaran_pengelolaan_program</td></tr></tbody></table>

#### **Relasi**

<table><thead><tr><th width="214">Model / Tabel</th><th width="149">Relasi</th><th>Model/Tabel</th></tr></thead><tbody><tr><td>tkai_profile_industry </td><td>belongs to</td><td>tkai_user</td></tr><tr><td>tkai_profile_industry </td><td>has many</td><td>tkai_matching_fund</td></tr><tr><td>tkai_profile_innovator</td><td>belongs to </td><td>tkai_user </td></tr><tr><td>tkai_profile_innovator</td><td>has many</td><td>tkai_user </td></tr><tr><td>mf_proposals </td><td>has one </td><td>mf_proposal_penetapans</td></tr><tr><td>mf_proposals</td><td>has many</td><td>mf_proposal_anggarans (Anggaran2024)</td></tr><tr><td>mf_temas</td><td>has many</td><td>mf_proposals </td></tr><tr><td>tkai_matching_fund </td><td>belongs to</td><td>tkai_profile_industry</td></tr><tr><td>tkai_matching_fund</td><td>has one</td><td>proposal_ditetapkans</td></tr><tr><td>tkai_matching_fund</td><td> has many </td><td><ul><li>anggaran_honorarium</li><li>anggaran_peralatan_pendukung</li><li>anggaran_bahan_prototype</li><li>anggaran_pendampingan</li><li>anggaran_fgd</li><li>anggaran_survey</li><li>anggaran_pengujian_produk</li><li>anggaran_pendaftaran_hki</li><li>anggaran_biaya_perjalanan</li><li>anggaran_bantuan_insentif_mahasiswa</li><li>anggaran_produk_skala_terbatas</li><li>anggaran_pengelolaan_program</li></ul></td></tr></tbody></table>

#### Nama Komponen

<table><thead><tr><th width="79">No</th><th width="288">Nama Folder</th><th>Nama File</th></tr></thead><tbody><tr><td>1</td><td>Mitra/User</td><td>ProfileMitra.php</td></tr><tr><td>2</td><td>Mitra/User</td><td>ProposalMitra.php</td></tr><tr><td>3</td><td>Mitra/User</td><td>ProposalMitra2023.php</td></tr><tr><td>4</td><td>Komponen/Mitra/User</td><td>ProfileCard.php</td></tr><tr><td>5</td><td>Komponen/Mitra/User</td><td>PendanaanProposal.php</td></tr><tr><td>6</td><td>Komponen/Mitra/User</td><td>ListProposal.php</td></tr><tr><td>7</td><td>Komponen/Mitra/User/Proposal</td><td>Proposal2023.php</td></tr><tr><td>8</td><td>Komponen/Mitra/User/Proposal</td><td>Proposal2024.php</td></tr></tbody></table>



### Admin Mitra&#x20;

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption><p>Tampilan Daftar Mitra</p></figcaption></figure>

<figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption><p>Proposal 2024</p></figcaption></figure>

<figure><img src=".gitbook/assets/image (3).png" alt=""><figcaption><p>Proposal 2023</p></figcaption></figure>

<figure><img src=".gitbook/assets/FilterProposal (1).jpeg" alt=""><figcaption><p>Filter dan Search Proposal</p></figcaption></figure>

<figure><img src=".gitbook/assets/detailtag.jpeg" alt=""><figcaption><p>Detail Tag</p></figcaption></figure>

<figure><img src=".gitbook/assets/detailmitra.jpeg" alt=""><figcaption><p>Detail Mitra</p></figcaption></figure>

Keterangan

<table><thead><tr><th width="162">Fitur</th><th width="168">Deskripsi </th><th width="182">Latar Belakang</th><th>Tujuan</th></tr></thead><tbody><tr><td>Proposal 2023/2024</td><td>Fitur ini berisi Daftar Proposal yang telah diajukan</td><td>karena fitur tersebut belum ada sebelumnya. </td><td>Berfungsi untuk menampilkan proposal  yang telah diajukan</td></tr><tr><td><p>Filter </p><p>(Nama Mitra, </p><p>Jenis Mitra, Kategori Mitra, Provinsi Mitra)</p></td><td>Fitur ini berisi Filter pencarian berdasarkan Nama Mitra, Jenis Mitra, Kategori Mitra, Provinsi Mitra</td><td>Karena dibutuhkan  untuk mencari informasi berdasarkan kriteria tertentu</td><td>Berfungsi untuk mempermudah pencarian berdasarkan Nama Mitra, Jenis Mitra, Kategori Mitra, Provinsi Mitra</td></tr><tr><td>Multiple filter</td><td>Fitur ini berisi Filter pencarian multiple untuk pencarian ganda</td><td>Karena dibutuhkan untuk mencari informasi berdasarkan berbagai ketentuan tertentu</td><td>Berfungsi untuk memungkinkan pengguna memasukkan beberapa parameter pencarian dalam filter.</td></tr><tr><td>Daftar Mitra</td><td>Fitur ini berisi Daftar Mitra yang terdaftar</td><td>Karena fitur tersebut belum ada sebelumnya.</td><td>Berfungsi untuk memberikan informasi tentang daftar mitra yang terdaftar.</td></tr><tr><td>Export Mitra</td><td>Fitur ini berisi Export data Mitra dan anggaran-anggaran</td><td>Karena fitur tersebut belum ada sebelumnya.</td><td>Berfungsi untuk mengekspor data mitra dan anggaran-anggaran.</td></tr><tr><td>Tagging Mitra</td><td>Fitur ini berisi</td><td></td><td></td></tr></tbody></table>

#### **Model**

2023

<table><thead><tr><th width="75">No</th><th width="288">Model</th><th>Nama Tabel</th></tr></thead><tbody><tr><td>1</td><td>tkaiIndustry</td><td>tkai_profile_industry</td></tr><tr><td>2</td><td>tkaiProposal</td><td>tkai_matching_fund</td></tr><tr><td>3</td><td></td><td><p>anggaran_bahan_prototype</p><p>anggaran_bantuan_insentif_mahasiswa</p><p>anggaran_biaya_perjalanan</p><p>anggaran_fgd</p><p>anggaran_honorerium</p><p>anggaran_pendaftaran_hki</p><p>anggaran_pendampingan</p><p>anggaran_pengelolaan_program</p><p>anggaran_pengujian_produk</p><p>anggaran_peralatan_pendukung</p><p>anggaran_produk_skala_terbatas</p><p>anggaran_survey</p></td></tr><tr><td>4</td><td>tx_proposal_status</td><td>tx_proposal_status</td></tr></tbody></table>

2024

<table><thead><tr><th width="79">No</th><th width="288">Model</th><th>Nama Tabel</th></tr></thead><tbody><tr><td>1</td><td>mf_proposal </td><td>mf_proposals</td></tr><tr><td>2</td><td>mf_proposal_anggaran</td><td>mf_proposal_anggarans</td></tr><tr><td>3</td><td></td><td><p>mf_proposal_statuses</p><p>mf_proposal_penetapans</p></td></tr></tbody></table>

<table><thead><tr><th width="79">No</th><th width="288">Model</th><th>Nama Tabel</th></tr></thead><tbody><tr><td>1</td><td>MasterTag </td><td>master_tags</td></tr><tr><td>2</td><td>MitraTag</td><td>mitra_tags</td></tr></tbody></table>

#### Relasi

<table><thead><tr><th width="200">Model / Tabel</th><th width="149">Relasi</th><th>Model/Tabel</th></tr></thead><tbody><tr><td>Tkai_industry </td><td>has many </td><td>Tkai_matching_fund (Proposal 2023)</td></tr><tr><td>Tkai_industry </td><td>has many</td><td>Mf_Proposals (Proposal 2024)</td></tr><tr><td>Mf_Proposals </td><td>has many</td><td>Mf_Proposal_anggarans (Anggaran2024)</td></tr><tr><td>Tkai_matching_fund</td><td>has many </td><td><ul><li>anggaran_bahan_prototype</li><li>anggaran_bantuan_insentif_mahasiswa</li><li>anggaran_biaya_perjalanan, anggaran_fgd</li><li>anggaran_honorerium</li><li>anggaran_pendaftaran_hki</li><li>anggaran_pendampingan</li><li>anggaran_pengelolaan_program</li><li>anggaran_pengujian_produk</li><li>anggaran_pendukung</li><li>anggaran_produk_skala_terbatas</li><li>anggaran_survey,(Anggaran2023).                           </li></ul></td></tr><tr><td>Mf_Proposals </td><td> has one </td><td><p>mf_proposal_penetapans </p><p>(sk penetapan dan anggaran ditetapkan2024)</p></td></tr><tr><td>tkai_matching_fund</td><td>has one</td><td><p>proposal_ditetapkan </p><p>(sk penetapan dan anggaran ditetapkan2023)</p></td></tr><tr><td>MasterTag</td><td>belongs to many</td><td>mitras</td></tr><tr><td>MitraTag</td><td>belongs to many</td><td>tags</td></tr></tbody></table>

#### Nama Komponen

<table><thead><tr><th width="79">No</th><th width="288">Nama Folder</th><th>Nama File</th></tr></thead><tbody><tr><td>1</td><td>komponen/mitra/</td><td>list_proposal2023, list_proposal2024</td></tr><tr><td>2</td><td><strong>index</strong> </td><td>show</td></tr></tbody></table>

## PERGURUAN TINGGI

***

### List Proposal

<figure><img src=".gitbook/assets/list proposal 2021 (sisi user).jpeg" alt=""><figcaption><p>list proposal 2021 (sisi user)</p></figcaption></figure>

<figure><img src=".gitbook/assets/list proposal 2023 (sisi user).jpeg" alt=""><figcaption><p>list proposal 2023 (sisi user)</p></figcaption></figure>

<figure><img src=".gitbook/assets/list proposal 2024 (sisi user).jpeg" alt=""><figcaption><p>list proposal 2024 (sisi user)</p></figcaption></figure>

<figure><img src=".gitbook/assets/unggah pengumuman (admin).jpeg" alt=""><figcaption><p>unggah pengumuman (admin)</p></figcaption></figure>

<figure><img src=".gitbook/assets/list pengumuman per perguruan tinggi (admin).jpeg" alt=""><figcaption><p>list pengumuman per perguruan tinggi (admin)</p></figcaption></figure>

<figure><img src=".gitbook/assets/manajemen pengumuman (admin).jpeg" alt=""><figcaption><p>manajemen pengumuman (admin)</p></figcaption></figure>

<figure><img src=".gitbook/assets/list kontrak 2023.jpeg" alt=""><figcaption><p>list kontrak 2023</p></figcaption></figure>

<figure><img src=".gitbook/assets/list kontrak 2024.jpeg" alt=""><figcaption><p>list kontrak 2024</p></figcaption></figure>

#### Keterangan

<table><thead><tr><th width="188">Fitur</th><th width="217">Deskripsi </th><th width="195">Latar Belakang</th><th>Tujuan</th></tr></thead><tbody><tr><td>List Proposal 2021-2024</td><td>Fitur ini berisi Daftar proposal yang telah diajukan </td><td>karena fitur tersebut belum ada sebelumnya.</td><td>Berfungsi untuk menampilkan proposal berdasarkan tahun</td></tr><tr><td><p>Filter </p><p>(company name, nama innovator, proposal id, judul proposal)</p></td><td>Fitur ini berisi Filter pencarian berdasarkan Company Name, Nama Innovator, Proposal Id, dan Judul Proposal yang dituju</td><td>karena fitur tersebut belum ada sebelumnya.</td><td>Berfungsi untuk mempermudah pencarian berdasarkan </td></tr><tr><td>Pengumuman </td><td>Fitur ini berisi Deskripsi, file, judul. admin bisa membuat pengumuman, update, dan delete. user hanya bisa melihat pengumuman</td><td></td><td>Berfungsi untuk menerima notifikasi atau pengumuman dari admin</td></tr></tbody></table>

#### **Model**

<table><thead><tr><th width="75">No</th><th width="288">Model</th><th>Nama Tabel</th></tr></thead><tbody><tr><td>1</td><td>TkaiInnovator</td><td>tkai_profile_innovator</td></tr><tr><td>2</td><td>MfProposal(24)</td><td>mf_proposals</td></tr><tr><td>3</td><td>MfProposalStatus(24)</td><td>mf_proposal_statuses</td></tr><tr><td>4</td><td>TkaiProposal</td><td>tkai_matching_fund</td></tr><tr><td>5</td><td>TxProposalStatus</td><td>tx_proposal_status</td></tr><tr><td>6</td><td>TkaiInnovation</td><td>tkai_innovation</td></tr><tr><td>7</td><td>TkaiMitra</td><td>tkai_profile_industry</td></tr><tr><td>8</td><td>TkaiProposalDes</td><td>tkai_matching_fund_desc</td></tr><tr><td>9</td><td>ProposalDitetapkan</td><td>tkai_matching_fund</td></tr></tbody></table>

<table><thead><tr><th width="75">No</th><th width="288">Model</th><th>Nama Tabel</th></tr></thead><tbody><tr><td>1</td><td>Pengumuman (UP)</td><td>pengumuman</td></tr><tr><td>2</td><td>PerguruanTinggi</td><td>perguruan_tinggis</td></tr><tr><td>3</td><td>UnitPengelola</td><td>unit_pengelola</td></tr><tr><td>4</td><td></td><td></td></tr><tr><td>5</td><td></td><td></td></tr></tbody></table>

#### **Relasi**

<table><thead><tr><th width="187">Model / Tabel</th><th width="149">Relasi</th><th>Model/Tabel</th></tr></thead><tbody><tr><td>TkaiInnovator</td><td>belongs To </td><td>TkaiUser</td></tr><tr><td>MfProposal </td><td>belongs to </td><td><ul><li>MfSkema</li><li>MfTema</li><li>MfBatch</li><li>TkaiIndustry</li><li>TkaiProfileInnovator</li><li>TkaiProfileIndustry</li></ul></td></tr><tr><td>TkaiProposal </td><td>has one </td><td>ProposalDitetapkan</td></tr><tr><td>TkaiProposal</td><td>has many</td><td>TkaiIndustry</td></tr><tr><td>TkaiBusinessCase</td><td>has many </td><td>TkaiBusinessBid</td></tr><tr><td>TkaiBusinessCase</td><td>belongs to </td><td>TkaiIndustry</td></tr><tr><td>TkaiInnovation </td><td>has many </td><td>TkaiInnovationBid</td></tr><tr><td>TkaiInnovation </td><td> belongs to </td><td>TkaiInnovator</td></tr><tr><td>MfProposalStatus </td><td>belong to</td><td>MfProposal (2024)</td></tr><tr><td>TxProposalStatus </td><td>belong to</td><td>TkaiProposal (2023)</td></tr></tbody></table>

#### Nama Komponen

<table><thead><tr><th width="79">No</th><th width="348">Nama Folder</th><th>Nama File</th></tr></thead><tbody><tr><td>1</td><td>Komponen/UnitPengelola/TahunSebelum</td><td><p>DaftarProposal2021.php, DaftarProposal2022.php, DaftarProposal2023.php, </p><p>DaftarProposal.php</p></td></tr><tr><td></td><td>Livewire/Proposal/TahunSebelumnya</td><td>Status.php, Status2023.php</td></tr><tr><td>2</td><td>Livewire/UnitPengelola/DaftarUsulan/</td><td>Index.php</td></tr></tbody></table>



### Detail Proposal

<figure><img src=".gitbook/assets/ListPerguruanTinggi.jpeg" alt=""><figcaption><p>List Proposal (Admin)</p></figcaption></figure>

<figure><img src=".gitbook/assets/ListProposalPerguruanTinggi2024.jpeg" alt=""><figcaption><p>List Proposal Perguruan Tinggi 2024</p></figcaption></figure>

<figure><img src=".gitbook/assets/ListProposalPerguruanTinggi24.jpeg" alt=""><figcaption><p>List Proposal Perguruan Tinggi 2024</p></figcaption></figure>

<figure><img src=".gitbook/assets/ListProposalPerguruanTinggi22.jpeg" alt=""><figcaption><p>List Proposal Perguruan Tinggi 2022</p></figcaption></figure>

<figure><img src=".gitbook/assets/ListProposalPerguruanTinggi21.jpeg" alt=""><figcaption><p>List Proposal Perguruan Tinggi 2021</p></figcaption></figure>

#### Keterangan

<table><thead><tr><th width="190">Fitur</th><th width="217">Deskripsi </th><th width="173">Latar Belakang</th><th>Tujuan</th></tr></thead><tbody><tr><td><p>Detail Proposal</p><p>2023/2024</p></td><td>Fitur ini berisi user yang mengajukan proposal tahun 2023/2024</td><td>karena fitur tersebut belum ada sebelumnya.</td><td>Berfungsi untuk menampilkan user  yang mengajukan proposal.</td></tr><tr><td>Detail Anggaran</td><td>Fitur ini berisi anggaran secara keseluruhan</td><td>karena fitur tersebut belum ada sebelumnya.</td><td>Berfungsi untuk menampilkan anggaran keseluruhan dari proposal</td></tr><tr><td>Detail Mitra</td><td>Fitur ini berisi Detail Mitra</td><td>karena fitur tersebut belum ada sebelumnya.</td><td>Berfungsi untuk melihat detail mitra</td></tr><tr><td>Detail Anggota Tim Proposal</td><td>Fitur ini berisi Detail Anggota Tim Proposal</td><td>karena fitur tersebut belum ada sebelumnya.</td><td>Berfungsi untuk melihat siapa saja dosen dan mahasiswa yang berkontribusi </td></tr><tr><td>Dokumen Pitching (Langkah- langkah pengajuan proposal)</td><td>Fitur ini berisi langkah-langkah pengajuan proposal dari awal hingga akhir.</td><td>karena fitur tersebut belum ada sebelumnya.</td><td>Berfungsi untuk meilhat status pengajuan proposal dari awal sampai akhir</td></tr><tr><td>List Perguruan Tinggi dari Sisi Admin</td><td>Fitur ini berisi Daftar Perguruan Tinggi yang telah mendaftar sebagai Unit Pengelola</td><td>Admin kesulitan melihat list Perguruan Tinggi yang telah mendaftar sebagai Unit Pengelola</td><td>Berfungsi untuk meilhat Perguruan Tinggi yang telah mendaftar sebagai Unit Pengelola</td></tr><tr><td>List Proposal setiap Perguruan Tinggi dari sisi Admin</td><td>Fitur ini berisi Daftar Proposal tiap tahun (2024-2021) yang mencakup informasi pendanaan, status, SK, dll.</td><td>Admin kesulitan melihat  proposal setiap Perguruan Tinggi</td><td>Berfungsi untuk meilhat proposal dari Perguruan Tinggi</td></tr></tbody></table>

#### **Model**

<table><thead><tr><th width="75">No</th><th width="288">Model</th><th>Nama Tabel</th></tr></thead><tbody><tr><td>1</td><td>RiwayatPengusul</td><td>riwayat_pengusul</td></tr><tr><td>2</td><td>MfProposal(24)</td><td>mf_proposals</td></tr><tr><td>3</td><td>MfProposalStatus(24)</td><td>mf_proposal_statuses</td></tr><tr><td>4</td><td>TkaiProposal</td><td>tkai_matching_fund</td></tr><tr><td>5</td><td>TkaiProposalDesc</td><td>tkai_matching_fund_description</td></tr><tr><td>6</td><td>MasterDocument</td><td>master_documents</td></tr><tr><td>7</td><td>TxProposalStatus</td><td>tx_proposal_status</td></tr></tbody></table>

dibawah ini merupakan model untuk List Perguruan Tinggi dan List Proposal setiap Perguruan Tinggi dari Sisi Admin

<table><thead><tr><th width="75">No</th><th width="288">Model</th><th>Nama Tabel</th></tr></thead><tbody><tr><td>1</td><td>TkaiPerguruanTinggi</td><td>tkai_master_pt</td></tr><tr><td>2</td><td>UnitPengelola</td><td>backoffice_unit_pengelola</td></tr><tr><td>3</td><td>PenanggungJawab</td><td>penanggung_jawabs</td></tr><tr><td>4</td><td>MfProposalAnggaran</td><td>mf_proposal_anggarans</td></tr><tr><td>5</td><td>AnggaranHonorarium</td><td>anggaran_honorarium</td></tr><tr><td>6</td><td>AnggaranPeralatanPendukung</td><td>anggaran_peralatan_pendukung</td></tr><tr><td>7</td><td>AnggaranBahanPrototype</td><td>anggaran_bahan_prototype</td></tr><tr><td>8</td><td>AnggaranPendampingan</td><td>anggaran_pendampingan</td></tr><tr><td>9</td><td>AnggaranFGD</td><td>anggaran_fgd</td></tr><tr><td>10</td><td>AnggaranSurvey</td><td>anggaran_survey</td></tr><tr><td>11</td><td>AnggaranPengujianProduk</td><td>anggaran_pengujian_produk</td></tr><tr><td>12</td><td>AnggaranPendaftaranHKI</td><td>anggaran_pendaftaran_hki</td></tr><tr><td>13</td><td>AnggaranBiayaperjalananDinas</td><td>anggaran_biaya_perjalanan</td></tr><tr><td>14</td><td>AnggaranBantuanInsentifMahasiswa</td><td>anggaran_bantuan_insentif_mahasiswa</td></tr><tr><td>15</td><td>AnggaranProdukSkalaTerbatas</td><td>anggaran_produk_skala_terbatas</td></tr><tr><td>16</td><td>AnggaranPengelolaanProgram</td><td>anggaran_pengelolaan_program</td></tr><tr><td>17</td><td>MfProposalPenetapan</td><td>mf_proposal_penetapans</td></tr></tbody></table>

#### **Relasi**

Tidak ada relasi

<table><thead><tr><th width="212">Model / Tabel</th><th width="163">Relasi</th><th>Model/Tabel</th></tr></thead><tbody><tr><td>TkaiPeguruanTinggi</td><td>belongs to </td><td>PerguruanTinggi</td></tr><tr><td>  </td><td>has one </td><td>UnitPengelola</td></tr><tr><td>mf_proposals</td><td> has one  </td><td>mf_proposal_penetapans</td></tr><tr><td>mf_proposals</td><td>has many</td><td>Mf_Proposal_anggotas (Anggota2024)</td></tr><tr><td>tkai_matching_fund </td><td>has many</td><td><ul><li>anggaran_bahan_prototype</li><li>anggaran_bantuan_insentif_mahasiswa</li><li>anggaran_biaya_perjalanan</li><li>anggaran_fgd, anggaran_honorerium</li><li>anggaran_pendaftaran_hki</li><li>anggaran_pendampingan</li><li>anggaran_pengelolaan_program</li><li>anggaran_pengujian_produk</li><li>anggaran_pendukung</li><li>anggaran_produk_skala_terbatas</li><li>anggaran_survey,(Anggaran2023)</li></ul><p></p></td></tr><tr><td>tkai_matching_fund</td><td>has one</td><td>proposal_ditetapkans</td></tr></tbody></table>

#### Nama Komponen

Tahun 2024

<table><thead><tr><th width="79">No</th><th width="348">Nama Folder</th><th>Nama File</th></tr></thead><tbody><tr><td>1</td><td>Komponen/Proposal/Status</td><td>Status.php</td></tr><tr><td>2</td><td>Komponen/Proposal-similar</td><td>proposalsimiliar.php</td></tr><tr><td>3</td><td>Komponen/Proposal-mitra</td><td>Proposalmitra.php</td></tr><tr><td>4</td><td>Komponen/Proposal/Detail</td><td>Detail.php</td></tr><tr><td>5</td><td>Komponen/Proposal/Pra-kontrak ( 1-5 24)</td><td>Prakontrak.php</td></tr></tbody></table>

Tahun 2023, 2022, 2021

<table><thead><tr><th width="79">No</th><th width="348">Nama Folder</th><th>Nama File</th></tr></thead><tbody><tr><td>1</td><td>Komponen/Proposal/Tahun-sebelumnya/Status2023</td><td>Status2023.php</td></tr><tr><td>2</td><td>Livewire/Informasi-pengusul-dan-mitra</td><td>Informasipengusuldanmitra.php</td></tr><tr><td>3</td><td>Livewire/Informasi-proposal</td><td>Informasiproposal.php</td></tr><tr><td>4</td><td>Livewire/Anggota-peneliti</td><td>Anggotapeneliti.php</td></tr><tr><td>5</td><td>Livewire/Verifikasi-dokumen</td><td>Verifikasidokumen.php</td></tr><tr><td>6</td><td>Livewire/Verifikasi-proposal</td><td>Verifikasiproposal.php</td></tr><tr><td>7</td><td>Livewire/Anggaran-pengusul-rekap</td><td>Anggaranpengusulrekap.php</td></tr><tr><td>8</td><td>Livewire/Vk-ulang-consent</td><td>Vkulangconsent.php</td></tr><tr><td>9</td><td>Livewire/Proposal-luaran</td><td>Proposalluaran.php</td></tr><tr><td>10</td><td>Livewire/Realisasi-luaran</td><td>realisasiluaran.php</td></tr><tr><td>11</td><td>Livewire/Log-aktivitas</td><td>Logaktivitas.php</td></tr><tr><td>12</td><td>Pelaporan/Anggaran-keseluruhan</td><td>Anggarankeseluruhan.php</td></tr><tr><td>13</td><td>Komponen/Pengusul/Laporan-akhir</td><td>Laporanakhir.php</td></tr><tr><td>14</td><td>Komponen/Berkas</td><td>Berkas.php</td></tr><tr><td>15</td><td>Reviewer/Penugasan-rekon</td><td>Rekon.php</td></tr><tr><td>16</td><td>Komponen/Unit-Pengelola/Admin</td><td><ul><li>ListProposal2024</li><li>ListProposal2023</li><li>ListProposal2022</li><li>ListProposal2021</li></ul></td></tr></tbody></table>

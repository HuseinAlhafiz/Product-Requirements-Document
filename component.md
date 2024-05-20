# Component

## ADMIN

***

#### NAMA KOMPONEN

1. PergguruanTinggiIndex

#### Deskripsi

PergguruanTinggiIndex berfungsi sebagai akses membuka menu daftar perguruan tinggi (tab Perguruan Tinggi)

#### Variable

```
$search, $perPage, $perPageOptions
```

#### Method

```
mount(), render()
```

***

#### NAMA KOMPONEN

2. PerguruanTinggiShow

#### Deskripsi

PerguruanTinggiShow berfungsi sebagai akses membuka detail perguruan tinggi

#### Variable

```
$kode_pt,  $search, $canExport = false, $is_negeri, $tab,  $proposalStatuses $proposal_status, $jadwal, $allProposalIds, $arr_penetapan, $statusProposal, $pernah_revisi, $nomor_batch 
```

#### Method

```
updatedSearch(), updatedStatusProposal, mount($pt), render(), getPengusuls()
```

***

#### NAMA KOMPONEN

3. PendaftaranPTIndex

#### Deskripsi

PendaftaranPTIndex berfungsi sebagai akses membuka daftar pendaftaran pada tab PendaftaranPT

#### Variable

```
$search, $perPage, $perPageOptions, $filters, $perFilter
```

#### Method

```
mount($pt), updatingSearch(), render()
```

***

#### NAMA KOMPONEN

PendaftaranPTShow

#### Deskripsi

PendaftaranPTShow berfungsi sebagai akses membuka detail pendaftaran pada tab PendaftaranPT

#### Variable

```
$idPendaftaran, $pendaftaran, $ptPendaftaran, $komentarPendaftaran, $alertSimpanKomentar, $kategori_berkas_pengajuan_akun, $kode_pt, $sudah_diterima, $pt, $is_negeri
```

#### Method

```
refreshPage(), mount($pt), simpanKomentar(), simpanKomentarModal(), handleKomentarTersimpan(), closeArt(), render(), diterima(), ditolak()
```

***

#### NAMA KOMPONEN

PengusulIndex

#### Deskripsi

PengusulIndex berfungsi sebagau akses membuka list proposal dari pengusul (tab Pengusul)

#### Variable

```
$search, $jenis_pt, $nomor_batch, $proposalStatuses, $statusProposal, $pernah_revisi, $proposal_status, $jadwal, $reviewerPenugasan, $tab, $allProposalIds, $canExport, $is_super_admin, $arr_penetapan
```

#### Method

```
updatedSearch(), updatedJenisPT(), updatedStatusProposal(), mount(), render(), getPengusuls($paginate = 0), export(), 
```

***

#### NAMA KOMPONEN

PengusulShow

#### Deskripsi

PengusulShow berfungsi sebagai akses membuka detail proposal dari satu pengusul

#### Variable

```
$proposals, $proposals_desc, $ptab, $tab, $masterDocuments, $id_proposal, $is_volunteer, $documents, $riwayatPengusul, $proposalHistories, $showProposalHistory, $msgSyncStatus, $formInputSyncStatus, $syncStatusProposalConfirmation, $allTxProposalStatus, $queryString
```

#### Method

```
/Render(), mount(), fetchDocuments(), updateTab(), updatedFormInputSyncStatusKey($value), unduhRab(), getLastestHistory(), syncStatusProposal(), openSyncStatusProposalConfirmation(), fetchAllProposalStatus(($key = ''), generateBaMonev()
```

***

#### NAMA KOMPONEN

KontrakIndex

#### Deskripsi

KontrakIndex berfungsi sebagai akses membuka list kontrak dari setiap perguruan tinggi

#### Variable

```
$tab, $paginateOptions, $selectedPaginate, $statusBerkas, $statusTtd, $search,
$nama_dosen, $filterStatusBerkas, $allJenisKontrak, $filterJenisKontrak
```

#### Method

```
updatedFilterJenisKontrak(), mount(), render()
```

***

#### NAMA KOMPONEN

KontrakDiksi

#### Deskripsi

KontrakDiksi berfungsi sebagai akses membuka list kontrak dari setiap DIKSI

#### Variable

```
$tab, $paginateOptions, $selectedPaginate, $statusBerkas, $statusTtd, $namaDosen, $search, $filterStatusBerkas, $allJenisKontrak, $filterJenisKontrak
```

#### Method

```
mount(), render()
```

***

#### NAMA KOMPONEN

MergeDokumenKontrak

#### Deskripsi

MergeDokumenKontrak berfungsi sebagai akses membuka merge dokumen kontrak

#### Variable

```
$showModal, $selectedKontrak, $paginateOptions, $selectedPaginate, $search, $listBerkas
```

#### Method

```
mount(), render(), openKontrak($kontrakId)
```

***

#### NAMA KOMPONEN

KontrakShow

#### Deskripsi

KontrakShow berfungsi sebagai akses membuka detail dan informasi kontrak

#### Variable

```
$id_kontrak, $kontrak, $tabKontrak, $queryString, $kontrakStatus, $proposals, $isEditForm, $total_dana, $data, $listBerkas, $proposalDitetapkan, $inputNomorKontrak, $isPjVerified, $isRekeningVerified, $rekening, $pj, $isTransfer, $proposalStatuses, $proposalKontrakMitras, $adendumKhusus
```

#### Method

```
mount(), getBerkas(), render(), setEditForm(), updateAdendumKhusus(), downloadAdendum(), deleteAdendum()
```

***

#### NAMA KOMPONEN

UpdloadDocumentSigningPage

#### Deskripsi

Akses membuka detail dan informasi kontrak

#### Variable

```
$current_url, $user_id, $kontrak_id, $kategori_berkas_id, $kontrak, $kategori_berkas, $temporary_file, $temporary_file_url, $existing_berkas, $existing_berkas_url, $recipients, $existing_recipients, $canContinue, $canEdit, $listeners.
```

#### Method

```
render(), mount(), evaluateCan(), updateKontrakStatus(), updateTemporaryFile, removeTemporaryFile(), removeExistingFile(),saveProgress(), addPerson($privy = NULL), removePerson($index), redirectToKontrak(), nextPagetoVerify().
```

***

#### NAMA KOMPONEN

VerifyDocumentSigningPage

#### Deskripsi

VerifyDocumentSigningPage berfungsi sebagai akses membuka detail dan informasi kontrak

#### Variable

```
$current_url, $kontrak_id, $kategori_berkas_id, $kategori_berkas, $user_id, $listTxVerifBerkas, $existing_berkas, $existing_berkas_url, $existing_recipients, $open_modal, $verif_options, $current_option, $canContinue, $canEdit, $listeners
```

#### Method

```
mount(), rendeer(), updateKontrakStatus(), redirectToKontrak(), nextPageToTTE(), getRoleString($role_id), changeStatus($value), submit().
```

***

#### NAMA KOMPONEN

ConfigurationTte

#### Deskripsi

ConfigurationTte berfungsi sebagai akses membuka detail dan informasi kontrak

#### Variable

```
$user_id, $kontrak_id, $kategori_berkas_id, $recipients, $openConfirmation, $temporaryUrl, $berkasFileName, $berkasId, $picked, $canEdit, $payload, $progressMessage, $showResponsePrivy, $errorMessage, $responseData, $isPrivyDocumentExist, $listeners, $rules
```

#### Method

```
render(), mount(), updateKontrakStatus(), updateRecipients($_, $key), updateShowResponsPrivy($value), handleErrorLoadPdf($reason), handleUpdateSelectedPosition($option), saveState(), sendKontrak(), handleHitPrivyApi(), handleSaveResponsePrivyApi($isError), nextPage().
```

***

#### NAMA KOMPONEN

PreviewUploadedDocument

#### Deskripsi

PreviewUploadedDocument berfungsi sebagai akses membuka detail dan informasi kontrak

#### Variable

```
$user_id, $kontrak, $kontrak_id, $kategori_berkas_id, $isSysAdmin = false, $documentHistories, $documentStatus, $berkas, $document, $referenceNumber, $documentToken, $errorMessage, $documentSigningLinks, $otherDocumentSigningLinks, $tempUrlSignedDocument, public $canEditDocument
```

#### Method

```
mount(), render(), loadData($user_id = 0), updateKontrakStatus(), queryDocumentHistories(), queryDocumentStatus(), queryTempUrlSignedDocument(), unduh()
```

***

#### NAMA KOMPONEN

MitraIndex (ON GOING)

#### Deskripsi

Akses membuka tab Mitra

#### Variable

```
// Some code
```

#### Method

```
render()
```

***

#### NAMA KOMPONEN

ReviewerIndex

#### Deskripsi

ReviewerIndex berfungsi sebagai akses membuka tab Reviewer

#### Variable

```
$perPageOptions, $perPage, $search, $filters, $roles, $perFilter, $perRole
```

#### Method

```
mount(), render(), openModalReviewerDetail($reviwerId), export()
```

***

#### NAMA KOMPONEN

ReviewerShow

#### Deskripsi

ReviewerShow berfungsi sebagai akses membuka detail reviewer di tab Reviewer

#### Variable

```
$reviewer_id, $dataPenugasan, $reviewer,  $isBersedia, $isHaveJadwalPenugasan, $bank, $keuangan, $kepegawaian
```

#### Method

```
KesediaanUpdated(), mount($id), render(), 
```

***

#### NAMA KOMPONEN

UserManagement

#### Deskripsi

UserManagement berfungsi sebaai akses membuka tab User Management

#### Variable

```
$page. $page_list, $queryStrinh
```

#### Method

```
render()
```

***

#### NAMA KOMPONEN

PengumumanIndex

#### Deskripsi

Akses manajemen Pengumuman

#### Variable

```
$search, $perPage, $perPageOptions, $filters, $open = false, $openEdit = false, $perFilter, $scheme_filterFor, $idEdit, $judul, $informasi, $status, $target, $attachment, $rules
```

#### Method

```
mount(), updatingSearch(), submit(), ubahPengumuman($id), simpanPerubahan(), render()
```

***

#### NAMA KOMPONEN

DashboardStatistikAdmin

#### Deskripsi

DashboardStatistikAdmin berfungsi sebagai akses membuka statistik umum proposal yang masuk

#### Variable

```
$satkerArray, $jumlahProposaAwalBelumDiverifikasi, $jumlahProposalAwalDiverifikasi, $jumlahProposalAwalDiterima, $jumlahProposalAwalDitolak, $jumlahProposalAwalDirevisi, $jumlahProposalPitching, $jumlahProposalPitchingLolos, $jumlahProposalPitchingTidakLolos, $jumlahProposalPitchingBelumSepakat, $allStatusesProposalAwalDiterima, $jumlahProposal, $jumlahProposalDikti, $jumlahProposalDiksi, $tipeProposal, $jumlahProposalAwalA1, $jumlahProposalAwalA2, $jumlahProposalAwalA3, $jumlahProposalAwalA4, $jumlahProposalAwalB1, $jumlahProposalAwalB2, $jumlahProposalPitchingA1, $jumlahProposalPitchingA2, $jumlahProposalPitchingA3, $jumlahProposalPitchingA4, $jumlahProposalPitchingB1, $jumlahProposalPitchingB2, $jumlahProposalAwalEkonomiBiru, $jumlahProposalAwalEkonomiDigital, $jumlahProposalAwalEkonomiHijau, $jumlahProposalAwalKemandirianKesehatan, $jumlahProposalAwalNonTematikUmum, $jumlahProposalAwalPenguatanPariwisata, $jumlahProposalPitchingEkonomiBiru $jumlahProposalPitchingEkonomiDigital, $jumlahProposalPitchingEkonomiHijau, $jumlahProposalPitchingKemandirianKesehatan, $jumlahProposalPitchingNonTematikUmum,$jumlahProposalPitchingPenguatanPariwisata, $jumlahProposalA1, $jumlahProposalA2, $jumlahProposalA3, $jumlahProposalA4, $jumlahProposalB1,$jumlahProposalB2, $jumlahProposalEkonomiBiru, $jumlahProposalEkonomiDigital, $jumlahProposalEkonomiHijau, $jumlahProposalKemandirianKesehatan, $jumlahProposalNonTematikUmum, $jumlahProposalPenguatanPariwisata, $fundIdsSemua, $fundIdsDikti, public $fundIdsDiksi, $filters, $filterBatch, $batch, $skema, $skemaCode, $tema, $lembaga, 
```

#### Method

```
render(), iniData(), updatedTipeProposal(), updatedNomorBatch(), setJumlahProposal(), setSatkerArray()
```

***

#### NAMA KOMPONEN

DashboardStatistik2024

#### Deskripsi

DashboardStatistik2024 berfungsi sebagai akses membuka statistik umum proposal yang masuk

#### Variable

```
$filterBatch, $ddlBatch, $allProposal, $ids_proposal, $allStatus, $jenis_pt, $jumlahProposalKeseluruhan, $jumlahProposalReka, $rekas
```

#### Method

```
updatedFilterBatch(), updatedJenisPt(), mount(), render()
```

***

#### NAMA KOMPONEN

MonitoringIndex

#### Deskripsi

MonitoringIndex berfungsi sebagai

#### Variable

```
$penugasans, $proposals
```

#### Method

```
mount(), render()
```

***

#### NAMA KOMPONEN

PusatBantuan

#### Deskripsi

PusatBantuan berfungsi sebagai

#### Variable

```
$sub, $page, $pageList
```

#### Method

```
render()
```

***

#### NAMA KOMPONEN

Export

#### Deskripsi

Export berfungsi sebagai akses membuka export sebagai admin

#### Variable

```
$isSysAdmin, $can, $search, $flag
```

#### Method

```
render(), mount(), create(), access(), exportPelaporanDiksi($jenisDokumen, $flag)
```

***

#### NAMA KOMPONEN

SemHasDiktiIndex

#### Deskripsi

Akses admin untuk dapat melihat seminar

#### Variable

```
$search, $filter_upload, $proposalStatuses, $statusProposal, $proposal_status, $allProposalIds, $canExport, $is_super_admin, $tahun, $arr_penetapan, $sqlQuery, $showDebug $queryString
```

#### Method

```
updateSearch(), mount(), render(), getPengusuls($paginate = 0)
```

***

#### NAMA KOMPONEN

SeminarHasilShow

#### Deskripsi

SeminarHasilShow berfungsi sebagai akses admin untuk dapat melihat seminar

#### Variable

```
$id_proposal, $proposal, $seminarHasil, $listReviewerPenugasan, $showHasilPenilaian, $showHasilPenilaianRekon, $tab, $tabs, $isRekonActivated,  $openModalRekon
```

#### Method

```
mount(), render(), checkRekonActivation, activateRekon(), loadTabs()
```

***

#### NAMA KOMPONEN

SemHasDiksiIndex (2022/2023)

#### Deskripsi

SemHasDiksiIndex (2022/2023) berfungsi sebagai akses admin untuk dapat melihat seminar diksi

#### Variable

```
$search, $filter_upload, $proposalStatuses, $statusProposal, $proposal_status,  $allProposalIds, $canExport, $is_super_admin, $tahun, $arr_penetapan, $sqlQuery,  $showDebug, $submitted2023, $queryString
```

#### Method

```
updateSearch(), mount(), render(), getPengusuls($paginate = 0), getPengusuls2023($paginate = 0)
```

***

#### NAMA KOMPONEN

SemHasDiksiShow

#### Deskripsi

SemHasDiksiShow berfungsi sebagai akses admin untuk dapat melihat seminar diksi

#### Variable

```
$id_proposal, $proposal, $seminarHasil, $listReviewerPenugasan, $showHasilPenilaian, $showHasilPenilaianRekon, $tab, $tabs, public $edutype, $fiscal_year, $isRekonActivated, $openModalRekon
```

#### Method

```
mount(), render(), checkRekonActivation(), activateRekon(), loadTabs()
```

***

#### NAMA KOMPONEN

PencairanIndex

#### Deskripsi

PencairanIndex berfungsi sebagai akses admin untuk melakukan pencairan

#### Variable

```
$isThereAnyData, $kontrak, $danaTahap2, $pencairans, $pencairan, $openModal, $isAdmin, $step_pembayaran, $step_berkas, $stepPembayaran $stepBerkas
```

#### Method

```
mount(), saveChange($id), showModal($index), generateBerkas($idx), render()
```

***

#### NAMA KOMPONEN

PencairanShow&#x20;

#### Deskripsi

PencairanShow berfungsi sebagai akses admin untuk melakukan pencairan

#### Variable

```
// Some code
```

#### Method

```
render()
```

***

#### NAMA KOMPONEN

BuatPencairan2&#x20;

#### Deskripsi

BuatPencairan2 berfungsi sebagai Akses membuat pencairan tahap 2

#### Variable

```
$proposals, $kontrak, $id_kontrak, $isProposalSelected, $isProposalEligible;, $selectedFundIds, $danaTahap2
```

#### Method

```
mount(), selectProposal($fund_id), createPencairan, render()
```

***

#### NAMA KOMPONEN

UnggahBerkasTahap2

#### Deskripsi

UnggahBerkasTahap2 berfungsi sebagai

#### Variable

```
$editable, $pencairan, $recipients, $person, $berkas, $kategoriBerkas, $verifikasiAdmin, $verifikasiUnitPengelola, $fileUpload, $isAdmin, $isUnitPengelola, $rules
```

#### Method

```
render(), mount($pencairan_id), removeTemporary(), saveTemporary(), removeBerkas(), saveBerkas(), updatedVerifikasiAdmin(), updatedVerifikasiUnitPengelola(), addPerson($privyId = null, $tipeUser = 1, $eMaterai = 0), removePerson($index), simpanRecipient(), 
```

***

#### NAMA KOMPONEN

TandaTanganBerkasTahap2

#### Deskripsi

TandaTanganBerkasTahap2 berfungsi sebagai

#### Variable

```
$user_id, $pencairan, $recipients, $isAdmin, $editable, $openConfirmation, $temporaryUrl, $berkasFileName, $berkasId, $picked, $payload, $progressMessage, $showResponsePrivy, $errorMessage, $responseData, $isPrivyDocumentExist, $isBerkasExist, $listeners, $rules, 
```

#### Method

```
render(), mount($pencairan_id), updatedRecipients($_, $key), updatedShowResponsePrivy($value), handleErrorLoadPdf($reason), handleUpdateSelectedPosition($option), saveState(), sendKontrak(), handleHitPrivyApi(), handleSaveResponsePrivyApi($isError).
```

***

#### NAMA KOMPONEN

TandaTanganBerkasTahap2

#### Deskripsi

TandaTanganBerkasTahap2 berfungsi sebagai

#### Variable

```
$todoList, $pencairan, $berkas, $recipients, $privyDoc, $isSysAdmin, $canEditDocument, $user_id, $documentHistories, $documentStatus, $document, $referenceNumber, $documentToken, $errorMessage, $documentSigningLinks, $otherDocumentSigningLinks, $tempUrlSignedDocument, $kategoriBerkas;
```

#### Method

```
render(), mount($pencairan_id), unggahBerkasPencairanTahap2(), verifikasiDariAdmin(), verifikasiDariUnitPengelola(), mendaftarkanPenandatanganBerkas(), mengaturPosisiTandaTangan(), mengunggahBerkasKePrivy(), queryDocumentHistories(), queryDocumentStatus(),  queryTempUrlSignedDocument(), unduhSigned()
```

***

#### NAMA KOMPONEN

KelengkapanTanganBerkasTahap2

#### Deskripsi

KelengkapanTanganBerkasTahap2 berfungsi sebagai

#### Variable

```
$todoList, $pencairan, $berkas, $recipients, $privyDoc, $isSysAdmin, $canEditDocument, $user_id, $documentHistories, $documentStatus, $document, $referenceNumber, $documentToken, $errorMessage, $documentSigningLinks, $otherDocumentSigningLinks, $tempUrlSignedDocument, $kategoriBerkas;
```

#### Method

```
render(), mount($pencairan_id), unggahBerkasPencairanTahap2(), verifikasiDariAdmin(), verifikasiDariUnitPengelola(), mendaftarkanPenandatanganBerkas(), mengaturPosisiTandaTangan(), mengunggahBerkasKePrivy(), queryDocumentHistories(), queryDocumentStatus(),  queryTempUrlSignedDocument(), unduhSigned()
```

***

#### NAMA KOMPONEN

DaftarPengajuanImpor

#### Deskripsi

DaftarPengajuanImpor berfungsi sebagai akses admin untuk melihat, mengajukan, dan memperbarui status izin impor

#### Variable

```
$listPengajuan, $paginate, $paginateOptions, $search, $filterPengajuan, $status_filter, $applied_status_filter, $perguruanTinggi, $upOrAdmin, $filteredIds, $pengusuls, $listeners
```

#### Method

```
mount(), render(), 
```

***

#### NAMA KOMPONEN

BuatIzinImpor

#### Deskripsi

BuatIzinImpor berfungsi sebagai akses admin untuk melihat, mengajukan, dan memperbarui status izin

#### Variable

```
$openUploadModal, $addItemModalFundId, $kategori, $berkas, $kategoriBerkas, $berkasFundId, $tempBerkas, $searchPt, $list_pt,  $selected_kode_pt, $selected_nama_pt, $nomor_surat, $tanggal_surat, $searchPengusul, $listPengusul, $list_selected_pengusul, $listItem, $nilai_total_impor, $item_nama, $item_deskripsi, $item_alasan_kebutuhan, $item_kuantitas, $item_harga_satuan;
```

#### Method

```
mount(), updateSearchPT(), resetSearchPt(), searchPtQuery, updateSearchPengusul(), resetSearchPengusul(), searchPengusulQuery, render(), selectPt($kode_pt, $nama_pt), removePt(), addPengusul(), addPengusul($fund_id, $nama, $judul), removePengusul($fund_id), openUpload($kategori, $fund_id = null), addBerkas(), removeUpload($kategori_berkas, $fund_id), addItem($fund_id), removeItem($fund_id, $i), submit()
```

***

#### NAMA KOMPONEN

DetailIzinImpor

#### Deskripsi

Akses admin untuk melihat, mengajukan, dan memperbarui status izin

#### Variable

```
$id_izin_impor, $pengajuan, $openUploadModal, $showPreviewModal, $kategoriBerkas, $kategori, $berkas, $status, $nomor_surat, $tanggal_surat, $catatan, $fund_id, $berkasFundId, $pengajuanStatus.
```

#### Method

```
mount(), updateStatus(), render(), openUpload($kategori, $fund_id = null), uploadBerkas($fund_id = null), removeUpload($fund_id = null), submit(), downloadExcel($berkas)
```

***

**2024**

#### NAMA KOMPONEN

UsulanIndex

#### Deskripsi

UsulanIndex berfungsi sebagai akses membuka list proposal dikti dari pengusul (tab Pengusul)

#### Variable

```
$openFilter, $filterStatusKonsep, $filterStatusAdministrasi, $filterStatusRevisi, $filterStatusPraKontrak, $filterStatusEvaluasi, $filterStatusPresentasi, $filterStatusVeka, $filterBatch, $rules
```

#### Method

```
mount(), resetFilter(), changeTab($key), render()
```

***

#### NAMA KOMPONEN

UsulanShow

#### Deskripsi

UsulanShow berfungsi sebagai akses membuka detail proposal dari satu pengusul

#### Variable

```
$proposal, $id_proposa, $is_admin_dikti, $tab, $queryString
```

#### Method

```
mount(), render()
```

***

#### NAMA KOMPONEN

IndexRekaCipta

#### Deskripsi

IndexRekaCipta berfungsi sebagai akses menu index kreasi reka dan peluang cipta

#### Variable

```
$applied_paginate, $applied_year, $applied_status, $applied_search, $tab,$jumlahKreasiReka, $jumlahKreasiRekaDiterima, $jumlahKreasiRekaDiajukan, $jumlahPeluangCipta, $jumlahPeluangCiptaDiterima, $jumlahPeluangCiptaDiajukan;
```

#### Method

```
mount(),changeTab($tab), render()
```

***

#### NAMA KOMPONEN

ShowRekaCipta

#### Deskripsi

ShowRekaCipta berfungsi sebagai akses menu show atau detail dari kreasi reka dan peluang cipta

#### Variable

```
$tipe_bid, $id_bid, $bid, $bidders
```

#### Method

```
mount(), render()
```

***

#### NAMA KOMPONEN

ReportAdminIndex

#### Deskripsi

ReportAdminIndex berfungsi sebagai

#### Variable

```
$filterStatusLaporan, $filterStatusLaporanSelected, $filterVerifikasiLaporan, $filterVerifikasiLaporanSelected, $paginate, $search
```

#### Method

```
updatingSearch(), mount(), render(), 
```

updatingSearch(), mount(), render(),&#x20;

***

#### NAMA KOMPONEN

ReportAdminShow

#### Deskripsi

ReportAdminShow berfungsi sebagai

#### Variable

```
$report, $openStatusModal, $statuses, $notes, $statusTo;
```

#### Method

```
mount($reportId), render(), save()
```

***

#### NAMA KOMPONEN

AdminKontrak

#### Deskripsi

AdminKontrak berfungsi sebagai

#### Variable

```
$search
```

#### Method

```
render()
```

***

#### NAMA KOMPONEN

Show

#### Deskripsi

Show berfungsi sebagai

#### Variable

```
$kontrak, $tab $queryString
```

#### Method

```
render()
```

***

#### NAMA KOMPONEN

ProposalA3

#### Deskripsi

ProposalA3 berfungsi sebagai

#### Variable

```
-
```

#### Method

```
render()
```

***

#### NAMA KOMPONEN

ProposalA3Show

#### Deskripsi

ProposalA3Show berfungsi sebagai

#### Variable

```
$proposal, $tab $queryString
```

$proposal, $tab $queryString

#### Method

```
render()
```

***

#### NAMA KOMPONEN

ProposalA3Show

#### Deskripsi

#### Variable

```
$proposal, $tab $queryString
```

#### Method

```
render()
```



## ADMIN VOLUNTEER

***

Nama Komponen

VolunteerPengusulIndex

#### DESKRIPSI

Akses untuk admin volunter ke daftar usulan

#### **VARIABLE**

$proposals, $allProposalIds, $tab, $statusProposa, $pernah\_revisi;

#### METHOD

mount(), render(), getPengusuls($paginate = 0)



Nama Komponen

PengusulShow

#### DESKRIPSI

Akses untuk admin volunter ke detail usulan

#### **VARIABLE**

$proposa, $proposal\_desc, $ptab = 'seleksi', $tab, $masterDocuments, $id\_proposal, $is\_volunteer, $documents, $riwayatPengusul, $proposalHistories, $showProposalHistory, $msgSyncStatus, $formInputSyncStatus, $syncStatusProposalConfirmation, $allTxProposalStatus, $queryString

#### METHOD

render(), mount(), fetchDocuments(), updateTab(), updatedFormInputSyncStatusKey($value), unduhRab(), getLastestHistory(), syncStatusProposal(), openSyncStatusProposalConfirmation(), fetchAllProposalStatus($key = ''), generateBaMonev()



## REVIEWER

***

Nama Komponen

ReviewerPenugasanIndex

#### DESKRIPSI

Akses membuka daftar tugas yang diberikan sebagai Reviewer

#### **VARIABLE**

$isDebug, $reviewer, $penugasan, $penugasan\_de, $penugasan\_pitching, $penugasan\_veka, $isBersedia, $isHaveJadwalPenugasan, $bank, $keuangan, $kepegawaian, $tab, $search, $allFilterTanggal, $filterTanggal, $allFilterJenis, $filterJenis, $isBersediaDeskEval, $isHaveJadwalPenugasanDeskEval, $numOfSemhasDiksi2023,  $listeners, $queryString

#### METHOD

kesediaanUpdated(), updatedTab(), updatedSearch(), updatedFilterTanggal(), updatedFilterJenis(), semhasDiksi2023(), mount(), render()



Nama Komponen

ReviewerPenugasanShow

#### DESKRIPSI

Akses membuka detail tugas yang diberikan sebagai Reviewer

#### **VARIABLE**

$tugas, $proposal\_desc, $list\_dokumen, $isReviewersDoneGrading, $isReviewersDoneRekon, $txRekon, $key, $lembar\_kerja, $tab, $queryString, $riwayatPengusul, $proposal

#### METHOD

mount(), getDokumen(), checkStatus(), checkRekon(), render()



Nama Komponen

PenugasanReviewerSemhas

#### DESKRIPSI

Akses membuka detail tugas yang diberikan sebagai Reviewer

#### **VARIABLE**

$fiscal\_year, ReviewerPenugasan $tugas, TkaiProposal $proposal, $key, $tab, $lembar\_kerja, $seminarHasil, $showRekon

#### METHOD

checkRekon(), mount(), render()



Nama Komponen

PenugasanReviewerMonev

#### DESKRIPSI

Akses membuka detail tugas yang diberikan sebagai Reviewer

#### **VARIABLE**

$tugas, $proposal, $proposal\_desc, $dokumen,  $key, $tab,  $lembar\_kerja, $seminarHasil, $showRekon, $laporanKemajuan;

#### METHOD

mount(), downloadRab(), render()



Nama Komponen

EvaluasiProposal

#### DESKRIPSI

#### **VARIABLE**

$tugas, $proposal, $is\_rekon\_activated, $lastReminder,  $canRemind = false, $isDone, $isOtherReviewerNotDone, $tab

#### METHOD

mount(), render(), remind(), reminderCacheKey(), loadLastReminder(), loadCanRemind(), loadDoneStatuses()



Nama Komponen

PresentasiProposal

#### DESKRIPSI

#### **VARIABLE**

$tugas, $proposal, $tab, $files

#### METHOD

mount(), render()



Nama Komponen

VekaProposal

#### DESKRIPSI

#### **VARIABLE**

$tugas, $proposal, $tab

#### METHOD

mount(), render()



## UNIT PENGELOLA

***

NamaKomponen&#x20;

UnitPengelolaIndex

#### DESKRIPSI

Akses membuka daftar proposal yang diajukan PT sebagai Unit Pengelola

#### **VARIABLE**

$search, $tahapanProposal, $perguruanTinggi, $penanggungJawabPt, $rekeningKontrak, $proposalsId, $proposalStatuses, $proposalKontrakMitras, $enableLaporan

#### METHOD

mount(), render()



NamaKomponen&#x20;

UnitPengeloShow

#### DESKRIPSI

Akses membuka detail progress proposal yang diajukan PT sebagai Unit Pengelola

#### **VARIABLE**

$proposal, $tab, $documents, $proposal\_desc,  $id\_proposal, $tahap\_proposal, $tahap\_proposal\_flag, $queryString

#### METHOD

setTahapProposalFlag(), changeTab($tab), mount(), render()



NamaKomponen&#x20;

UnitPengeloKontrakIndex

#### DESKRIPSI

Akses membuka list kontrak dari setiap perguruan tinggi untuk Unit Pengelola PT

#### **VARIABLE**

$tab, $paginateOptions, $selectedPaginate, $statusBerkas, $statusTtd, $search, $nama\_dosen, $filterStatusBerkas$proposalDitetapkans, $proposalTerkontrak, $danaProposalDitetapkans, $danaProposalTerkontrak, $danaProposalBelumTerkontrak, $perguruanTinggi;

#### METHOD

mount(), render(), create()



NamaKomponen&#x20;

CreateKontrak

#### DESKRIPSI

Akses membuka list kontrak dari setiap perguruan tinggi untuk Unit Pengelola PT

#### **VARIABLE**

$isBuatRekeningBaru, $isBuatPjBaru, $selectedPj, $selectedRekening, $user, $perguruanTinggi, $searchPj, $searchRekening, $existingRekening, $existingPj,$listProposals, $isProposalContracted, $isProposalSelected, $selectedFundIds, $penetapanProposals, $kategoriBerkasNpwp, $kategoriBerkasKopSurat, $uploadedNpwp, $uploadedKop, $newKontrak, $penanggungJawab, $rekeningKontrak, $banks, $jenisRekeningKontrak, $jenisKontrak;

#### METHOD

rules(), messages(), validationAttributes(), updateSearchRekening(), updateSearchPJ(), updateIsBuatRekeningBaru(), updateIsBuatPjBaru(), selectRekening($val), selectPj($val), updated($propertyName), mount(), selectProposal($fundId),  loadExistingPj(), loadExistingRekening(), loadProposals(), generateNewKontrak(), generatePenanggungJawab(), generateRekeningKontrak(), simpan(), render()



NamaKomponen&#x20;

UnitPengeloKontrakShow

#### DESKRIPSI

Akses membuka detail dan informasi kontrak untuk Unit Pengelola PT

#### **VARIABLE**

$tab, $queryString, $id\_kontrak, $kontrak, $proposals, $total\_dana, $data, $kategoriBerkas, $proposalDitetapkan;

#### METHOD

mount(), getBerkas(), render(), changeTab($tab)



NamaKomponen&#x20;

VerifikasiUploadDocumentPrivy

#### DESKRIPSI

Akses membuka detail dan informasi kontrak untuk Unit Pengelola PT

#### **VARIABLE**

$tab, $queryString, $id\_kontrak, $kontrak, $proposals, $total\_dana, $data, $kategoriBerkas, $proposalDitetapkan;

#### METHOD

mount(),  render(), evaluateCan(), updateKontrakStatus(), redirectToKontrak(), changeStatus($value), submit(),&#x20;



NamaKomponen&#x20;

DaftarPengajuaImporUp

#### DESKRIPSI

Akses unit pengelola untuk melihat dan mengajukan izin impor

#### **VARIABLE**

$listPengajuan, $paginate, $paginateOptions, $search, $filterPengajuan, $status\_filter, $applied\_status\_filter, $perguruanTinggi, $izinImporUp, $listeners

#### METHOD

mount(),  render(),&#x20;



NamaKomponen&#x20;

BuatIzinImporUp

#### DESKRIPSI

Akses unit pengelola untuk melihat dan mengajukan izin impor

#### **VARIABLE**

$kategori, $berkas, $kategoriBerkas, $berkasFundId, $tempBerkas, $selected\_kode\_pt, $selected\_nama\_pt, $searchPt, $list\_pt, $nomor\_surat, $tanggal\_surat,  $searchPengusul, $listPengusul, $list\_selected\_pengusul, $listItem, $nilai\_total\_impor, $item\_nama, $item\_deskripsi, $item\_alasan\_kebutuhan, $item\_kuantitas, $item\_harga\_satuan;

#### METHOD

mount(), updatedSearchPt(), resetSearchPt(), searchPtQuery(), updatedSearchPengusul(), resetSearchPengusul(), searchPengusulQuery(), render(), selectPt($kode\_pt, $nama\_pt), removePt(), addPengusul($fund\_id, $nama, $judul), removePengusul($fund\_id), openUpload($kategori, $fund\_id = null), addBerkas(), removeUpload($kategori\_berkas, $fund\_id), addItem($fund\_id), removeItem($fund\_id, $i), submit()



NamaKomponen&#x20;

DetaiIzinImporUp

#### DESKRIPSI

Akses unit pengelola untuk melihat dan mengajukan izin impor

#### **VARIABLE**

$id\_izin\_impor, $pengajuan, $openUploadModal, $showPreviewModal,  $kategoriBerkas, $kategori, $berkas,  $status, $nomor\_surat, $tanggal\_surat, $catatan, $fund\_id, $berkasFundId,  $pengajuanStatus

#### METHOD

mount(), updateStatus(), render(), downloadExcel($berkas)



NamaKomponen&#x20;

Laporan

#### DESKRIPSI

#### **VARIABLE**

$perguruanTinggi;

#### METHOD

mount(),  render()



**`2024`**



NamaKomponen&#x20;

UnitPengelola2024index

#### DESKRIPSI

Akses membuka daftar proposal yang diajukan PT sebagai Unit Pengelola

#### **VARIABLE**

$search, $perguruanTinggi, $unitPengelola, $penandaTangan, $rekening, $tab, $queryString

#### METHOD

mount(),  render()



NamaKomponen&#x20;

UnitPengelola2024Show

#### DESKRIPSI

Akses membuka detail progress proposal yang diajukan PT sebagai Unit Pengelola

#### **VARIABLE**

$proposal, $proposal\_id,  $tab, $queryString

#### METHOD

mount(),  render()



NamaKomponen&#x20;

BuatKontrak

#### DESKRIPSI

#### **VARIABLE**

$perguruanTinggi, $unitPengelola, $penandaTangan, $rekening, $mekanisme, $direktorat, $proposals, $selectedProposals, $terkontrak

#### METHOD

mount(), tambahProposal($id), hapusProposal($id), simpan(), render()



NamaKomponen&#x20;

Kontrak

#### DESKRIPSI

#### **VARIABLE**

$kontrak, $tab, $queryString

#### METHOD

render()



## OPERATOR

***

Nama Komponen

PerguruanTinggiRegister

#### DESKRIPSI

Akses membuka formulir pendaftaran Unit Pengelola sebagai Operator

#### **VARIABLE**

$unit\_pengelola, $is\_mengajukan, $is\_edit = false, $kode\_pt,  $listeners

#### METHOD

mount(), render(), editUlang(), PendaftaranUnitPengelolaCreated()



NamaKomponen&#x20;

EditDaftarUp

#### DESKRIPSI

Akses membuka formulir pendaftaran Unit Pengelola sebagai Operator

#### **VARIABLE**

$pj\_nama, $pj\_alamat, $pj\_telp, $pj\_nomor, $pj\_surel, $up\_nama, $up\_alamat, $up\_telp, $up\_nomor, $up\_surel, $bp\_nama, $bp\_nama\_ketua, $bp\_alamat, $bp\_telp, $bp\_nomor, $kode\_pt, $perguruan, $up;

#### METHOD

mount(), render(), rules(), submit()



## FRONT OFFICE

***

Nama Komponen

FoIndex

#### DESKRIPSI

Akses melihat seluruh status proposal pada sistem backoffice

#### **VARIABLE**

$tab, $key, $search\_fundid, $value

#### METHOD

detail($fund\_id), changeTab($tab), render()



Nama Komponen

**FoShow**

#### DESKRIPSI

Akses melihat seluruh status proposal pada sistem backoffice

#### **VARIABLE**

$proposal, $historyFO, $latestFO, $historyBO, $latestBO, $fullHistory

#### METHOD

mount($fund\_id),loadFullHistory(), render()



Nama Komponen

ProposalDescriptionIndex

#### DESKRIPSI

Akses melihat seluruh deskripsi proposal pada sistem backoffice

#### **VARIABLE**

$columns

#### METHOD

render()



Nama Komponen

ProposalDescriptionShow

#### DESKRIPSI

Akses melihat seluruh deskripsi proposal pada sistem backoffice

#### **VARIABLE**

$proposalDescription

#### METHOD

render(), mount($description\_id)



## PENGUSUL

***

Nama Komponen

Dashboard

#### DESKRIPSI

Akses pengusul untuk melihat laman informasi pengusul beserta proposal dan daftar kolaborasi

#### **VARIABLE**

$skemaProposal, $pilihSkemaModal, $innovator

#### METHOD

goesToUnggahProposal(), singkronData(), mount(), render()



Nama Komponen

Proposal

#### DESKRIPSI

Akses pengusul untuk melihat detail dari proposal yang telah diajukan

#### **VARIABLE**

$proposal, $tab, $isDiksi&#x20;

#### METHOD

mount(), render()



NamaKomponen&#x20;

PengajuanProposal

#### DESKRIPSI

Akses pengusul untuk mengajukan proposal baru untuk masuk ke selesksi administrasi

#### **VARIABLE**

$tahapanPengajuanProposal, $currentTahapPengajuan, $selectedTahapPengajuan, $listSkemaProposal, $showTambahDosenModal, $showTambahNonDosenModal, $daftarNonDosenTerlibat, $isianNamaDosen, $isianNamaNonDosen, $draftProposal, $jenjangPendidikans, $jumlahMahasiswaPerJenjang,  $proposal, $innovatorId, $allTema

$rules, $draftProposalDosenTerlibat, $draftProposalNonDosenTerlibat.

#### METHOD

updatedJumlahMahasiswaPerJenjang(), mount(), moveToTahap($key), saveProposal(), render()



NamaKomponen&#x20;

PengusulShowProposal

#### DESKRIPSI

Akses pengusul untuk melihat detail dari proposal yang telah diajukan

#### **VARIABLE**

$isPengusul, public $proposal, $statusProposal, $proposal\_desc, $tab, $masterDocuments, $id\_proposal, $documents, $riwayatPengusul, proposalHistories, $showProposalHistory, $msgSyncStatus, $formInputSyncStatus, $syncStatusProposalConfirmation $allTxProposalStatus, public $lorem;

#### METHOD

mount(), render()

\


\


\

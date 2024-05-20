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

4. PendaftaranPTShow

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

5. PengusulIndex

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

6. PengusulShow

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

7. KontrakIndex

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

8. KontrakDiksi

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

9. MergeDokumenKontrak

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

10. KontrakShow

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

11. UpdloadDocumentSigningPage

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

12. VerifyDocumentSigningPage

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

13. ConfigurationTte

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

14. PreviewUploadedDocument

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

15. MitraIndex&#x20;

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

16. ReviewerIndex

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

17. ReviewerShow

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

18. UserManagement

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

19. PengumumanIndex

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

20. DashboardStatistikAdmin

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

21. DashboardStatistik2024

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

22. MonitoringIndex

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

23. PusatBantuan

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

24. Export

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

25. SemHasDiktiIndex

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

26. SeminarHasilShow

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

27. SemHasDiksiIndex (2022/2023)

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

28. SemHasDiksiShow

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

29. PencairanIndex

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

30. PencairanShow&#x20;

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

31. BuatPencairan2&#x20;

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

32. UnggahBerkasTahap2

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

33. TandaTanganBerkasTahap2

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

34. TandaTanganBerkasTahap2

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

35. KelengkapanTanganBerkasTahap2

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

36. DaftarPengajuanImpor

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

37. BuatIzinImpor

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

38. DetailIzinImpor

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

39. UsulanIndex

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

40. UsulanShow

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

41. IndexRekaCipta

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

42. ShowRekaCipta

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

43. ReportAdminIndex

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

44. ReportAdminShow

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

45. AdminKontrak

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

46. Show

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

47. ProposalA3

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

48. ProposalA3Show

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

49. ProposalA3Show

#### Deskripsi

ProposalA3Show berfungsi sebagai

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

#### NAMA KOMPONEN

1. VolunteerPengusulIndex

#### Deskripsi

VolunteerPengusulIndex berfungsi sebagai akses untuk admin volunter ke daftar usulan

#### Variable

```
$proposals, $allProposalIds, $tab, $statusProposa, $pernah_revisi;
```

#### Method

```
mount(), render(), getPengusuls($paginate = 0)
```

***

#### NAMA KOMPONEN

2. PengusulShow

#### Deskripsi

PengusulShow berfungsi sebagai akses untuk admin volunter ke detail usulan

#### Variable

```
$proposa, $proposal_desc, $ptab = 'seleksi', $tab, $masterDocuments, $id_proposal, $is_volunteer, $documents, $riwayatPengusul, $proposalHistories, $showProposalHistory, $msgSyncStatus, $formInputSyncStatus, $syncStatusProposalConfirmation, $allTxProposalStatus, $queryString
```

#### Method

```
render(), mount(), fetchDocuments(), updateTab(), updatedFormInputSyncStatusKey($value), unduhRab(), getLastestHistory(), syncStatusProposal(), openSyncStatusProposalConfirmation(), fetchAllProposalStatus($key = ''), generateBaMonev()
```

## REVIEWER

***

#### NAMA KOMPONEN

1. ReviewerPenugasanIndex

#### Deskripsi

ReviewerPenugasanIndex berfungsi sebagai akses membuka daftar tugas yang diberikan sebagai Reviewer

#### Variable

```
$isDebug, $reviewer, $penugasan, $penugasan_de, $penugasan_pitching, $penugasan_veka, $isBersedia, $isHaveJadwalPenugasan, $bank, $keuangan, $kepegawaian, $tab, $search, $allFilterTanggal, $filterTanggal, $allFilterJenis, $filterJenis, $isBersediaDeskEval, $isHaveJadwalPenugasanDeskEval, $numOfSemhasDiksi2023,  $listeners, $queryString
```

#### Method

```
kesediaanUpdated(), updatedTab(), updatedSearch(), updatedFilterTanggal(), updatedFilterJenis(), semhasDiksi2023(), mount(), render()
```

***

#### NAMA KOMPONEN

2. ReviewerPenugasanShow

#### Deskripsi

ReviewerPenugasanShow berfungsi sebagai akses membuka detail tugas yang diberikan sebagai Reviewer

#### Variable

```
$tugas, $proposal_desc, $list_dokumen, $isReviewersDoneGrading, $isReviewersDoneRekon, $txRekon, $key, $lembar_kerja, $tab, $queryString, $riwayatPengusul, $proposal
```

#### Method

```
mount(), getDokumen(), checkStatus(), checkRekon(), render()
```

***

#### NAMA KOMPONEN

3. PenugasanReviewerSemhas

#### Deskripsi

PenugasanReviewerSemhas berfungsi sebagai akses membuka detail tugas yang diberikan sebagai Reviewer

#### Variable

```
$fiscal_year, ReviewerPenugasan $tugas, TkaiProposal $proposal, $key, $tab, $lembar_kerja, $seminarHasil, $showRekon
```

#### Method

```
checkRekon(), mount(), render()
```

***

#### NAMA KOMPONEN

4. PenugasanReviewerMonev

#### Deskripsi

PenugasanReviewerMonev berfungsi sebagai akses membuka detail tugas yang diberikan sebagai Reviewer

#### Variable

```
$tugas, $proposal, $proposal_desc, $dokumen,  $key, $tab,  $lembar_kerja, $seminarHasil, $showRekon, $laporanKemajuan;
```

#### Method

```
mount(), downloadRab(), render()
```

***

#### NAMA KOMPONEN

5. EvaluasiProposal

#### Deskripsi

#### Variable

```
$tugas, $proposal, $is_rekon_activated, $lastReminder,  $canRemind = false, $isDone, $isOtherReviewerNotDone, $tab
```

#### Method

```
mount(), render(), remind(), reminderCacheKey(), loadLastReminder(), loadCanRemind(), loadDoneStatuses()
```

***

#### NAMA KOMPONEN

6. PresentasiProposal

#### Deskripsi

PresentasiProposal berfungsi sebagai

#### Variable

```
$tugas, $proposal, $tab, $files
```

#### Method

```
mount(), render()
```

***

#### NAMA KOMPONEN

7. VekaProposal

#### Deskripsi

VekaProposal berfungsi sebagai

#### Variable

```
$tugas, $proposal, $tab
```

#### Method

```
mount(), render()
```



## UNIT PENGELOLA

***

#### NAMA KOMPONEN

1. UnitPengelolaIndex

#### Deskripsi

Akses membuka daftar proposal yang diajukan PT sebagai Unit Pengelola

#### Variable

```
$search, $tahapanProposal, $perguruanTinggi, $penanggungJawabPt, $rekeningKontrak, $proposalsId, $proposalStatuses, $proposalKontrakMitras, $enableLaporan
```

#### Method

```
mount(), render()
```

***

#### NAMA KOMPONEN

2. UnitPengeloShow

#### Deskripsi

UnitPengeloShow berfungsi sebagai akses membuka detail progress proposal yang diajukan PT sebagai Unit Pengelola

#### Variable

```
$proposal, $tab, $documents, $proposal_desc,  $id_proposal, $tahap_proposal, $tahap_proposal_flag, $queryString
```

#### Method

```
setTahapProposalFlag(), changeTab($tab), mount(), render()
```

***

#### NAMA KOMPONEN

3. UnitPengeloKontrakIndex

#### Deskripsi

UnitPengeloKontrakIndex berfungsi sebagai akses membuka list kontrak dari setiap perguruan tinggi untuk Unit Pengelola PT

#### Variable

```
$tab, $paginateOptions, $selectedPaginate, $statusBerkas, $statusTtd, $search, $nama_dosen, $filterStatusBerkas$proposalDitetapkans, $proposalTerkontrak, $danaProposalDitetapkans, $danaProposalTerkontrak, $danaProposalBelumTerkontrak, $perguruanTinggi;
```

#### Method

```
mount(), render(), create()
```

***

#### NAMA KOMPONEN

4. CreateKontrak

#### Deskripsi

CreateKontrak berfungsi sebagai akses membuka list kontrak dari setiap perguruan tinggi untuk Unit Pengelola PT

#### Variable

```
$isBuatRekeningBaru, $isBuatPjBaru, $selectedPj, $selectedRekening, $user, $perguruanTinggi, $searchPj, $searchRekening, $existingRekening, $existingPj,$listProposals, $isProposalContracted, $isProposalSelected, $selectedFundIds, $penetapanProposals, $kategoriBerkasNpwp, $kategoriBerkasKopSurat, $uploadedNpwp, $uploadedKop, $newKontrak, $penanggungJawab, $rekeningKontrak, $banks, $jenisRekeningKontrak, $jenisKontrak;
```

#### Method

```
rules(), messages(), validationAttributes(), updateSearchRekening(), updateSearchPJ(), updateIsBuatRekeningBaru(), updateIsBuatPjBaru(), selectRekening($val), selectPj($val), updated($propertyName), mount(), selectProposal($fundId),  loadExistingPj(), loadExistingRekening(), loadProposals(), generateNewKontrak(), generatePenanggungJawab(), generateRekeningKontrak(), simpan(), render()
```

***

#### NAMA KOMPONEN

5. UnitPengeloKontrakShow

#### Deskripsi

UnitPengeloKontrakShow berfungsi sebagai akses membuka detail dan informasi kontrak untuk Unit Pengelola PT

#### Variable

```
$tab, $queryString, $id_kontrak, $kontrak, $proposals, $total_dana, $data, $kategoriBerkas, $proposalDitetapkan;
```

#### Method

```
mount(), getBerkas(), render(), changeTab($tab)
```

***

#### NAMA KOMPONEN

6. VerifikasiUploadDocumentPrivy

#### Deskripsi

VerifikasiUploadDocumentPrivy berfungsi sebagai akses membuka detail dan informasi kontrak untuk Unit Pengelola PT

#### Variable

```
$tab, $queryString, $id_kontrak, $kontrak, $proposals, $total_dana, $data, $kategoriBerkas, $proposalDitetapkan;
```

#### Method

```
mount(),  render(), evaluateCan(), updateKontrakStatus(), redirectToKontrak(), changeStatus($value), submit(), 
```

***

#### NAMA KOMPONEN

7. DaftarPengajuaImporUp

#### Deskripsi

DaftarPengajuaImporUp berfungsi sebagai akses unit pengelola untuk melihat dan mengajukan izin impor

#### Variable

```
$listPengajuan, $paginate, $paginateOptions, $search, $filterPengajuan, $status_filter, $applied_status_filter, $perguruanTinggi, $izinImporUp, $listeners
```

#### Method

```
mount(),  render(), 
```

***

#### NAMA KOMPONEN

8. BuatIzinImporUp

#### Deskripsi

BuatIzinImporUp berfungsi sebagai akses unit pengelola untuk melihat dan mengajukan izin impor

#### Variable

```
$kategori, $berkas, $kategoriBerkas, $berkasFundId, $tempBerkas, $selected_kode_pt, $selected_nama_pt, $searchPt, $list_pt, $nomor_surat, $tanggal_surat,  $searchPengusul, $listPengusul, $list_selected_pengusul, $listItem, $nilai_total_impor, $item_nama, $item_deskripsi, $item_alasan_kebutuhan, $item_kuantitas, $item_harga_satuan;
```

#### Method

```
mount(), updatedSearchPt(), resetSearchPt(), searchPtQuery(), updatedSearchPengusul(), resetSearchPengusul(), searchPengusulQuery(), render(), selectPt($kode_pt, $nama_pt), removePt(), addPengusul($fund_id, $nama, $judul), removePengusul($fund_id), openUpload($kategori, $fund_id = null), addBerkas(), removeUpload($kategori_berkas, $fund_id), addItem($fund_id), removeItem($fund_id, $i), submit()
```

***

#### NAMA KOMPONEN

9. DetaiIzinImporUp

#### Deskripsi

DetaiIzinImporUp berfungsi sebagai akses unit pengelola untuk melihat dan mengajukan izin impor

#### Variable

```
$id_izin_impor, $pengajuan, $openUploadModal, $showPreviewModal,  $kategoriBerkas, $kategori, $berkas,  $status, $nomor_surat, $tanggal_surat, $catatan, $fund_id, $berkasFundId,  $pengajuanStatus
```

#### Method

```
mount(), updateStatus(), render(), downloadExcel($berkas)
```

***

#### NAMA KOMPONEN

#### 10. Laporan

#### Deskripsi

Laporan berfungsi sebagai

#### Variable

```
$perguruanTinggi;
```

$perguruanTinggi;

#### Method

```
mount(),  render()
```

***

**`2024`**

#### NAMA KOMPONEN

11. UnitPengelola2024index

#### Deskripsi

UnitPengelola2024index berfungsi sebagai akses membuka daftar proposal yang diajukan PT sebagai Unit Pengelola

#### Variable

```
$search, $perguruanTinggi, $unitPengelola, $penandaTangan, $rekening, $tab, $queryString
```

#### Method

```
mount(),  render()
```

mount(),  render()

***

#### NAMA KOMPONEN

12. UnitPengelola2024Show

#### Deskripsi

UnitPengelola2024Show berfungsi sebagai akses membuka detail progress proposal yang diajukan PT sebagai Unit Pengelola

#### Variable

```
$proposal, $proposal_id,  $tab, $queryString
```

#### Method

```
mount(),  render()
```

***

#### NAMA KOMPONEN

13. BuatKontrak

#### Deskripsi

BuatKontrak berfungsi sebagai

#### Variable

```
$perguruanTinggi, $unitPengelola, $penandaTangan, $rekening, $mekanisme, $direktorat, $proposals, $selectedProposals, $terkontrak
```

#### Method

```
mount(), tambahProposal($id), hapusProposal($id), simpan(), render()
```

***

#### NAMA KOMPONEN

14. Kontrak

#### Deskripsi

Kontrak berfungsi sebagai

#### Variable

```
$kontrak, $tab, $queryString
```

#### Method

```
render()
```

## OPERATOR

***

#### NAMA KOMPONEN

1. PerguruanTinggiRegister

#### Deskripsi

PerguruanTinggiRegister berfungsi sebagai akses membuka formulir pendaftaran Unit Pengelola sebagai Operator

#### Variable

```
$unit_pengelola, $is_mengajukan, $is_edit = false, $kode_pt,  $listeners
```

#### Method

```
mount(), render(), editUlang(), PendaftaranUnitPengelolaCreated()
```

***

#### NAMA KOMPONEN

2. EditDaftarUp

#### Deskripsi

EditDaftarUp berfungsi sebagai akses membuka formulir pendaftaran Unit Pengelola sebagai Operator

#### Variable

```
$pj_nama, $pj_alamat, $pj_telp, $pj_nomor, $pj_surel, $up_nama, $up_alamat, $up_telp, $up_nomor, $up_surel, $bp_nama, $bp_nama_ketua, $bp_alamat, $bp_telp, $bp_nomor, $kode_pt, $perguruan, $up;
```

#### METHOD

```
mount(), render(), rules(), submit()
```



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

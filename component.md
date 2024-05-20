# Component

## ADMIN

***

#### NAMA KOMPONEN

> PergguruanTinggiIndex

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

#### Nama Komponen

> PerguruanTinggiShow

#### DESKRIPSI

PerguruanTinggiShow berfungsi sebagai akses membuka detail perguruan tinggi

#### **VARIABLE**

```
$kode_pt,  $search, $canExport = false, $is_negeri, $tab,  $proposalStatuses $proposal_status, $jadwal, $allProposalIds, $arr_penetapan, $statusProposal, $pernah_revisi, $nomor_batch 
```

#### METHOD

```
updatedSearch(), updatedStatusProposal, mount($pt), render(), getPengusuls()
```

***

Nama Komponen

PendaftaranPTIndex

#### DESKRIPSI

akses membuka daftar pendaftaran pada tab PendaftaranPT

#### **VARIABLE**

$search, $perPage, $perPageOptions, $filters, $perFilter

#### METHOD

mount($pt), updatingSearch(), render()



Nama Komponen

PendaftaranPTShow

#### DESKRIPSI

Akses membuka detail pendaftaran pada tab PendaftaranPT

#### **VARIABLE**

$idPendaftaran, $pendaftaran, $ptPendaftaran, $komentarPendaftaran, $alertSimpanKomentar, $kategori\_berkas\_pengajuan\_akun, $kode\_pt, $sudah\_diterima, $pt, $is\_negeri

#### METHOD

refreshPage(), mount($pt), simpanKomentar(), simpanKomentarModal(), handleKomentarTersimpan(), closeArt(), render(), diterima(), ditolak()



Nama Komponen

PengusulIndex

#### DESKRIPSI

Akses membuka list proposal dari pengusul (tab Pengusul)

#### **VARIABLE**

$search, $jenis\_pt, $nomor\_batch, $proposalStatuses, $statusProposal, $pernah\_revisi, $proposal\_status, $jadwal, $reviewerPenugasan, $tab, $allProposalIds, $canExport, $is\_super\_admin, $arr\_penetapan

#### METHOD

updatedSearch(), updatedJenisPT(), updatedStatusProposal(), mount(), render(), getPengusuls($paginate = 0), export(),&#x20;



NamaKomponen&#x20;

PengusulShow

#### DESKRIPSI

Akses membuka detail proposal dari satu pengusul

#### **VARIABLE**

$proposals, $proposals\_desc, $ptab, $tab, $masterDocuments, $id\_proposal, $is\_volunteer, $documents, $riwayatPengusul, $proposalHistories, $showProposalHistory, $msgSyncStatus, $formInputSyncStatus, $syncStatusProposalConfirmation, $allTxProposalStatus, $queryString

#### METHOD

Render(), mount(), fetchDocuments(), updateTab(), updatedFormInputSyncStatusKey($value), unduhRab(), getLastestHistory(), syncStatusProposal(), openSyncStatusProposalConfirmation(), fetchAllProposalStatus(($key = ''), generateBaMonev()



Nama Komponen

KontrakIndex

#### DESKRIPSI

Akses membuka list kontrak dari setiap perguruan tinggi

#### **VARIABLE**

$tab, $paginateOptions, $selectedPaginate, $statusBerkas, $statusTtd, $search;

$nama\_dosen, $filterStatusBerkas, $allJenisKontrak, $filterJenisKontrak

#### METHOD

updatedFilterJenisKontrak(), mount(), render()



Nama Komponen

KontrakDiksi

#### DESKRIPSI

Akses membuka list kontrak dari setiap DIKSI

#### **VARIABLE**

$tab, $paginateOptions, $selectedPaginate, $statusBerkas, $statusTtd, $namaDosen, $search, $filterStatusBerkas, $allJenisKontrak, $filterJenisKontrak

#### METHOD

mount(), render()



Nama Komponen

MergeDokumenKontrak

#### DESKRIPSI

Akses membuka merge dokumen kontrak

#### **VARIABLE**

$showModal, $selectedKontrak, $paginateOptions, $selectedPaginate, $search, $listBerkas;

#### METHOD

mount(), render(), openKontrak($kontrakId)



Nama Komponen

KontrakShow

#### DESKRIPSI

akses membuka detail dan informasi kontrak

#### **VARIABLE**

$id\_kontrak, $kontrak, $tabKontrak, $queryString, $kontrakStatus, $proposals, $isEditForm, $total\_dana, $data, $listBerkas, $proposalDitetapkan, $inputNomorKontrak, $isPjVerified, $isRekeningVerified, $rekening, $pj, $isTransfer, $proposalStatuses, $proposalKontrakMitras, $adendumKhusus

#### METHOD

mount(), getBerkas(), render(), setEditForm(), updateAdendumKhusus(), downloadAdendum(), deleteAdendum()



Nama Komponen

UpdloadDocumentSigningPage

#### DESKRIPSI

Akses membuka detail dan informasi kontrak

#### **VARIABLE**

$current\_url, $user\_id, $kontrak\_id, $kategori\_berkas\_id, $kontrak, $kategori\_berkas, $temporary\_file, $temporary\_file\_url, $existing\_berkas, $existing\_berkas\_url, $recipients, $existing\_recipients, $canContinue, $canEdit, $listeners.

#### METHOD

render(), mount(), evaluateCan(), updateKontrakStatus(), updateTemporaryFile, removeTemporaryFile(), removeExistingFile(),saveProgress(), addPerson($privy = NULL), removePerson($index), redirectToKontrak(), nextPagetoVerify().



Nama Komponen

VerifyDocumentSigningPage

#### DESKRIPSI

Akses membuka detail dan informasi kontrak

#### **VARIABLE**

$current\_url, $kontrak\_id, $kategori\_berkas\_id, $kategori\_berkas, $user\_id, $listTxVerifBerkas, $existing\_berkas, $existing\_berkas\_url, $existing\_recipients, $open\_modal, $verif\_options, $current\_option, $canContinue, $canEdit, $listeners

#### METHOD

mount(), rendeer(), updateKontrakStatus(), redirectToKontrak(), nextPageToTTE(), getRoleString($role\_id), changeStatus($value), submit().



Nama Komponen

ConfigurationTte

#### DESKRIPSI

Akses membuka detail dan informasi kontrak

#### **VARIABLE**

$user\_id, $kontrak\_id, $kategori\_berkas\_id, $recipients, $openConfirmation, $temporaryUrl, $berkasFileName, $berkasId, $picked, $canEdit, $payload, $progressMessage, $showResponsePrivy, $errorMessage, $responseData, $isPrivyDocumentExist, $listeners, $rules

#### METHOD

render(), mount(), updateKontrakStatus(), updateRecipients($\_, $key), updateShowResponsPrivy($value), handleErrorLoadPdf($reason), handleUpdateSelectedPosition($option), saveState(), sendKontrak(), handleHitPrivyApi(), handleSaveResponsePrivyApi($isError), nextPage().



Nama Komponen

PreviewUploadedDocument

#### DESKRIPSI

Akses membuka detail dan informasi kontrak

#### **VARIABLE**

$user\_id, $kontrak, $kontrak\_id, $kategori\_berkas\_id, $isSysAdmin = false, $documentHistories, $documentStatus, $berkas, $document, $referenceNumber, $documentToken, $errorMessage, $documentSigningLinks, $otherDocumentSigningLinks, $tempUrlSignedDocument, public $canEditDocument

#### METHOD

mount(), render(), loadData($user\_id = 0), updateKontrakStatus(), queryDocumentHistories(), queryDocumentStatus(), queryTempUrlSignedDocument(), unduh()



Nama Komponen

MitraIndex (ON GOING)

#### DESKRIPSI

Akses membuka tab Mitra

#### **VARIABLE**

#### METHOD

render()



Nama Komponen

ReviewerIndex (ON GOING)

#### DESKRIPSI

Akses membuka tab Reviewer

#### **VARIABLE**

$perPageOptions, $perPage, $search, $filters, $roles, $perFilter, $perRole

#### METHOD

mount(), render(), openModalReviewerDetail($reviwerId), export()



Nama Komponen

ReviewerShow

#### DESKRIPSI

Akses membuka detail reviewer di tab Reviewer

#### **VARIABLE**

$reviewer\_id, $dataPenugasan, $reviewer,  $isBersedia, $isHaveJadwalPenugasan, $bank, $keuangan, $kepegawaian

#### METHOD

KesediaanUpdated(), mount($id), render(),&#x20;



Nama Komponen

UserManagement

#### DESKRIPSI

Akses membuka tab User Management

#### **VARIABLE**

$page. $page\_list, $queryStrinh

#### METHOD

render()



Nama Komponen

PengumumanIndex

#### DESKRIPSI

Akses manajemen Pengumuman

#### **VARIABLE**

$search, $perPage, $perPageOptions, $filters, $open = false, $openEdit = false, $perFilter, $scheme\_filterFor, $idEdit, $judul, $informasi, $status, $target, $attachment, $rules

#### METHOD

mount(), updatingSearch(), submit(), ubahPengumuman($id), simpanPerubahan(), render()



Nama Komponen

DashboardStatistikAdmin

#### DESKRIPSI

Akses membuka statistik umum proposal yang masuk

#### **VARIABLE**

$satkerArray, $jumlahProposaAwalBelumDiverifikasi, $jumlahProposalAwalDiverifikasi, $jumlahProposalAwalDiterima, $jumlahProposalAwalDitolak, $jumlahProposalAwalDirevisi, $jumlahProposalPitching, $jumlahProposalPitchingLolos, $jumlahProposalPitchingTidakLolos, $jumlahProposalPitchingBelumSepakat, $allStatusesProposalAwalDiterima, $jumlahProposal, $jumlahProposalDikti, $jumlahProposalDiksi, $tipeProposal, $jumlahProposalAwalA1, $jumlahProposalAwalA2, $jumlahProposalAwalA3, $jumlahProposalAwalA4, $jumlahProposalAwalB1, $jumlahProposalAwalB2, $jumlahProposalPitchingA1, $jumlahProposalPitchingA2, $jumlahProposalPitchingA3, $jumlahProposalPitchingA4, $jumlahProposalPitchingB1, $jumlahProposalPitchingB2, $jumlahProposalAwalEkonomiBiru, $jumlahProposalAwalEkonomiDigital, $jumlahProposalAwalEkonomiHijau, $jumlahProposalAwalKemandirianKesehatan, $jumlahProposalAwalNonTematikUmum, $jumlahProposalAwalPenguatanPariwisata, $jumlahProposalPitchingEkonomiBiru $jumlahProposalPitchingEkonomiDigital, $jumlahProposalPitchingEkonomiHijau, $jumlahProposalPitchingKemandirianKesehatan, $jumlahProposalPitchingNonTematikUmum,$jumlahProposalPitchingPenguatanPariwisata, $jumlahProposalA1, $jumlahProposalA2, $jumlahProposalA3, $jumlahProposalA4, $jumlahProposalB1,$jumlahProposalB2, $jumlahProposalEkonomiBiru, $jumlahProposalEkonomiDigital, $jumlahProposalEkonomiHijau, $jumlahProposalKemandirianKesehatan, $jumlahProposalNonTematikUmum, $jumlahProposalPenguatanPariwisata, $fundIdsSemua, $fundIdsDikti, public $fundIdsDiksi, $filters, $filterBatch, $batch, $skema, $skemaCode, $tema, $lembaga,&#x20;

#### METHOD

render(), iniData(), updatedTipeProposal(), updatedNomorBatch(), setJumlahProposal(), setSatkerArray()



Nama Komponen

DashboardStatistik2024

#### DESKRIPSI

Akses membuka statistik umum proposal yang masuk

#### **VARIABLE**

$filterBatch, $ddlBatch, $allProposal, $ids\_proposal, $allStatus, $jenis\_pt, $jumlahProposalKeseluruhan, $jumlahProposalReka, $rekas

#### METHOD

updatedFilterBatch(), updatedJenisPt(), mount(), render()



Nama Komponen

MonitoringIndex

#### DESKRIPSI

#### **VARIABLE**

$penugasans, $proposals

#### METHOD

mount(), render()



Nama Komponen

PusatBantuan

#### DESKRIPSI

#### **VARIABLE**

$sub, $page, $pageList

#### METHOD

render()



Nama Komponen

Export

#### DESKRIPSI

Akses membuka export sebagai admin

#### **VARIABLE**

$isSysAdmin, $can, $search, $flag

#### METHOD

render(), mount(), create(), access(), exportPelaporanDiksi($jenisDokumen, $flag)



Nama Komponen

SemHasDiktiIndex

#### DESKRIPSI

Akses admin untuk dapat melihat seminar

#### **VARIABLE**

$search, $filter\_upload, $proposalStatuses, $statusProposal, $proposal\_status, $allProposalIds, $canExport, $is\_super\_admin, $tahun, $arr\_penetapan, $sqlQuery, $showDebug $queryString

#### METHOD

updateSearch(), mount(), render(), getPengusuls($paginate = 0)



Nama Komponen

SeminarHasilShow

#### DESKRIPSI

Akses admin untuk dapat melihat seminar

#### **VARIABLE**

$id\_proposal, $proposal, $seminarHasil, $listReviewerPenugasan, $showHasilPenilaian, $showHasilPenilaianRekon, $tab, $tabs, $isRekonActivated,  $openModalRekon

#### METHOD

mount(), render(), checkRekonActivation, activateRekon(), loadTabs()



Nama Komponen

SemHasDiksiIndex (2022/2023)

#### DESKRIPSI

Akses admin untuk dapat melihat seminar diksi

#### **VARIABLE**

$search, $filter\_upload, $proposalStatuses, $statusProposal, $proposal\_status,  $allProposalIds, $canExport, $is\_super\_admin, $tahun, $arr\_penetapan, $sqlQuery,  $showDebug, $submitted2023, $queryString

#### METHOD

updateSearch(), mount(), render(), getPengusuls($paginate = 0), getPengusuls2023($paginate = 0)



Nama Komponen

SemHasDiksiShow

#### DESKRIPSI

Akses admin untuk dapat melihat seminar diksi

#### **VARIABLE**

$id\_proposal, $proposal, $seminarHasil, $listReviewerPenugasan, $showHasilPenilaian, $showHasilPenilaianRekon, $tab, $tabs, public $edutype, $fiscal\_year, $isRekonActivated, $openModalRekon

#### METHOD

mount(), render(), checkRekonActivation(), activateRekon(), loadTabs()



Nama Komponen

PencairanIndex

#### DESKRIPSI

Akses admin untuk melakukan pencairan

#### **VARIABLE**

$isThereAnyData, $kontrak, $danaTahap2, $pencairans, $pencairan, $openModal, $isAdmin, $step\_pembayaran, $step\_berkas, $stepPembayaran $stepBerkas

#### METHOD

mount(), saveChange($id), showModal($index), generateBerkas($idx), render()



Nama Komponen

PencairanShow (ON GOING)

#### DESKRIPSI

Akses admin untuk melakukan pencairan

#### **VARIABLE**

\-

#### METHOD

render()



Nama Komponen

BuatPencairan2 (ON GOING)

#### DESKRIPSI

Akses membuat pencairan tahap 2

#### **VARIABLE**

$proposals, $kontrak, $id\_kontrak, $isProposalSelected, $isProposalEligible;, $selectedFundIds, $danaTahap2

#### METHOD

mount(), selectProposal($fund\_id), createPencairan, render()



Nama Komponen

UnggahBerkasTahap2

#### DESKRIPSI

#### **VARIABLE**

$editable, $pencairan, $recipients, $person, $berkas, $kategoriBerkas, $verifikasiAdmin, $verifikasiUnitPengelola, $fileUpload, $isAdmin, $isUnitPengelola, $rules

#### METHOD

render(), mount($pencairan\_id), removeTemporary(), saveTemporary(), removeBerkas(), saveBerkas(), updatedVerifikasiAdmin(), updatedVerifikasiUnitPengelola(), addPerson($privyId = null, $tipeUser = 1, $eMaterai = 0), removePerson($index), simpanRecipient(),&#x20;



Nama Komponen

TandaTanganBerkasTahap2

#### DESKRIPSI

#### **VARIABLE**

$user\_id, $pencairan, $recipients, $isAdmin, $editable, $openConfirmation, $temporaryUrl, $berkasFileName, $berkasId, $picked, $payload, $progressMessage, $showResponsePrivy&#x20;

$errorMessage, $responseData, $isPrivyDocumentExist, $isBerkasExist, $listeners, $rules,&#x20;

#### METHOD

render(), mount($pencairan\_id), updatedRecipients($\_, $key), updatedShowResponsePrivy($value), handleErrorLoadPdf($reason), handleUpdateSelectedPosition($option), saveState(), sendKontrak(), handleHitPrivyApi(), handleSaveResponsePrivyApi($isError).



Nama Komponen

TandaTanganBerkasTahap2

#### DESKRIPSI

#### **VARIABLE**

$todoList, $pencairan, $berkas, $recipients, $privyDoc, $isSysAdmin, $canEditDocument, $user\_id, $documentHistories, $documentStatus, $document, $referenceNumber, $documentToken, $errorMessage, $documentSigningLinks, $otherDocumentSigningLinks, $tempUrlSignedDocument, $kategoriBerkas;

#### METHOD

render(), mount($pencairan\_id), unggahBerkasPencairanTahap2(), verifikasiDariAdmin(), verifikasiDariUnitPengelola(), mendaftarkanPenandatanganBerkas(), mengaturPosisiTandaTangan(), mengunggahBerkasKePrivy(), queryDocumentHistories(), queryDocumentStatus(),  queryTempUrlSignedDocument(), unduhSigned()



Nama Komponen

KelengkapanTanganBerkasTahap2

#### DESKRIPSI

#### **VARIABLE**

$todoList, $pencairan, $berkas, $recipients, $privyDoc, $isSysAdmin, $canEditDocument, $user\_id, $documentHistories, $documentStatus, $document, $referenceNumber, $documentToken, $errorMessage, $documentSigningLinks, $otherDocumentSigningLinks, $tempUrlSignedDocument, $kategoriBerkas;

#### METHOD

render(), mount($pencairan\_id), unggahBerkasPencairanTahap2(), verifikasiDariAdmin(), verifikasiDariUnitPengelola(), mendaftarkanPenandatanganBerkas(), mengaturPosisiTandaTangan(), mengunggahBerkasKePrivy(), queryDocumentHistories(), queryDocumentStatus(),  queryTempUrlSignedDocument(), unduhSigned()



Nama Komponen

DaftarPengajuanImpor

#### DESKRIPSI

Akses admin untuk melihat, mengajukan, dan memperbarui status izin impor

#### **VARIABLE**

$listPengajuan, $paginate, $paginateOptions, $search, $filterPengajuan, $status\_filter, $applied\_status\_filter, $perguruanTinggi, $upOrAdmin, $filteredIds, $pengusuls, $listeners

#### METHOD

mount(), render(),&#x20;



Nama Komponen

BuatIzinImpor

#### DESKRIPSI

Akses admin untuk melihat, mengajukan, dan memperbarui status izin

#### **VARIABLE**

$openUploadModal, $addItemModalFundId, $kategori, $berkas, $kategoriBerkas,&#x20;

$berkasFundId, $tempBerkas, $searchPt, $list\_pt,  $selected\_kode\_pt, $selected\_nama\_pt, $nomor\_surat, $tanggal\_surat, $searchPengusul, $listPengusul, $list\_selected\_pengusul, $listItem, $nilai\_total\_impor, $item\_nama, $item\_deskripsi, $item\_alasan\_kebutuhan, $item\_kuantitas, $item\_harga\_satuan;

#### METHOD

mount(), updateSearchPT(), resetSearchPt(), searchPtQuery, updateSearchPengusul(), resetSearchPengusul(), searchPengusulQuery, render(), selectPt($kode\_pt, $nama\_pt), removePt(), addPengusul(), addPengusul($fund\_id, $nama, $judul), removePengusul($fund\_id), openUpload($kategori, $fund\_id = null), addBerkas(), removeUpload($kategori\_berkas, $fund\_id), addItem($fund\_id), removeItem($fund\_id, $i), submit()



Nama Komponen

DetailIzinImpor

#### DESKRIPSI

Akses admin untuk melihat, mengajukan, dan memperbarui status izin

**VARIABLE**

$id\_izin\_impor, $pengajuan, $openUploadModal, $showPreviewModal, $kategoriBerkas, $kategori, $berkas, $status, $nomor\_surat, $tanggal\_surat;

&#x20;$catatan, $fund\_id, $berkasFundId, $pengajuanStatus.

#### METHOD

mount(), updateStatus(), render(), openUpload($kategori, $fund\_id = null), uploadBerkas($fund\_id = null), removeUpload($fund\_id = null), submit(), downloadExcel($berkas)



**`2024`**

Nama Komponen

UsulanIndex

#### DESKRIPSI

Akses membuka list proposal dikti dari pengusul (tab Pengusul)

#### **VARIABLE**

$openFilter, $filterStatusKonsep, $filterStatusAdministrasi, $filterStatusRevisi, $filterStatusPraKontrak, $filterStatusEvaluasi, $filterStatusPresentasi, $filterStatusVeka, $filterBatch, $rules

#### METHOD

mount(), resetFilter(), changeTab($key), render()



Nama Komponen

UsulanShow

#### DESKRIPSI

Akses membuka detail proposal dari satu pengusul

#### **VARIABLE**

$proposal, $id\_proposa, $is\_admin\_dikti, $tab, $queryString

#### METHOD

mount(), render()



Nama Komponen

IndexRekaCipta

#### DESKRIPSI

Akses menu index kreasi reka dan peluang cipta

#### **VARIABLE**

$applied\_paginate, $applied\_year, $applied\_status, $applied\_search, $tab,$jumlahKreasiReka, $jumlahKreasiRekaDiterima, $jumlahKreasiRekaDiajukan, $jumlahPeluangCipta, $jumlahPeluangCiptaDiterima, $jumlahPeluangCiptaDiajukan;

#### METHOD

mount(),changeTab($tab), render()



Nama Komponen

ShowRekaCipta

#### DESKRIPSI

akses menu show atau detail dari kreasi reka dan peluang cipta

#### **VARIABLE**

$tipe\_bid, $id\_bid, $bid, $bidders

#### METHOD

mount(), render()



Nama Komponen

ReportAdminIndex

#### DESKRIPSI

#### **VARIABLE**

$filterStatusLaporan, $filterStatusLaporanSelected, $filterVerifikasiLaporan, $filterVerifikasiLaporanSelected, $paginate, $search

#### METHOD

updatingSearch(), mount(), render(),&#x20;



Nama Komponen

ReportAdminShow

#### DESKRIPSI

#### **VARIABLE**

$report, $openStatusModal, $statuses, $notes, $statusTo;

#### METHOD

mount($reportId), render(), save()



Nama Komponen

AdminKontrak

#### DESKRIPSI

**VARIABLE**

$search

#### METHOD

render()



Nama Komponen

Show

#### DESKRIPSI

#### **VARIABLE**

$kontrak, $tab $queryString

#### METHOD

render()



Nama Komponen

ProposalA3

#### DESKRIPSI

#### **VARIABLE**

\-

#### METHOD

render()



Nama Komponen

ProposalA3Show

#### DESKRIPSI

#### **VARIABLE**

$proposal, $tab $queryString

#### METHOD

render()

\


Nama Komponen

ProposalA3Show

#### DESKRIPSI

#### **VARIABLE**

$proposal, $tab $queryString

#### METHOD

render()



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

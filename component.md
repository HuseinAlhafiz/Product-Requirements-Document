# Component

### ADMIN

Nama Komponen

PergguruanTinggiIndex

**`[DESKRIPSI]`**

Akses membuka menu daftar perguruan tinggi (tab Perguruan Tinggi)

**`[VARIABLE]`**&#x20;

$search, $perPage, $perPageOptions

**`[METHOD]`**

mount(), render()



Nama Komponen

PerguruanTinggiShow

**`[DESKRIPSI]`**

akses membuka detail perguruan tinggi

**`[VARIABLE]`**&#x20;

$kode\_pt,  $search, $canExport = false, $is\_negeri, $tab,  $proposalStatuses $proposal\_status, $jadwal, $allProposalIds, $arr\_penetapan, $statusProposal, $pernah\_revisi, $nomor\_batch&#x20;

**`[METHOD]`**&#x20;

updatedSearch(), updatedStatusProposal, mount($pt), render(), getPengusuls()

\


Nama Komponen

PendaftaranPTIndex

**`[DESKRIPSI]`**

akses membuka daftar pendaftaran pada tab PendaftaranPT

**`[VARIABLE]`**&#x20;

$search, $perPage, $perPageOptions, $filters, $perFilter

**`[METHOD]`**&#x20;

mount($pt), updatingSearch(), render()



Nama Komponen

PendaftaranPTShow

**`[DESKRIPSI]`**

Akses membuka detail pendaftaran pada tab PendaftaranPT

**`[VARIABLE]`**&#x20;

$idPendaftaran, $pendaftaran, $ptPendaftaran, $komentarPendaftaran, $alertSimpanKomentar, $kategori\_berkas\_pengajuan\_akun, $kode\_pt, $sudah\_diterima, $pt, $is\_negeri

**`[METHOD]`**&#x20;

refreshPage(), mount($pt), simpanKomentar(), simpanKomentarModal(), handleKomentarTersimpan(), closeArt(), render(), diterima(), ditolak()



Nama Komponen

PengusulIndex

**`[DESKRIPSI]`**

Akses membuka list proposal dari pengusul (tab Pengusul)

**`[VARIABLE]`**&#x20;

$search, $jenis\_pt, $nomor\_batch, $proposalStatuses, $statusProposal, $pernah\_revisi, $proposal\_status, $jadwal, $reviewerPenugasan, $tab, $allProposalIds, $canExport, $is\_super\_admin, $arr\_penetapan

**`[METHOD]`**&#x20;

updatedSearch(), updatedJenisPT(), updatedStatusProposal(), mount(), render(), getPengusuls($paginate = 0), export(),&#x20;



NamaKomponen&#x20;

PengusulShow

**`[DESKRIPSI]`**

Akses membuka detail proposal dari satu pengusul

**`[VARIABLE]`**&#x20;

$proposals, $proposals\_desc, $ptab, $tab, $masterDocuments, $id\_proposal, $is\_volunteer, $documents, $riwayatPengusul, $proposalHistories, $showProposalHistory, $msgSyncStatus, $formInputSyncStatus, $syncStatusProposalConfirmation, $allTxProposalStatus, $queryString

**`[METHOD]`**&#x20;

Render(), mount(), fetchDocuments(), updateTab(), updatedFormInputSyncStatusKey($value), unduhRab(), getLastestHistory(), syncStatusProposal(), openSyncStatusProposalConfirmation(), fetchAllProposalStatus(($key = ''), generateBaMonev()



Nama Komponen

KontrakIndex

**`[DESKRIPSI]`**

Akses membuka list kontrak dari setiap perguruan tinggi

**`[VARIABLE]`**&#x20;

$tab, $paginateOptions, $selectedPaginate, $statusBerkas, $statusTtd, $search;

$nama\_dosen, $filterStatusBerkas, $allJenisKontrak, $filterJenisKontrak

**`[METHOD]`**&#x20;

updatedFilterJenisKontrak(), mount(), render()



Nama Komponen

KontrakDiksi

**`[DESKRIPSI]`**

Akses membuka list kontrak dari setiap DIKSI

**`[VARIABLE]`**&#x20;

$tab, $paginateOptions, $selectedPaginate, $statusBerkas, $statusTtd, $namaDosen, $search, $filterStatusBerkas, $allJenisKontrak, $filterJenisKontrak

**`[METHOD]`**&#x20;

mount(), render()



Nama Komponen

MergeDokumenKontrak

**`[DESKRIPSI]`**

Akses membuka merge dokumen kontrak

**`[VARIABLE]`**&#x20;

$showModal, $selectedKontrak, $paginateOptions, $selectedPaginate, $search, $listBerkas;

**`[METHOD]`**&#x20;

mount(), render(), openKontrak($kontrakId)



Nama Komponen

KontrakShow

**`[DESKRIPSI]`**

akses membuka detail dan informasi kontrak

**`[VARIABLE]`**&#x20;

$id\_kontrak, $kontrak, $tabKontrak, $queryString, $kontrakStatus, $proposals, $isEditForm, $total\_dana, $data, $listBerkas, $proposalDitetapkan, $inputNomorKontrak, $isPjVerified, $isRekeningVerified, $rekening, $pj, $isTransfer, $proposalStatuses, $proposalKontrakMitras, $adendumKhusus

**`[METHOD]`**&#x20;

mount(), getBerkas(), render(), setEditForm(), updateAdendumKhusus(), downloadAdendum(), deleteAdendum()



Nama Komponen

UpdloadDocumentSigningPage

**`[DESKRIPSI]`**

Akses membuka detail dan informasi kontrak

**`[VARIABLE]`**&#x20;

$current\_url, $user\_id, $kontrak\_id, $kategori\_berkas\_id, $kontrak, $kategori\_berkas, $temporary\_file, $temporary\_file\_url, $existing\_berkas, $existing\_berkas\_url, $recipients, $existing\_recipients, $canContinue, $canEdit, $listeners.

**`[METHOD]`**&#x20;

render(), mount(), evaluateCan(), updateKontrakStatus(), updateTemporaryFile, removeTemporaryFile(), removeExistingFile(),saveProgress(), addPerson($privy = NULL), removePerson($index), redirectToKontrak(), nextPagetoVerify().



Nama Komponen

VerifyDocumentSigningPage

**`[DESKRIPSI]`**

Akses membuka detail dan informasi kontrak

**`[VARIABLE]`**&#x20;

$current\_url, $kontrak\_id, $kategori\_berkas\_id, $kategori\_berkas, $user\_id, $listTxVerifBerkas, $existing\_berkas, $existing\_berkas\_url, $existing\_recipients, $open\_modal, $verif\_options, $current\_option, $canContinue, $canEdit, $listeners

**`[METHOD]`**&#x20;

mount(), rendeer(), updateKontrakStatus(), redirectToKontrak(), nextPageToTTE(), getRoleString($role\_id), changeStatus($value), submit().



Nama Komponen

ConfigurationTte

**`[DESKRIPSI]`**

Akses membuka detail dan informasi kontrak

**`[VARIABLE]`**&#x20;

$user\_id, $kontrak\_id, $kategori\_berkas\_id, $recipients, $openConfirmation, $temporaryUrl, $berkasFileName, $berkasId, $picked, $canEdit, $payload, $progressMessage, $showResponsePrivy, $errorMessage, $responseData, $isPrivyDocumentExist, $listeners, $rules

**`[METHOD]`**&#x20;

render(), mount(), updateKontrakStatus(), updateRecipients($\_, $key), updateShowResponsPrivy($value), handleErrorLoadPdf($reason), handleUpdateSelectedPosition($option), saveState(), sendKontrak(), handleHitPrivyApi(), handleSaveResponsePrivyApi($isError), nextPage().



Nama Komponen

PreviewUploadedDocument

**`[DESKRIPSI]`**

Akses membuka detail dan informasi kontrak

**`[VARIABLE]`**&#x20;

$user\_id, $kontrak, $kontrak\_id, $kategori\_berkas\_id, $isSysAdmin = false, $documentHistories, $documentStatus, $berkas, $document, $referenceNumber, $documentToken, $errorMessage, $documentSigningLinks, $otherDocumentSigningLinks, $tempUrlSignedDocument, public $canEditDocument

**`[METHOD]`**&#x20;

mount(), render(), loadData($user\_id = 0), updateKontrakStatus(), queryDocumentHistories(), queryDocumentStatus(), queryTempUrlSignedDocument(), unduh()



Nama Komponen

MitraIndex (ON GOING)

**`[DESKRIPSI]`**

Akses membuka tab Mitra

**`[VARIABLE]`**&#x20;

**`[METHOD]`**&#x20;

render()



Nama Komponen

ReviewerIndex (ON GOING)

**`[DESKRIPSI]`**&#x20;

Akses membuka tab Reviewer

**`[VARIABLE]`**&#x20;

$perPageOptions, $perPage, $search, $filters, $roles, $perFilter, $perRole

**`[METHOD]`**&#x20;

mount(), render(), openModalReviewerDetail($reviwerId), export()



Nama Komponen

ReviewerShow

**`[DESKRIPSI]`**

Akses membuka detail reviewer di tab Reviewer

**`[VARIABLE]`**&#x20;

$reviewer\_id, $dataPenugasan, $reviewer,  $isBersedia, $isHaveJadwalPenugasan, $bank, $keuangan, $kepegawaian

**`[METHOD]`**&#x20;

KesediaanUpdated(), mount($id), render(),&#x20;



Nama Komponen

UserManagement

**`[DESKRIPSI]`**

Akses membuka tab User Management

**`[VARIABLE]`**&#x20;

$page. $page\_list, $queryStrinh

**`[METHOD]`**&#x20;

render()



Nama Komponen

PengumumanIndex

**`[DESKRIPSI]`**

Akses manajemen Pengumuman

**`[VARIABLE]`**&#x20;

$search, $perPage, $perPageOptions, $filters, $open = false, $openEdit = false, $perFilter, $scheme\_filterFor, $idEdit, $judul, $informasi, $status, $target, $attachment, $rules

**`[METHOD]`**&#x20;

mount(), updatingSearch(), submit(), ubahPengumuman($id), simpanPerubahan(), render()



Nama Komponen

DashboardStatistikAdmin

**`[DESKRIPSI]`**

Akses membuka statistik umum proposal yang masuk

**`[VARIABLE]`**&#x20;

$satkerArray, $jumlahProposaAwalBelumDiverifikasi, $jumlahProposalAwalDiverifikasi, $jumlahProposalAwalDiterima, $jumlahProposalAwalDitolak, $jumlahProposalAwalDirevisi, $jumlahProposalPitching, $jumlahProposalPitchingLolos, $jumlahProposalPitchingTidakLolos, $jumlahProposalPitchingBelumSepakat, $allStatusesProposalAwalDiterima, $jumlahProposal, $jumlahProposalDikti, $jumlahProposalDiksi, $tipeProposal, $jumlahProposalAwalA1, $jumlahProposalAwalA2, $jumlahProposalAwalA3, $jumlahProposalAwalA4, $jumlahProposalAwalB1, $jumlahProposalAwalB2, $jumlahProposalPitchingA1, $jumlahProposalPitchingA2, $jumlahProposalPitchingA3, $jumlahProposalPitchingA4, $jumlahProposalPitchingB1, $jumlahProposalPitchingB2, $jumlahProposalAwalEkonomiBiru, $jumlahProposalAwalEkonomiDigital, $jumlahProposalAwalEkonomiHijau, $jumlahProposalAwalKemandirianKesehatan, $jumlahProposalAwalNonTematikUmum, $jumlahProposalAwalPenguatanPariwisata, $jumlahProposalPitchingEkonomiBiru $jumlahProposalPitchingEkonomiDigital, $jumlahProposalPitchingEkonomiHijau, $jumlahProposalPitchingKemandirianKesehatan, $jumlahProposalPitchingNonTematikUmum,$jumlahProposalPitchingPenguatanPariwisata, $jumlahProposalA1, $jumlahProposalA2, $jumlahProposalA3, $jumlahProposalA4, $jumlahProposalB1,$jumlahProposalB2, $jumlahProposalEkonomiBiru, $jumlahProposalEkonomiDigital, $jumlahProposalEkonomiHijau, $jumlahProposalKemandirianKesehatan, $jumlahProposalNonTematikUmum, $jumlahProposalPenguatanPariwisata, $fundIdsSemua, $fundIdsDikti, public $fundIdsDiksi, $filters, $filterBatch, $batch, $skema, $skemaCode, $tema, $lembaga,&#x20;

**`[METHOD]`**&#x20;

render(), iniData(), updatedTipeProposal(), updatedNomorBatch(), setJumlahProposal(), setSatkerArray()



Nama Komponen

DashboardStatistik2024

**`[DESKRIPSI]`**

Akses membuka statistik umum proposal yang masuk

**`[VARIABLE]`**&#x20;

$filterBatch, $ddlBatch, $allProposal, $ids\_proposal, $allStatus, $jenis\_pt, $jumlahProposalKeseluruhan, $jumlahProposalReka, $rekas

**`[METHOD]`**&#x20;

updatedFilterBatch(), updatedJenisPt(), mount(), render()



Nama Komponen

MonitoringIndex

**`[DESKRIPSI]`**

**`[VARIABLE]`**&#x20;

$penugasans, $proposals

**`[METHOD]`**&#x20;

mount(), render()



Nama Komponen

PusatBantuan

**`[DESKRIPSI]`**

**`[VARIABLE]`**&#x20;

$sub, $page, $pageList

**`[METHOD]`**&#x20;

render()



Nama Komponen

Export

**`[DESKRIPSI]`**

Akses membuka export sebagai admin

**`[VARIABLE]`**&#x20;

$isSysAdmin, $can, $search, $flag

**`[METHOD]`**&#x20;

render(), mount(), create(), access(), exportPelaporanDiksi($jenisDokumen, $flag)



Nama Komponen

SemHasDiktiIndex

**`[DESKRIPSI]`**

Akses admin untuk dapat melihat seminar

**`[VARIABLE]`**&#x20;

$search, $filter\_upload, $proposalStatuses, $statusProposal, $proposal\_status, $allProposalIds, $canExport, $is\_super\_admin, $tahun, $arr\_penetapan, $sqlQuery, $showDebug $queryString

**`[METHOD]`**&#x20;

updateSearch(), mount(), render(), getPengusuls($paginate = 0)



Nama Komponen

SeminarHasilShow

**`[DESKRIPSI]`**

Akses admin untuk dapat melihat seminar

**`[VARIABLE]`**&#x20;

$id\_proposal, $proposal, $seminarHasil, $listReviewerPenugasan, $showHasilPenilaian, $showHasilPenilaianRekon, $tab, $tabs, $isRekonActivated,  $openModalRekon

**`[METHOD]`**&#x20;

mount(), render(), checkRekonActivation, activateRekon(), loadTabs()



Nama Komponen

SemHasDiksiIndex (2022/2023)

**`[DESKRIPSI]`**

Akses admin untuk dapat melihat seminar diksi

**`[VARIABLE]`**&#x20;

$search, $filter\_upload, $proposalStatuses, $statusProposal, $proposal\_status,  $allProposalIds, $canExport, $is\_super\_admin, $tahun, $arr\_penetapan, $sqlQuery,  $showDebug, $submitted2023, $queryString

**`[METHOD]`**&#x20;

updateSearch(), mount(), render(), getPengusuls($paginate = 0), getPengusuls2023($paginate = 0)



Nama Komponen

SemHasDiksiShow

**`[DESKRIPSI]`**

Akses admin untuk dapat melihat seminar diksi

**`[VARIABLE]`**&#x20;

$id\_proposal, $proposal, $seminarHasil, $listReviewerPenugasan, $showHasilPenilaian, $showHasilPenilaianRekon, $tab, $tabs, public $edutype, $fiscal\_year, $isRekonActivated, $openModalRekon

**`[METHOD]`**&#x20;

mount(), render(), checkRekonActivation(), activateRekon(), loadTabs()



Nama Komponen

PencairanIndex

**`[DESKRIPSI]`**

Akses admin untuk melakukan pencairan

**`[VARIABLE]`**&#x20;

$isThereAnyData, $kontrak, $danaTahap2, $pencairans, $pencairan, $openModal, $isAdmin, $step\_pembayaran, $step\_berkas, $stepPembayaran $stepBerkas

**`[METHOD]`**&#x20;

mount(), saveChange($id), showModal($index), generateBerkas($idx), render()



Nama Komponen

PencairanShow (ON GOING)

**`[DESKRIPSI]`**

Akses admin untuk melakukan pencairan

**`[VARIABLE]`**&#x20;

\-

**`[METHOD]`**&#x20;

render()



Nama Komponen

BuatPencairan2 (ON GOING)

**`[DESKRIPSI]`**

Akses membuat pencairan tahap 2

**`[VARIABLE]`**&#x20;

$proposals, $kontrak, $id\_kontrak, $isProposalSelected, $isProposalEligible;, $selectedFundIds, $danaTahap2

**`[METHOD]`**&#x20;

mount(), selectProposal($fund\_id), createPencairan, render()



Nama Komponen

UnggahBerkasTahap2

**`[DESKRIPSI]`**

**`[VARIABLE]`**&#x20;

$editable, $pencairan, $recipients, $person, $berkas, $kategoriBerkas, $verifikasiAdmin, $verifikasiUnitPengelola, $fileUpload, $isAdmin, $isUnitPengelola, $rules

**`[METHOD]`**&#x20;

render(), mount($pencairan\_id), removeTemporary(), saveTemporary(), removeBerkas(), saveBerkas(), updatedVerifikasiAdmin(), updatedVerifikasiUnitPengelola(), addPerson($privyId = null, $tipeUser = 1, $eMaterai = 0), removePerson($index), simpanRecipient(),&#x20;



Nama Komponen

TandaTanganBerkasTahap2

**`[DESKRIPSI]`**

**`[VARIABLE]`**&#x20;

$user\_id, $pencairan, $recipients, $isAdmin, $editable, $openConfirmation, $temporaryUrl, $berkasFileName, $berkasId, $picked, $payload, $progressMessage, $showResponsePrivy&#x20;

$errorMessage, $responseData, $isPrivyDocumentExist, $isBerkasExist, $listeners, $rules,&#x20;

**`[METHOD]`**&#x20;

render(), mount($pencairan\_id), updatedRecipients($\_, $key), updatedShowResponsePrivy($value), handleErrorLoadPdf($reason), handleUpdateSelectedPosition($option), saveState(), sendKontrak(), handleHitPrivyApi(), handleSaveResponsePrivyApi($isError).



Nama Komponen

TandaTanganBerkasTahap2

**`[DESKRIPSI]`**

**`[VARIABLE]`**&#x20;

$todoList, $pencairan, $berkas, $recipients, $privyDoc, $isSysAdmin, $canEditDocument, $user\_id, $documentHistories, $documentStatus, $document, $referenceNumber, $documentToken, $errorMessage, $documentSigningLinks, $otherDocumentSigningLinks, $tempUrlSignedDocument, $kategoriBerkas;

**`[METHOD]`**&#x20;

render(), mount($pencairan\_id), unggahBerkasPencairanTahap2(), verifikasiDariAdmin(), verifikasiDariUnitPengelola(), mendaftarkanPenandatanganBerkas(), mengaturPosisiTandaTangan(), mengunggahBerkasKePrivy(), queryDocumentHistories(), queryDocumentStatus(),  queryTempUrlSignedDocument(), unduhSigned()



Nama Komponen

KelengkapanTanganBerkasTahap2

**`[DESKRIPSI]`**

**`[VARIABLE]`**&#x20;

$todoList, $pencairan, $berkas, $recipients, $privyDoc, $isSysAdmin, $canEditDocument, $user\_id, $documentHistories, $documentStatus, $document, $referenceNumber, $documentToken, $errorMessage, $documentSigningLinks, $otherDocumentSigningLinks, $tempUrlSignedDocument, $kategoriBerkas;

**`[METHOD]`**&#x20;

render(), mount($pencairan\_id), unggahBerkasPencairanTahap2(), verifikasiDariAdmin(), verifikasiDariUnitPengelola(), mendaftarkanPenandatanganBerkas(), mengaturPosisiTandaTangan(), mengunggahBerkasKePrivy(), queryDocumentHistories(), queryDocumentStatus(),  queryTempUrlSignedDocument(), unduhSigned()



Nama Komponen

DaftarPengajuanImpor

**`[DESKRIPSI]`**

Akses admin untuk melihat, mengajukan, dan memperbarui status izin impor

**`[VARIABLE]`**&#x20;

$listPengajuan, $paginate, $paginateOptions, $search, $filterPengajuan, $status\_filter, $applied\_status\_filter, $perguruanTinggi, $upOrAdmin, $filteredIds, $pengusuls, $listeners

**`[METHOD]`**&#x20;

mount(), render(),&#x20;



Nama Komponen

BuatIzinImpor

**`[DESKRIPSI]`**

Akses admin untuk melihat, mengajukan, dan memperbarui status izin

**`[VARIABLE]`**&#x20;

$openUploadModal, $addItemModalFundId, $kategori, $berkas, $kategoriBerkas,&#x20;

$berkasFundId, $tempBerkas, $searchPt, $list\_pt,  $selected\_kode\_pt, $selected\_nama\_pt, $nomor\_surat, $tanggal\_surat, $searchPengusul, $listPengusul, $list\_selected\_pengusul, $listItem, $nilai\_total\_impor, $item\_nama, $item\_deskripsi, $item\_alasan\_kebutuhan, $item\_kuantitas, $item\_harga\_satuan;

**`[METHOD]`**&#x20;

mount(), updateSearchPT(), resetSearchPt(), searchPtQuery, updateSearchPengusul(), resetSearchPengusul(), searchPengusulQuery, render(), selectPt($kode\_pt, $nama\_pt), removePt(), addPengusul(), addPengusul($fund\_id, $nama, $judul), removePengusul($fund\_id), openUpload($kategori, $fund\_id = null), addBerkas(), removeUpload($kategori\_berkas, $fund\_id), addItem($fund\_id), removeItem($fund\_id, $i), submit()



Nama Komponen

DetailIzinImpor

**`[DESKRIPSI]`**

Akses admin untuk melihat, mengajukan, dan memperbarui status izin

**`[VARIABLE]`**&#x20;

$id\_izin\_impor, $pengajuan, $openUploadModal, $showPreviewModal, $kategoriBerkas, $kategori, $berkas, $status, $nomor\_surat, $tanggal\_surat;

&#x20;$catatan, $fund\_id, $berkasFundId, $pengajuanStatus.

**`[METHOD]`**&#x20;

mount(), updateStatus(), render(), openUpload($kategori, $fund\_id = null), uploadBerkas($fund\_id = null), removeUpload($fund\_id = null), submit(), downloadExcel($berkas)



**`2024`**

Nama Komponen

UsulanIndex

**`[DESKRIPSI]`**

Akses membuka list proposal dikti dari pengusul (tab Pengusul)

**`[VARIABLE]`**&#x20;

$openFilter, $filterStatusKonsep, $filterStatusAdministrasi, $filterStatusRevisi, $filterStatusPraKontrak, $filterStatusEvaluasi, $filterStatusPresentasi, $filterStatusVeka, $filterBatch, $rules

**`[METHOD]`**&#x20;

mount(), resetFilter(), changeTab($key), render()



Nama Komponen

UsulanShow

**`[DESKRIPSI]`**

Akses membuka detail proposal dari satu pengusul

**`[VARIABLE]`**&#x20;

$proposal, $id\_proposa, $is\_admin\_dikti, $tab, $queryString

**`[METHOD]`**&#x20;

mount(), render()



Nama Komponen

IndexRekaCipta

**`[DESKRIPSI]`**

Akses menu index kreasi reka dan peluang cipta

**`[VARIABLE]`**&#x20;

$applied\_paginate, $applied\_year, $applied\_status, $applied\_search, $tab,$jumlahKreasiReka, $jumlahKreasiRekaDiterima, $jumlahKreasiRekaDiajukan, $jumlahPeluangCipta, $jumlahPeluangCiptaDiterima, $jumlahPeluangCiptaDiajukan;

**`[METHOD]`**&#x20;

mount(),changeTab($tab), render()



Nama Komponen

ShowRekaCipta

**`[DESKRIPSI]`**

akses menu show atau detail dari kreasi reka dan peluang cipta

**`[VARIABLE]`**&#x20;

$tipe\_bid, $id\_bid, $bid, $bidders

**`[METHOD]`**&#x20;

mount(), render()



Nama Komponen

ReportAdminIndex

**`[DESKRIPSI]`**

**`[VARIABLE]`**&#x20;

$filterStatusLaporan, $filterStatusLaporanSelected, $filterVerifikasiLaporan, $filterVerifikasiLaporanSelected, $paginate, $search

**`[METHOD]`**&#x20;

updatingSearch(), mount(), render(),&#x20;



Nama Komponen

ReportAdminShow

**`[DESKRIPSI]`**

**`[VARIABLE]`**&#x20;

$report, $openStatusModal, $statuses, $notes, $statusTo;

**`[METHOD]`**&#x20;

mount($reportId), render(), save()



Nama Komponen

AdminKontrak

**`[DESKRIPSI]`**

**`[VARIABLE]`**&#x20;

$search

**`[METHOD]`**&#x20;

render()



Nama Komponen

Show

**`[DESKRIPSI]`**

**`[VARIABLE]`**&#x20;

$kontrak, $tab $queryString

**`[METHOD]`**&#x20;

render()



Nama Komponen

ProposalA3

**`[DESKRIPSI]`**

**`[VARIABLE]`**&#x20;

\-

**`[METHOD]`**&#x20;

render()



Nama Komponen

ProposalA3Show

**`[DESKRIPSI]`**

**`[VARIABLE]`**&#x20;

$proposal, $tab $queryString

**`[METHOD]`**&#x20;

render()

\


Nama Komponen

ProposalA3Show

**`[DESKRIPSI]`**

**`[VARIABLE]`**&#x20;

$proposal, $tab $queryString

**`[METHOD]`**&#x20;

render()



### ADMIN VOLUNTEER



Nama Komponen

VolunteerPengusulIndex

**`[DESKRIPSI]`**

Akses untuk admin volunter ke daftar usulan

**`[VARIABLE]`**&#x20;

$proposals, $allProposalIds, $tab, $statusProposa, $pernah\_revisi;

**`[VARIABLE]`**

mount(), render(), getPengusuls($paginate = 0)



Nama Komponen

PengusulShow

**`[DESKRIPSI]`**

Akses untuk admin volunter ke detail usulan

**`[VARIABLE]`**&#x20;

$proposa, $proposal\_desc, $ptab = 'seleksi', $tab, $masterDocuments, $id\_proposal, $is\_volunteer, $documents, $riwayatPengusul, $proposalHistories, $showProposalHistory, $msgSyncStatus, $formInputSyncStatus, $syncStatusProposalConfirmation, $allTxProposalStatus, $queryString

**`[VARIABLE]`**

render(), mount(), fetchDocuments(), updateTab(), updatedFormInputSyncStatusKey($value), unduhRab(), getLastestHistory(), syncStatusProposal(), openSyncStatusProposalConfirmation(), fetchAllProposalStatus($key = ''), generateBaMonev()



### REVIEWER



Nama Komponen

ReviewerPenugasanIndex

**`[DESKRIPSI]`**

Akses membuka daftar tugas yang diberikan sebagai Reviewer

**`[VARIABLE]`**&#x20;

$isDebug, $reviewer, $penugasan, $penugasan\_de, $penugasan\_pitching, $penugasan\_veka, $isBersedia, $isHaveJadwalPenugasan, $bank, $keuangan, $kepegawaian, $tab, $search, $allFilterTanggal, $filterTanggal, $allFilterJenis, $filterJenis, $isBersediaDeskEval, $isHaveJadwalPenugasanDeskEval, $numOfSemhasDiksi2023,  $listeners, $queryString

**`[METHOD]`**

kesediaanUpdated(), updatedTab(), updatedSearch(), updatedFilterTanggal(), updatedFilterJenis(), semhasDiksi2023(), mount(), render()



Nama Komponen

ReviewerPenugasanShow

**`[DESKRIPSI]`**

Akses membuka detail tugas yang diberikan sebagai Reviewer

**`[VARIABLE]`**&#x20;

$tugas, $proposal\_desc, $list\_dokumen, $isReviewersDoneGrading, $isReviewersDoneRekon, $txRekon, $key, $lembar\_kerja, $tab, $queryString, $riwayatPengusul, $proposal

**`[METHOD]`**

mount(), getDokumen(), checkStatus(), checkRekon(), render()



Nama Komponen

PenugasanReviewerSemhas

**`[DESKRIPSI]`**

Akses membuka detail tugas yang diberikan sebagai Reviewer

**`[VARIABLE]`**&#x20;

$fiscal\_year, ReviewerPenugasan $tugas, TkaiProposal $proposal, $key, $tab, $lembar\_kerja, $seminarHasil, $showRekon

**`[METHOD]`**

checkRekon(), mount(), render()



Nama Komponen

PenugasanReviewerMonev

**`[DESKRIPSI]`**

Akses membuka detail tugas yang diberikan sebagai Reviewer

**`[VARIABLE]`**&#x20;

$tugas, $proposal, $proposal\_desc, $dokumen,  $key, $tab,  $lembar\_kerja, $seminarHasil, $showRekon, $laporanKemajuan;

**`[METHOD]`**

mount(), downloadRab(), render()



Nama Komponen

EvaluasiProposal

**`[DESKRIPSI]`**

**`[VARIABLE]`**&#x20;

$tugas, $proposal, $is\_rekon\_activated, $lastReminder,  $canRemind = false, $isDone, $isOtherReviewerNotDone, $tab

**`[METHOD]`**

mount(), render(), remind(), reminderCacheKey(), loadLastReminder(), loadCanRemind(), loadDoneStatuses()



Nama Komponen

PresentasiProposal

**`[DESKRIPSI]`**

**`[VARIABLE]`**&#x20;

$tugas, $proposal, $tab, $files

**`[METHOD]`**

mount(), render()



Nama Komponen

VekaProposal

**`[DESKRIPSI]`**

**`[VARIABLE]`**&#x20;

$tugas, $proposal, $tab

**`[METHOD]`**

mount(), render()



### UNIT PENGELOLA



NamaKomponen&#x20;

UnitPengelolaIndex

**`[DESKRIPSI]`**

Akses membuka daftar proposal yang diajukan PT sebagai Unit Pengelola

**`[VARIABLE]`**&#x20;

$search, $tahapanProposal, $perguruanTinggi, $penanggungJawabPt, $rekeningKontrak, $proposalsId, $proposalStatuses, $proposalKontrakMitras, $enableLaporan

**`[VARIABLE]`**

mount(), render()



NamaKomponen&#x20;

UnitPengeloShow

**`[DESKRIPSI]`**

Akses membuka detail progress proposal yang diajukan PT sebagai Unit Pengelola

**`[VARIABLE]`**

$proposal, $tab, $documents, $proposal\_desc,  $id\_proposal, $tahap\_proposal, $tahap\_proposal\_flag, $queryString

**`[METHOD]`**&#x20;

setTahapProposalFlag(), changeTab($tab), mount(), render()



NamaKomponen&#x20;

UnitPengeloKontrakIndex

**`[DESKRIPSI]`**

Akses membuka list kontrak dari setiap perguruan tinggi untuk Unit Pengelola PT

**`[VARIABLE]`**

$tab, $paginateOptions, $selectedPaginate, $statusBerkas, $statusTtd, $search, $nama\_dosen, $filterStatusBerkas$proposalDitetapkans, $proposalTerkontrak, $danaProposalDitetapkans, $danaProposalTerkontrak, $danaProposalBelumTerkontrak, $perguruanTinggi;

**`[METHOD]`**&#x20;

mount(), render(), create()



NamaKomponen&#x20;

CreateKontrak

**`[DESKRIPSI]`**

Akses membuka list kontrak dari setiap perguruan tinggi untuk Unit Pengelola PT

**`[VARIABLE]`**

$isBuatRekeningBaru, $isBuatPjBaru, $selectedPj, $selectedRekening, $user, $perguruanTinggi, $searchPj, $searchRekening, $existingRekening, $existingPj,$listProposals, $isProposalContracted, $isProposalSelected, $selectedFundIds, $penetapanProposals, $kategoriBerkasNpwp, $kategoriBerkasKopSurat, $uploadedNpwp, $uploadedKop, $newKontrak, $penanggungJawab, $rekeningKontrak, $banks, $jenisRekeningKontrak, $jenisKontrak;

**`[METHOD]`**&#x20;

rules(), messages(), validationAttributes(), updateSearchRekening(), updateSearchPJ(), updateIsBuatRekeningBaru(), updateIsBuatPjBaru(), selectRekening($val), selectPj($val), updated($propertyName), mount(), selectProposal($fundId),  loadExistingPj(), loadExistingRekening(), loadProposals(), generateNewKontrak(), generatePenanggungJawab(), generateRekeningKontrak(), simpan(), render()



NamaKomponen&#x20;

UnitPengeloKontrakShow

**`[DESKRIPSI]`**

Akses membuka detail dan informasi kontrak untuk Unit Pengelola PT

**`[VARIABLE]`**

$tab, $queryString, $id\_kontrak, $kontrak, $proposals, $total\_dana, $data, $kategoriBerkas, $proposalDitetapkan;

**`[METHOD]`**&#x20;

mount(), getBerkas(), render(), changeTab($tab)



NamaKomponen&#x20;

VerifikasiUploadDocumentPrivy

**`[DESKRIPSI]`**

Akses membuka detail dan informasi kontrak untuk Unit Pengelola PT

**`[VARIABLE]`**

$tab, $queryString, $id\_kontrak, $kontrak, $proposals, $total\_dana, $data, $kategoriBerkas, $proposalDitetapkan;

**`[METHOD]`**&#x20;

mount(),  render(), evaluateCan(), updateKontrakStatus(), redirectToKontrak(), changeStatus($value), submit(),&#x20;



NamaKomponen&#x20;

DaftarPengajuaImporUp

**`[DESKRIPSI]`**

Akses unit pengelola untuk melihat dan mengajukan izin impor

**`[VARIABLE]`**

$listPengajuan, $paginate, $paginateOptions, $search, $filterPengajuan, $status\_filter, $applied\_status\_filter, $perguruanTinggi, $izinImporUp, $listeners

**`[METHOD]`**&#x20;

mount(),  render(),&#x20;



NamaKomponen&#x20;

BuatIzinImporUp

**`[DESKRIPSI]`**

Akses unit pengelola untuk melihat dan mengajukan izin impor

**`[VARIABLE]`**

$kategori, $berkas, $kategoriBerkas, $berkasFundId, $tempBerkas, $selected\_kode\_pt, $selected\_nama\_pt, $searchPt, $list\_pt, $nomor\_surat, $tanggal\_surat,  $searchPengusul, $listPengusul, $list\_selected\_pengusul, $listItem, $nilai\_total\_impor, $item\_nama, $item\_deskripsi, $item\_alasan\_kebutuhan, $item\_kuantitas, $item\_harga\_satuan;

**`[METHOD]`**&#x20;

mount(), updatedSearchPt(), resetSearchPt(), searchPtQuery(), updatedSearchPengusul(), resetSearchPengusul(), searchPengusulQuery(), render(), selectPt($kode\_pt, $nama\_pt), removePt(), addPengusul($fund\_id, $nama, $judul), removePengusul($fund\_id), openUpload($kategori, $fund\_id = null), addBerkas(), removeUpload($kategori\_berkas, $fund\_id), addItem($fund\_id), removeItem($fund\_id, $i), submit()



NamaKomponen&#x20;

DetaiIzinImporUp

**`[DESKRIPSI]`**

Akses unit pengelola untuk melihat dan mengajukan izin impor

**`[VARIABLE]`**

$id\_izin\_impor, $pengajuan, $openUploadModal, $showPreviewModal,  $kategoriBerkas, $kategori, $berkas,  $status, $nomor\_surat, $tanggal\_surat, $catatan, $fund\_id, $berkasFundId,  $pengajuanStatus

**`[METHOD]`**&#x20;

mount(), updateStatus(), render(), downloadExcel($berkas)



NamaKomponen&#x20;

Laporan

**`[DESKRIPSI]`**

**`[VARIABLE]`**

$perguruanTinggi;

**`[METHOD]`**&#x20;

mount(),  render()



**`2024`**



NamaKomponen&#x20;

UnitPengelola2024index

**`[DESKRIPSI]`**

Akses membuka daftar proposal yang diajukan PT sebagai Unit Pengelola

**`[VARIABLE]`**

$search, $perguruanTinggi, $unitPengelola, $penandaTangan, $rekening, $tab, $queryString

**`[METHOD]`**&#x20;

mount(),  render()



NamaKomponen&#x20;

UnitPengelola2024Show

**`[DESKRIPSI]`**

Akses membuka detail progress proposal yang diajukan PT sebagai Unit Pengelola

**`[VARIABLE]`**

$proposal, $proposal\_id,  $tab, $queryString

**`[METHOD]`**&#x20;

mount(),  render()



NamaKomponen&#x20;

BuatKontrak

**`[DESKRIPSI]`**

**`[VARIABLE]`**

$perguruanTinggi, $unitPengelola, $penandaTangan, $rekening, $mekanisme, $direktorat, $proposals, $selectedProposals, $terkontrak

**`[METHOD]`**&#x20;

mount(), tambahProposal($id), hapusProposal($id), simpan(), render()



NamaKomponen&#x20;

Kontrak

**`[DESKRIPSI]`**

**`[VARIABLE]`**

$kontrak, $tab, $queryString

**`[METHOD]`**&#x20;

render()



### OPERATOR



Nama Komponen

PerguruanTinggiRegister

**`[DESKRIPSI]`**

Akses membuka formulir pendaftaran Unit Pengelola sebagai Operator

**`[VARIABLE]`**&#x20;

$unit\_pengelola, $is\_mengajukan, $is\_edit = false, $kode\_pt,  $listeners

**`[METHOD]`**

mount(), render(), editUlang(), PendaftaranUnitPengelolaCreated()



NamaKomponen&#x20;

EditDaftarUp

**`[DESKRIPSI]`**

Akses membuka formulir pendaftaran Unit Pengelola sebagai Operator

**`[VARIABLE]`**&#x20;

$pj\_nama, $pj\_alamat, $pj\_telp, $pj\_nomor, $pj\_surel, $up\_nama, $up\_alamat, $up\_telp, $up\_nomor, $up\_surel, $bp\_nama, $bp\_nama\_ketua, $bp\_alamat, $bp\_telp, $bp\_nomor, $kode\_pt, $perguruan, $up;

**`[METHOD]`**

mount(), render(), rules(), submit()



### FRONT OFFICE

Nama Komponen

FoIndex

**`[DESKRIPSI]`**

Akses melihat seluruh status proposal pada sistem backoffice

**`[VARIABLE]`**&#x20;

$tab, $key, $search\_fundid, $value

**`[METHOD]`**

detail($fund\_id), changeTab($tab), render()



Nama Komponen

**FoShow**

**`[DESKRIPSI]`**

Akses melihat seluruh status proposal pada sistem backoffice

**`[VARIABLE]`**&#x20;

$proposal, $historyFO, $latestFO, $historyBO, $latestBO, $fullHistory

**`[METHOD]`**

mount($fund\_id),loadFullHistory(), render()



Nama Komponen

ProposalDescriptionIndex

**`[DESKRIPSI]`**

Akses melihat seluruh deskripsi proposal pada sistem backoffice

**`[VARIABLE]`**&#x20;

$columns

**`[METHOD]`**

render()



Nama Komponen

ProposalDescriptionShow

**`[DESKRIPSI]`**

Akses melihat seluruh deskripsi proposal pada sistem backoffice

**`[VARIABLE]`**&#x20;

$proposalDescription

**`[METHOD]`**

render(), mount($description\_id)



### PENGUSUL

Nama Komponen

Dashboard

**`[DESKRIPSI]`**

Akses pengusul untuk melihat laman informasi pengusul beserta proposal dan daftar kolaborasi

**`[VARIABLE]`**&#x20;

$skemaProposal, $pilihSkemaModal, $innovator

**`[METHOD]`**

goesToUnggahProposal(), singkronData(), mount(), render()



Nama Komponen

Proposal

**`[DESKRIPSI]`**

Akses pengusul untuk melihat detail dari proposal yang telah diajukan

**`[VARIABLE]`**&#x20;

$proposal, $tab, $isDiksi&#x20;

**`[METHOD]`**

mount(), render()



NamaKomponen&#x20;

PengajuanProposal

**`[DESKRIPSI]`**

Akses pengusul untuk mengajukan proposal baru untuk masuk ke selesksi administrasi

**`[VARIABLE]`**&#x20;

$tahapanPengajuanProposal, $currentTahapPengajuan, $selectedTahapPengajuan, $listSkemaProposal, $showTambahDosenModal, $showTambahNonDosenModal, $daftarNonDosenTerlibat, $isianNamaDosen, $isianNamaNonDosen, $draftProposal, $jenjangPendidikans, $jumlahMahasiswaPerJenjang,  $proposal, $innovatorId, $allTema

$rules, $draftProposalDosenTerlibat, $draftProposalNonDosenTerlibat.

**`[METHOD]`**

updatedJumlahMahasiswaPerJenjang(), mount(), moveToTahap($key), saveProposal(), render()



NamaKomponen&#x20;

PengusulShowProposal

**`[DESKRIPSI]`**

Akses pengusul untuk melihat detail dari proposal yang telah diajukan

**`[VARIABLE]`**&#x20;

$isPengusul, public $proposal, $statusProposal, $proposal\_desc, $tab, $masterDocuments, $id\_proposal, $documents, $riwayatPengusul, proposalHistories, $showProposalHistory, $msgSyncStatus, $formInputSyncStatus, $syncStatusProposalConfirmation $allTxProposalStatus, public $lorem;

**`[METHOD]`**

mount(), render()

\


\


\

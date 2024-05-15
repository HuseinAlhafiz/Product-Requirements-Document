# Page

## ADMIN

***

1. **/perguruan-tinggi**

#### CARA AKSES

Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard , Pilih navigasi admin (DIKTI), Pilih opsi Perguruan Tinggi pada dropdown.

#### PERMISSION

> perguruan-tinggi-menu

#### REDIRECT&#x20;

{% code fullWidth="false" %}
```
admin/perguruan-tinggi/{pt}
```
{% endcode %}



2. **/perguruan-tinggi/{pt}**

#### CARA AKSES

Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Perguruan Tinggi pada dropdown, Pilih Perguruan Tinggi yang dituju.

#### PERMISSION

> perguruan-tinggi.show-menu

#### REDIRECT

```
admin/pengusul/{id_proposal} 
```

3. **/pendaftaran-pt**&#x20;

#### CARA AKSES

Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard , Pilih navigasi admin (DIKTI), Pilih opsi Daftar Pengajuan Unit Pengelola pada dropdown

#### PERMISSION

pendaftaran-pt-menu

#### REDIRECT

```
admin/pendaftaran-pt/{pt}
```



4. **/pendaftaran-pt/{pt}**&#x20;

#### CARA AKSES

Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Daftar Pengajuan Unit Pengelola pada dropdown, Pilih Detail Pendaftaran Pengelola MF yang dituju dengan mengetuk ikon pencarian "searchbar".

#### PERMISSION

pendaftaran-pt-show-menu

#### REDIRECT

\-



5. **/pengusul**

#### CARA AKSES

Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi ProposalMF2023 pada dropdown.

#### PERMISSION

pengusul-menu

#### REDIRECT

```
admin/pengusul/{id_proposal}
```



**/pengusul/{id\_proposal}**

#### CARA AKSES

Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi ProposalMF2023 pada dropdown, Pilih proposal yang dituju

#### PERMISSION

pengusul.show-menu

#### REDIRECT

\-



6. **/kontrak**

#### `CARA AKSES`

Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard , Pilih navigasi admin (DIKTI), Pilih opsi KontrakMF2023 pada dropdown.

#### PERMISSION

kontrak-menu

#### REDIRECT

```
admin/kontrak/{id_kontrak}
```



7. **`/diksi-kontrak (skip dulu)`**

#### CARA AKSES 

#### PERMISSION

diksi-kontrak-menu

#### REDIRECT



8. **/kontrak/merge-dokumen-kontrak**

#### CARA AKSES

Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Merge Dokumen Kontrak pada dropdown.

#### PERMISSION

kontrak.merge-dokumen-kontrak

#### REDIRECT

\-

\


9. **/kontrak/{id\_kontrak}**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/)., Masuk ke dalam menu dashboard., Pilih navigasi admin (DIKTI), Pilih opsi Kontrak MF 2023 pada dropdown, Pilih detail kontrak yang dituju dengan mengetuk ikon pencarian "searchbar".

#### PERMISSION

kontrak.show-menu

#### REDIRECT

\-



10. **/kontrak/{kontrak\_id}/upload/{kategori\_berkas\_id} (ini juga skip dulu)**

#### CARA AKSES



#### PERMISSION

kontrak.show-menu

#### REDIRECT



11. **/kontrak/{kontrak\_id}/verifikasi/{kategori\_berkas\_id}  (ini juga skip dulu)**

#### CARA AKSES



#### PERMISSION



kontrak.show-menu

#### REDIRECT

\


12. **/kontrak/{kontrak\_id}/preview/{kategori\_berkas\_id} (ini juga skip dulu)**

#### CARA AKSES

#### PERMISSION

kontrak.show-menu

#### REDIRECT



13. **/mitra (On Going)**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Mitra pada dropdown.

#### PERMISSION

mitra-menu

#### REDIRECT

\-



14. **/reviewer**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/)., Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi reviewer pada dropdown.

#### PERMISSION

reviewer-menu

#### REDIRECT

```
admin/reviewer/{id}
```



15. **/reviewer/{id}**

#### CARA AKSES

1. Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Reviewer pada dropdown, Pilih detail kontrak yang dituju dengan mengetuk ikon pencarian "searchbar", Pilih opsi View pada menu ikon yang tercantum pada bagian Aksi.

#### PERMISSION

reviewer-show-menu

#### REDIRECT

```
admin/pegusul/{id_proposal}
```



16. **/user-management**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi User Management pada dropdown.

#### PERMISSION

user-management-menu

#### REDIRECT

\-



17. **/manajemen-pengumuman**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Manajemen Pengumuman pada dropdown.

#### PERMISSION

Manajemen-pengumuman &#x20;

#### REDIRECT

\-



18. **/statistik (Skip dulu)**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Statistik pada dropdown.

#### PERMISSION

akses-statistik

#### REDIRECT

\-



19. **/statistik-2024 (Skip dulu)**

#### CARA AKSES



#### PERMISSION

akses-statistik-2024

#### REDIRECT

\-



20. **/monitoring**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Papan Monitoring VK pada dropdown.

#### PERMISSION

\-

#### REDIRECT

\-



21. **/pusatbantuan**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Papan Monitoring VK pada dropdown.

#### PERMISSION

\-

#### REDIRECT

\-



22. **/export**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/)., Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Export pada dropdown.

#### PERMISSION

export-document

#### REDIRECT

\-



23. **/seminar-hasil-2022-dikti**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Seminar Hasil DIKTI 2022 pada dropdown.

#### PERMISSION

seminar-admin

#### REDIRECT

```
/seminar-hasil-2022-dikti/{id_proposal}
```



24. **/seminar-hasil-2022-dikti/{id\_proposal}**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Seminar Hasil DIKTI 2022 pada dropdown, Pilih proposal yang dituju dengan mengetuk ikon pencarian "searchbar".

#### PERMISSION

seminar-admin

#### REDIRECT

\-



25. **seminar-hasil-diksi/2022**&#x20;

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKSI), Pilih opsi Seminar Hasil DIKSI 2022 pada dropdown.

#### PERMISSION

seminar-admin-diksi

#### REDIRECT

```
/seminar-hasil-diksi/{fiscal_year}/{id_proposal}
```



26. **seminar-hasil-diksi/2023 (Skip Dulu)**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKSI), Pilih opsi Seminar Hasil DIKSI 2023 pada dropdown.

#### PERMISSION

seminar-admin-diksi

#### REDIRECT

\-



27. **/seminar-hasil-diksi/{fiscal\_year}/{id\_proposal}**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKSI), Pilih opsi Seminar Hasil DIKSI 2023 pada dropdown, Pilih proposal yang dituju dengan mengetuk ikon pencarian "searchbar".

#### PERMISSION

seminar-admin-diksi

#### REDIRECT

\-



28. **/pencairan**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Daftar Pencairan pada dropdown.

#### PERMISSION

pencairan-admin-index

#### REDIRECT

```
/pencairan/{id}
```



29. **/pencairan/{id}**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Daftar Pencairan pada dropdown.

\[PERMISSION]&#x20;

pencairan-admin-index

#### REDIRECT

\-



30. **/kontrak/{id\_kontrak}/pencairan-tahap-2**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Kontrak PDP 2024 pada dropdown, Pilih Kontrak yang dituju dengan mengetuk ikon pencarian "searchbar".

#### PERMISSION

pencairan-tahap-2

#### REDIRECT

\-



31. **/kontrak/{pencairan\_id}/unggah-berkas-tahap-2 (Skip Dulu)**

#### CARA AKSES

#### PERMISSION

\-

#### REDIRECT

\-



32. **/kontrak/{pencairan\_id}/tanda-tangan-berkas-tahap-2 (Skip Dulu)**

#### CARA AKSES

\-

#### PERMISSION

\-

#### REDIRECT

\-



33. **/kontrak/{pencairan\_id}/kelengkapan-berkas-tahap-2(Skip Dulu)**

#### CARA AKSES

#### PERMISSION

\-

#### REDIRECT

\-

\


34. **/izin-impor**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Izin Import pada dropdown.

#### PERMISSION

izin-impor

#### REDIRECT

```
/izin-impor/buat,
```

```
/izin-impor/{id_izin_impor}
```



35. **/izin-impor/buat**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Izin Import pada dropdown, Pilih button “Buat Pengajuan”

#### PERMISSION

izin-impor

#### REDIRECT



36. **/izin-impor/{id\_izin\_impor}**

#### CARA AKSES

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Izin Import pada dropdown, Pilih Daftar Pengajuan Izin Impor yang dituju dengan mengetuk ikon pencarian "searchbar".

#### PERMISSION&#x20;

izin-impor

#### REDIRECT

\-



## ADMIN VOLUNTEER

***

1. **/pengusul**

#### CARA AKSES

#### PERMISSION

volunteer-pengusul-menu

#### REDIRECT

\


2. **/pengusul/{id\_proposal}**

#### CARA AKSES

#### PERMISSION

volunteer-show-pengusul-menu

#### REDIRECT



## REVIEWER

***

1. **reviewer/**

#### CARA AKSES

Login sebagai reviewer ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).

#### PERMISSION

index-tugas-menu

#### REDIRECT

```
reviewer/evaluasi-proposal/{id-proposal}
```

```
reviewer/presentasi-proposal/{id-proposal}
```



2. **/tugas/{tugas}**

#### CARA AKSES

#### PERMISSION

show-tugas-menu

#### REDIRECT



3. **/tugas-semhas/{fiscal\_year}/{tugas}**

#### CARA AKSES

#### PERMISSION

show-tugas-menu

#### REDIRECT

\


4. **/tugas-monev-2023/{tugas}**

#### CARA AKSES

#### PERMISSION

show-tugas-menu

#### REDIRECT



5. **/evaluasi-proposal/{tugas}**

#### CARA AKSES

#### PERMISSION

\-

#### REDIRECT

\


6. **/presentasi-proposal/{tugas}**

#### CARA AKSES

#### PERMISSION

\-

#### REDIRECT

\-

7. **/veka/{tugas}**

#### CARA AKSES

#### PERMISSION

\-

#### REDIRECT

\-



## UNIT PENGELOLA

***

1. **/pengusul**

#### CARA AKSES

#### PERMISSION

up-index-proposal-menu

#### REDIRECT



2. **/pengusul/{id\_proposal}**

#### CARA AKSES

#### PERMISSION

up-show-proposal-menu

#### REDIRECT



3. **/kontrak**

#### CARA AKSES

#### PERMISSION

up-index-kontrak-menu

#### REDIRECT



4. **/kontrak/create**

#### CARA AKSES

#### PERMISSION

up-index-kontrak-menu

#### REDIRECT



5. **/kontrak/{id\_kontrak}**

#### CARA AKSES

#### PERMISSION

up-show-kontrak-menu

#### REDIRECT



6. **/kontrak/{kontrak\_id}/verifikasi/{kategori\_berkas\_id}**

#### CARA AKSES

#### PERMISSION

up-show-kontrak-menu

#### REDIRECT



7. **/izin-impor**

#### CARA AKSES

#### PERMISSION

up-izin-impor

#### REDIRECT



8. **/izin-impor/buat**

#### CARA AKSES

#### PERMISSION

up-izin-impor

#### REDIRECT



8. **/izin-impor/{id\_izin\_impor}**

#### CARA AKSES

#### PERMISSION

up-izin-impor

#### REDIRECT



9. **/laporan**

#### CARA AKSES

#### PERMISSION

\-

#### REDIRECT



## OPERATOR

***

**`/pendaftaran-pt`**

#### CARA AKSES

#### PERMISSION

\-

#### REDIRECT



**`/edit-pt`**

#### CARA AKSES

#### PERMISSION

operator-daftar-up-menu

#### REDIRECT



## FRONT OFFICE

***

**`status-proposal`**

#### CARA AKSES

#### PERMISSION

system-status-proposal

#### REDIRECT

\


**`status-proposal/{fund_id}`**

#### CARA AKSES

#### PERMISSION

system-status-proposal

#### REDIRECT



**`deskripsi-proposal`**

#### CARA AKSES

#### PERMISSION

\-

#### REDIRECT



**`deskripsi-proposal/`**

#### CARA AKSES

#### PERMISSION

system-description-proposal

#### REDIRECT



**`/{description_id}`**

#### CARA AKSES

#### PERMISSION

system-description-proposal

#### REDIRECT



## PENGUSUL

***

1. **pengusul/**

#### CARA AKSES

1. Login sebagai pengusul ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).
2. Masuk ke dalam menu dashboard.
3. Pilih navigasi admin (DIKTI).
4. Pilih opsi Izin Import pada dropdown.
5. Pilih Daftar Pengajuan Izin Impor yang dituju dengan mengetuk ikon pencarian "searchbar".

#### PERMISSION

pengusul-dashboard

#### REDIRECT

```
/pengusul/proposal/{id_proposal
```



2. **/proposal/{proposal}**

#### CARA AKSES

#### PERMISSION

pengusul-show-proposal

#### REDIRECT



3. **/pengajuan-proposal**

#### CARA AKSES

#### PERMISSION

pengusul-pengajuan

#### REDIRECT

\


4. **/usulan/{id\_proposal}**

#### CARA AKSES

#### PERMISSION

pengusul-show-proposal

#### REDIRECT


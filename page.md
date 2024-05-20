# Page

## ADMIN

***

#### **NAMA PAGE**

1. **/perguruan-tinggi**

#### Cara Akses

Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard , Pilih navigasi admin (DIKTI), Pilih opsi Perguruan Tinggi pada dropdown.

#### Permission

```
perguruan-tinggi-menu
```

#### Redirect

{% code fullWidth="false" %}
```
admin/perguruan-tinggi/{pt}
```
{% endcode %}

***

#### **NAMA PAGE**

2. **/perguruan-tinggi/{pt}**

#### Cara Akses

Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Perguruan Tinggi pada dropdown, Pilih Perguruan Tinggi yang dituju.

#### Permission

```
perguruan-tinggi.show-menu
```

#### Redirect

```
admin/pengusul/{id_proposal} 
```

***

#### **NAMA PAGE**

3. **/pendaftaran-pt**&#x20;

#### Cara Akses

Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard , Pilih navigasi admin (DIKTI), Pilih opsi Daftar Pengajuan Unit Pengelola pada dropdown

#### Permission

```
pendaftaran-pt-menu
```

#### Redirect

```
admin/pendaftaran-pt/{pt}
```

***

#### **NAMA PAGE**

4. **/pendaftaran-pt/{pt}**&#x20;

#### Cara Akses

Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Daftar Pengajuan Unit Pengelola pada dropdown, Pilih Detail Pendaftaran Pengelola MF yang dituju dengan mengetuk ikon pencarian "searchbar".

#### Permission

```
pendaftaran-pt-show-menu
```

pendaftaran-pt-show-menu

#### Redirect

```
-
```

***

#### **NAMA PAGE**

5. **/pengusul**

#### Cara Akses

Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi ProposalMF2023 pada dropdown.

#### Permission

```
pengusul-menu
```

#### Redirect

```
admin/pengusul/{id_proposal}
```

***

#### **NAMA PAGE**

6. **/pengusul/{id\_proposal}**

#### Cara Akses

Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi ProposalMF2023 pada dropdown, Pilih proposal yang dituju

#### Permission

```
pengusul.show-menu
```

#### Redirect

```
-
```

***

#### **NAMA PAGE**

7. **/kontrak**

#### Cara Akses

Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard , Pilih navigasi admin (DIKTI), Pilih opsi KontrakMF2023 pada dropdown.

#### Permission

```
kontrak-menu
```

#### Redirect

```
admin/kontrak/{id_kontrak}
```

***

#### **NAMA PAGE**

7. **/diksi-kontrak**&#x20;

#### Cara Akses

#### Permission

```
diksi-kontrak-menu
```

#### Redirect

```
-
```

***

#### **NAMA PAGE**

8. **/kontrak/merge-dokumen-kontrak**

#### Cara Akses

Login sebagai super admin kedalam website backoffice kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Merge Dokumen Kontrak pada dropdown.

#### Permission

```
kontrak.merge-dokumen-kontrak
```

#### Redirect

```
-
```

***

#### **NAMA PAGE**

9. **/kontrak/{id\_kontrak}**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/)., Masuk ke dalam menu dashboard., Pilih navigasi admin (DIKTI), Pilih opsi Kontrak MF 2023 pada dropdown, Pilih detail kontrak yang dituju dengan mengetuk ikon pencarian "searchbar".

#### Permission

```
kontrak.show-menu
```

kontrak.show-menu

#### Redirect

```
-
```

***

#### **NAMA PAGE**

10. **/kontrak/{kontrak\_id}/upload/{kategori\_berkas\_id} (ini juga skip dulu)**

#### Cara Akses



#### Permission

```
kontrak.show-menu
```

#### Redirect

***

#### **NAMA PAGE**

11. **/kontrak/{kontrak\_id}/verifikasi/{kategori\_berkas\_id}  (ini juga skip dulu)**

#### Cara Akses



#### Permission

```
kontrak.show-menu
```

#### Redirect

```
// Some code
```

***

#### **NAMA PAGE**

12. **/kontrak/{kontrak\_id}/preview/{kategori\_berkas\_id} (ini juga skip dulu)**

#### Cara Akses



#### Permission

```
kontrak.show-menu
```

#### Redirect

```
// Some code
```

***

#### **NAMA PAGE**

13. **/mitra (On Going)**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Mitra pada dropdown.

#### Permission

```
mitra-menu
```

#### Redirect

```
```

***

#### **NAMA PAGE**

14. **/reviewer**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/)., Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi reviewer pada dropdown.

#### Permission



reviewer-menu

#### Redirect

```
admin/reviewer/{id}
```

***

#### **NAMA PAGE**

15. **/reviewer/{id}**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Reviewer pada dropdown, Pilih detail kontrak yang dituju dengan mengetuk ikon pencarian "searchbar", Pilih opsi View pada menu ikon yang tercantum pada bagian Aksi.

#### Permission

```
reviewer-show-menu
```

#### Redirect

```
admin/pegusul/{id_proposal}
```

***

#### **NAMA PAGE**

16. **/user-management**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi User Management pada dropdown.

#### Permission

```
user-management-menu
```

#### Redirect

```
```

***

#### **NAMA PAGE**

17. **/manajemen-pengumuman**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Manajemen Pengumuman pada dropdown.

#### Permission

```
Manajemen-pengumuman 
```

#### Redirect

```
-
```

***

#### **NAMA PAGE**

18. **/statistik (Skip dulu)**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Statistik pada dropdown.

#### Permission

```
akses-statistik
```

#### Redirect

```
```

***

#### **NAMA PAGE**

19. **/statistik-2024 (Skip dulu)**

#### Cara Akses



#### Permission

```
akses-statistik-2024
```

#### Redirect

```
-
```

***

#### **NAMA PAGE**

20. **/monitoring**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Papan Monitoring VK pada dropdown.

#### Permission

```
-
```

#### Redirect

```
-
```

***

#### **NAMA PAGE**

21. **/pusatbantuan**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Papan Monitoring VK pada dropdown.

#### Permission

```
-
```

#### Redirect

```
-
```

***

#### **NAMA PAGE**

22. **/export**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/)., Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Export pada dropdown.

#### Permission

```
export-document
```

#### Redirect

```
-
```

***

#### **NAMA PAGE**

23. **/seminar-hasil-2022-dikti**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Seminar Hasil DIKTI 2022 pada dropdown.

#### Permission

```
seminar-admin
```

#### Redirect

```
/seminar-hasil-2022-dikti/{id_proposal}
```

***

#### **NAMA PAGE**

24. **/seminar-hasil-2022-dikti/{id\_proposal}**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Seminar Hasil DIKTI 2022 pada dropdown, Pilih proposal yang dituju dengan mengetuk ikon pencarian "searchbar".

#### Permission

```
seminar-admin
```

#### Redirect

```
-
```

***

#### **NAMA PAGE**

25. **seminar-hasil-diksi/2022**&#x20;

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKSI), Pilih opsi Seminar Hasil DIKSI 2022 pada dropdown.

#### Permission

```
seminar-admin-diksi
```

seminar-admin-diksi

#### Redirect

```
/seminar-hasil-diksi/{fiscal_year}/{id_proposal}
```

***

#### **NAMA PAGE**

26. **seminar-hasil-diksi/2023 (Skip Dulu)**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKSI), Pilih opsi Seminar Hasil DIKSI 2023 pada dropdown.

#### Permission

```
seminar-admin-diksi
```

#### Redirect

```
```

***

#### **NAMA PAGE**

27. **/seminar-hasil-diksi/{fiscal\_year}/{id\_proposal}**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKSI), Pilih opsi Seminar Hasil DIKSI 2023 pada dropdown, Pilih proposal yang dituju dengan mengetuk ikon pencarian "searchbar".

#### Permission

```
seminar-admin-diksi
```

#### Redirect

```
```

***

#### **NAMA PAGE**

28. **/pencairan**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Daftar Pencairan pada dropdown.

#### Permission

```
pencairan-admin-index
```

#### Redirect

```
/pencairan/{id}
```

***

#### **NAMA PAGE**

29. **/pencairan/{id}**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Daftar Pencairan pada dropdown.

#### Permission

```
pencairan-admin-index
```

#### Redirect

```
```

***

#### **NAMA PAGE**

30. **/kontrak/{id\_kontrak}/pencairan-tahap-2**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Kontrak PDP 2024 pada dropdown, Pilih Kontrak yang dituju dengan mengetuk ikon pencarian "searchbar".

#### Permission

```
pencairan-tahap-2
```

#### Redirect

```
-
```

***

#### **NAMA PAGE**

31. **/kontrak/{pencairan\_id}/unggah-berkas-tahap-2 (Skip Dulu)**

#### Cara Akses

#### Permission

```
-
```

#### Redirect

```
-
```

***

#### **NAMA PAGE**

32. **/kontrak/{pencairan\_id}/tanda-tangan-berkas-tahap-2 (Skip Dulu)**

#### Cara Akses

#### Permission

```
-
```

#### Redirect

```
-
```

***

#### **NAMA PAGE**

33. **/kontrak/{pencairan\_id}/kelengkapan-berkas-tahap-2(Skip Dulu)**

#### Cara Akses

#### Permission

```
-
```

#### Redirect

```
-
```

***

#### **NAMA PAGE**

34. **/izin-impor**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Izin Import pada dropdown.

#### Permission

```
izin-impor
```

#### Redirect

```
/izin-impor/buat, /izin-impor/{id_izin_impor}
```

***

#### **NAMA PAGE**

35. **/izin-impor/buat**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Izin Import pada dropdown, Pilih button “Buat Pengajuan”

#### Permission

```
izin-impor
```

#### Redirect

```
-
```

***

#### **NAMA PAGE**

36. **/izin-impor/{id\_izin\_impor}**

#### Cara Akses

Login sebagai super admin ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/), Masuk ke dalam menu dashboard, Pilih navigasi admin (DIKTI), Pilih opsi Izin Import pada dropdown, Pilih Daftar Pengajuan Izin Impor yang dituju dengan mengetuk ikon pencarian "searchbar".

#### Permission

```
izin-impor
```

#### Redirect

```
-
```



## ADMIN VOLUNTEER

***

#### **NAMA PAGE**

1. **/pengusul**

#### Cara Akses

#### Permission

```
volunteer-pengusul-menu
```

#### Redirect

```
-
```

***

#### **NAMA PAGE**

2. **/pengusul/{id\_proposal}**

#### Cara Akses

#### Permission

```
volunteer-show-pengusul-menu
```

#### Redirect

```
```



## REVIEWER

***

#### **NAMA PAGE**

1. **reviewer/**

#### Cara Akses

Login sebagai reviewer ke dalam website backoffice Kedaireka (https://backoffice.kedaireka.id/).

#### Permission

index-tugas-menu

#### Redirect

```
reviewer/evaluasi-proposal/{id-proposal}, reviewer/presentasi-proposal/{id-proposal}
```

***

#### **NAMA PAGE**

2. **/tugas/{tugas}**

#### Cara Akses

#### Permission

```
show-tugas-menu
```

#### Redirect

```
```

***

#### **NAMA PAGE**

3. **/tugas-semhas/{fiscal\_year}/{tugas}**

#### Cara Akses

#### Permission

```
show-tugas-menu
```

#### Redirect

```
-
```

***

**NAMA PAGE**

4. **/tugas-monev-2023/{tugas}**

#### Cara Akses

#### Permission

```
show-tugas-menu
```

#### Redirect

```
-
```

***

**NAMA PAGE**

5. **/evaluasi-proposal/{tugas}**

#### Cara Akses

#### Permission

```
-
```

#### Redirect

```
-
```

***

**NAMA PAGE**

6. **/presentasi-proposal/{tugas}**

#### Cara Akses

#### Permission

```
-
```

#### Redirect

```
-
```

***

**NAMA PAGE**

7. **/veka/{tugas}**

#### Cara Akses

#### Permission

```
-
```

#### Redirect

```
-
```



## UNIT PENGELOLA

***

**NAMA PAGE**

1. **/pengusul**

#### Cara Akses

#### Permission

```
up-index-proposal-menu
```

#### Redirect

```
-
```

***

**NAMA PAGE**

2. **/pengusul/{id\_proposal}**

#### Cara Akses

#### Permission

```
up-show-proposal-menu
```

#### Redirect

```
-
```

***

**NAMA PAGE**

3. **/kontrak**

#### Cara Akses

#### Permission

```
up-index-kontrak-menu
```

#### Redirect

```
-
```

***

**NAMA PAGE**

4. **/kontrak/create**

#### Cara Akses

#### Permission

```
up-index-kontrak-menu
```

#### Redirect

```
-
```

***

**NAMA PAGE**

5. **/kontrak/{id\_kontrak}**

#### Cara Akses

#### Permission

```
up-show-kontrak-menu
```

#### Redirect

```
-
```

***

**NAMA PAGE**

6. **/kontrak/{kontrak\_id}/verifikasi/{kategori\_berkas\_id}**

#### Cara Akses

#### Permission

```
up-show-kontrak-menu
```

#### Redirect

```
-
```

***

**NAMA PAGE**

7. **/izin-impor**

#### Cara Akses

#### Permission

```
up-izin-impor
```

#### Redirect

```
-
```

***

**NAMA PAGE**

8. **/izin-impor/buat**

#### Cara Akses

#### Permission

```
up-izin-impor
```

#### Redirect

```
-
```

***

**NAMA PAGE**

8. **/izin-impor/{id\_izin\_impor}**

#### Cara Akses

#### Permission

```
up-izin-impor
```

#### Redirect

```
-
```

***

**NAMA PAGE**

9. **/laporan**

#### Cara Akses

#### Permission

```
up-izin-impor
```

#### Redirect

```
-
```



## OPERATOR

***

**NAMA PAGE**

1. **/pendaftaran-pt**

#### Cara Akses

#### Permission

```
-
```

#### Redirect

```
-
```

***

**NAMA PAGE**

2. **/edit-pt**

#### Cara Akses

#### Permission

```
operator-daftar-up-menu
```

#### Redirect

```
```



## FRONT OFFICE

***

**NAMA PAGE**

1. **status-proposal**

#### Cara Akses

#### Permission

```
system-status-proposal
```

#### Redirect

```
-
```

***

**NAMA PAGE**

2. **status-proposal/{fund\_id}**

#### Cara Akses

#### Permission

```
system-status-proposal
```

#### Redirect

```
-
```

***

**NAMA PAGE**

3. **deskripsi-proposal**

#### Cara Akses

#### Permission

```
-
```

#### Redirect

```
-
```

***

**NAMA PAGE**

4. **deskripsi-proposal/**

#### Cara Akses

#### Permission

```
system-description-proposal
```

#### Redirect

```
-
```

***

**NAMA PAGE**

5. **/{description\_id}**

#### Cara Akses

#### Permission

```
system-description-proposal
```

#### Redirect

```
-
```



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


---
title: Kirim Data Perolehan Suara
description: Panduan ptps
permalink: /docs/ptps/perolehanhasil/
---

| :---:			| :---			|
| Perintah:		| [/perolehanhasil]({{ '/docs/ptps/perolehanhasil' | relative_url }})	|
| Jenis Data:	| teks terformat			|

Perintah [/perolehanhasil]({{ '/docs/ptps/perolehanhasil' | relative_url }}) digunakan untuk mengirimkan data perolehan suara di masing-masing ptps berupa teks terformat oleh pengawas TPS.

### Langkah-langkah
* Kirimkan perintah [/perolehanhasil]({{ '/docs/ptps/perolehanhasil' | relative_url }}) kepada bot
	![perintah kirim perintah]({{ '/img/contents/perolehanhasil_kirim_perintah.jpg'}})
* Kirimkan data hasil perolehan suara sesuai format yang ditunjukkan bot. Untuk Kabupaten/Kota dengan 3 paslon maka akan muncul format 3 paslon, jika Kabupaten/Kota dengan 2 paslon maka bot akan memberikan format 2 paslon.<br />
	![perintah kirim data]({{ '/img/contents/perolehanhasil_kirim_data.jpg'}})
* Bot akan memberikan notifikasi terkait data yang anda input. Ditahap ini silahkan anda periksa apakah data yang anda input sesuai dengan data pada notifikasi bot.
	![perintah konfirmasi]({{ '/img/contents/perolehanhasil_konfirmasi.jpg'}})
* Apabila data yang ditunjukkan notifikasi tidak sesuai, silahkan lakukan perbaikan data dengan cara membalas notifikasi dengan data yang benar sesuai format awal.
	![perintah kirim perbaikan]({{ '/img/contents/perolehanhasil_kirim_perbaikan.jpg'}})
* Bot akan memberikan notifikasi terkait data yang barusaja anda perbaiki. Ditahap ini silahkan anda periksa kembali apakah data yang anda input sesuai dengan data pada notifikasi bot.
	![perintah konfirmasi perbaikan]({{ '/img/contents/perolehanhasil_konfirmasi_perbaikan.jpg'}})
* Apabila data yang dikonfirmasikan bot sudah benar, anda bisa melanjutkan dengan klik tombol YA untuk menyimpan kedalam database server. <br /> Gunakan tidak apabila anda ingin membatalkan perintah input data.
	![perintah konfirmasi perbaikan]({{ '/img/contents/perolehanhasil_tombol_konfirmasi.jpg'}})


\* Catatan: Apabila anda mengirim data perolehan ini lebih dari 1x. Maka, data akan tetap diterima, dan data yang paling akhir yang akan digunakan oleh system.
# Kelompok7_RC_VDI24-25
Repositori ini dibuat untuk memenuhi tugas besar mata kuliah Visualisasi Data dan Analisis tahun 2024.
====================================================================================
Keterangan data
====================================================================================
poiID (Integer): ID unik untuk setiap POI.
poiName (String): Nama lokasi wisata dalam format teks URL-encoded.
lat dan long (Float): Koordinat geografis lintang dan bujur.
theme (String): Kategori POI, seperti Palace, Zoo, Museum, dan Entertainment.
from (Integer): poiID dari titik asal.
to (Integer): poiID dari titik tujuan.
cost (Float): jarak antara titik POI asal dan POI tujuan dalam meter.
profit (Integer): jumlah kedatangan pengunjung POI.
photoID : ID foto berdasarkan flickr
userID : ID pengguna berdasarkan flickr
dateTaken : Waktu pengambilan foto
poiTheme : Kategori POI
poiFreq : Jumlah kunjungan ke POI
seqID : Nomor urutan perjalanan
====================================================================================
Referensi
====================================================================================
If you use this dataset, please cite the following papers:
 - Kwan Hui Lim, Jeffrey Chan, Christopher Leckie and Shanika Karunasekera. "Personalized Tour Recommendation based on User Interests and Points of Interest Visit Durations". In Proceedings of the 24th International Joint Conference on Artificial Intelligence (IJCAI'15). Pg 1778-1784. Jul 2015.
 - Kwan Hui Lim, Jeffrey Chan, Christopher Leckie and Shanika Karunasekera. "Towards Next Generation Touring: Personalized Group Tours". In Proceedings of the 26th International Conference on Automated Planning and Scheduling (ICAPS'16). Pg 412-420. Jun 2016.

The corresponding bibtex for these papers are:
 @INPROCEEDINGS { lim-ijcai15,
	AUTHOR = {Kwan Hui Lim and Jeffrey Chan and Christopher Leckie and Shanika Karunasekera},
	TITLE = {Personalized Tour Recommendation based on User Interests and Points of Interest Visit Durations},
	BOOKTITLE = {Proceedings of the 24th International Joint Conference on Artificial Intelligence (IJCAI'15)},
	PAGES = {1778-1784},
	YEAR = {2015}
 }
 @INPROCEEDINGS { lim-icaps16,
	AUTHOR = {Kwan Hui Lim and Jeffrey Chan and Christopher Leckie and Shanika Karunasekera},
	TITLE = {Towards Next Generation Touring: Personalized Group Tours},
	BOOKTITLE = {Proceedings of the 26th International Conference on Automated Planning and Scheduling (ICAPS'16)},
	PAGES = {412-420},
	YEAR = {2016}
 } 

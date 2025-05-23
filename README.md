# 🛍️ Analisis Kunjungan Koperasi Kampus (15 April)

## 📚 Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis pola kunjungan ke koperasi kampus pada  **tanggal 15 April** , dengan data yang dicatat setiap **10 menit** dari pukul  **09.10 sampai 14.00** . Dari data ini, kita mau tahu:

* Jam berapa koperasi paling ramai dan paling sepi?
* Rentang waktu mana saja yang jumlah pengunjungnya  **lebih dari 10 orang** ?

## 📂 Dataset

Dataset terdiri dari dua kolom utama:

* `Jam` → Waktu dalam format `HH:MM`, dicatat tiap 10 menit
* `Jumlah` → Jumlah pengunjung yang datang pada waktu tersebut

Data ini hanya mencakup  **satu hari** , yaitu tanggal  **15 April** , jadi analisisnya fokus dan mendalam untuk hari tersebut.

## 🛠️ Tools & Library

Analisis dilakukan dengan menggunakan:

* **Python**
* **Pandas** → untuk manipulasi data
* **Matplotlib** → buat bantu visualisasi tren kunjungan

## 🧪 Metodologi

Langkah-langkah yang dilakukan dalam proyek ini:

**a. Persiapan Data**

* Pastikan data bersih dan urut sesuai waktu

**b. Analisis**

* Cari waktu dengan jumlah pengunjung **terbanyak** dan **tersedikit** menggunakan **pencarian nilai ekstrem**
* Filter jam-jam yang pengunjungnya **lebih dari 10 orang** menggunakan **sequential search & binary search**
* Visualisasi data untuk melihat pola kunjungan

## 🔎 Hasil Analisis

Berikut beberapa insight yang ditemukan:

* ⏰ **Waktu paling ramai:** jam  **09:40** , ada **24 pengunjung**
* 💤 **Waktu paling sepi:** jam  **11:00** , cuma **1** **pengunjung**
* 🔥 **Jam sibuk (pengunjung > 10):** Terjadi di antara **09:20 – 13:20**

## 💬 Interpretasi

**a. Jam Kunjung Terpadat**

* Paling ramai terjadi pukul **09:40** dengan  **24 pengunjung** .
* Kemungkinan karena mahasiswa atau pegawai mampir membeli sarapan sebelum mulai aktivitas pagi.

**b. Periode Waktu Ramai**

* Pengunjung lebih dari 10 orang terjadi mulai dari  **09:20 sampai 13:20** .
* **Pagi (09:20–10:30)** : terjadi lonjakan awal.
* **Siang (11:10–13:20)** : jumlah pengunjung stabil meskipun tidak sebanyak pagi.

**c. Rekomendasi Strategi**

* Tambah staf kasir antara  **09:20–10:30** , karena itu jam tersibuk.

**d. Saran**

* Buat **promo di jam sepi** untuk seimbangkan kunjungan.
* **Siapkan stok** sebelum jam 09:20 supaya siap saat ramai pengunjung.

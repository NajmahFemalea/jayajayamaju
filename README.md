# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech


**Peringatan!**

Skenario dalam proyek ini hanyalah fiktif belaka. Apabila terdapat kesamaan nama tokoh, perusahaan, ataupun produk, itu adalah kebetulan semata dan tidak ada unsur kesengajaan.

## Business Understanding

Jaya Jaya Maju merupakan salah satu perusahaan multinasional yang telah berdiri sejak tahun 2000. Ia memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri.

### Permasalahan Bisnis

Jaya Jaya Maju mengalami kesulitan dalam mengelola karyawan. Hal ini berimbas tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%.

### Cakupan Proyek

Proyek ini bertujuan untuk mengidentifikasi beberapa faktor yang dapat menyebabkan tingginya attrition rate yang terjadi di perusahaan Jaya Jaya Maju seperti Menghitung proporsi “Stay” vs “Leave”, rata-rata pendapatan, dan distribusi menurut JobRole, JobSatisfaction, dll. Proyek ini juga membangun model prediktif untuk mem-forecast karyawan berisiko resign dan Menyajikan metrik kunci dan visualisasi interaktif di Metabase.

### Persiapan

Sumber data: [employee data](https://github.com/dicodingacademy/dicoding_dataset/blob/main/employee/employee_data.csv)

Setup environment:

Clone repo
```
git clone https://github.com/NajmahFemalea/jayajayamaju.git
cd jayajayamaju
```
Setup virtual Environtment (opsional)
```
python -m venv ./venv
venv\Scripts\activate 
```
Install Dependencies
```
pip install -r requirements.txt
```
## Business Dashboard

Dashboard ini mencakup, tiga metrik kunci di bagian atas: jumlah karyawan yang bertahan (“Attrition No”), jumlah karyawan yang telah keluar (“Attrition Yes”), rata-rata gaji bulanan karyawan, distribusi total karyawan, jumlah yang keluar, dan jumlah yang bertahan untuk setiap tingkat kepuasan kerja—dari level “Low” hingga “Very High.”. Visualisasi menggunakan bar chart untuk menunjukkan perbandingan. Keseluruhan tampilan ini dirancang untuk membantu manajer dan pemangku kepentingan HR memantau tren attrition secara real-time dan mengambil tindakan pencegahan yang tepat berdasarkan data.

## Conclusion

Secara keseluruhan, analisis menunjukkan bahwa tingkat kepuasan kerja (JobSatisfaction) merupakan prediktor kuat bagi kemungkinan karyawan untuk keluar—khususnya mereka yang melaporkan kepuasan rendah menghadapi risiko attrition tertinggi (sekitar 23 %). Sebaliknya, kelompok dengan kepuasan menengah maupun sangat tinggi menunjukkan tingkat turnover yang jauh lebih rendah (keduanya di bawah 15 %), meski rata-rata pendapatan bulanan hampir seragam di seluruh kelompok. Temuan ini menegaskan bahwa faktor-faktor non-finansial—seperti dukungan manajerial, kesempatan pengembangan karier, dan work–life balance—perlu menjadi fokus utama intervensi HR, karena meningkatkan kepuasan kerja berpotensi menurunkan angka resign dan menjaga stabilitas tim jangka panjang.

### Rekomendasi Action Items (Optional)

Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.

- Implement Stay Interviews untuk Karyawan dengan Kepuasan Rendah<br>
Jadwalkan wawancara rutin dengan karyawan yang melaporkan JobSatisfaction di level “Low” untuk memahami penyebab ketidakpuasan—apakah berkaitan beban kerja, dukungan manajerial, atau fasilitas—sehingga tim HR dapat merancang intervensi tepat sasaran sebelum mereka memutuskan untuk keluar.

- Transparansi Jalur Karier & Rencana Pengembangan<br>
Ciptakan peta karier yang jelas dengan kriteria promosi dan jalur pembinaan kompetensi untuk setiap JobRole. Komunikasikan secara terbuka kapan dan bagaimana karyawan dapat naik jabatan atau mendapatkan tanggung jawab baru—ini meningkatkan motivasi dan mengurangi ketidakpastian yang sering memicu resign.

- Luncurkan Survei Kepuasan Berkala & Tindak Lanjut Cepat<br>
Adakan survei pulse survey triwulanan yang menilai faktor-faktor seperti work–life balance, kesempatan pelatihan, dan budaya kerja. Pastikan hasilnya dianalisis segera, dan hasil analisis disampaikan kembali kepada tim dengan action plan spesifik—misalnya penyesuaian kebijakan fleksibilitas atau peningkatan fasilitas kantor.

- Review Kompensasi Non-Finansial & Program Penghargaan<br>
Selain gaji yang relatif merata, kembangkan insentif non-finansial—seperti penghargaan “Employee of the Month,” voucher pengembangan diri, atau program well-being (yoga, konseling)—untuk meningkatkan rasa dihargai. Pengakuan ini membangun keterikatan emosional dan menurunkan keinginan karyawan untuk mencari peluang di tempat lain.

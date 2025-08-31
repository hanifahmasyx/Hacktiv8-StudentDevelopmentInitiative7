# Hacktiv8-StudentDevelopmentInitiative7
HR data analysis project exploring employee demographics, performance, engagement, and turnover. Includes dataset link, analysis process, insights with visualizations, conclusions, and AI support explanation.

**Title project** → HR Analytics Dashboard: Employee Engagement & Performance

**Project overview** → Proyek ini bertujuan menganalisis data SDM guna memperoleh insight strategis terkait **demografi, status kerja, absensi, engagement, performa, serta faktor yang memengaruhi turnover**. Analisis dilakukan menggunakan Python (Google Colab) dengan fokus pada visualisasi, pola keterlibatan, serta hubungan antara tenure, absensi, dan kinerja. Hasil analisis diharapkan memberikan rekomendasi berbasis data bagi pengambilan keputusan HR yang lebih efektif.

**Raw dataset link** → https://www.kaggle.com/datasets/rhuebner/human-resources-data-set

**Insight & findings** → 
- **Employment Status Distribution** :
Mayoritas karyawan berstatus Active, diikuti oleh kategori Voluntarily Terminated dan erminated for Cause. Hal ini menunjukkan adanya tingkat turnover moderat, dengan sebagian karyawan memilih keluar secara sukarela, sementara sebagian lainnya bertahan dalam jangka panjang.
- **Department Distribution** :
Departemen Production menjadi yang paling dominan, mencerminkan fokus utama organisasi pada kegiatan produksi serta layanan teknologi informasi.
- **Gender Distribution** :
Komposisi karyawan didominasi oleh perempuan, dengan jumlah laki-laki yang lebih sedikit. Ketidakseimbangan ini dapat menjadi perhatian dalam strategi rekrutmen maupun retensi untuk meningkatkan keberagaman.
- **Marital Status Distribution** :
Karyawan berstatus lajang (0) mendominasi, diikuti oleh karyawan menikah (1). Sementara itu, jumlah karyawan dengan status bercerai (2), berpisah (3), dan duda/janda (4) relatif kecil. Informasi ini penting sebagai dasar perumusan kebijakan HR, khususnya terkait tunjangan keluarga, cuti khusus, serta program dukungan kesejahteraan karyawan.
- **Position Distribution** :
Posisi yang paling banyak ditempati adalah Production Technician serta berbagai peran di bidang IT, menunjukkan kebutuhan tinggi pada peran operasional dan teknologi.
- **PayRate Distribution** :
Rata-rata tingkat gaji berada di kisaran menengah (sekitar $60,000), dengan variasi yang cukup besar antar karyawan. Hal ini menunjukkan adanya rentang kompensasi yang mencerminkan perbedaan posisi dan level tanggung jawab.
- **Performance Score Distribution** :
Mayoritas karyawan memiliki skor kinerja Fully Meets dan Exceeds, menandakan secara umum tenaga kerja berkinerja baik. Namun, terdapat sebagian kecil karyawan dengan skor Needs Improvement yang perlu perhatian lebih lanjut.
- **Engagement Survey Scores** :
Rata-rata skor keterlibatan (engagement) berada pada level cukup tinggi, sekitar 4.6. Ini mengindikasikan bahwa karyawan merasa cukup terhubung dengan pekerjaan dan perusahaan.
- **Employee Satisfaction Scores** :
Rata-rata kepuasan karyawan berada pada angka 3.89. Meskipun menunjukkan tingkat kepuasan yang positif, masih terdapat ruang untuk perbaikan agar kepuasan karyawan dapat meningkat lebih merata.
- **Correlation Heatmap** :
Faktor keterlibatan (EngagementSurvey) adalah indikator yang paling berpengaruh terhadap PerformanceScore. Gaji (PayRate) dan Absensi (Absences) bukan faktor penentu utama kinerja karyawan dalam dataset ini. Fokus peningkatan kinerja sebaiknya diarahkan pada peningkatan engagement karyawan dibanding hanya menaikkan gaji atau menurunkan absensi.
- **Turnover Trend** :
Tahun 2010–2015 terjadi kenaikan turnover yang signifikan, dari hanya 1 orang (2010) hingga puncaknya 18 orang (2015). Hal ini menunjukkan adanya masalah retensi atau kondisi kerja yang mungkin kurang mendukung pada periode tersebut. Tahun 2016 turnover masih tinggi (18), menunjukkan tren puncak yang bertahan. Tahun 2017 terjadi penurunan drastis hingga hanya 6 orang, yang bisa mengindikasikan adanya perbaikan dalam manajemen SDM, kebijakan retensi, atau kondisi organisasi. Tahun 2018 turnover kembali naik sedikit menjadi 9 orang, namun tidak setinggi periode 2015–2016.

**AI support explanation** →
Dalam proyek ini, AI digunakan untuk:  
- Analisis data & visualisasi dengan Python (pandas, matplotlib, seaborn) di Google Collab.  
- Prediksi pola turnover menggunakan algoritma machine learning sederhana.  
- Generasi insight otomatis menggunakan model AI untuk menyarikan hasil analisis dan membuat rekomendasi.  


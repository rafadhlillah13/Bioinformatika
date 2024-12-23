# Pemodelan dan Analisis Potensi Senyawa terhadap HSP90 dengan Prediksi pIC50, Fingerprint Molekul dan Klasifikasi Bioaktivitas Menggunakan Random Forest dan Neural Network

Selamat datang di repositori proyek **Pemodelan dan Analisis Potensi Senyawa terhadap HSP90**. Dalam proyek ini, kami fokus pada pengembangan model untuk memprediksi potensi senyawa kimia terhadap target biologis HSP90 (Heat Shock Protein 90), menggunakan berbagai teknik machine learning. Tujuan utama proyek ini adalah untuk membantu penelitian farmasi dan biologi molekuler dalam mengidentifikasi senyawa yang memiliki potensi tinggi terhadap HSP90.

## 🔍 **Ringkasan Proyek**

### 1. **Regresi Random Forest untuk Prediksi Nilai pIC50**
**Tujuan**: Membangun model regresi untuk memprediksi nilai **pIC50** (potency index) senyawa kimia menggunakan teknik Random Forest.

**Deskripsi**: pIC50 digunakan untuk mengukur potensi senyawa kimia terhadap target biologis seperti protein atau enzim. Dengan menggunakan fitur-fitur molekuler seperti fingerprint kimia, kita akan memprediksi nilai pIC50 untuk membantu penelitian dalam mengembangkan obat yang lebih efektif.

**Metode Utama**:
- Rekayasa fitur dengan fingerprint molekul
- Model regresi menggunakan **Random Forest**

### 2. **Perbandingan Model Regresi Menggunakan LazyPredict**
**Tujuan**: Membandingkan kinerja berbagai model regresi, termasuk **Random Forest**, dalam memprediksi nilai pIC50.

**Deskripsi**: Menggunakan **LazyPredict** untuk membandingkan berbagai model regresi dengan cepat dan efisien, serta menilai kinerja masing-masing model untuk memprediksi nilai pIC50 dari senyawa kimia.

**Metode Utama**:
- Penggunaan **LazyPredict** untuk evaluasi otomatis model
- Metrik evaluasi: **RMSE**, **MAE**, **R²**

### 3. **Analisis Fingerprint Molekul dan Analisis Kesamaan**
**Tujuan**: Melakukan analisis fingerprint molekul dan menghitung kesamaan antar senyawa menggunakan koefisien **Tanimoto**.

**Deskripsi**: Proyek ini bertujuan untuk memahami kesamaan antara senyawa kimia berdasarkan struktur molekulnya, yang diwakili oleh fingerprint. Analisis ini membantu dalam mengelompokkan senyawa dengan karakteristik kimia yang mirip, yang dapat berpengaruh pada aktivitas biologisnya.

**Metode Utama**:
- **Fingerprinting** molekul menggunakan berbagai jenis algoritma (MACCS, Morgan)
- **Analisis kesamaan** menggunakan koefisien **Tanimoto**
- Visualisasi data untuk eksplorasi lebih lanjut

### 4. **Klasifikasi Bioaktivitas Menggunakan Random Forest dan Neural Network**
**Tujuan**: Membangun model klasifikasi untuk memprediksi apakah senyawa kimia bersifat **bioaktif** atau tidak aktif berdasarkan sifat kimianya.

**Deskripsi**: Dengan menggunakan **Random Forest** dan **Neural Network**, kita akan memprediksi status bioaktivitas senyawa kimia. Proyek ini juga mencakup analisis pentingnya fitur dan interpretabilitas model untuk memberikan wawasan yang lebih dalam mengenai proses pengambilan keputusan model.

**Metode Utama**:
- **Random Forest** dan **Neural Network** untuk klasifikasi
- Analisis **pentingnya fitur**
- Interpretabilitas model menggunakan **LIME** (Local Interpretable Model-agnostic Explanations)

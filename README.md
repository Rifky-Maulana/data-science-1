# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech


# HR Analytics - Attrition Analysis

## Business Understanding (Latar Belakang Bisnis)

**Jaya Jaya Maju** merupakan perusahaan multinasional yang berdiri sejak tahun 2000 dan telah memiliki lebih dari 1.000 karyawan yang tersebar di seluruh Indonesia. Meski tergolong perusahaan besar dan mapan, perusahaan ini tengah menghadapi tantangan serius dalam aspek manajemen sumber daya manusia, terutama dalam hal mempertahankan karyawan.

Saat ini, **tingkat attrition (attrition rate)** atau tingkat keluarnya karyawan dari perusahaan telah mencapai **16,9%**, yang termasuk dalam kategori **High Risk**. Angka ini menunjukkan bahwa perusahaan kehilangan hampir 1 dari setiap 6 karyawannya, yang dapat berdampak pada stabilitas operasional, produktivitas, serta biaya perekrutan dan pelatihan ulang.

---

## Permasalahan Bisnis

Berdasarkan data dan visualisasi yang tersedia, berikut adalah permasalahan bisnis yang dihadapi Jaya Jaya Maju:

1. **Tingginya Tingkat Attrition (16,9%)**
   - Angka ini berada di atas ambang batas yang wajar untuk industri, dan berisiko mengganggu kontinuitas serta efisiensi bisnis.

2. **Attrition Tinggi pada Departemen Tertentu**
   - **Departemen R&D (Research & Development)** memiliki attrition tertinggi sebesar **33%**.
   - Menunjukkan potensi masalah dalam budaya kerja, kepuasan, atau jalur karier di departemen ini.

3. **Attrition Berdasarkan Peran (Job Role)**
   - **Laboratory Technician** merupakan posisi dengan jumlah karyawan keluar tertinggi (**27,37% dari total attrition**).
   - Menandakan kemungkinan ketidakpuasan kerja, beban kerja tinggi, atau kurangnya insentif.

4. **Ketimpangan Gender**
   - Attrition lebih tinggi pada **karyawan laki-laki (60%)** dibandingkan perempuan (40%), menunjukkan kemungkinan faktor budaya, beban kerja, atau ketimpangan kesempatan.

5. **Kurangnya Mekanisme Monitoring**
   - Manajer HR membutuhkan **dashboard bisnis** untuk memonitor tren dan pola attrition, namun belum memiliki sistem pemantauan yang terintegrasi dan informatif.

---

## Cakupan Proyek

Proyek ini akan difokuskan pada:

1. **Analisis Data Attrition**
   - Menggunakan data historis karyawan untuk mengidentifikasi pola dan faktor utama yang menyebabkan tingginya attrition.
   - Fokus pada variabel seperti departemen, job role, gender, dan usia.

2. **Pembuatan Business Dashboard**
   - Membangun dashboard interaktif yang memvisualisasikan attrition rate secara real-time berdasarkan berbagai kategori (departemen, gender, usia, dll).
   - Memberikan insight yang mudah dibaca dan actionable bagi manajemen HR.

3. **Pemberian Rekomendasi Strategis**
   - Memberikan rekomendasi berbasis data seperti:
     - Perluasan jalur karier untuk peran teknis.
     - Retention program untuk departemen R&D.
     - Survei kepuasan kerja untuk job role dengan attrition tinggi.

4. **Pengukuran dan Monitoring KPI**
   - Menyusun metrik kunci (Key Performance Indicators) untuk mengukur keberhasilan intervensi dan strategi retensi ke depan.


## Persiapan

### Sumber Data

Dataset yang digunakan berasal dari perusahaan **Jaya Jaya Maju**, yang mencakup informasi:

- Data demografis karyawan
- Departemen
- Job Role
- Status Attrition (Keluar atau Tetap)

Jumlah data:
- **Total Karyawan:** 1.058
- **Karyawan Keluar (Attrition):** 179
- **Karyawan Tetap:** 879

### Setup Environment

Bahasa pemrograman: **Python**

Library yang digunakan:

```
python
# Import libraries yang diperlukan
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
import plotly.graph_objects as go
from plotly.subplots import make_subplots
import streamlit as st


# Konfigurasi visualisasi
plt.style.use('default')
sns.set_palette("husl")
```

### Business Dashboard
Business dashboard telah dikembangkan menggunakan teknologi web modern dengan fitur-fitur komprehensif untuk monitoring attrition analysis. Dashboard ini dapat diakses dengan kredensial berikut:
Akses Dashboard:
```
URL: http://localhost:3000
Username: root@mail.com
Password: root123
```
Fitur Dashboard meliputi:

1. Overall Attrition Rate Monitoring
   - Menampilkan tingkat attrition keseluruhan (16,9%) dengan indikator status "High Risk"
   - Real-time tracking perubahan attrition rate

2. Department-wise Attrition Analysis
   - Visualisasi bar chart menunjukkan distribusi attrition per departemen
   - R&D Department tertinggi (114 karyawan keluar), diikuti Sales (56 karyawan)

3. Job Satisfaction Impact Analysis
   - Breakdown attrition berdasarkan job role dengan persentase detail
   - Laboratory Technician (27,37%) dan Sales Executive (21,79%) sebagai fokus utama

4. Age Group Attrition Patterns
   - Analisis rata-rata usia karyawan yang keluar (37,06 tahun)
   - Membantu mengidentifikasi pola attrition berdasarkan demografi usia

5. Income-based Attrition Insights
   - Korelasi antara tingkat kompensasi dengan keputusan karyawan keluar
   - Memungkinkan analisis cost-benefit untuk strategi retensi

Dashboard ini memberikan kemudahan bagi tim HR untuk:
- Monitoring real-time attrition trends
- Identifikasi departemen dan role berisiko tinggi
- Pengambilan keputusan berbasis data untuk strategi retensi

### Conclusion
Berdasarkan analisis data HR Analytics Jaya Jaya Maju, dapat disimpulkan bahwa:
**Temuan Utama:**

1. Tingkat attrition 16,9% termasuk kategori High Risk dan memerlukan intervensi segera
2. Departemen R&D menjadi area kritikal dengan 114 karyawan keluar (63,7% dari total attrition)
3. Laboratory Technician sebagai job role dengan attrition tertinggi (27,37%)
4. Gender disparity menunjukkan laki-laki lebih rentan keluar (60,3% vs 39,7%)
5. Usia produktif (rata-rata 37,06 tahun) menjadi demografi yang paling banyak keluar

Expected Impact:
Dengan implementasi strategi ini, perusahaan diharapkan dapat menurunkan attrition rate dari 16,9% menjadi di bawah 10% dalam 12 bulan ke depan, menghemat biaya rekrutmen dan training, serta meningkatkan produktivitas dan stabilitas operasional.

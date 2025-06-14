# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Jaya Jaya Maju


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


## Persiapan Proyek

Pastikan instruksi dijelaskan dengan sistematis agar proyek dapat dijalankan tanpa hambatan. Berikut beberapa hal penting yang harus dijelaskan:

### 📂 Melampirkan Sumber Data

Dataset yang digunakan berasal dari perusahaan **Jaya Jaya Maju**, yang mencakup informasi:

| No. | Kolom                      | Penjelasan                                                                 |
|-----|----------------------------|---------------------------------------------------------------------------|
| 1   | Age                        | Ini adalah kolom yang berisi umur pegawai.                                |
| 2   | Attrition                  | Ini adalah kolom yang berisi status keluar/tidaknya pegawai dari perusahaan. |
| 3   | BusinessTravel             | Ini adalah kolom yang berisi frekuensi perjalanan dinas pegawai.           |
| 4   | DailyRate                  | Ini adalah kolom yang berisi tarif harian gaji pegawai.                    |
| 5   | Department                 | Ini adalah kolom yang berisi departemen tempat pegawai bekerja.           |
| 6   | DistanceFromHome           | Ini adalah kolom yang berisi jarak rumah pegawai ke tempat kerja (dalam km/mil). |
| 7   | Education                  | Ini adalah kolom yang berisi tingkat pendidikan pegawai.                  |
| 8   | EducationField             | Ini adalah kolom yang berisi bidang pendidikan pegawai.                   |
| 9   | EmployeeCount              | Ini adalah kolom yang berisi jumlah pegawai (mungkin bernilai 1 untuk setiap baris). |
| 10  | EnvironmentSatisfaction    | Ini adalah kolom yang berisi tingkat kepuasan pegawai terhadap lingkungan kerja. |
| 11  | Gender                     | Ini adalah kolom yang berisi jenis kelamin pegawai.                       |
| 12  | HourlyRate                 | Ini adalah kolom yang berisi tarif upah per jam pegawai.                  |
| 13  | JobInvolvement             | Ini adalah kolom yang berisi tingkat keterlibatan pegawai dalam pekerjaan. |
| 14  | JobLevel                   | Ini adalah kolom yang berisi level pekerjaan pegawai.                     |
| 15  | JobRole                    | Ini adalah kolom yang berisi peran/jabatan pegawai.                       |
| 16  | JobSatisfaction            | Ini adalah kolom yang berisi tingkat kepuasan pegawai terhadap pekerjaan. |
| 17  | MaritalStatus              | Ini adalah kolom yang berisi status pernikahan pegawai.                   |
| 18  | MonthlyIncome              | Ini adalah kolom yang berisi pendapatan bulanan pegawai.                  |
| 19  | MonthlyRate                | Ini adalah kolom yang berisi tarif bulanan gaji pegawai.                  |
| 20  | NumCompaniesWorked         | Ini adalah kolom yang berisi jumlah perusahaan tempat pegawai pernah bekerja sebelumnya. |
| 21  | Over18                     | Ini adalah kolom yang berisi status apakah pegawai berusia di atas 18 tahun (Ya/Tidak). |
| 22  | OverTime                   | Ini adalah kolom yang berisi status lembur pegawai.                       |
| 23  | PercentSalaryHike          | Ini adalah kolom yang berisi persentase kenaikan gaji pegawai.            |
| 24  | PerformanceRating          | Ini adalah kolom yang berisi rating kinerja pegawai.                      |
| 25  | RelationshipSatisfaction   | Ini adalah kolom yang berisi tingkat kepuasan pegawai terhadap hubungan kerja dengan rekan. |
| 26  | StandardHours              | Ini adalah kolom yang berisi jam kerja standar pegawai.                   |
| 27  | StockOptionLevel           | Ini adalah kolom yang berisi level opsi saham yang dimiliki pegawai.      |
| 28  | TotalWorkingYears          | Ini adalah kolom yang berisi total tahun pengalaman kerja pegawai.        |
| 29  | TrainingTimesLastYear      | Ini adalah kolom yang berisi frekuensi pelatihan yang diikuti pegawai tahun lalu. |
| 30  | WorkLifeBalance            | Ini adalah kolom yang berisi tingkat keseimbangan kerja-hidup pegawai.    |
| 31  | YearsAtCompany             | Ini adalah kolom yang berisi lama pegawai bekerja di perusahaan (dalam tahun). |
| 32  | YearsInCurrentRole         | Ini adalah kolom yang berisi lama pegawai berada di peran saat ini (dalam tahun). |
| 33  | YearsSinceLastPromotion    | Ini adalah kolom yang berisi waktu sejak promosi terakhir pegawai (dalam tahun). |
| 34  | YearsWithCurrManager       | Ini adalah kolom yang berisi lama pegawai bekerja dengan manajer saat ini (dalam tahun). |


**Jumlah Data:**

- **Total Karyawan:** 1.058
- **Karyawan Keluar (Attrition):** 179
- **Karyawan Tetap:** 879

Data disimpan secara online di **Supabase** dan diakses menggunakan SQLAlchemy dengan session pooling.

```python
# Import libraries
import pandas as pd
from sqlalchemy import create_engine

# Connection string
DB_URL = "postgresql://<username>:<password>@<host>:<port>/<database>"

# Create engine
engine = create_engine(DB_URL)

# Test connection
df = pd.read_sql("SELECT version()", engine)
print("✅ Connected!")
print(df)
```

### 🐍 Membuat dan Mengaktifkan Virtual Environment (venv)

Untuk menjaga lingkungan pengembangan tetap stabil dan terisolasi:

```bash
# Membuat virtual environment
python -m venv venv
```

 **Mengaktifkan virtual environment (Windows)**
```
venv\Scripts\activate
```
**Mengaktifkan virtual environment (Linux/Mac)**
```
source venv/bin/activate
```

### 📦 Menginstall Dependensi dari `requirements.txt`

Instal seluruh pustaka yang dibutuhkan menggunakan pip:

```bash
pip install -r requirements.txt
```

Contoh library yang digunakan:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import classification_report, confusion_matrix, roc_auc_score, roc_curve
from sklearn.preprocessing import LabelEncoder, StandardScaler
import warnings
from sqlalchemy import create_engine, text
from sklearn.metrics import roc_auc_score, classification_report
warnings.filterwarnings('ignore')
```

---
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

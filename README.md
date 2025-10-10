<h1 align="center">Muhammad Irsyad Dimas Abdillah</h1>

<p align="center">
  <a href="mailto:2341720088@student.polinema.ac.id"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.instagram.com/not.samiddd"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
</p>

---

## Tentang Saya

Mahasiswa **Teknik Informatika** di **Politeknik Negeri Malang** dengan fokus pada pengembangan backend, optimasi database, serta integrasi IoT dan Machine Learning.

```python
def introduce():
    profile = {
        "education": "Teknik Informatika - Politeknik Negeri Malang",
        "passion": ["Backend Development", "Database Optimization", "IoT", "Machine Learning"],
        "philosophy": "First, solve the problem. Then, write the code."
    }
    return profile
```

---

## Keahlian Teknis

### Bahasa Pemrograman & Framework

```javascript
const technicalSkills = {
    languages: ['PHP', 'Python', 'JavaScript', 'Java', 'Dart'],
    frameworks: ['Laravel', 'TensorFlow', 'Keras'],
    databases: ['MySQL', 'SQL Server'],
    tools: ['Git', 'VS Code', 'Postman', 'Arduino', 'Jupyter']
};
```

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

### Manajemen Database

```sql
SELECT skill_name, proficiency_level
FROM my_skills
WHERE category = 'Database Management'
ORDER BY proficiency_level DESC;
```

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)

### Machine Learning & Data Science

```python
import numpy as np
import pandas as pd
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
from tensorflow.keras.models import Sequential, load_model
from tensorflow.keras.layers import LSTM, Dense, Dropout

class MLEnthusiast:
    def __init__(self):
        self.frameworks = ['TensorFlow', 'Keras', 'Scikit-learn']
        self.libraries = ['NumPy', 'Pandas', 'Matplotlib']
        self.expertise = [
            'Time Series Forecasting',
            'Deep Learning (LSTM)',
            'Model Evaluation & Optimization',
            'Data Preprocessing & Visualization'
        ]
```

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

### Tools & Platforms

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)

---

## Proyek Unggulan

### MAGNET - Sistem Informasi Magang

```php
namespace App\Projects\MAGNET;

class InternshipRecommendation {
    use RecommendationBasedonPreference, optimizeData;
    
    public function getOptimalPlacement(Student $student): Recommendation
    {
        return $this->algorithm
            ->considerLocation($student->location)
            ->analyzeSkills($student->skills)
            ->matchWithCompanies()
            ->optimize();
    }
}
```

**Stack:** Laravel 10, Livewire, MySQL

Sistem manajemen magang dengan algoritma rekomendasi cerdas untuk penempatan mahasiswa secara optimal. Fitur utama mencakup rekomendasi berbasis preferensi pengguna dan optimasi penempatan berbasis data.

[Lihat Repository →](https://github.com/Maju-Lancar/MAGNET-Magang-Network-And-Tracking)

---

### IHSG LSTM Forecasting

```python
import tensorflow as tf
from keras.models import Sequential
from keras.layers import LSTM, Dense, Dropout

class IHSGForecaster:
    def __init__(self):
        self.model = self.build_lstm_model()
        self.metrics = {
            'MAPE': '1.33%',
            'architecture': 'Optimized LSTM Neural Network'
        }
    
    def build_lstm_model(self):
        model = Sequential([
            LSTM(units=50, return_sequences=True),
            Dropout(0.2),
            LSTM(units=50),
            Dense(units=1)
        ])
        return model
```

**Stack:** Python, TensorFlow, Keras

Model forecasting time series untuk IHSG menggunakan LSTM Neural Networks dengan hasil MAPE 1.33% dan arsitektur optimal.

[Lihat Repository →](https://github.com/Dimas0824/IHSG-LSTM_Forecasting)

---

### Website Portfolio Pribadi

```javascript
const portfolio = {
    stack: ['Laravel', 'Bootstrap', 'Filament'],
    features: {
        responsive: true,
        adminPanel: 'Filament',
        design: 'Modern & Clean'
    }
};
```

**Stack:** Laravel, Bootstrap, Filament

Website portfolio modern dan responsive dengan admin panel berbasis Filament.

[Lihat Repository →](https://github.com/Dimas0824/PersonalWeb)

---

### Sistem Kasir Cafe

```java
public class CafePOS {
    private MenuManager menuManager;
    private InventorySystem inventory;
    private SalesAnalytics analytics;
    
    public Transaction processOrder(Order order) {
        inventory.updateStock(order.getItems());
        Transaction transaction = new Transaction(order);
        analytics.recordSale(transaction);
        return transaction;
    }
}
```

**Stack:** Java

Sistem POS untuk manajemen kafe mencakup menu, inventori, dan analitik penjualan.

[Lihat Repository →](https://github.com/HaikalMuhammadRafli/Sistem-Kasir_kel01)

---

## Statistik GitHub

<p align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=Dimas0824&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=C3D1D9" />
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dimas0824&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=C3D1D9" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Dimas0824&theme=tokyonight&hide_border=true&background=0D1117&ring=00D9FF&fire=00D9FF" alt="GitHub Streak" />
</p>

---

## Kontak

```sql
SELECT 'Email' as contact_type, '2341720088@student.polinema.ac.id' as value
UNION ALL
SELECT 'Instagram' as contact_type, '@not.samiddd' as value;
```

Jika anda ingin berkolaborasi atau berdiskusi, hubungi saya melalui:

- Email: 2341720088@student.polinema.ac.id
- Instagram: [@not.samiddd](https://www.instagram.com/not.samiddd)

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Dimas0824&color=00D9FF&style=for-the-badge&label=Profile+Views" alt="Profile views"/>
</p>

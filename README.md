# Machine Predictive Maintenance Classification

## Deskripsi Project

Project ini bertujuan untuk melakukan preprocessing data pada dataset predictive maintenance menggunakan machine learning.

Dataset yang digunakan adalah **Machine Predictive Maintenance Classification Dataset** yang berisi data sensor industri untuk mendeteksi potensi kerusakan mesin (*machine failure*).

Dalam industri Oil and Gas maupun manufaktur, predictive maintenance sangat penting untuk:

* Mengurangi downtime mesin
* Meningkatkan efisiensi operasional
* Mengurangi biaya maintenance
* Mencegah kerusakan mesin secara tiba-tiba

## Dataset

Sumber dataset:
https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification

Dataset terdiri dari 10.000 data dengan beberapa fitur utama, antara lain:

* Type
* Air Temperature [K]
* Process Temperature [K]
* Rotational Speed [rpm]
* Torque [Nm]
* Tool Wear [min]

Target utama pada dataset:

* Target → kondisi machine failure (0 = normal, 1 = failure)

## Tahapan Project

Tahapan preprocessing yang dilakukan pada project ini meliputi:

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning
4. Feature Encoding
5. Train-Test Split
6. Feature Scaling

## Tools dan Library

Project ini menggunakan beberapa library Python, antara lain:

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* KaggleHub

## Struktur Repository

```text
Eksperimen_SML_RezaFahlefi/
│
├── machine_predictive_maintenance_raw/
│   └── ai4i2020.csv
│
├── preprocessing/
│   └── Eksperimen_RezaFahlefi.ipynb
│
├── machine_predictive_maintenance_preprocessing/
│   ├── X_train.csv
│   ├── X_test.csv
│   ├── y_train.csv
│   └── y_test.csv
│
├── requirements.txt
└── README.md
```

## Hasil Project

Dataset berhasil diproses dan dipersiapkan untuk tahap modeling machine learning dengan:

* Data kategorikal yang telah diencoding
* Dataset yang telah dibagi menjadi data training dan testing
* Fitur numerik yang telah dinormalisasi menggunakan StandardScaler

Project ini dapat digunakan sebagai dasar pengembangan sistem predictive maintenance pada lingkungan industri.

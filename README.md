# BankingMarketingTargets
Dalam project ini dilakukan prediksi apakah nasabah menerima tawaran untuk menjadi nasabah deposito atau tidak. Dalam pengerjaan project ini terdapat beberapa tahap diantaranya adalah:  
1. Penentuan Problem Statement, Goals, Objective dan Business Metrics  
2. Exploratory Data Analysis, Insight, dan Visualization
3. Modelling
4. Simulasi Bisnis

Dari project ini diperoleh bahwa model mampu meningkatkan persentase conversion rate dan juga meningkatkan ROI (Return on Invesment). Berikut merupakan variable atau kolom yang terdapat pada data set yang digunakan.

**Data Klien Bank**

| Code         | Deskripsi |
|:-------------|:-----|
| age |: usia (numerikal)|
| job |: jenis pekerjaan (kategorikal: 'admin.', 'blue-collar','entrepreneur', 'housemaid', 'management', 'retired','self-employed', 'services', 'student', 'technician', 'unemployed','unknown')|
| marital |: status pernikahan (kategorikal: 'divorced', 'married', 'single', 'unknown'; note 'divorced' means divorced or widowed)|
| education |: tingkat pendidikan (kategorikal: primary, secondary, tertiary and unknown)|
| default |: memiliki kredit sebelumnya? (kategorikal: 'no','yes','unknown')|
| housing |: memiliki cicilan rumah? (kategorikal: 'no','yes','unknown')|
| loan |: memiliki pinjaman pribadi? (kategorikal: 'no','yes','unknown')|
| balance |: saldo individual|  

**Kolom lainnya**  

| Code         | Deskripsi |
|:-------------|:-----|
| campaign|: jumlah kontak yang dilakukan selama kampanye ini dan untuk klien ini (numerikal)|
| pdays|: jumlah hari yang berlalu setelah klien terakhir dihubungi dari kampanye sebelumnya (numerikal, -1 berarti klien belum dihubungi sebelumnya)|
| previous|: jumlah kontak yang dilakukan sebelum kampanye ini dan untuk klien ini (numerikal)|
| poutcome|: hasil dari kampanye pemasaran sebelumnya (kategorikal: "unknown","other","failure","success")|

**Variabel Ouput (target yang akan diprediksi):**

| Code         | Deskripsi |
|:-------------|:-----|
| y |: apakah klien berlangganan deposito berjangka? (biner: "yes","no")|  

Untuk informasi lebih rinci dapat dilihat pada file .ipynb.

Terima Kasih!

link dataset: https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets



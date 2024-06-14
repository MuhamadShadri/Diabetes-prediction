# Submission 1: Diabetes-prediction
Nama: Muhamad Shadri

Username Dicoding: [muhamad_shadri](https://www.dicoding.com/users/muhamad_shadri/academies)

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [Diabetes prediction dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset) |
| Masalah | Diabetes atau penyakit gula adalah kondisi kronis yang memerlukan perhatian serius. Ciri utama dari diabetes adalah tingginya kadar gula darah (glukosa) yang melebihi batas normal. Penyakit ini terjadi ketika tubuh tidak dapat lagi mengambil glukosa ke dalam sel dan menggunakannya sebagai sumber energi, yang menyebabkan penumpukan glukosa dalam aliran darah. Angka kematian akibat diabetes sangat tinggi, dengan data tahun 2021 menunjukkan bahwa diabetes menyebabkan 6,7 juta kematian di seluruh dunia, yang berarti satu kematian setiap lima detik. Dataset yang digunakan dalam proyek ini berisi apakah seseorang mempunyai penyakit diabetes, sehingga saat di predict dengan sistem machine learningnya, jika  dikategorikan 0 maka tidak terkena penyakit diabetes, sedangkan untuk yang mengidap penyakit diabetes di kategorikan/label dengan angka 1 |
| Solusi machine learning | Oleh karena itu, untuk mendeteksi diabetes biasanya pasien harus menjalani pemeriksaan kadar gula darah. Namun, dokter tidak bisa langsung menyimpulkan diabetes hanya dari pemeriksaan ini. Dengan menggunakan sistem klasifikasi diabetes berbasis machine learning, dokter dapat memperoleh informasi tambahan yang membantu dalam diagnosis dan perencanaan perawatan pasien di masa depan. |
| Metode pengolahan | Metode pengolahan data yang digunakan pada proyek ini adalah dengan menghapus atau drop datasetnya sehingga hanya mengambil 1000 baris pertama agar proses trainingnya bisa lebih cepat, melakukan tahap Data Ingestion dengan membagi dataset menjadi data training dan data evaluation dengan rasio 8:2. Kemudian melakukan tahap Data Validation dengan cara melihat statistik data, data schema. Setelah itu melakukan tahap Data Preprocessing dengan melakukan transformasi fitur input pada data. |
| Arsitektur model | Deskripsi arsitektur model yang diguanakan |
| Metrik evaluasi | Metrik evaluasi yang digunakan yaitu AUC, Precision, Recall, ExampleCount dan BinaryAccuracy |
| Performa model | Deksripsi performa model yang dibuat |
| Opsi deployment | Deksripsi tentang opsi deployment |
| Web app | Tautan web app yang digunakan untuk mengakses model serving. Contoh: [nama-model](https://model-resiko-kredit.herokuapp.com/v1/models/model-resiko-kredit/metadata)|
| Monitoring | Deksripsi terkait hasil monitoring dari model serving |

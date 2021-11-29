# Multilabel Emotion Classification

## Daftar Isi 
+ [Info Umum](#info) 
+ [Kebutuhan](#kebutuhan)
+ [Potongan Kode](#potongan)
+ [Hasil](#hasil)
-----
<a name="info"></a>
### Info Umum
Pendeteksian emosi menggunakan klasifikasi multi-label menjadi masalah karena suatu kalimat cenderung melibatkan lebih dari satu kategori emosi. Sehingga, tantangan utama yang muncul adalah bagaimana memodelkan ketergantungan antar label menggunakan pendekatan klasifikasi. Analisis emosi melalui sebuah teks tampaknya juga menjadi tantangan karena faktanya bahwa ekspresi tekstual tidak selalu secara langsung melibatkan kata-kata yang berhubungan dengan emosi, tetapi seringkali suatu kalimat perlu dipahami untuk memberikan sebuah makna.

Penelitian ini menggunakan metode `Bi-LSTM (Bidirectional Long Short Term Memory) dan word embedding GloVe`. Dimana Bi-LSTM sangat baik digunakan untuk mengenali pola dalam kalimat, dikarenakan setiap kata dalam kalimat diproses secara sekuensial, kemudian word embedding GloVe memiliki akurasi yang baik untuk memproses pembobotan kata dalam data dibanding model word embeddings lain seperti CBOW dan skip-grams.

-----
<a name="kebutuhan"></a>
### Kebutuhan
+ Python
+ Anaconda
+ Jupyter Notebook
+ [Word embedding GloVe](https://www.kaggle.com/thanakomsn/glove6b300dtxt)

-----
<a name="potongan"></a>
### Potongan Kode
+ Bi-LSTM <br />
![bilstm](https://user-images.githubusercontent.com/60679744/143877704-2c6a2934-4518-484c-ad92-7ae2d5a83bc6.PNG)

+ GloVe <br />
![glove](https://user-images.githubusercontent.com/60679744/143881087-e35e1853-2df2-4022-9d53-506b503e3d5d.PNG)

+ Evaluation
![evaluation](https://user-images.githubusercontent.com/60679744/143879569-22e592a5-2a85-4d9b-b024-3171ea3990b5.PNG)

-----
<a name="Hasil"></a>
### Hasil
![chart](https://user-images.githubusercontent.com/60679744/143879558-7419894d-33aa-4cf7-bfe0-e98a07114d4a.PNG) 

-----

## Kontributor
+ 12S18004 - Rosalia Pane <a href="https://github.com/RosaliaPane">(@RosaliaPane)</a>
+ 12S18008 - Indah Tri Anastasya Manik <a href="https://github.com/indahmanik">(@indahmanik)</a>
+ 12S18011 - Nadya Putri Tambunan <a href="https://github.com/NadyaTambunan">(@NadyaTambunan)</a>
+ 12S18043 - Roy Gunawan Napitupulu <a href="https://github.com/hisublime">(@hisublime)</a>
+ 12S18048 - Rifka Uli Siregar <a href="https://github.com/RifkaSiregar">(@RifkaSiregar)</a>

# Pendeteksi Emosi

Pendeteksi emosi merupakan salah satu masalah bisnis dari Sentimen Analisis. Dataset ini diambil dari API IndoLU yang berisi tentang twit yang telah memiliki label, dimana label yang dimiliki bertotal 5.
Keterangan label
* 0 = Sadness
* 1 = Anger
* 2 = Love
* 3 = Fear
* 4 = Happy

Sumber dataset dapat ditemukan [disini](https://huggingface.co/datasets/indonlu)

Proses yang dilakukan adalah
1. Extract data from API
2. Text-preprocessing (Cleansing, Stopwords, Steamming, Tokenizing, Padded Sequences)
3. Modeling (CNN with 4 layers)
4. Evaluation (Sparse Categorical Crossentropy, Adam, dan Callbacks)
5. Prediction Testing

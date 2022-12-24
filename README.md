# Final-Project-Gaia.Inc
Final Project Brazilian E-commerce Dataset - Gaia.Inc - Purwadhika

*Member:*
- Muhammad Nurrizka Ramadhan
- Muhammad Faizal Akbar
- Shofli Yazid Khoirul Roziqin

##**Content**

1. Business Problem Understanding

2. Data Understanding & Preprocessing

3. EDA

4. RFM Analyisis

5. Modelling 

6. Conclusion

7. Recommendation

***

##**Business Problem Understanding**

**Context** <br>
Sejak kemunculan internet ditahun 1990-an membuat dunia berevolusi sangat cepat. Internet telah merubah segala bidang mulai dari ekonomi, pendidikan, sampai dengan budaya yang ada di dunia saat ini. Salah satu perubahan yang paling signifikan sejak lahirnya era internet adalah terjadinya revolusi dalam berbisnis seperti munculnya e-commerce. E-commerce merupakan salah satu revolusi dalam dunia saat ini yang disebabkan oleh internet, e-commerce sendiri sangat memudahkan manusia dimana kita sebagai manusia dapat membeli segala jenis barang yang kita inginkan dan barang tersebut akan diantarkan tepat didepan rumah kita. Saat ini banyak sekali e-commerce yang bertebaran didunia mulai dari yang memiliki pangsa pasar global seperti Amazon dan Alibaba, atau juga e-commerce yang memiliki pangsa pasar khusus di suatu negara seperti Tokopedia yang ada di Indonesia dan juga Olist yang salah satunya berada di Brazil. Saat ini GAIA.INC sebagai salah satu perusahaan konsultan telah berhasil memenangkan tender untuk membantu Olist untuk meramal performance perusahaan untuk periode selanjutnya untuk dapat menentukan langkah-langkah tepat yang dapat diambil.

**Problem Statement** <br>
Berdasarkan tender yang berhasil didapatkan sebelumnya, Olist memberikan penjelasan bahwa mereka memiliki dataset penjualan dari tahun 2016 - 2018 yang berada di Brazil. Dataset tersebut memiliki sekitar 100.000 data informasi terkait pemesanan yang dilakukan oleh customer. Pihak Olist juga mengatakan bahwa mereka memiliki banyak data namun bingung bagaimana untuk meramal performance penjualan untuk memutuskan langkah apa yang dapat dibuat untuk dapat tetap meningkatkan keuntungan. 

Dari beberapa penjelasan tersebut, GAIA.INC sebagai konsultan yang ditunjuk oleh Olist memberikan rekomendasi untuk membuat analisis forecasting ditambah dengan RFM analysis dari data yang ada untuk dapat memprediksi sales. 

**Goals** <br>
Penjelasan di bagian **Context** & **Problem Statement** dapat disimpulkan bahwa analisa Forecasting Timeseries merupakan metode yang dapat memproyeksikan performance sales, maka dari itu Olist membutuhkan kemampuan prediksi untuk dapat melihat trend penjualan berdasarkan performance tanggal-tanggal sebelumnya. Selain itu, dapat juga dilakukan analisis segmentasi customer agar perusahaan dapat memberikan treatment yang tepat terhadap jenis-jenis customer yang berbeda dari segi recency, frequency, dan moneytary.

Dengan mengetahui itu semua, Olist dapat membuat strategi yang tepat untuk meningkatkan sales dan revenue seperti penyediaan stock barang yang laku terjual pada waktu-waktu tertentu ataupun pemilihan strategi marketing dan promosi perusahaan sehingga dapat memberikan keuntungan yang lebih pada perusahaan.

**Analytic Approach** <br>
Jadi GAIA.INC akan melakukan analisis data untuk memprediksi sales yang kemungkinan terjadi dari situs e-commerce Olist. Prediksi tersebut didasarkan pada performa sales selama 2 tahun terakhir yaitu tahun 2016-2018.
Selain itu juga akan dilakukan analisis RFM untuk membagi customer menjadi beberapa segmen berdasarkan recency, frequency, dan moneytary.

**Metric Evaluation** <br>
RMSE (Root Mean Square Error)

Ecommerce Customer - Churn Analysis

Ivan Triandjono Putra

Dendi Mahawarman

Aqilah Aini Zahra

Dataset Source : https://www.kaggle.com/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction

Contents Flowchart Program :
1. Business Problem Understanding
2. Data Understanding / EDA
3. Data Preprocessing
4. Modeling
5. Conclusion
6. Recommendation

**Problem Understanding :**

Sebuah perusahaan e-commerce yang bergerak dalam bisnis jual beli barang secara online merupakan salah satu solusi dalam dunia digital yang mempermudah pelanggan dalam memenuhi kebutuhannya tanpa harus berkunjung secara langsung ke toko penjual. Online e-commerce menawarkan banyak kemudahan bagi pelanggan diantaranya pelanggan dapat membandingkan banyak produk sekaligus untuk mendapatkan produk dengan harga yang murah dan berkualitas, banyak tersedia berbagai macam barang dalam satu tampilan, menyediakan berbagai metode pembayaran dari pembayaran secara cash hingga cicil melalui kartu kredit atau financial partner, hingga terdapat banyak promo dari diskon hingga cashback yang ditawarkan kepada pelanggan. Dalam bisnis online e-commerce, pelanggan menjadi komponen penting dalam pendapatan perusahaan contohnya seperti pelanggan dapat memberikan pendapatan secara langsung ketika pelanggan tersebut melakukan transaksi melalui online platform perusahaan, atau tingkat keramaian atau trafic pelanggan dalam online platform perusahaan juga dapat menarik brand untuk bekerjasama ikut memasarkan produknya melalui online platform perusahaan. Oleh karena itu menjadi hal yang sangat penting untuk perusahaan agar dapat menjaga pelanggannya agar tetap setia / loyal tidak berpindah pada online platform perusahaan lain (Customer Churn). Kita dapat melihat pada kasus netflix yang merupakan online platform untuk menonton film, pada kuartal 1 tahun 2022 netflix kehilangan hingga 200.000 pelanggan yang tentunya dapat berpengaruh cukup signifikan terhadap pendapatan perusahaan.

Customer Churn atau yang dikenal juga dengan pindahnya pelanggan adalah pemutusan jasa suatu perusahaan oleh pelanggan karena pelanggan tersebut memilih menggunakan jasa layanan lain (Masarifoglu & Buyuklu, 2019). Dengan memprediksi churn perusahaan dapat mengidentifikasi churn lebih awal sehingga kerugian perusahaan akibat konsumen yang pindah dapat dihindari. Konsumen adalah aset utama perusahaan sehingga salah satu cara perusahaan mempertahankan konsumen adalah dengan mengenali pelanggan potensial dan harus mampu mempertahankan pelanggan potensial (customer retention) sehingga dapat mencegah pelanggan menghentikan pembelian dan berpindah ke perusahaan pesaing (churn).

Menurut Emmet C. Murphy dan Mark A. Murphy dalam buku Leading On The Edge of Chaos bahwa memperoleh pelanggan baru menghabiskan biaya lima kali lipat dari biaya untuk memuaskan dan mempertahankan pelanggan lama, sementara itu peningkatan sebanyak 2% dalam mempertahankan pelanggan (customer retention) punya dampak terhadap laba seperti memangkas biaya sebesar 10%. Dengan menerapkan churn prediction, perusahaan dapat melakukan identifikasi pelanggan churn dan menerapkan strategi pemasaran yang tepat terhadap pelanggan – pelanggan lama dengan harapan dapat meningkatkan pendapatan perusahaan.

Target :

0 : Pelanggan tetap menggunakan E-commerce/Loyal

1 : Pelanggan meninggalkan menggunakan E-commerce/Keluar


**Problem Statement :**

Salah satu permasalahan yang penting dalam bisnis jual beli online adalah bagaimana perusahaan dapat menjaga konsumennya agar tetap loyal dan tidak pindah ke online platform perusahaan lain. Konsumen adalah aset utama perusahaan sehingga salah satu cara perusahaan mempertahankan konsumen yaitu dengan melakukan prediksi pelanggan churn. Dengan melalukan prediksi, perusahaan mampu mengidentifikasi pelanggan potensial (customer retention) sehingga perusahaan dapat menerapkan strategi pemasaran yang tepat seperti memberikan promo diskon atau cashback kepada pelanggan yang berpotensi churn sehingga dapat mencegah pelanggan tersebut menghentikan pembelian dan berpindah ke perusahaan pesaing (churn).

Dengan adanya model prediksi pelanggan churn ini, perusahaan dapat meminimalkan kerugian akibat kehilangan sejumlah pelanggan karena perusahaan mampu mengidentifikasi pelanggan yang loyal dan tidak. Sehingga biaya yang keluar untuk menarik pelanggan baru dapat dihindari dengan mempertahankan pelanggan yang loyal dimana biaya untuk mempertahankan pelanggan yang sudah ada relatif lebih rendah dibanding dengan menarik pelanggan baru.


**Goals :**

Berdasarkan permasalahan tersebut, perusahaan harus memiliki tools yang dapat memprediksi pelanggan churn dan mengenali karakteristik pelanggan churn sehingga perusahaan dapat mengambil langkah - langkah antisipatif untuk menjaga pelanggan tersebut. Variabel - variabel yang berpengaruh dalam pelanggan churn diantaranya gender, tenure / masa lama pakai aplikasi, kemudahan dalam menggunakan aplikasi (user friendly), jumlah promo yang ada dalam aplikasi, jangka waktu pengiriman barang hingga respon dari customer service jika terdapat kendala selama bertransaksi.

Tujuan pemodelan dengan memprediksi pelanggan churn adalah mengetahui karakteristik pelanggan churn berdasarkan metode klasifikasi. Pemodelan ini diharapkan mampu mengidentifikasi pelanggan churn dan tidak sehingga perusahaan mampu menerapkan strategi customer retention dan costumer churn yang tepat. Dan juga perusahaan dapat mengetahui variable kostumer loyal atau tidak terhadap layanan.

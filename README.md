# California Housing Price Prediction 1990

**Latar Belakang**

California adalah salah satu negara bagian yang paling berkembang dan terkenal di Amerika Serikat. Statusnya sebagai pusat teknologi, bisnis, dan hiburan menarik orang-orang untuk tinggal dan bekerja di wilayah ini. Karena itu, permintaan tinggi akan rumah di California menjadi salah satu faktor utama yang mendorong harga rumah menjadi tinggi. Pertumbuhan ekonomi yang berkelanjutan dan lapangan kerja yang kuat di wilayah ini membuat banyak orang mencari rumah, sehingga permintaan yang tinggi meningkatkan nilai properti.

Investasi di sektor real estat merupakan pilihan menarik bagi para investor untuk mencapai keuntungan jangka panjang. Salah satu sumber keuntungan utama bagi investor dalam real estat adalah peningkatan nilai properti dari waktu ke waktu. Potensi kenaikan nilai properti ini memberikan kesempatan bagi investor untuk memperoleh pengembalian investasi yang menguntungkan.

Dalam investasi di bidang real estat, para investor perlu mengidentifikasi dan memahami nilai jual properti dengan baik. Oleh karena itu, dilakukan prediksi harga rumah guna menilai apakah properti tersebut memiliki harga jual yang rasional dan sesuai. Informasi prediksi ini memiliki nilai signifikan bagi para investor dalam menentukan apakah investasi di properti tertentu akan menghasilkan pengembalian investasi yang menguntungkan atau tidak.

Dengan demikian, prediksi harga rumah memiliki peran penting dalam membantu para investor di sektor real estat untuk mengidentifikasi peluang investasi yang menjanjikan dan mencapai hasil yang menguntungkan dari investasi yang mereka lakukan.

**Problem Statement**

Bagaimana melakukan prediksi harga rumah dengan akurat untuk membantu para investor dalam menilai potensi kenaikan nilai properti dan memastikan bahwa investasi yang direncanakan akan memberikan pengembalian investasi yang menguntungkan?

**Goals**

Mengembangkan model prediksi harga rumah yang akurat berdasarkan data historis dan faktor-faktor terkait seperti lokasi, karakteristik properti, dan kondisi ekonomi memiliki potensi untuk memberikan wawasan yang lebih mendalam bagi para investor di sektor real estat. Dengan prediksi harga rumah yang dapat diandalkan, para investor dapat memahami lebih baik tentang potensi kenaikan nilai properti dan membuat keputusan investasi yang lebih bijaksana. Faktor-faktor yang memberikan pengaruh signifikan terhadap harga rumah meliputi Demographics (lokasi properti), Home size and usable space, Age and condition, Distance, Popularity dan serta faktor-faktor ekonomi (pendapatan masyarakat).

Reference:
* RESEARCH ON FACTORS AFFECTING REAL ESTATE VALUES BY DATA MINING\
https://www.researchgate.net/publication/329778823_Research_on_Factors_Affecting_Real_Estate_Values_by_Data_Mining
* Effects of socioeconomic factors on regional housing prices in the USA\
https://www.emerald.com/insight/content/doi/10.1108/IJHMA-11-2012-0056/full/html
* Factors Affecting Housing Prices: International Evidence\
https://websites.ucy.ac.cy/erc/documents/Paper4_87-96.pdf 
* Analysis of factors influencing the price of real estate based on interpretative structural model\
https://www.atlantis-press.com/article/25891072.pdf

**Analytic Approach**

Jadi yang akan kita lakukan adalah menganalisis data historis tentang harga rumah di California untuk menemukan pola-pola yang mempengaruhi kenaikan harga perumahan. Kemudian kita akan membangun model regresi yang dapat membantu dalam memprediksi harga perumahan berdasarkan faktor-faktor yang relevan.

Model Regression memungkinkan kita untuk memodelkan hubungan antara variabel-variabel numerik seperti longitude, latitude, housing_median_age, total_rooms, total_bedrooms, population, households, dan median_income terhadap variabel target "median_house_value." Model regresi akan membantu dalam memahami bagaimana variabel-variabel ini berkontribusi terhadap harga rumah dan memberikan prediksi harga rumah yang akurat berdasarkan nilai-nilai variabel independen yang ada.

Dengan menggunakan metode Machine Learning Regression, para investor dapat memprediksi harga rumah berdasarkan atribut-atribut properti yang relevan. Hal ini akan membantu mereka dalam menilai potensi harga jual dan membuat keputusan investasi yang lebih baik dan berdasarkan analisis data yang lebih informatif.

**Metric Evaluation**

Evaluasi metrik yang akan digunakan adalah MAE, MAPE dan RMSE. Nilai MAE yang lebih rendah menunjukkan bahwa model memiliki kesalahan prediksi yang lebih kecil dan untuk MAPE menunjukan persentase error yang dihasilkan oleh model regresi semakin kecil nilai MAPE maka model semakin akurat dalam memprediksi. Sedangkan untuk RMSE semakin rendah nilai RMSE semakin baik performa model dalam memprediksi harga rumah. maka standar deviasi dari penyimapangan residu semakin rendah

Selain itu, kita juga bisa menggunakan nilai R-squared. Nilai R-squared yang mendekati 1 menunjukkan bahwa model berhasil menjelaskan variasi harga dengan baik (hanya digunakan saat model linier)

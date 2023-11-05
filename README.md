CALIFORNIA HOUSING PRICE
**Konteks**
Dataset merupakan kumpulan data perumahan di California, Amerika Serikat, yang berasal dari sensus yang dilakukan pada tahun 1990. Dataset tersebut berisikan data-data demography (income,populasi,house occupancy), lokasi area (longitude,latitude) dan informasi general terkait perumahan pada daerah tersebut (number of rooms, number of bedrooms, house age).

**Pernyataan Masalah**
Tantangan dari setiap developer perumahan adalah bagaimana menentukan harga perumahan yang tepat serta dimana lokasi untuk membangun perumahan agar tidak salah sasaran ketika menentukan harga dan lokasi perumahannya. developer tentu saja tidak ingin membangun perumahan elit di kawasan yang notabene warga sekitarnya berpenghasilan rendah, atau membangun perumahan yang biasa saja di kawasan elit. Hal ini tentu saja akan berdampak dari penjualan properti rumah tersebut.

**Tujuan**
Untuk menentukan harga jual suatu rumah di daerah California berdasarkan fitur-fitur yang ada. Terdapat berbagai perbedaan fitur pada suatu properti, seperti jumlah kamar, lokasinya, median income yang dapat membedakan harga jual secara prediksi, yang mana dapat mendatangkan profit bagi setiap developer rumahan yang juga sesuai dengan target marketing developer tersebut.

**Analytic Approach**
Analisis data sangat penting dan akan dilakukan karena untuk dapat menemukan pola-pola dari fitur yang ada yang membedakan properti-propertinya.  
Selanjutnya, suatu model regresi akan dibangun yang akan membantu perusahaan untuk dapat menyediakan alat prediksi harga jual rumah yang baru yang akan berguna untuk menentukan harga jual suatu rumah pada daerah tersebut.

**Metrics Evaluation**
Evaluasi metrik yang akan digunakan adalah RMSE, MAE, dan MAPE, di mana RMSE adalah nilai rataan akar kuadrat dari error, MAE adalah rataan nilai absolut dari error, sedangkan MAPE adalah rataan persentase error yang dihasilkan oleh model regresi. Semakin kecil nilai RMSE, MAE, dan MAPE yang dihasilkan, berarti model semakin akurat dalam memprediksi harga sewa sesuai dengan limitasi fitur yang digunakan.

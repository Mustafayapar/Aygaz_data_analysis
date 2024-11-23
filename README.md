# Aygaz_data_analysis
Depression Dataset Analysis

#1. Gerekli Kütüphanelerin Yüklenmesi
Proje başında, veri analizi ve işleme için gerekli Python kütüphaneleri yüklendi:

pandas: Veri manipülasyonu ve analiz için.
numpy: Sayısal işlemler için.
seaborn ve matplotlib: Görselleştirme için.
scikit-learn: Makine öğrenimi ve eksik veri tamamlama işlemleri için.

# 2. Veri Yükleme ve İlk İnceleme
Veri kümesi, pandas kullanılarak yüklendi ve ilk incelemeler yapıldı:

.head() ve .info(): Veri kümesinin genel yapısı incelendi (sütun isimleri, veri türleri ve eksik değerler).
.describe(): Sayısal değişkenlerin istatistiksel özetleri incelendi.

# 4. Eksik Verilerin Doldurulması
Eksik veriler, KNNImputer kullanılarak tamamlandı. Bu yöntem, en yakın komşuların değerlerinin ortalamasını alarak eksik verileri doldurur:

# 5. Kategorik Verilerin İncelenmesi
Kategorik değişkenler (Marital Status gibi) için seaborn ile sütun bazlı dağılımlar görselleştirildi.
Hataları önlemek için sütun isimlerinde ya da yöntemlerde düzeltmeler yapıldı.

# 6. Veri Görselleştirme
Veri dağılımını anlamak ve analiz sonuçlarını yorumlamak için şu görselleştirme yöntemleri kullanıldı:

Seaborn Heatmap: Değişkenler arasındaki korelasyonu göstermek için.
Countplot: Kategorik değişkenlerin frekanslarını göstermek için.
Histogram ve Boxplot: Sayısal değişkenlerin dağılımını incelemek için.

# 7. Veri Analizi
Proje kapsamında gerçekleştirilen veri analizleri:

Kategorik ve sayısal değişkenler arasındaki ilişkiler incelendi.
Veri setinin genel eğilimleri ve anomaliler (uç değerler) analiz edildi.
Görselleştirme ve istatistiksel yöntemlerle raporlandı.

# Kaggle Notebook Linki
Projenin Kaggle üzerindeki notebook'una buradan ulaşabilirsiniz: [Kaggle Notebook](https://www.kaggle.com/code/mustafayapar/data-analysis-deppression)


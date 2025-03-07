﻿# Titanic Veri Seti ile Keşifçi Veri Analizi ve Sınıflandırma Projesi

Bu proje, Titanic veri seti kullanarak keşifçi veri analizi, veri ön işleme, görselleştirme ve sınıflandırma modelleri geliştirilmesini içermektedir. Proje, farklı aşamalarda veri analizi ve modelleme tekniklerini uygulamayı amaçlamaktadır.

## Proje İçeriği

### 1. **Veri Seti Seçimi**
- Titanic veri seti, Seaborn kütüphanesinden alınmıştır ve en az 6 değişken içermektedir.
- Veri seti, eksik veriler ve farklı türdeki (sayısal ve kategorik) değişkenleri içerir.
- Hedef değişkenimiz, yolcuların hayatta kalıp kalmadığını belirten "Survived" değişkenidir.

### 2. **Keşifçi Veri Analizi ve Görselleştirme**
- Veri seti hikâyesi anlatılmış, her bir değişkenin anlamı ve verinin nasıl oluştuğu açıklanmıştır.
- Veri yapısı detaylandırılmıştır:
  - Gözlem sayısı (satır sayısı)
  - Değişkenler ve türleri
  - Sayısal değişkenler için betimsel istatistikler
  - Kategorik değişkenler için sınıf sayıları ve frekanslar
  - Eksik verilerin tespiti ve sayıları
- Farklı görselleştirme teknikleri ile veri analiz edilmiştir.

### 3. **Veri Ön İşleme**
- Aykırı değer problemleri tespit edilerek ortalama ile doldurma ya da baskılama yöntemi ile çözümlenmiştir.
- Eksik veriler, silme, değer atama ve tahmin yöntemleri ile çözülmüştür.
- Kategorik değişkenler için one-hot encoding ve sayısal dönüşümler yapılmıştır.

### 4. **Sınıflandırma Modelleri**
- Titanic veri seti ile sınıflandırma problemi çözülmüştür.
- Derste anlatılan 4 farklı sınıflandırma modeli (örneğin, Logistic Regression, Decision Tree, Random Forest, SVM) kullanılarak hiperparametreler k-kat çapraz doğrulama ile optimize edilmiştir.
- Modellerin performansları şu metriklere göre karşılaştırılmıştır:
  - Test doğruluğu (accuracy)
  - Ortalama kesinlik (precision)
  - Ortalama F1-skoru (F1-Score)
  - Her bir sınıf için duyarlılık (recall)
- Boyut azaltma yöntemleri kullanılarak, en iyi modelin boyutu azaltılmış veri seti üzerinde performansı değerlendirilmiştir.

## Kullanılan Teknolojiler

- **Python**: Veri analizi ve modelleme için kullanılan ana programlama dili.
- **Pandas**: Veri işleme ve analizi.
- **Seaborn**: Veri görselleştirme.
- **Scikit-learn**: Makine öğrenmesi modelleri ve metrikleri.
- **Matplotlib**: Ekstra görselleştirme.
- **Numpy**: Sayısal işlemler ve hesaplamalar.

## Proje Adımları

1. **Keşifçi Veri Analizi ve Görselleştirme**
   - Titanic veri seti ile genel keşifçi analiz yapılmış ve verinin hikâyesi anlatılmıştır.
   - Veri yapısı detaylandırılmış ve görselleştirmelerle desteklenmiştir.

2. **Veri Ön İşleme**
   - Aykırı değerler tespit edilmiş ve çözülmüştür.
   - Eksik veriler çözülmüş ve değişken dönüşümleri gerçekleştirilmiştir.

3. **Sınıflandırma**
   - 4 farklı sınıflandırma modeli seçilmiş, optimize edilmiştir.
   - Modellerin performansları karşılaştırılmış ve boyut azaltma teknikleri ile yapılan testler değerlendirilmiştir.

## Proje Sonuçları

Bu proje, Titanic veri seti üzerinden yapılan analiz ve modelleme sürecini kapsamaktadır. Sonuçlar, veriyi anlamak ve makine öğrenmesi modelleri ile tahmin yapma sürecini içerir. Ayrıca, modellerin başarıları karşılaştırılmış ve boyut azaltma tekniklerinin performansa etkisi incelenmiştir.

Proje, Titanic veri seti ile gerekli analizleri ve modelleme adımlarını gerçekleştirecektir.

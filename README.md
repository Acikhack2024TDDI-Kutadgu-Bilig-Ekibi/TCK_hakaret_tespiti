 <b>Proje Planı: TCK'ya göre Hakaret İçeren Yorumları Tespit Etme Sistemi </b>

 1. Proje Tanımı <b>(Yapıldı)</b>
 
   - Amaç: Popüler kadın programının Instagram hesabından toplanan yorumları analiz ederek hakaret içeren yorumları tespit etmek.
   - Hedef: Sosyal medya platformlarında kullanıcı güvenliğini artırmak ve olumsuz içerikleri filtrelemek.

 2. Veri Toplama  <b><u>(Yapıldı, kodlar ve etiketlenen dataset eklendi)</u></b>
   - Veri Kaynağı:  8 Temmuz - 14 Temmuz 2024
     - Popüler kadın programının Instagram hesabından yorumları toplamak için bir web scraping aracı kullanılacak.
   - Veri Setinin Oluşturulması: 15 Temmuz - 21 Temmuz 2024  
     - Toplanan yorumlar, hakaret içeren ve içermeyen olarak etiketlenecek. 
     
 3. Veri Ön İşleme  22 Temmuz - 28 Temmuz 2024 
   - Temizlik:
     - Toplanan verilerdeki gereksiz karakterler, boşluklar ve özel semboller temizlenecek.
   - Tokenizasyon:
     - Metinler kelimelere veya alt kelimelere ayrılacak.
   - Düşük Frekanslı Kelimelerin Çıkarılması:
     - Sıklığı düşük olan kelimeler veri setinden çıkarılacak (Stop-Word).
   - Kelime Gömme:
     - Kelimeleri sayısal verilere dönüştürmek için Word2Vec, GloVe veya FastText gibi teknikler kullanılacak.

 4. Model Seçimi
   - Derin Öğrenme Modelleri:  22 Temmuz - 28 Temmuz 2024 
     - LSTM, BiLSTM, GRU, CNN gibi derin öğrenme modelleri belirlenecek.
   - Klasik Makine Öğrenmesi Modelleri:
     - Naive Bayes, SVM, Karar Ağacı, Rastgele Orman, Lojistik Regresyon gibi klasik makine öğrenmesi teknikleri belirlenecek.

 5. Model Geliştirme 
   - Modelin Eğitilmesi:   22 Temmuz - 28 Temmuz 2024 
     - Seçilen modeller eğitim verisi ile eğitilecek.
   - Hiperparametre Ayarı:
     - Modellerin hiperparametre ayarları optimize edilecek.
   - Modelin Değerlendirilmesi:
     - Eğitim ve test verileri kullanılarak modellerin performansı değerlendirilecek.

 6. Performans Ölçümü    22 Temmuz - 28 Temmuz 2024 
   - Performans Metrikleri:
     - F1 puanı, doğruluk, hassasiyet ve geri çağırma gibi metrikler hesaplanacak.
   - Karşılaştırma:
     - Derin öğrenme ve klasik makine öğrenmesi modelleri bu metrikler açısından karşılaştırılacak.

 7. Sonuçların Analizi   29 Temmuz - 4 Ağustos  2024 
   - Model Başarısı:
     - Hangi modelin en iyi sonuçları verdiği analiz edilecek.
   - Hata Analizi:
     - Yanlış sınıflandırılan örnekler incelenecek ve modelin zayıf noktaları belirlenecek.

 8. Uygulama Geliştirme 29 Temmuz - 4 Ağustos  2024 
   - Modelin Entegrasyonu:
     - En iyi performansı gösteren model, sosyal medya platformlarında kullanılabilir bir yorum filtreleme sistemi olarak entegre edilecek.
   
 9. Sonuçların Raporlanması 29 Temmuz - 4 Ağustos  2024 
   - Rapor Yazımı:
     - Proje süreci, bulgular ve sonuçlar içeren bir rapor hazırlanacak.
   - Sunum Hazırlığı:
     - Projeyi sunmak için bir sunum hazırlanacak ve mentorün geri bildirimleriyle geliştirilecek.

 10. Veri Paylaşımı ve Yaygınlaştırma 5 Ağustos  2024 
   - Veri Kümesi Yayınlama:
   - Araştırma Sonuçlarının Paylaşılması:
     

 11. Geri Bildirim ve İyileştirme 6 Ağustos  2024 
   - Geri Bildirim Alma:
    - İyileştirme:
     

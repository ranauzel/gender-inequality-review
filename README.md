Gender Inequality Review

Proje Hakkında

Bu proje, Hi-Code Veri Bilimi kapsamında Ceyda Yelkenci, Fatma Nur Kahveci ve Sima Aykut ile birlikte hazırlanmıştır. Çalışmamızda, ülkeler bazında kadın eşitsizlikleri üzerine odaklanan bir veri setini kullanarak analizler gerçekleştirdik.

Veri Seti

Veri setimiz Human Development Report'tan alınmıştır.

🔗 Veri Seti Kaynağı: Gender Inequality Index - Kaggle

Veri seti, 1995-2019 yılları arasındaki aşağıdaki değişkenleri içermektedir:

Gender Inequality Index (GII): Kadınlar ve erkekler arasındaki eşitsizliği ölçen bileşik bir endeks.

Maternal Mortality Ratio (MMR): 100.000 canlı doğum başına gebelikle ilişkili ölümler.

Adolescent Birth Rate (ABR): 15-19 yaş arası kadınlar için her 1.000 kişi başına doğum oranı.

Parlamentodaki Kadın Temsili: Ulusal parlamentoda kadınların sahip olduğu koltuk oranı (% olarak).

Ortaöğretim Görmüş Nüfus Oranı: 25 yaş ve üzeri nüfusun en az ortaöğretim düzeyine ulaşmış yüzdesi.

İşgücüne Katılım Oranı: 15 yaş ve üzeri nüfusun işgücüne katılım yüzdesi.

Veri Ön İşleme

Veri setinde eksik verileri analiz etmek için Missingno kütüphanesi kullanıldı. Eksik değerleri doldurmak için:

Ortalamayla doldurma ve

Önceki değeri kullanma yöntemleri uygulandı.
Bu sayede veri seti en optimize şekilde tamamlandı.

Kullanılan Yöntemler ve Analizler

📌 Regresyon Modeli:

2025 yılı için metrikleri tahmin etmek amacıyla regresyon modeli kullanıldı.

Modelimiz 0.98 doğruluk oranı elde etti.

📌 Ergen Doğum Oranı Analizi:

Bölgeler bazında incelendi ve Türkiye'nin konumu belirlendi.

📌 Korelasyon Analizi ve Hipotez Testi:

Parlamentodaki kadın temsili ile ergen doğum oranı arasındaki ilişki incelendi.

H0 hipotezi testi uygulandı.

📌 Haritalandırma:

Dünya haritası üzerinde 2019 yılı için kadın temsili ve ergen doğum oranlarının karşılaştırması yapıldı.

Sonuçlar

Bu proje kapsamında, kadın eşitsizliğine dair önemli içgörüler elde ettik. Gelecekte eşitsizlik oranlarının azalması ve kadın temsiliyetinin artması üzerine çalışmalar yapılabilir.

🚀 Daha fazla detay için veri setini ve kodları inceleyebilirsiniz!


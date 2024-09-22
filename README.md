# Pusula_Tuba_AKBAS

## Proje Adı:

- İlaçların Yan Etkisi

## Veri Seti Hakkında:

- side_effect_data isimli veri seti 2357 satır ve 19 kolondan oluşmaktadır.
- Kullanici_Id : int64
- Cinsiyet: object
- Dogum_Tarihi: datetime
- Uyruk: object
- Il: object
- Ilac_Adi: object
- Ilac_Baslangic_Tarihi: datetime
- Ilac_Bitis_Tarihi: datetime
- Yan_Etki: object
- Yan_Etki_Bildirim_Tarihi: datetime
- Alerjilerim: object
- Kronik_Hastaliklarim: object
- Baba_Kronik_Hastaliklari: object
- Anne_Kronik_Hastaliklari: object
- Kiz_Kardes_Kronik_Hastaliklari: object
- Erkek_Kardes_Kronik_Hastaliklari: object
- Kan_Grubu: object
- Kilo: float64
- Boy: float64

- Kronik_Hastaliklarim, Baba_Kronik_Hastaliklari, Anne_Kronik_Hastaliklari, Kiz_Kardes_Kronik_Hastaliklari, Erkek_Kardes_Kronik_Hastaliklari ve Ilac_Adi isimli kolonlarda birden fazla değer olduğu için verilerin tek satır haline gelmesiyle toplamda 40820 satır elde edilmiştir.

## Yol Haritası:

1. Gerekli Kütüphaneleri İçe Aktarma
2. Veriyi Alma
3. Veriyi Keşfetme ve Inceleme
4. Veri Ön İşleme - Data Prepprocessing
   - Veriyi temizleme
   - Eksik veya anlamsız verileri düzenleme (KNNImputer)
5. Veri Görselleştirme - Data Visualization
   - Veri setini anlamak amacıyla grafiklerin çizdirilmesi
6. Verinin Normalize Edilmesi (Kilo, Boy, Yas, Tedavi_Suresi ve Yan_Etki_Bildirim_Suresi)
7. One-Hot Encoder Islemi
8. Veri Bölme (80-20)
9. Sınıflandırma (SVM)
10. Model Eğitimi
11. Tahmin
12. F1 Score ve Accuracy Score Hesaplama

## Kurulum:

- Projeyi çalıştırmak için bir kopyasını indirebilirsiniz.
- Gerekli kütüphaneleri yükleyiniz.
- Ardından veri setini de alarak Side_Effect.ipynb dosyasındaki diğer aşamaları uygulayabilirsiniz.

## Proje Gereksinimleri:

- Sürüm: 3.11.5
- requirements.txt dosyası içerisinde kütüphanelerin sürümlerini kontrol edebilirsiniz.

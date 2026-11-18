# Online Alışverişte Satınalma Niyeti

> BIL545 · Veri Madenciliğinde İleri Konular · 2026–2027 Güz · Üsküdar Üniversitesi

## Grup

| Üye | Öğrenci no |
| :--- | :--- |
| Belgin Yavuz | 264329004 |

* **Grup adı:** V1
* **İletişim sorumlusu:** Belgin Yavuz, belgin.yavuz@st.uskudar.edu.tr
* **Grup tipi:** 1 kişi (Bu çalışma 1. ve 3. bölümlerden oluşmaktadır.)

## Soru

Oturum satınalmayla bitti mi?

## Veri

|||
|-|-|
|**Veri kümesi**|\[Online Shoppers Purchasing Intention Dataset]|
|**Kaynak**|\[https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset]|
|**Lisans**|\[ Creative Commons Attribution 4.0 International (CC BY 4.0) license]|
|**Boyut**|\[12330 × 17]|
|**Hedef değişken**|\[Revenue:Online Kullanıcıların Satın alma Niyeti]|



**Verinin indirilmesi:** Veri bu depoda yoktur.
Veri Kaynakta belirtilen linkten indirilerek Google Drive'a kopyalanmış paylaşıma açılmıştır. Colabta kodlar Drive linkinden alacak şekilde yazılmıştır.
https://drive.google.com/file/d/1jdg4x1QybV0rpoGCgaQoglRql5DOUDG5/view?usp=drive\_link

Colab Not defteri Google driveda görüntüleme amaçlı paylaşıma açılmıştır
https://colab.research.google.com/drive/1tMvCJX2IPBgsZqAsuNRef5_lgVU5QJct

GitHub deposu public yapılmıştır.
https://github.com/belginbyavuz/BIL545_Proje1_V1

**Sunum Dosyaları**

Sunum dosyaları aşağıdaki drive linkine eklenmiştir. Bölüm1 ve Bölüm3 için iki ayrı video çekilerek eklendi.
https://drive.google.com/drive/folders/1wnkNRUkJv3WhY1iYirwFiAJL1tkRMeGk?usp=drive\_link


## Depo yapısı

```
Proje 1 için yapı şu şekildedir
README.md
BIL545_Proje1_V1.ipynb

Proje 2 için yeni repository açılacaktır
README.md
BIL545_Proje2_V1.ipynb
```
## Çalıştırma

1. Defteri Colab'da açın: \[https://colab.research.google.com/drive/1tMvCJX2IPBgsZqAsuNRef5\_lgVU5QJct?usp=sharing]
2. Veriyi yukarıdaki adımlarla yükleyin.
3. **Çalışma Zamanı → Tümünü çalıştır.** Kütüphane sürümleri defterin ilk hücresinde yazdırılır.

## Sonuç özeti

### Proje 1 (vize)

* **Baseline:** \[ölçüt: 0,8437 ± 0,0002]
* **En iyi model:** \[model; Doğru Kurulum ölçüt: 0,6083 ± 0,0161]
* **Sızıntı deneyi:** \[Doğru Kurulum ölçüt: 0,6083 ± 0,0161, Yanlış Kurulum ölçüt: 0,6082 ± 0,0159, veri dengesiz olduğu için Accuracy yerine,F1 metriğine göre model değerlendirmesi yapılmıştır. ]
* **Önemli bulgular:** \[Baseline model %84 doğruluk oranıyla çoğunluk sınıfına odaklanarak baseline modeli çok başarılıymış gibi göstermiştir.Doğru Kurulumdaki %60'lık F1 skoru veri setindeki dengesizliğin model başarısını gizlediğini ortaya koymaktadır.Model, çoğunluğu oluşturan 'False' sınıfını tahmin ederek 'doğruluk' oranını yüksek gösterse de, asıl önemli olan 'True' sınıfında yanılıyor. F1 skorunun %61'de kalması, modelin satın alma niyetini yakalamakta zorlandığını ve dengesiz veri setinde iyileştirmeye ihtiyaç duyduğunu kanıtlıyor.]

### Proje 2 (final)

* **Proje 1'den düzeltilenler:** \[kısa liste]
* **Bölüm bulguları:** \[kümeleme, aykırı gözlem, alt grup analizi için birer cümle; 4–5 kişilik gruplar ek paketler için de]
* **Sınırlılıklar:** \[2–3 madde]

## Katkı beyanı

|Üye|Çalıştığı alt başlıklar ve işler|Sunumda anlattığı alt başlık|
|-|-|-|
|\[Belgin Yavuz]|\[Bölüm 1:Veri, ön işleme ve sızıntı]|\[Bölüm 1:Veri, ön işleme ve sızıntı ]|
|\[Belgin Yavuz]|\[Bölüm 2:Veri küpü ve birliktelik analizi]|\[Bölüm 2:Veri küpü ve birliktelik analizi]|
|...|||
||||
||||

## Yapay zekâ beyanı

\[Kullanılan araçlar, hangi aşamada ve ne için; kullanılmadıysa "Kullanılmadı".]



Bölüm 1 ve Bölüm 2'de Phyton kodlarını yazarken alınan hatalarda ve yazım aşamasında ise birçok bölümde yapay zeka uygulamalarından destek alındı.

Bölüm 2'de Birliktelik Analizinin İlgi Ölçütleri maddesinde nadir bir kategoriyi içeren kuralların mantığının oluşturulmasında ve üç kuralı alan bilgisiyle yorumlarken destek alındı.

## Kaynaklar

* \[https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset]
* \[Bölümlerin makaleleri ve diğer kaynaklar]


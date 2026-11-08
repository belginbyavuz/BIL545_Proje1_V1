# Online Alışverişte Satınalma Niyeti

> BIL545 · Veri Madenciliğinde İleri Konular · 2026–2027 Güz · Üsküdar Üniversitesi
> Bu dosya grubun GitHub deposunun ana sayfasıdır. Köşeli parantez içindeki yerleri doldurun ve her proje tesliminde güncelleyin.

## Grup

|Üye|Öğrenci no|
|-|-|
|Emircan Demir||
|Mehmet Tankut Yolsal||
|Şahin Güngördü||
|Belgin Yavuz|264329004|

* **Grup adı:** \[V1]
* **İletişim sorumlusu:** \[Şahin Güngördü, sahin.gungordu@st.uskudar.edu.tr]
* **Grup tipi:** 4 kişi (+ Ek paket 1)

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

Veri Kaynakta belirtilen linkten indirilerek Google Drive'da, projenin bulunduğu dizine  /content/drive/MyDrive/Colab Notebooks altına kopyalandı.

Sonrasında, google drive bağlantısı yapıldı.



## Depo yapısı

```
.
├── README.md
├── BIL545\_Proje1\_V1/
│   └── BIL545\_Proje1\_V1.ipynb
└── BIL545\_Proje2\_V1/
    └── BIL545\_Proje2\_V1.ipynb
```

## Çalıştırma

1. Defteri Colab'da açın: \[https://colab.research.google.com/drive/1tMvCJX2IPBgsZqAsuNRef5\_lgVU5QJct?usp=sharing] · \[Proje 2 Colab bağlantısı]
2. Veriyi yukarıdaki adımlarla yükleyin.
3. **Çalışma Zamanı → Tümünü çalıştır.** Kütüphane sürümleri defterin ilk hücresinde yazdırılır.

## Sonuç özeti

### Proje 1 (vize)

* **Baseline:** \[ölçüt: 0,8437 ± 0,0002]
* **En iyi model:** \[model; Doğru Kuruum ölçüt: 0,6154 ± 0,0159]
* **Sızıntı deneyi:** \[Doğru Kurulum ölçüt: 0,6154 ± 0,0159, Yanlış Kurulum ölçüt: 0,6156 ± 0,0162, veri dengesiz olduğu için Accuracy yerine,F1 metriğine göre model değerlendirmesi yapılmıştır. ]
* **Önemli bulgular:** \[Baseline model %84 doğruluk oranıyla çoğunluk sınıfına odaklanarak baseline modeli çok başarılıymış gibi göstermiştir.Doğru Kurulumdaki %61'lik F1 skoru veri setindeki dengesizliğin model başarısını gizlediğini ortaya koymaktadır.Model, çoğunluğu oluşturan 'False' sınıfını tahmin ederek 'doğruluk' oranını yüksek gösterse de, asıl önemli olan 'True' sınıfında yanılıyor. F1 skorunun %61'de kalması, modelin satın alma niyetini yakalamakta zorlandığını ve dengesiz veri setinde iyileştirmeye ihtiyaç duyduğunu kanıtlıyor.]

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


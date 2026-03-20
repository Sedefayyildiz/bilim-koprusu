# Bilim Köprüsü - PRD (Product Requirement Document)

## 1. Projenin Özeti
"Bilim Köprüsü", kırsal bölgelerdeki öğrencilerin ve eğitim gönüllülerinin bilimsel kavramları somutlaştırmasını sağlayan çift modlu bir web uygulamasıdır. Gemini API kullanarak teorik soruları günlük atık malzemelerle yapılabilecek fiziksel deneylere ve atölye planlarına dönüştürür.

## 2. Kullanıcılar
- **Kâşifler:** Meraklı, deney yapmak isteyen öğrenciler.
- **Rehberler:** Kısıtlı bütçeyle atölye düzenleyen eğitimciler.

## 3. Ekranlar ve UI/UX Özellikleri
- **Arayüz Teması:** Öğrencileri bilime teşvik edecek, laboratuvar veya uzay temalı gerçekçi arka plan görselleri.
- **Karşılama Ekranı:** "Ben bir Kâşifim" veya "Ben bir Rehberim" butonları ile giriş.
- **Kâşif Modu Ekranı:** Soru girilecek metin kutusu ve "Deney Tasarla" butonu. Sonuç olarak hikayeleştirilmiş DIY (Kendin Yap) deney adımları.
- **Rehber Modu Ekranı:** Konu ve sınıf mevcudu girilecek form, "Atölye Planla" butonu. Sonuç olarak malzeme listesi ve pedagojik atölye adımları.
- **Bekleme (Loading) Ekranı:** API çağrısı sırasında kullanıcıyı sıkmamak ve temayı yansıtmak için roket fırlatma, dönen dişli çarklar veya sıvı dökülen deney tüpü animasyonları.

## 4. Başarı Kriteri
Sistemin 30 saniye içinde sorunsuz çalışarak girdileri uygulanabilir bir fiziksel deneye dönüştürmesi ve mobil uyumlu, ilham verici bir tasarıma sahip olması.
# Kahve Sokağı: Oyun Tasarımı

## Özet
Oyuncu bir kafede barista olarak işe başlar. Müşterilerin istediği kahveleri hazırlar, kazandığı parayla kafesini geliştirir.

## Oyun Döngüsü
1. Gün başlar (sabah).
2. Müşteri gelir ve sipariş verir.
3. Oyuncu siparişi hazırlar ve teslim eder.
4. Para (ve bazen bahşiş) kazanır.
5. Gün sonunda kazanç özetlenir.
6. Oyuncu kazandığı parayla makine ve malzeme alır.
7. Yeni gün başlar.

## Günün Bölümleri
| Zaman | Görünüm | Not |
|-------|---------|-----|
| Sabah | Aydınlık, sakin | Güne yeni başlanır |
| Öğle  | Parlak | Yoğun saatler |
| Akşam | Sıcak, turuncu tonlar | Gün kapanışı |

(Hangi saatte hangi müşterilerin geleceği daha sonra belirlenecek.)

## Müşteri Karakterleri
Her müşterinin kendine özgü bir özelliği ve sipariş tarzı vardır.

| Karakter | Özellik | Sipariş eğilimi |
|----------|---------|-----------------|
| İş insanı | Bahşişi fazla verir | _Belirlenecek_ |
| Öğrenci | İndirimli alışveriş yapar | _Belirlenecek_ |
| _Yeni karakter_ | _Belirlenecek_ | _Belirlenecek_ |

## Geliştirme (Satın Alma)
- Yeni makineler (ör. espresso makinesi, filtre kahve makinesi)
- Yeni malzemeler (ör. süt, şurup, farklı kahve çekirdekleri)
- Yeni malzeme ve makineler yeni kahve çeşitlerinin kilidini açar.

## Yapılacaklar
- [ ] Şablondan gelen Counter ve Weather sayfalarını kaldır
- [ ] Ana menü ekranı
- [ ] Müşteri, Sipariş ve Kahve modelleri (`KahveSokagi.Core`)
- [ ] Gün sistemi ve sabah/öğle/akşam görünümü
- [ ] Sipariş alma ve hazırlama ekranı
- [ ] Para ve bahşiş hesaplama
- [ ] Karakter özellikleri (bahşiş, indirim)
- [ ] Mağaza: makine ve malzeme satın alma
- [ ] Oyunu kaydetme ve yükleme
- [ ] Görseller ve sesler

## Açık Sorular
- Sipariş hazırlama nasıl olacak (sürükle bırak, adım adım seçim, süre sınırı)?
- Yanlış sipariş verilirse ne olur?
- Oyunun bir sonu var mı, yoksa sonsuz mu devam eder?

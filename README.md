# CD4047BE ile LED Gösterge Devresi

Bu proje, **CD4047BE** entegresi kullanılarak yapılan basit bir LED gösterge devresini içerir. Bu devre, kare dalga osilatörü kullanarak bir LED'in belirli bir frekansta yanıp sönmesini sağlar.

## Devre Şeması

Devre şeması proje dosyalarında yer almaktadır. Şemada CD4047BE entegresinin bağlantılarını ve kullanılan bileşenleri bulabilirsiniz.

## Kullanılan Bileşenler

- **1 x CD4047BE** - Osilatör entegresi
- **1 x LED** - Gösterge LED'i
- **2 x Direnç** - R1, R2 (zamanlama dirençleri)
- **2 x Kapasitör** - C1, C2 (zamanlama kapasitörleri)
- **Güç Kaynağı** - 5V veya 12V güç kaynağı

## Devrenin Çalışma Prensibi

Devre, CD4047BE entegresinin astable modunda çalışmasıyla kare dalga sinyali üretir. Bu sinyal, LED'in belirli bir aralıkta yanıp sönmesini sağlar. Kullanılan direnç ve kapasitör değerleri, osilasyon frekansını belirler. Farklı değerler ile frekans değiştirilebilir.

## Proje Detayları

- **CD4047BE** entegresi ile basit bir astable osilatör devresi tasarlanmıştır.
- LED, kare dalga çıkışı ile belirli bir frekansta yanıp söner.
- Devre, zamanlama elemanları (R1, R2, C1, C2) ile osilasyon frekansını ayarlamayı öğretmektedir.

## Nasıl Kullanılır

1. Tüm bileşenleri devre şemasına uygun olarak yerleştirin.
2. CD4047BE'yi astable modda çalıştırmak için direnç ve kapasitörleri bağlayın.
3. Güç kaynağını bağlayın ve LED'in yanıp sönmesini gözlemleyin.
4. Farklı direnç ve kapasitörler kullanarak osilasyon frekansını değiştirebilirsiniz.

## Gelecekteki İyileştirmeler

- Frekans ayarını daha rahat yapmak için bir potansiyometre eklenebilir.
- Daha karmaşık gösterge devreleri için birden fazla LED eklenebilir.


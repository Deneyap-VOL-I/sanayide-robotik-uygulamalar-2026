# VOL-i Logo Dosyaları

Bu klasör, VOL-i için kullanılan logo ve logo varyantlarını tutar.

## Klasörler

- `svg/`: Vektörel wordmark kaynakları. Ölçeklenebilir kullanım ve yeniden dışa aktarma için ana kaynak bu klasördür.
- `png/`: Rapor, sunum, web ve hızlı paylaşım için dışa aktarılmış PNG varyantları.
- `archive/`: Önceki logo denemeleri, eski PNG çıktıları ve düzenlenebilir kaynak dosyaları.

## Güncel Varyantlar

- `pad-tight`: Yatay kullanım için kırpılmış/sıkı boşluklu wordmark.
- `pad-wide`: Yatay kullanım için daha geniş güvenli boşluklu wordmark.
- `square`: Kare alanlarda kullanılacak wordmark.
- `bg-transparent`: Şeffaf arka planlı sürüm.
- `bg-white`: Beyaz arka planlı sürüm.
- `bg-dark`: Koyu arka planlı sürüm.

## Genel Kural

- Rapor ve sunumlarda önce `png/` altındaki hazır çıktılar tercih edilmeli.
- Kalite kaybı olmadan yeni boyut gerekiyorsa `svg/` altındaki kaynaklardan yeniden dışa aktarılmalı.
- Eski denemeler doğrudan rapora eklenmemeli; karşılaştırma veya geri dönüş gerektiğinde `archive/` altında tutulmalı.
- PNG dosya adlarında varyant, arka plan türü ve piksel ölçüsü açıkça yazılmalı.

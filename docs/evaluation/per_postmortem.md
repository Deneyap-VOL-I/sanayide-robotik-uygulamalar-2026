# PER Sonrası Değerlendirme Notları

Bu not, 2026 PER aşaması sonucundan sonra repo ve gelecek başvuru çalışmaları için çıkarılan dersleri toplar. Amaç gönderilen raporu değiştirmek değil; gönderilen hali, hakem sonucunu ve bir sonraki rapor için yapılması gerekenleri ayrı ayrı saklamaktır.

## Korunacaklar

- Proje ana fikri: Otonom Endüstriyel Forklift Mobil Robot.
- Ana teknik çizgi: kamera, LiDAR, çatal mekanizması, güvenli duruş, fabrika otomasyon sistemiyle haberleşme.
- Gönderilen rapor kopyaları: `docs/submissions/2026/per/` altında arşiv olarak kalmalı.
- Kaynak şablonlar ve şartname: `docs/reference/` altında değişmeden tutulmalı.

## Ana Dersler

| Hakem Geri Bildirimi | Gelecek Çalışmada Yapılacak Karşılık |
|---|---|
| Rapor özeti çok kısa | Özette amaç, yapılan çalışmalar, alt sistemler, test planı ve sonuç/çıktı durumu birlikte verilecek. |
| Sistem gereksinimleri yok | Fonksiyonel, mekanik, elektronik, yazılım, güvenlik ve yarışma gereksinimleri tabloya ayrılacak. |
| Sistem diyagramı yok | Güç, kontrol, algılama, haberleşme ve mekanik alt sistemleri gösteren blok diyagram eklenecek. |
| Elektronik genel yapı eksik | Batarya, DC-DC, kontrol kartları, sensörler, motor sürücüler ve güvenlik hattı ayrı diyagramla gösterilecek. |
| Algoritmalar belirtilmemiş | Haritalama, lokalizasyon, rota takibi, QR okuma, çizgi/şerit algılama, hizalama ve güvenli duruş algoritmaları ayrı ayrı yazılacak. |
| Dış arayüz mesajları yok | Görev alma, kapı izni, yük alındı/bırakıldı, hata ve acil stop mesajları alanlarıyla tabloya dökülecek. |
| Güvenlik yüzeysel | Tehlike, önlem, algılama yöntemi, güvenli durum ve doğrulama yöntemi içeren güvenlik matrisi hazırlanacak. |
| Test senaryoları yok | Her test için amaç, kurulum, ölçüm yöntemi, başarı kriteri ve beklenen çıktı yazılacak. |
| Zaman/bütçe kırılımı yok | İş paketleri, alt görevler, sorumlu rol, tahmini süre ve bütçe kalemleri detaylandırılacak. |
| Yerlilik oranı yok | Hazır alınan, takım tasarımı ve yerli/ithal bileşen ayrımı yapılarak oran hesaplanacak. |
| Ticarileşme zayıf | Hedef kullanıcı, gelir modeli, maliyet kalemleri, rakip analizi ve ölçeklenebilirlik ayrı alt başlıklar olacak. |

## Repo İçin Sonraki Düzen Hedefleri

- `docs/evaluation/` altında tüm hakem geri bildirimleri tutulacak.
- `docs/submissions/` altında T3KYS'ye gerçekten gönderilen dosyalar değişmeden saklanacak.
- `docs/reports/` altında çalışma kopyaları ve yeni revizyonlar tutulacak.
- Gelecek rapor revizyonlarında kaynak dosya, gönderim arşivi ve çalışma kopyası birbirine karıştırılmayacak.
- Yeni diyagram, tablo ve bütçe verileri üretilirse bunların ham kaynakları `data/`, `media/` veya `wip/` altında ayrıca saklanacak.

## Gelecek Başvuru İçin Minimum Kontrol Listesi

- [ ] Rapor özeti en az proje amacı, yapılan çalışma, alt sistemler ve doğrulama planını içeriyor.
- [ ] Sistem gereksinimleri tablosu var.
- [ ] Sistem blok diyagramı var.
- [ ] Elektronik blok diyagramı var.
- [ ] Algoritma akış diyagramı ve algoritma listesi var.
- [ ] Dış arayüz mesaj tablosu var.
- [ ] Güvenlik matrisi var.
- [ ] Test senaryoları ve ölçüm metodolojileri var.
- [ ] Zaman çizelgesi iş alt kırılımlarıyla verilmiş.
- [ ] Bütçe kalemleri ve toplam bütçe tutarlı.
- [ ] Yerlilik oranı hesaplanmış.
- [ ] Ticarileşme için gelir modeli ve maliyet analizi var.
- [ ] Kaynakça metin içi atıflarla tutarlı.
- [ ] Sayfa önizlemeleri kontrol edilmiş; taşma, boş sayfa, kayma ve bozuk karakter yok.

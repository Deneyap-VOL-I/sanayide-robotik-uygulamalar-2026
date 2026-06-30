# Teknofest 2026 Sanayide Robotik Uygulamalar | VOL-İ

Bu repo, Deneyap / TEKNOFEST 2026 Sanayide Robotik Uygulamalar Yarışması için VOL-İ takımının başvuru verilerini, rapor dokümanlarını, görev dağılımını, konsept modelini ve proje görsellerini düzenli tutar.

## Proje Bilgileri

### Proje Özeti

- Proje adı: Otonom Endüstriyel Forklift Mobil Robot
- Takım: VOL-İ
- Kurum: Talas Deneyap Teknoloji Atölyesi
- Yarışma: 2026 Robotics Applications in Industry Competition
- Hedef: Fabrika içi lojistik süreçlerinde paletli yükleri otonom şekilde taşıyabilen güvenli ve geliştirilebilir bir mobil robot sistemi tasarlamak.

### Proje Açıklaması

Bu proje, fabrika içi lojistik ve depo süreçlerinde kullanılmak üzere otonom bir forklift mobil robot geliştirmeyi amaçlamaktadır. Robot; haritalama, rota takibi, QR kod algılama, görüntü işleme destekli çizgi takibi, engel algılama ve fabrika otomasyon sistemiyle haberleşme özellikleriyle palet üzerindeki yükleri belirlenen alma noktasından alıp bırakma noktasına taşıyacaktır.

### Görev Dağılımı

| Kişiler | Görev Adı |
|---|---|
| Ayşenur Ünal | Algoritmalar, Yazılım |
| Yusuf Erdem Yazğan | Takım Tanıtımı, Elektronik, Algoritmalar, Yazılım |
| Berra Nisa Şahin | Robot Üst Yapı |
| Beyzanur Can | Robot Üst Yapı |
| Ebrar Ölçekçioğlu | Mekanik |
| Eymen Asaf Aral | Elektronik |
| Furkan Dönmez | Mekanik |
| Talha Aydın | Araç Tasarımı, Elektronik |
| Muhammed Osman Temiz | Mekanik |
| Nurgül Solmaz Dal | Robot Üst Yapı |
| Mert Savar | Araç Tasarımı, Elektronik, Algoritmalar |

## Repo ve Dosya Düzeni

### Klasör Yapısı

- `docs/reference/`: Şartname ve elle düzenlenmeyecek resmi/kaynak şablonlar.
- `docs/reports/`: Doldurulmuş veya düzenlenen teknik yeterlilik raporları.
- `data/`: T3KYS başvuru bilgileri ve takım içi görev dağılımı gibi yapılandırılmış veriler.
- `models/`: 3B konsept model dosyaları.
- `media/photos/`: Proje ve sunum fotoğrafları.
- `media/team_task_distribution.svg`: Danışman öğretmenin verdiği görev dağılımı tablosunun görsel hali.

### Veri Dosyaları

- `data/t3kys_team_information.json`: T3KYS takım bilgileri, kurum bilgileri, konum ve takım tanıtım metni.
- `data/t3kys_pre_application.json`: Ön başvuru proje adı, proje açıklaması, TEKNOFEST geçmişi ve onaylar.
- `data/team_task_distribution.json`: Takım üyeleri ve danışman öğretmen tarafından verilen görev dağılımı.

### Doküman Düzeni

- `docs/reference/sartname.pdf`: Yarışma şartnamesi. Doğrudan düzenlenmemeli.
- `docs/reference/teknik_yeterlilik_rapor_sablonu.docx`: Hiç elle değiştirilmemiş rapor şablonu. Doğrudan düzenlenmemeli.
- `docs/reports/teknik_yeterlilik_raporu.docx`: Doldurulmuş veya üzerinde çalışılan teknik yeterlilik raporu.

### Çalışma Notları

- Dosya adları Git ve farklı işletim sistemleriyle daha sorunsuz çalışması için boşluksuz ve tarih-saat tabanlı düzenlendi.
- PDF, DOCX, STL ve görsel dosyaları binary olarak işaretlendi.
- Yeni yüklenecek hiç elle değiştirilmemiş kaynak dokümanlar `docs/reference/` altında tutulmalı.
- `docs/reference/` altındaki dosyalar doğrudan düzenlenmemeli; düzenleme gerekiyorsa önce `docs/reports/` altında bir çalışma kopyası oluşturulmalı.
- T3KYS ekranlarından alınan bilgiler JSON olarak `data/` altında tutulur. Böylece metinler rapor, sunum veya kod tarafında tekrar kullanılabilir.
- VOL-i takım/organizasyon logo kaynakları bu yarışma reposunda tutulmaz; ana logo arşivi [Deneyap-VOL-I/brand-assets](https://github.com/Deneyap-VOL-I/brand-assets) reposundadır.

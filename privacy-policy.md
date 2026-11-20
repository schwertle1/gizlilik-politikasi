# Gizlilik Politikası / Privacy Policy

**Son güncelleme / Last updated:** Kasım 2026 / November 2026

## Uygulama / Application

**Vaktin Nuru — Namaz Vakitleri ve Ezan Alarmı** (`com.vaktinnuru.app`)

## Kısa Özet / Summary

- **Hesap yoktur, kayıt yoktur.** Reklamlar **yalnızca Google AdMob** (banner) üzerinden ve yalnızca bazı araç ekranlarında gösterilir. Ayrı bir analitik/takip kitaplığı **yoktur**.
- Ayarlarınız yalnızca cihazınızda saklanır.
- Konumunuz **hiçbir zaman** bizim sunucumuza gönderilmez; bizim sunucumuz yok. Uygulama yalnızca aşağıda **adıyla listelenen** üçüncü taraf servislere, yalnızca o işlevi yerine getirmek için istek yapar.

## Dışarı Gönderilen Veriler / Data Sent to Third Parties

| Servis / Service | Ne zaman / When | Ne gönderilir / What is sent |
|---|---|---|
| **Diyanet İşleri** `ezanvakti.emushaf.net` | Namaz vakitleri güncellenirken | Seçili **il/ilçe numarası** ve tarih. Konum koordinatı gönderilmez. |
| **OpenStreetMap Nominatim** `nominatim.openstreetmap.org` | Yakın çevre araması açıldığında | **Aranan bölgenin sınırlayıcı kutusu (viewbox) ve yaklaşık konum**; serbest metin araması yapılmaz. |
| **Overpass API** | Camiler listelenirken | **Aynı yaklaşık konum kutusu** (yakındaki camileri bulmak için). |
| **api.alquran.cloud** | Günün ayeti meali önbellekte yokken | Yalnızca **sure/ayet numarası**. Konum veya kullanıcı bilgisi gönderilmez. |
| **Radyo istasyonları** | Radyo dinlenirken | Dinamik yayın akışının talep edilmesi. |
| **Google AdMob** (Google Mobile Ads SDK) | Reklam gösterilen araç ekranlarında | **Reklam kimliği (AD_ID)**, IP adresi ve SDK'nın topladığı cihaz/reklam etkileşim bilgileri. |

Cihaz ayarlarından reklam kimliğini sıfırlayabilir veya kişiselleştirilmiş reklamları kapatabilirsiniz. İstekler HTTPS üzerinden yapılır (yayın akışları istisnadır).

## İzinler / Permissions

| İzin / Permission | Kullanım amacı / Purpose |
|---|---|
| `ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION` | Konumdan vakit hesaplama ve yakın cami araması. |
| `POST_NOTIFICATIONS` | Vakit ve ezan bildirimleri. |
| `USE_EXACT_ALARM`, `SCHEDULE_EXACT_ALARM` | Ezanı tam vaktinde çalmak. |
| `VIBRATE` | Bildirim titreşimi. |
| `RECEIVE_BOOT_COMPLETED` | Yeniden başlatmadan sonra alarmları geri yüklemek. |
| `FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_MEDIA_PLAYBACK` | Ezan/radyo sesini arka planda çalmak. |
| `WAKE_LOCK` | Ses çalarken cihazı uyutmamak. |
| `INTERNET`, `ACCESS_NETWORK_STATE` | Yukarıdaki servislerden veri çekmek. |
| `com.google.android.gms.permission.AD_ID` | AdMob reklam kimliğine erişim. |

## Cihazda Kalan Veriler / Data Kept on the Device

Namaz vakti ayarları, seçili konum, bildirim/ses tercihleri ve favoriler yalnızca cihazınızda saklanır; sunucuya yüklenmez.

## Çocukların Gizliliği / Children's Privacy

Bu uygulama 13 yaş altı çocuklardan bilerek veri toplamaz.

## Değişiklikler / Changes

Bu politika gerektiğinde güncellenir; önemli değişiklikler uygulama güncellemesinde duyurulur.

## İletişim / Contact

Sorularınız için / Questions: **emretas092@gmail.com**

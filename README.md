# MASSIPTV — sürümler

MASSIPTV'nin yayınlanmış sürümleri: Android (telefon, tablet, TV kutusu, araç kutusu — tek APK) ve Windows.

- **Güncelleme:** Uygulama yeni sürümü buradan kendisi denetler; yeni sürüm çıkınca uyarır ve tek dokunuşla günceller
  (Ayarlar › Hakkında › Güncellemeler). Uygulama buraya kendi sürüm numarası dışında hiçbir bilgi göndermez.
- **Her sürümde:** Android APK, Windows kurulumu, o sürümün kaynak kodu (`…-kaynak.zip`, GPLv3) ve sürüm bilgisi
  (`surum.json`: dosyaların adresi, boyutu ve SHA-256 özeti).
- **İlk kurulum:** Android'de "bilinmeyen kaynaklardan yükleme" izni gerekir. Windows kurulumu imzasız olduğu için
  SmartScreen "Ek bilgi › Yine de çalıştır" ister. Yeni sürüm eskisinin üstüne kurulur; kaldırmak gerekmez, veriler korunur.
- MASSIPTV yalnızca bir oynatıcıdır: hiçbir yayın, liste ya da kanal içermez ve önermez. Kullanıcı kendi M3U ya da
  Xtream Codes bilgisini girer.

Lisans: GPLv3 (kaynak arşivindeki `LICENSE`). Üçüncü taraf bileşenler: kaynak arşivindeki `THIRD_PARTY_NOTICES.md`.

---

Published releases of MASSIPTV (Android single APK for phones, TV boxes and car units; Windows installer).
The app checks this repository for updates and sends nothing but its own version number. Each release contains the
APK, the Windows installer, the release's source code (GPLv3) and `surum.json` (file URLs, sizes, SHA-256).
MASSIPTV is only a player: it contains and recommends no streams, playlists or channels.

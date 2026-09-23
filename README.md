<p align="center">
  <img src="screenshot.png" width="420" alt="Walker Media Downloader">
</p>

<h1 align="center">Walker Media Downloader</h1>

<p align="center">
  YouTube ve X (Twitter) videolarını MP4 ya da MP3 olarak indirmek için sade bir Windows uygulaması.
</p>

<p align="center">
  <a href="../../releases/latest"><b>İndir (Windows)</b></a>
</p>

---

## Özellikler

- YouTube, YouTube Shorts, YouTube Music ve X (Twitter) desteği
- Video için 4K'ya kadar kalite seçimi, isteğe bağlı H.264 uyumluluk modu
- Ses için MP3 (128–320 kbps), M4A, FLAC ve WAV
- Videonun yalnızca belirli bir aralığını indirme
- Playlist ve çoklu videolu X gönderileri
- Giriş gerektiren içerikler için tarayıcı oturumu desteği (Firefox, Chrome, Edge, Brave)
- Kapak görseli ve etiketler dosyaya otomatik eklenir
- İndirme hızı, kalan süre ve görev çubuğunda ilerleme

## Kurulum

1. [Releases](../../releases/latest) sayfasından `WalkerMediaDownloader.exe` dosyasını indir.
2. Çalıştır. Kurulum gerekmez.

İlk açılışta gerekli bileşenler (yt-dlp, FFmpeg, Deno) resmi kaynaklarından otomatik olarak indirilir. Bu işlem bağlantı hızına göre bir iki dakika sürebilir. Bileşenler `%LOCALAPPDATA%\Walker\MediaDownloader` klasöründe tutulur ve yt-dlp haftada bir kendini günceller.

> Windows "Bilgisayarınız korundu" uyarısı gösterirse **Ek bilgi → Yine de çalıştır** seçeneğini kullan. Uygulama henüz dijital olarak imzalı olmadığı için bu uyarı çıkar.

## Gereksinimler

- Windows 10 veya Windows 11 (64-bit)
- .NET Framework 4.8 (Windows 10/11 ile birlikte gelir)

## Kullanım

1. Bir YouTube veya X bağlantısı yapıştır. Panoda bağlantı varsa uygulama açılırken otomatik doldurulur.
2. Video ya da Ses seç, kaliteyi belirle.
3. **İndir**'e bas. Dosyalar varsayılan olarak `İndirilenler\Walker` klasörüne kaydedilir; bu klasör uygulamadan değiştirilebilir.

## Üçüncü taraf bileşenler

Walker Media Downloader aşağıdaki açık kaynak araçları kullanır. Bu araçlar uygulamayla birlikte dağıtılmaz, ilk açılışta kendi resmi sürüm sayfalarından indirilir.

| Bileşen | Lisans | Kaynak |
|---|---|---|
| yt-dlp | Unlicense | https://github.com/yt-dlp/yt-dlp |
| FFmpeg | GPL | https://github.com/yt-dlp/FFmpeg-Builds |
| Deno | MIT | https://github.com/denoland/deno |

## Sorumluluk

Bu uygulama yalnızca kişisel kullanım içindir. İndirdiğin içeriklerin telif haklarına ve ilgili platformların kullanım koşullarına uymak senin sorumluluğundadır.

---

© 2026 Walker. Tüm hakları saklıdır.

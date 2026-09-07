# Canzies

Can'a adanmış resmi olmayan bir hayran topluluğu sayfası. Müzik, videolar ve sevgi dolu hayran mektupları içeren tek sayfalık bir site.

## Başlarken

Depoyu klonlayıp `index.html` dosyasını bir tarayıcıda açman yeterli, ayrıca bir kurulum gerekmiyor:

```bash
open index.html
```

## Şifre kapısı

Site belirli bir tarihe kadar bir şifreyle kilitli tutuluyor. Şifreyi ve açılış
tarihini değiştirmek için `index.html` içindeki `CORRECT_PW` ve `UNLOCK_DATE`
sabitlerini güncelle.

## Supabase bağlantısı (şarkı istekleri)

İstek şarkılar listesi siteyi ziyaret eden herkes arasında paylaşıldığı için
gerçek bir backend'e ihtiyaç duyar. Bağlanmadan da site çalışır, ama istekler
her cihazda ayrı ayrı `localStorage`'da tutulur.

1. [supabase.com](https://supabase.com) üzerinden ücretsiz bir proje oluştur.
2. `index.html` içindeki `SUPABASE_URL` ve `SUPABASE_KEY` değerlerini kendi
   projenin bilgileriyle güncelle.

## Gerçek içerikleri yerleştirme

- **Görsel**: `can.png` dosyasını değiştir ya da `index.html` içindeki `<img>`
  etiketinin `src`'sini güncelle.
- **Hayran mektupları / metinler**: `index.html` içindeki ilgili bölümleri
  doğrudan düzenle — site tek bir HTML dosyası içinde (HTML/CSS/JS bir arada).

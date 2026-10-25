# melihyonez.com

Sade, derleme aracı gerektirmeyen kişisel site (HTML + CSS). Site dili İngilizce; sözleşmelerin Türkçe sürümleri `tr/` altında.

## Yapı

```
index.html                  Ana sayfa
assets/style.css            Ortak stil (açık/koyu tema)
assets/main.js              Tema düğmesi, yıl
games/max/index.html        -> /games/max/
games/max/terms/index.html  -> /games/max/terms/
games/max/privacy/index.html-> /games/max/privacy/
games/max/*/tr/index.html   -> Sözleşmelerin Türkçe sürümleri (/terms/tr/, /privacy/tr/)
```

Yeni bir oyun için `games/max` klasörünü kopyalayıp adını değiştirmek yeterli.
Yollar `/` ile başladığı için site alan adının kökünde (melihyonez.com) çalışacak şekilde yazıldı.

## Yerelde çalıştırma

```
python -m http.server 8000
```
Sonra http://localhost:8000

# Kritik Teknoloji Bülteni

İHA ve savunma teknolojilerinde dünyadan günlük özet: rakipler, yeni teknolojiler, ihracat fırsatları, tedarik zinciri, enerji ve yapay zekâ.

Yayın adresi: https://elcuman.github.io/bulten/

## Yapı
- `index.html` — günün sayısı. Haberler sayfanın içindeki `<script id="news">` JSON bloğunda tutulur.
- `arsiv/` — önceki sayılar (`YYYY-MM-DD.html`) ve arşiv listesi.

## Günlük güncelleme
Her sabah yeni sayı `index.html`'e yazılır, bir kopyası `arsiv/` altına eklenir ve arşiv listesinde `<!-- YENI-SAYI -->` işaretinin altına bir satır eklenir.

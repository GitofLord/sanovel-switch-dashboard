# SANOVEL Switch & Sadakat Analizi Dashboard

Reçete–satış switch analizi interaktif panosu (Ocak 2025 – Mayıs 2026, 20 referans pazarı).

## İçerik
- `index.html` — Tamamen kendi kendine yeten (self-contained) tek dosyalık dashboard. Chart.js gömülü, harici bağımlılık yok, offline çalışır.

## Metodoloji
- **Birebir Aynı Verilme (Exact Match)**: A (Reçetelenen Ürün) = B (Satılan Ürün) olan satır sayısı / toplam reçete olayı
- **Switch**: A ≠ B olan satırların oranı
- **Kazanım (Win-back)**: A = rakip ürün, B = Sanovel ürünü olan satırlar; oran = kazanım / rakibin toplam reçete olayı
- Tüm hesaplamalar aynı referans pazarı içinde yapılmıştır.

## Deploy (Vercel)
```bash
npm i -g vercel
vercel --prod
```
veya GitHub'a push edip Vercel'de "Import Project" ile bağlayın.

---
SANOVEL İlaç · Business Excellence & Digital Transformation

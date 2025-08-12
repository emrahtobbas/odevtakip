# Ödev Takip Sistemi — GitHub Pages Demo

Bu depo, tamamen **HTML + JS (localStorage)** ile çalışır. Sunucu gerektirmez.  
Öğretmen/Öğrenci/Veli girişleri; öğrenci/veli ekleme; ödev oluşturma – hepsi tarayıcıda.

## Hızlı Başlangıç
1. Depoyu GitHub'a yükleyin.
2. **Settings → Pages**: Source olarak **Deploy from a branch** seçin, branch: `main` (veya `master`), folder: `/ (root)`.
3. Kaydedin. Birkaç dakika içinde Pages bağlantınız aktif olur. (Örn: https://kullaniciadi.github.io/depo-adi/)

## Demo Giriş
- Öğretmen: **ogretmen / 1234**  
- Öğrenci/Veli girişleri için sistemin verdiği **STU-… / PAR-…** kodlarını kullanın.

## Veri
- Veriler tarayıcıda `localStorage` içinde tutulur.
- **Dışa Aktar** ile JSON indirir; **İçe Aktar** ile geri yüklersiniz.
- **Sistemi Sıfırla** tüm yerel veriyi temizler.

## Görselleri Değiştirme
`assets/` klasöründeki yer tutucuları aynı adlarla değiştirin:
- `header-bg.jpg`, `footer-texture.png`, `side-left.png`, `side-right.png`, `logo.svg`

> Not: Çok kullanıcılı gerçek veritabanı gerekiyorsa Node.js + JSON DB sürümünü kurun.

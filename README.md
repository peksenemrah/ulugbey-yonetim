# Uluğbey Yönetim

Uluğbey İlkokulu için telefona yüklenebilir (PWA) yönetim uygulaması. İlk modül: **Etkinlik Takip**.

- Etkinlik bazında ücretli öğrenci ve kontenjan (ücretsiz) girişi
- Etkinlik arşivi, etkinlik raporu ve eğitim-öğretim yılı bazında yıllık rapor (PDF)
- A4 sayfaya 36 bilet, kesme çizgili bilet PDF'i
- Veriler Firebase Firestore'da (proje: `ulugbey-yonetim`), ortak PIN ile giriş

Dosyalar: `index.html` (uygulama), `manifest.webmanifest`, `sw.js` (çevrimdışı açılış), `icons/`, `firestore.rules` (Firestore güvenlik kuralları).

📍 İzleyeceğimiz yol haritası (sana net olması için):
1. Backend Kurulumu (Node.js + Express)
- index.js içinde Express sunucu hazır → ✅ bitirdik.
- API yapısını kuracağız: /recipes endpoint’i ile tarif ekleme, listeleme, silme.
- Veri önce geçici olarak JSON içinde tutulacak (dosya kaydı yok).
- Sonra veritabanına (PostgreSQL) bağlayacağız.

2. Frontend Kurulumu (HTML + Bootstrap)
- Anasayfa: Tarif listesi
- Tarif ekleme formu
- Tarif silme butonu

3. Backend ↔ Frontend Bağlantısı
- Fetch API ile frontend’den backend’e veri göndereceğiz.
- Yeni tarif eklenince sayfada otomatik görünecek.

4. Veritabanı Entegrasyonu
- PostgreSQL kuracağız.
- Tarifleri kalıcı olarak saklayacağız.

5. Ekstra Özellikler
- Fotoğraf ekleme (isteğe bağlı)
- Arama ve filtreleme
- Daha güzel tasarım

****************************
1. Backend API (CRUD)
 - Create (tarif ekleme)
 - Read (listeleme)
 - Update (tarif düzenleme)
 - Delete (tarif silme)
 - MongoDB Atlas bağlantısı kuruldu

2. Basit Frontend (Bootstrap ile)
 - Listeleme arayüzü
 - Ekleme formu
 - Düzenleme formu
 - Silme butonu

3. Frontend–Backend entegrasyonu
 - Fetch API ile bağlantılar kuruldu
 - CRUD işlemleri test edildi

4. Veritabanı entegrasyonu (in-memory → MongoDB)
 - Atlas’a geçildi, bağlantı çalışıyor
 - Gerçek kayıt ekleme, silme, düzenleme test edildi

5. Ekstra özellikler
 - Arama (search) özelliği
 - Görsel yükleme (upload)
 - Tasarım düzenlemeleri (Bootstrap ile responsive görünüm)

6. Yayına alma
 - Backend’i Render’da deploy etme
 - Frontend’i Vercel’de deploy etme
 - MongoDB Atlas ile canlı bağlantı kurma
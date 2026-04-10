# ✨ Lumina Digital Planner

**Lumina Digital Planner**, tüm planlama, hedef belirleme ve takip ihtiyaçlarınızı tek bir ekranda toplayan, tamamen yerel tarayıcı hafızasında (`localStorage`) çalışan **tek dosyadan (`.html`) ibaret** premium bir dijital planlayıcı uygulamasıdır. 

Modern, estetik ve minimalist tasarımıyla günlük rutininizi organize etmenize yardımcı olurken; sunucu, veritabanı veya karmaşık kurulum adımları gerektirmez. Dosyayı tarayıcınızda açmanız yeterlidir.

## 🚀 Öne Çıkan Özellikler

- **Tek Dosya Mimari:** `Lumina_Digital_Planner.html` dosyası içinde tüm CSS, JS ve HTML yapısını barındırır.
- **Yerel Depolama (Sıfır Kurulum):** Verileriniz tamamen kendi tarayıcınızda, güvende tutulur (`localStorage` ile sınırsız kalıcılık).
- **Kişiselleştirilebilir Arayüz:** 6 farklı pastel renk teması ve 3 farklı yazı tipi boyutu ile kendi tarzınızı yansıtın.
- **İçe/Dışa Aktarma (Yedekleme):** Verilerinizi tek tıkla `.json` dosyası olarak bilgisayarınıza indirebilirsiniz. 
- **Duyarlı Tasarım (Responsive):** Masaüstü, tablet ve mobil cihazlar ile uyumlu (PWA potansiyeline sahip) esnek grid yapısı.

## 🧩 Uygulama Modülleri

Uygulama içerisinde 9 farklı bölüm bulunmaktadır:

1. ⚡ **Dashboard (Kontrol Paneli):** Günlük görevlerin, alışkanlık ilerlemelerinin ve genel istatistiklerin özeti. Her güne özel motivasyon sözleri!
2. 📅 **Daily Plan (Günlük Plan):** Saatlik program, sabah/akşam rutinleri ve gün sonu değerlendirmeleri.
3. 🗓️ **Weekly & Monthly (Haftalık & Aylık):** Etkinlikleri ve görevleri genel bir takvim görünümünde takip edin.
4. ✅ **Tasks (Görevler):** Öncelik (Düşük/Orta/Yüksek) ve kategori etiketli, filtrelenebilir "To-Do" listesi.
5. 🌱 **Habits (Alışkanlıklar):** Emoji destekli alışkanlık takipçisi. 30 günlük ısı haritası (heatmap) ve "en iyi seri (streak)" hesaplaması.
6. 📓 **Notes (Notlar):** Zengin metin düzenleyici (Rich Text Editor) destekli, renkli vurgularla not ve günlük tutma alanı.
7. 🎯 **Goals (Hedefler):** Büyük hedefler ve bu hedefleri parçalara bölebildiğiniz ilerleme çubuğu destekli dönüm noktaları (Milestones).
8. 💰 **Finance (Finans):** Gelir/Gider takibi, net bakiye hesaplaması ve görsel bütçe çubukları.
9. ⚙️ **Settings (Ayarlar):** İsim, tema rengi, font ayarı, verileri `.json` olarak yedekleme (export) ve kalıcı olarak sıfırlama (erase) bölümü.

## 🛠️ Kullanılan Teknolojiler

Lumina, maksimum performans ve bağımsızlık için **saf (vanilla)** web teknolojileri ile geliştirilmiştir:
- **HTML5:** Yapılandırma ve semantik yapı.
- **CSS3:** Flexbox, Grid, CSS Değişkenleri (Variables) ve pürüzsüz mikro animasyonlar. 
- **Vanilla JavaScript (ES6):** `localStorage` veri yönetimi, DOM manipülasyonu ve uygulama mantığı.
- **Google Fonts:** "Playfair Display" (Başlıklar) ve "Inter" (Metinler).

## 🎯 Kurulum ve Çalıştırma

Lumina dijital planlayıcıyı kullanmak için sunucuya ihtiyacınız yoktur:

1. `Lumina_Digital_Planner.html` dosyasını bilgisayarınıza indirin.
2. Dosyaya çift tıklayarak favori tarayıcınızda (Chrome, Safari, Edge, Firefox vb.) açın.
3. Karşılama ekranında adınızı ve favori temanızı seçerek planlamaya başlayın!

> **İpucu:** Bu dosyayı tarayıcınızın "Yer İmleri" (Bookmarks) çubuğuna ekleyerek her gün hızlıca erişebilirsiniz.

## 🎨 Tasarım Felsefesi

Uygulama, estetik ve üretkenliğin kesişimi olarak tasarlandı.
- Cam görünümlü (Glassmorphism esintili) kart yapıları,
- Yumuşak köşe dönüşleri (`border-radius`),
- Sizi yormayan "pastel" ve "açık" renk paleti (Vanilla/Bej alt tonlar),
- Minimalist butonlar ve geri bildirim animasyonları (Toast bildirimler).

Her tıklama ve etkileşim, kullanıcıya "premium" bir deneyim sunacak şekilde, özel `transition` ve `@keyframes` animasyonları ile desteklenmiştir.

## 📄 Lisans & Gizlilik

Tüm veri kullanıcının kendi cihazında, çevrimdışı (offline) olarak saklanmaktadır. Dışa herhangi bir veri transferi yapılmaz. Gizlilik endişesi olmadan özel planlarınızı yapabilirsiniz.  
Bu uygulama **kişisel kullanım** amacıyla tasarlanmıştır. Yalnızca yerel cihazlarda çalıştırılmak üzere lisanslanmıştır.

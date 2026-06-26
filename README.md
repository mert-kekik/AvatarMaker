# Piksel Avatar Tasarımcısı 🎨

Bu proje, kullanıcıların tarayıcı üzerinden kendi piksel sanatı (pixel art) avatarlarını tasarlayabilecekleri ve cihazlarına indirebilecekleri basit, web tabanlı bir çizim uygulamasıdır. Hem masaüstü hem de mobil cihazlarda sorunsuz çalışacak şekilde tasarlanmıştır.

## 🌟 Özellikler

* **Izgara Tabanlı Çizim:** 320x320 piksel boyutlarında, 10x10'luk karelerden oluşan retro çizim tahtası.
* **Sınırsız Renk Seçeneği:** HTML5 renk paleti ile dilediğiniz rengi seçerek çizim yapabilme.
* **Mobil Uyumluluk:** `touch` (dokunmatik) ve `mouse` (fare) olaylarının entegrasyonu sayesinde telefon, tablet ve bilgisayarlarda kusursuz deneyim.
* **Hemen İndir:** Tasarlanan avatarı tek tıkla şeffaf arka planlı veya çizdiğiniz şekliyle `benim-avatarim.png` olarak cihaza kaydetme.

## 🚀 Nasıl Çalıştırılır?

Proje herhangi bir sunucu, kütüphane veya veritabanı kurulumu **gerektirmez**. 

1. Kodların bulunduğu dosyayı `index.html` adıyla bilgisayarınıza kaydedin.
2. Dosyaya çift tıklayarak modern bir web tarayıcısında (Chrome, Safari, Firefox, Edge vb.) açın.
3. Renk seçin, tuvale tıklayıp sürükleyerek çiziminizi yapın ve eseriniz bitince **Avatarı İndir** butonuna basın!

## 🛠️ Kullanılan Teknolojiler

* **HTML5:** Sayfa iskeleti ve `<canvas>` API'si için.
* **CSS3:** Arayüz şekillendirmesi, buton tasarımları ve mobil ekranlarda kaymayı engellemek (`touch-action: none`) için.
* **Vanilla JavaScript:** Çizim mantığı, ızgara (grid) sistemi hesaplamaları ve görseli `DataURL` formatına çevirip indirme işlemi için.

## 💡 Geliştirme Fikirleri (To-Do)

Eğer projeyi geliştirmek isterseniz aşağıdaki özellikleri ekleyebilirsiniz:
- [ ] Silgi aracı
- [ ] Çizim tahtasını (Canvas) tek tıkla temizleme butonu
- [ ] Farklı fırça/kare boyutları (5x5, 20x20 vb.)
- [ ] Arka plan rengini değiştirme seçeneği

## 📝 Lisans

Bu proje **[MIT](LICENSE)** lisansı altında lisanslanmıştır. Bu da demek oluyor ki kodu dilediğin gibi kopyalayabilir, değiştirebilir, ticari veya kişisel projelerinde tamamen ücretsiz ve özgürce kullanabilirsin. 

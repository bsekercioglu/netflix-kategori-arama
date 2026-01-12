# 🎥 Netflix Kategori Arama

Modern ve kullanıcı dostu bir Netflix kategori arama ve keşif aracı. Tüm Netflix kategorilerini kolayca arayın, filtreleyin ve doğrudan Netflix'te açın.

![Netflix Kategori Arama](https://img.shields.io/badge/Netflix-Category%20Search-E50914?style=for-the-badge&logo=netflix&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Özellikler

- 🔍 **Gelişmiş Arama**: Kategori adı veya kod numarası ile hızlı arama
- 🎯 **Akıllı Filtreleme**: Ana kategoriler, alt kategoriler, ülke bazlı ve daha fazlası
- 🎨 **Modern Tasarım**: Netflix benzeri koyu tema ve glassmorphism efektleri
- 📱 **Responsive**: Mobil, tablet ve masaüstü cihazlarda mükemmel görünüm
- 🚀 **Hızlı Erişim**: Tek tıkla Netflix'te kategoriyi açma
- 📋 **Kod Kopyalama**: Kategori kodlarını kolayca kopyalama
- 📊 **İstatistikler**: Toplam ve gösterilen kategori sayıları
- 🌐 **Türkçe Arayüz**: Tam Türkçe dil desteği

## 🎯 Kullanım

1. **Arama Yapın**: Arama kutusuna kategori adı veya kod numarası yazın
   - Örnek: "aksiyon", "1365", "komedi"

2. **Filtreleyin**: Filtre butonlarını kullanarak kategorileri daraltın
   - Tümü
   - Ana Kategoriler
   - Alt Kategoriler
   - Ülke Bazlı

3. **Kategorileri Keşfedin**: 
   - Kategori kartlarına tıklayarak alt kategorileri görüntüleyin
   - Ana kategori butonuna tıklayarak Netflix'te kategoriyi açın
   - Alt kategorilerdeki küçük butonlarla spesifik kategorileri açın

4. **Kodları Kopyalayın**: Alt kategorilerdeki 📄 butonuna tıklayarak kategori kodunu kopyalayın

## 🚀 Kurulum

### Yerel Kullanım

1. Projeyi klonlayın veya indirin:
```bash
git clone https://github.com/bsekercioglu/netflix-kategori-arama.git
cd netflix-kategori-arama
```

2. `index.html` dosyasını tarayıcıda açın:
   - Dosyaya çift tıklayarak açabilirsiniz
   - Veya bir web sunucusu kullanabilirsiniz

### Web Sunucusu ile (Önerilen)

```bash
# Python 3 ile
python -m http.server 8000

# Node.js ile (http-server)
npx http-server

# PHP ile
php -S localhost:8000
```

Ardından tarayıcınızda `http://localhost:8000` adresine gidin.

## 📁 Proje Yapısı

```
netflix-kategori-arama/
│
├── index.html          # Ana HTML dosyası (tüm kod tek dosyada)
├── data.json          # Netflix kategori verileri (JSON formatında)
└── README.md          # Bu dosya
```

## 🛠️ Teknolojiler

- **HTML5**: Yapısal markup
- **CSS3**: Modern styling, animations, glassmorphism
- **JavaScript (Vanilla)**: Tüm işlevsellik, arama ve filtreleme
- **Google Fonts**: Inter font ailesi
- **JSON**: Kategori verileri

## 📊 Kategori Kapsamı

Proje aşağıdaki Netflix kategorilerini içerir:

- 🎬 Aksiyon ve Macera
- 🚀 Bilim Kurgu ve Fantastik
- 😱 Korku ve Gerilim
- 😂 Komedi
- 🎭 Dram
- 🎨 Anime
- 👨‍👩‍👧‍👦 Çocuk ve Aile
- 📺 Belgeseller
- 📺 TV Dizileri
- 🌍 Dünya Sineması (Ülke Bazlı)
- 🎵 Müzik
- ⚽ Spor Filmleri
- ⭐ Özel İlgi Alanları
- 🎄 Mevsimsel ve Tatil

**Toplam**: 100+ ana kategori ve 200+ alt kategori

## 🎨 Özellikler Detayı

### Arama Özellikleri
- Gerçek zamanlı arama
- Kategori adı ve kod numarası ile arama
- Alt kategorilerde de arama
- Büyük/küçük harf duyarsız

### Tasarım Özellikleri
- Netflix benzeri koyu tema
- Glassmorphism efektleri
- Smooth animasyonlar
- Gradient arka planlar
- Hover efektleri
- Responsive grid layout

### Kullanıcı Deneyimi
- Hızlı yükleme (tüm veri client-side)
- Akıcı animasyonlar
- Görsel geri bildirimler
- Kolay navigasyon
- Mobil uyumlu dokunmatik kontroller

## 📱 Responsive Tasarım

Proje tüm cihazlarda mükemmel çalışır:
- 📱 Mobil (320px+)
- 📱 Tablet (768px+)
- 💻 Masaüstü (1024px+)
- 🖥️ Büyük Ekranlar (1440px+)

## 🔗 Netflix Entegrasyonu

Her kategori ve alt kategori için doğrudan Netflix bağlantıları:
- Format: `https://www.netflix.com/browse/genre/[KOD]`
- Yeni sekmede açılır
- Netflix hesabınızla otomatik giriş yapılır

## 📝 Notlar

- Bu proje Netflix'in resmi bir ürünü değildir
- Kategori kodları Netflix'in mevcut sistemine dayanmaktadır
- Bazı kategoriler bölgeye göre değişiklik gösterebilir
- Netflix hesabı gerektirir (kategorileri görüntülemek için)

## 🤝 Katkıda Bulunma

Katkılarınızı bekliyoruz! Lütfen:

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request açın

## 📄 Lisans

Bu proje açık kaynaklıdır ve MIT lisansı altında lisanslanmıştır.

## 👤 Yazar

**Burak Şekercioğlu**

- Website: [www.sekercioglu.eu/netflix](https://www.sekercioglu.eu/netflix)
- GitHub: [@bsekercioglu](https://github.com/bsekercioglu)

## 🙏 Teşekkürler

- Netflix için kategori sistemini sağladığı için
- Tüm açık kaynak topluluğuna
- Projeyi kullanan herkese

## ⭐ Yıldız Vermeyi Unutmayın!

Bu projeyi beğendiyseniz, yıldız vermeyi unutmayın! ⭐

---

**Not**: Bu proje eğitim ve kişisel kullanım amaçlıdır. Netflix'in ticari markaları ve telif hakları sahiplerine aittir.

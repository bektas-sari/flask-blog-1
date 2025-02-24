# Flask Blog Web Sitesi (Deneme Amaçlı Olarak Vo Ai Codere ile Oluşturulmuştur)

Bu proje, Flask framework'ü kullanılarak geliştirilen basit bir blog web sitesidir. Kullanıcıların blog yazılarını görüntülemesine, hakkımda bölümünü okumasına ve iletişim formu aracılığıyla mesaj göndermesine olanak tanır.

## Özellikler
- **Anasayfa**: Hoş geldiniz mesajı ile blog sitesine giriş.
- **Hakkımda**: Blog yazarının kendisini tanıttığı alan.
- **Blog Yazıları**: Farklı konularda blog yazılarının bulunduğu bölüm.
- **İletişim**: Kullanıcıların form doldurarak iletişim kurabileceği alan.
- **Responsive Tasarım**: Mobil uyumlu ve kullanıcı dostu arayüz.

## Kurulum

### Gereksinimler

Aşağıdaki yazılımların bilgisayarınızda kurulu olduğundan emin olun:

- Python (>= 3.8)
- Flask

### Adımlar

1. Projeyi klonlayın:
   ```bash
   git clone https://github.com/bektas-sari/flask-blog-1.git
   cd flask-blog
   ```

2. Sanal ortam oluşturun:
   ```bash
   python -m venv venv
   source venv/bin/activate  # macOS/Linux
   venv\Scripts\activate  # Windows
   ```

3. Bağımlılıkları yükleyin:
   ```bash
   pip install -r requirements.txt
   ```

4. Flask uygulamasını çalıştırın:
   ```bash
   export FLASK_APP=app.py  # macOS/Linux
   set FLASK_APP=app.py  # Windows
   flask run
   ```

5. Tarayıcınızda şu adrese gidin:
   ```
   http://127.0.0.1:5000
   ```

## Proje Yapısı

```
flask-blog/
│-- app.py             # Flask uygulama dosyası
│-- static/
│   └── css/
│       └── style.css  # Stil dosyası
│-- templates/
│   └── index.html     # Ana sayfa şablonu
│-- requirements.txt   # Gerekli bağımlılıklar
│-- README.md          # Proje hakkında bilgi
```

## Kullanılan Teknolojiler
- **Python (Flask Framework)** - Backend geliştirme için.
- **HTML, CSS, JavaScript** - Frontend geliştirme için.
- **AOS.js** - Sayfa kaydırma animasyonları için.

## Geliştirme
Projeye katkıda bulunmak için bir `feature` branch'i oluşturun ve değişikliklerinizi gönderin.

```bash
git checkout -b feature/yeniozellik
```

## Lisans
MIT lisansı.

## İletişim
**GitHub:** [bektas-sari](https://github.com/bektas-sari)
**Email:** [bektas.sari@gmail.com](mailto:bektas.sari@gmail.com)
**LinkedIn:** [bektas-sari](https://www.linkedin.com/in/bektas-sari)


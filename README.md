# Native-App Örnek Uygulama

Bu proje, Laravel NativePHP kullanılarak geliştirilecek bir örnek uygulamadır. Bu uygulama, basit bir not defteri uygulamasıdır ve kullanıcıların notlarını eklemelerine, düzenlemelerine ve silmelerine olanak sağlar.

## Gereksinimler

- PHP 7.4 veya daha üstü bir sürüm
- MySQL veya başka bir veritabanı
- Web sunucusu (Apache, Nginx vb.)
- Composer paket yöneticisi

## Kurulum

1. Projeyi klonlayın veya ZIP olarak indirin.
2. Terminalde projenin kök dizinine gidin ve aşağıdaki komutu çalıştırarak gerekli bağımlılıkları yükleyin:
   ```
   composer install
   ```
3. `.env.example` dosyasını `.env` olarak kopyalayın ve veritabanı bağlantı bilgilerini ayarlayın.
4. Veritabanını oluşturmak için aşağıdaki komutu çalıştırın:
   ```
   php artisan migrate
   ```
5. Uygulamayı başlatmak için aşağıdaki komutu çalıştırın:
   ```
   php artisan serve
   ```

## Kullanım

1. Tarayıcınızda uygulamaya erişmek için aşağıdaki URL'yi ziyaret edin:
   ```
   http://localhost:8000
   ```
2. Ana sayfada, "Not Ekle" butonuna tıklayarak yeni bir not oluşturun.
3. Not ekledikten sonra, "Notları Listele" sayfasına geri dönerek tüm notları görüntüleyin.
4. Notları liste üzerinden düzenleyebilir veya silebilirsiniz.

## Katkıda Bulunma

Eğer bu projeye katkıda bulunmak isterseniz, lütfen aşağıdaki adımları takip edin:

1. Bu depoyu çatallayın (fork) ve yerel bir kopya oluşturun.
2. Yeni özellikler veya düzeltmeler için bir dal (branch) oluşturun.
3. Değişikliklerinizi yapın ve uygun şekilde test edin.
4. Değişikliklerinizi ana depoya (upstream) göndermek için bir pull talebi (pull request) oluşturun.

Proje geliştirme sürecinde yardımcı olmanızı ve katkılarınızı bekliyoruz.

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Detaylı bilgi için `LICENSE` dosyasını inceleyin.

Aşağıda, verilen örneğe dayanarak `readme` dosyasının Türkçe ve İngilizce hallerini göstereceğim:

## Türkçe

# NativePHP İle Başlanmış Proje

Bu proje, NativePHP kullanılarak başlatılmış bir Laravel projesidir. Bu paket sayesinde mevcut bir Laravel uygulamasına kurulum yapabilir veya yeni bir Laravel projesi başlatabilirsiniz.

## Gereksinimler

- PHP 8.1
- Laravel 10 veya daha üstü
- NPM
- Linux/MacOS

## Kurulum

NativePHP paketini eklemek için aşağıdaki komutu çalıştırın:

```
composer require nativephp/electron
```

## Laravel Kurulumu

NativePHP, bir Laravel Paketidir. Mevcut bir Laravel uygulamasına yükleyebilir veya yeni bir proje başlatabilirsiniz.

## Kurulum Sihirbazını Çalıştırma

NativePHP kurulum sihirbazı, NativePHP servis sağlayıcısını yayınlama işlemini ve uygulamanızın bootstrapping işlemlerini yapar. Aynı zamanda NativePHP yapılandırma dosyasını da yayınlar.

```
php artisan native:install
```

## Geliştirme Sunucusunu Başlatma

```
php artisan native:serve
```

Ve bu kadar! Artık uygulamanızın yerel masaüstünde çalışan bir pencerede görüntülenmesini görebilirsiniz.

## English

# Project Started with NativePHP

This project is a Laravel project that has been initiated with NativePHP. With this package, you can install it on an existing Laravel application or start a new one.

## Requirements

- PHP 8.1
- Laravel 10 or higher
- NPM
- Linux/MacOS

## Installation

To add the NativePHP package, run the following command:

```
composer require nativephp/electron
```

## Install Laravel

NativePHP is a Laravel Package. You can install it on an existing Laravel application, or start a new one.

## Run the Installer

The NativePHP installer takes care of publishing the NativePHP service provider, which takes care of bootstrapping your native application. It also publishes the NativePHP configuration file.

```
php artisan native:install
```

## Start the Development Server

```
php artisan native:serve
```

And that's it! You should now see your application running in a native desktop window.

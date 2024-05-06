# Ninja Weather | FT
---
## Tanıtım

Bu uygulama, hava durumu bilgilerini görüntülemek için kullanıcı dostu bir arayüz sunar. AccuWeather API'sini kullanarak gerçek zamanlı hava durumu verilerini çeker ve kullanıcıya sunar.

![uygulama ornegi](/img/weatherFt.gif)

## Özellikler

- Kullanıcılar hava durumu bilgilerini herhangi bir şehir için sorgulayabilir.
- Anlık hava durumu bilgileri, şehir adı, hava durumu, sıcaklık gibi detayları içerir.
- Görsel olarak, mevcut hava durumuna uygun bir ikon ve günün saatine göre arkaplan görseli sağlanır.

## Kurulum

1. Projeyi klonlayın: `git clone https://github.com/furrkanntas/28_FT-Weather-Ninja.git`
2. Ana dizine gidin: `cd ninja-weather`
3. `index.html` dosyasını bir tarayıcıda açın veya bir sunucuda barındırın.

## Kullanım

1. Tarayıcınızda uygulamayı açın.
2. Arama kutusuna istediğiniz şehrin adını girin ve Enter tuşuna basın.
3. Hava durumu bilgileri ve görseller görüntülenecektir.

## Teknolojiler

- HTML
- CSS (Bootstrap)
- JavaScript

## API Kullanımı

Bu uygulama, AccuWeather API'sini kullanarak hava durumu verilerini alır. AccuWeather API anahtarınızı `forecast.js` dosyasında belirtmeniz gerekmektedir.

```javascript
const key = 'IOZY9eMgNcPgROS1wL1REeFb5nyYbwy1';

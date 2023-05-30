# Snap-Camera-Kit-WebSDK [EN](https://github.com/egemengulpinar/Snap-Camera-Kit-WebSDK/blob/main/README.md) | [ES](https://github.com/egemengulpinar/Snap-Camera-Kit-WebSDK/blob/main/docs/README_ES.md)
Temel Snap Camera-Kit Yayını & Entegrasyon rehberi. Daha fazla detay ve belgelendirme için lütfen Docs Snap CameraKit WebSDK kontrol edin.

Bu rehberde ayrıca bu projeyi vercel kullanarak NextJS ile yayınlıyoruz. Sonuçları görmek için aşağıdaki Demo uygulamasını kontrol edin.

## Demo
Lütfen önce kamera erişimine ve snap hukuki şartlarına izin verin.

 Güvenlik nedenleriyle, demo web uygulaması sonlandırıldı. Lütfen önce, repo üzerinde temsil ettiğim Sorunları çözmemize yardımcı olun.
~~[next-app-egemengulpinar.vercel.app](https://next-app-egemengulpinar.vercel.app/)~~

https://github.com/egemengulpinar/Snap-Camera-Kit-WebSDK/assets/71253469/413da48c-9adb-42ca-bb5f-8e640e0b3b55

## Bağımlılıkları Yükle (Yerel)
Snap Camera-Kit paketini yükleyin :

```
npm install @snap/camera-kit
```

```
npm install
```

## Token Ayarları
Öncelikle [camera-kit.snapchat.com](camera-kit.snapchat.com/) üzerinden alınan tokeninizi **.env** dosyasına ekleyin.

- **API TOKEN**
- **LENS ID** 
- **LENS GROUP ID** 

## Yapılandır ve Çalıştır (Yerel)
``` 
npm run build 

npm start 
 ```

##  Yapılandır & Yayınla (Vercel)
İlk önce bağımlılıkları yükleyin
```
npx create-next-app@latest
cd next-app
npm install @snap/camera-kit
npm install
sudo npm i -g vercel
```

Yerel olarak kontrol etmek için çalıştırın
```
npm run dev
```

Vercel'de yayınlamak için
```
vercel
```
## Katkıda Bulunma
Sayfanın denetlendiğinde tokenin görünür olmasıyla ilgili bir güvenlik sorunu olduğunu biliyorum. Bu durumu gidermek için sunucu-istemci iletişimi oluşturabiliriz.

Bu konuda katkıda bulunup bu sorunu çözebilirseniz, pull request yapmaktan çekinmeyin.

## Destek

Aşağıdaki bilgilerden bana ulaşabilirsin! (Discord ve e-mail)
- egemengulpinar@gmail.com
- egemengulpinar#3536
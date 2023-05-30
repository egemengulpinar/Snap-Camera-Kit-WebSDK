# Snap-Camera-Kit-WebSDK [EN](https://github.com/egemengulpinar/Snap-Camera-Kit-WebSDK/blob/main/README.md) | [TR](https://github.com/egemengulpinar/Snap-Camera-Kit-WebSDK/blob/main/docs/README_TR.md)
Guía básica de despliegue e integración de Snap Camera-Kit. Para más detalles y documentación, por favor consulte [Documentos de Snap CameraKit WebSDK](https://docs.snap.com/camera-kit/quick-start/integrate-sdk/integrate-sdk-web/web-configuration)

En esta guía, también desplegamos este proyecto a través de vercel usando NextJS. Para ver los resultados, por favor consulte la aplicación de demostración a continuación.

## Demo
Por favor, primero permita el acceso a la cámara y acepte los términos legales de Snap.

 Por razones de seguridad, la aplicación web de demostración fue terminada. Por favor, primero, ayude a corregir los problemas que he representado en el repositorio.
~~[next-app-egemengulpinar.vercel.app](https://next-app-egemengulpinar.vercel.app/)~~

https://github.com/egemengulpinar/Snap-Camera-Kit-WebSDK/assets/71253469/413da48c-9adb-42ca-bb5f-8e640e0b3b55

## Instalación de Dependencias (Local)
Instale el paquete Snap Camera-Kit :

```
npm install @snap/camera-kit 
``` 

``` 
npm install 
```


## Configuración del Token
Primero inserte su token en el archivo .env que se obtiene de [camera-kit.snapchat.com](camera-kit.snapchat.com/)

- **API TOKEN**
- **LENS ID** 
- **LENS GROUP ID** 
## Compilación y Ejecución (Local)

``` 
npm run build 

npm start 
 ```

## Compilación y Despliegue (Vercel)
Primero instale las dependencias

```
npx create-next-app@latest
cd next-app
npm install @snap/camera-kit
npm install
sudo npm i -g vercel
```
Para ejecutar localmente y comprobar

```
npm run dev
```
## Publicar en Vercel

```
vercel
```

## Contribuir
Sé que hay un problema de seguridad con el token que es visible cuando se inspecciona la página. Podría haber una comunicación servidor-cliente para ocultar la información del token.

Si contribuyes y solucionas este problema, siéntete libre de hacer solicitudes de extracción.

## Soporte
Puedes contactarme a través de correo electrónico y discord

- egemengulpinar@gmail.com
- egemengulpinar#3536
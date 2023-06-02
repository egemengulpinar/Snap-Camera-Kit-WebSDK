# Snap-Camera-Kit-WebSDK [TR](https://github.com/egemengulpinar/Snap-Camera-Kit-WebSDK/blob/main/docs/README_TR.md) | [ES](https://github.com/egemengulpinar/Snap-Camera-Kit-WebSDK/blob/main/docs/README_ES.md)

Basic Snap Camera-Kit Deployment & Integration guide. For more details and documentation please check [Docs Snap CameraKit WebSDK ](https://docs.snap.com/camera-kit/quick-start/integrate-sdk/integrate-sdk-web/web-configuration)

In this guide, we also deploy this project via **vercel** using with **NextJS**. For see results, please check Demo app below.

## Demo
 *Please first allow camera access and snap legal terms.*


[next-app-egemengulpinar.vercel.app](https://next-app-egemengulpinar.vercel.app/)



https://github.com/egemengulpinar/Snap-Camera-Kit-WebSDK/assets/71253469/413da48c-9adb-42ca-bb5f-8e640e0b3b55




## Install Dependencies(Local)
Install Snap Camera-Kit package :

```  npm install @snap/camera-kit ``` 

``` npm install ```

## Token Settings
First insert your token into **.env** file that are taken by [camera-kit.snapchat.com](camera-kit.snapchat.com/)
- **API TOKEN**
- **LENS ID** 
- **LENS GROUP ID** 




## Build and Run(Local)

``` 
npm run build 

npm start 
 ```

## Build & Deploy(Vercel)
first install dependencies 
```
npx create-next-app@latest
cd next-app
npm install @snap/camera-kit
npm install
sudo npm i -g vercel
```

for run locally to check
```
npm run dev
```

deploy to vercel
```
vercel
```

## Contributing
I know there's a security issue with the token being visible when you're inspect the page.There might be create server-client communication to hide token info.

If you contribute and fix this issue feel free to pull requests. 

## Support

You can contact with me via e-mail & discord
- egemengulpinar@gmail.com  
- egemengulpinar#3536

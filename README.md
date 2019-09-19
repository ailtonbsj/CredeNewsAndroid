# CREDE News App for Android

> Aplicativo Android usando Cordova do CREDE News.

O aplicativo CredeNews ajuda os professores desempregados do Ceará a ficarem de olho nas notícias e editais temporários das coordenadorias de educação.

## Características

- Listagem de notícias das 20 CREDEs do Ceará
- Notícias atualizadas de 2 em 2 horas
- Notícias do dia destacada de verde claro
- Opção de filtro persistivo por CREDE

## How to build

```
npm install
cordova platform add android
cordova requirements
cordova build --prod --release
```

## Criando uma aplicação Cordova

```
cordova create CredeNewsApp br.com.ailtonbsj.credenews CredeNews
cordova platform add android
cordova requirements
cordova build
cordova emulate android
cordova run android
```

## Assinando o aplicativo

```
keytool -genkey -v -keystore name.keystore -alias alias -keyalg RSA -keysize 2048 -validity 10000
cordova build --prod --release
``` 

## Require

- NPM
- Android Studio
- Cordova
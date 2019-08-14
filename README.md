# pixiv-login

![npm version](https://img.shields.io/badge/npm-1.0.0-brightgreen)

爬虫模拟Pixiv登陆，获取cookie

## install

```
npm install --save cocoguo-test
```

## Useage
```
const pixivLogin = require('cocoguo-test');

pixivLogin({
  username: 'your username',
  password: 'your password'
}).then((cookie) => {
  console.log('cookie');
}).catch((error) => {
  console.error(error);
})

```
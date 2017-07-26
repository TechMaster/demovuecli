# Demo Vue.js

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

## Một số chú ý
1. Sử dụng Component
2. Cách dùng Axios
3. Sử dụng Element.io

## Sử dụng Docker để map volume dist trên host vào docker container nginx

```
docker run --name web -p 80:80 -d nginx:alpine

docker run --name web -it nginx:alpine /bin/ash

docker run --name web -p 80:80 -d -v /Users/techmaster/Documents/VUE/demoVueCli/dist:/usr/share/nginx/html nginx:alpine
```

-v để ánh xạ volume từ host vào container

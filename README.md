
# 用 Docker 容器化部署 Angular6

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## 生成 Docker 镜像

```
$ docker build -t myapp . 
```

## 运行 Docker 容器

```
$ docker run -d -p 8080:80 myapp
```

The app will be available at http://localhost:8080

You can easily tweak the nginx config in ```nginx/default.conf```

浏览器打开后截图：

![](./1.png)

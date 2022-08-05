# UNPKG &middot; [![Travis][build-badge]][build]

[build-badge]: https://img.shields.io/travis/mjackson/unpkg/master.svg?style=flat-square
[build]: https://travis-ci.org/mjackson/unpkg

[UNPKG](https://unpkg.com) is a fast, global [content delivery network](https://en.wikipedia.org/wiki/Content_delivery_network) for everything on [npm](https://www.npmjs.com/).

### Documentation

Please visit [the UNPKG website](https://unpkg.com) to learn more about how to use it.

### Sponsors

Our sponsors and backers are listed [in SPONSORS.md](SPONSORS.md).

### 本地启动脚本：
node server.js
#### 遇到的问题：
Error: Missing the $CLOUDFLARE_EMAIL environment variable
#### 解决：
需要set NODE_ENV=production来绕开对$CLOUDFLARE_EMAIL的检验， 
在windows环境下，set NODE_ENV=production&&node server.js，Mac下是NODE_ENV=production node server.js，可以使用cross-env跨平台的设置

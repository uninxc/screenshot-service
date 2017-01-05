screenshot-service
==================
基于 phantomJs 的截屏服务

使用方法
--------------

- 安装 [phantomJs](https://github.com/ariya/phantomjs) 

```sh
git clone https://github.com/uninxc/screenshot-service.git
cd screenshot-service
phantomjs server.js "端口号"
```
- 通过对 YOUR_IP:PORT 请求，服务将会返回处理完成的图片
    * *url* = "some_url" This parameter is required
    * *timeout* = "timeout in milliseconds to allow the page to load" defaults to 1000ms
    * *width* = "width of browser window" defaults to 1366px
    * *height* = "height of browser window" defaults to 768px


License
-

MIT

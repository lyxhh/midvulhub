## PUT任意文件写入

IIS Server 在 Web 服务扩展中开启了 WebDAV之后，支持多种请求，配合写入权限，可造成任意文件写入。
![iisput01](./pic/iisput01.png)

![iisput02](./pic/iisput02.png)

### 修复建议

关闭WebDAV 和 写权限
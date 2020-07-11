## Weblogic 弱口令 && 后台getshell

弱口令参考：https://cirt.net/passwords?criteria=WebLogic

访问`http://127.0.0.1:7001/console` 
自动重定向到`http://127.0.0.1:7001/console/login/LoginForm.jsp`，使用弱口令登陆后台。

点击部署，进一步点击右边的安装。
![weblogic04](./pic/weblogic04.png)

点击上载文件，
![weblogic05](./pic/weblogic05.png)

选择war包，点击下一步
![weblogic06](./pic/weblogic06.png)

上传完成以后选中你上传的文件,点击下一步
![weblogic07](./pic/weblogic07.png)

选中作为应用程序安装，点击下一步
![weblogic08](./pic/weblogic08.png)

然后直接点击完成即可
![weblogic09](./pic/weblogic09.png)

选用我们安装的应用，点击启动即可。
![weblogic10](./pic/weblogic10.png)

访问：`http://ip:port/[war包名]/[包名内文件名]`
![weblogic11](./pic/weblogic11.png)

### 修复建议
避免后台弱口令。
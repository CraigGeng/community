## CraigGeng's Code Community


## 资料地址
SpringBoot文档：https://spring.io/guides

第一次创建SpringBoot项目：https://spring.io/guides/gs/serving-web-content/

GitHub仓库地址：https://github.com/CraigGeng/community

模板社区：https://elasticsearch.cn/

创建GitHub登录文档：https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/

Maven仓库（寻找maven项目中需要的jar包）：https://mvnrepository.com/

OKHTTP（轻量级网络框架）:https://square.github.io/okhttp/

## 学习心得

application properties用于设置项目中固定不变的量，定义名称 = 值；应用时使用@Value("${定义名称}")在前作为注释，后面定义相应的private变量。

Failed to start component [Connector[HTTP/1.1-8887]]这是端口已经被占用的错误。解决方法：cmd中键入netstat -ano | findstr 端口号      查看端口被ID为那个的进程占用，再键入taskkill （/f） /pid  ID号进行任务杀死即可
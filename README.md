# gulp_config_basic
This is a demo about gulp_config！
gulp 配置+sass+http-server自动刷新+添加版本号


LiveReload配置
1、安装Chrome LiveReload
2、通过npm安装http-server，快速建立http服务

npm install http-server -g
3、通过cd找到发布环境目录dist
4、运行http-server，默认端口是8080
5、访问路径localhost:8080
6、再打开一个cmd，通过cd找到项目路径执行gulp，清空发布环境并初始化
7、执行监控 gulp
8、点击chrome上的LiveReload插件，空心变成实心即关联上，你可以修改css、js、html即时会显示到页面中。


配置用sass去编译CSS

# Dashboard

Dashboard是一个针对perf4j进行性能数据渲染的项目，可以通过图表的方式展现数据。

### 启动Dashboard

#### 直接通过mvn jetty启动

在perf4j-dashboard目录下直接执行：mvn jetty:run
#### 选用Tocmat

你也可以打包扔在tomcat下运行...

### 配置数据来源api

启动成功后，可以直接点击添加机器按钮，添加获取数据的api，该api地址是你在项目中配置的地址
cluster用来对机器进行分组，node表示分组中的一台服务器，
url填写规则如下：若被监测服务器运行地址为localhost:8888
则此处应该配置为localhost:8888/perf4j


![Alt text](./perf4j_home.jpg)










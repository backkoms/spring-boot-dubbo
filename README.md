Spring boot 结合 Dubbo开发前、后端服务分离的案例

1、下载zookeeper后，复制zoo_sample.cfg后，修改名称为zoo.cfg。
2、进入zookeeper的bin目录，直接启动即可。
3、git项目最新的源码包，然后mvn package
4、启动accountServ、bizService的主类作为服务的提供者，在zookerper控制台可以看到服务注册成功
5、启动portal的主类，作为服务消费者。


### 制作jar包
```
去掉jar包后缀*.bak

阿里支付sdk-jar制作：
   mvn install:install-file -DgroupId=com.alipay -DartifactId=alipay-sdk-java -Dversion=3.3.0 -Dpackaging=jar -Dfile=alipay-sdk-java-3.3.0.jar
   mvn install:install-file -DgroupId=com.alipay -DartifactId=alipay-trade-sdk -Dversion=20161215 -Dpackaging=jar -Dfile=alipay-trade-sdk-20161215.jar
   
定时任务jar制作：
   mvn install:install-file -DgroupId=com.liuzm.paascloud -DartifactId=elastic-job-lite-starter -Dversion=1.0 -Dpackaging=jar -Dfile=elastic-job-lite-starter-1.0.jar
```
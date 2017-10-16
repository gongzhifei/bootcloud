# redcloud
Red Spring Cloud <br>
### 启动所有模块
$ ./gradlew bootRun
### 启动某个模块
$ ./gradlew :redcloud-eureka:bootRun

### Install Gradle
$ mkdir /opt/gradle <br>
$ unzip -d /opt/gradle gradle-4.1-bin.zip <br>
$ ls /opt/gradle/gradle-4.1 <br>
LICENSE  NOTICE  bin  getting-started.html  init.d  lib  media <br>
$ export PATH=$PATH:/opt/gradle/gradle-4.1/bin <br>
$ gradle -v

### Upgrade with the Gradle Wrapper
$ ./gradlew wrapper --gradle-version=4.1 --distribution-type=bin

### Building Java Applications
$ mkdir java-demo <br>
$ cd java-demo <br>
$ gradle init --type java-application <br>
$ ./gradlew build -x test <br>
$ ./gradlew run <br>
$ ./gradlew tasks

### Maven转Gradle
$ gradle init wrapper

### One more thing
www.toutiao.im

1. 下载安装包
```
wget http://apache.01link.hk/maven/maven-3/3.5.4/binaries/apache-maven-3.5.4-bin.tar.gz

```
2. 解压
```
tar -zxvf apache-maven-3.5.4-bin.tar.gz

```
3. 配置环境变量
```
vim /etc/profile

在尾部追加行：
export MAVEN_HOME={path}/apache-maven-3.5.4
export PATH=${MAVEN_HOME}/bin:${PATH}

使环境变量生效
soucre /etc/profile
```


# spd项目密码
---
## 项目部署包下载

* 网页地址：http://120.77.2.93/distribute/nzyy/
* 账号：distributor
* 密码：aoka1234

## SSH连接云主机

### IP地址：120.77.2.93

* 用户名：root
* 密码：0p;(OL8ik

### IP地址：

* 局域网IP：192.168.3.102
* 公网IP：14.23.113.5
* 账号：root
* 密码：aoka20!*

## jenkins登录账号

* 账号：zhouhc
* 密码：ak123456

## 腾讯企业邮箱
* 登录地址：https://exmail.qq.com/login

### 公司企业邮箱
* 账号：zhouhuancan
* 密码：Zhc2016

### 个人企业邮箱
* 账号：zhouhc@1ycloud.net
* 密码：Zhou@1029

### Google账号

账号：zhouhclwt@gmail.com

密码：zhou@1029

## CSDN账号：

* 登录地址：https://my.csdn.net/my/account/secureqa
* 账号：zhc1029
* 密码：zhou@921029

## RabbitMQ

* rabbitMQ: http://120.77.2.93:15672/
* 账号：rabbitmq_admin
* 密码：aoKA20!^


### 南州
* 密码:ak_nz_2016


## VPN翻墙

* 用户名：amonster2011
* 密码：aoka2017


## oracle
* UR地址：https://login.oracle.com/mysso/signon.jsp
* 账号：1024648143@qq.com
* 密码：Zhou@1029

## 禅道
* 地址：http://120.77.2.93/zentao/qa/
* 账号：admin
* 密码：aoka2016
* 个人账号：zhouhc
* 个人密码：ak1234


## 中二HIS系统视图数据库

* 链接地址：14.23.113.2
* 端口：1521
* SID：orcl
* 用户名：spd_z2
* 密码：spd_z2
* 服务器密码：ak1234!

## 测试用例数据库

* 链接地址：120.77.2.93
* 端口：1521
* SID:orcl11g
* 用户名：test_data_manager
* 密码：ak123456

## TeamViewer

| 链接地址     | ID          | 密码      | 系统登录密码  | 说明   |
| -------- | ----------- | ------- | ------- | ---- |
| 公司中六test | 896 018 625 | 7770808 |         |      |
| 南州社区医院   | 1106578669  | 7770808 | abc&123 |      |
| 中二医院跳板机  | 298586870   | 7770808 |         |      |

SELECT 'DELETE FROM '|| table_name || ';' FROM USER_TABLES ORDER BY TABLE_NAME;

## 常用命令

### yard_service cmd  mvn打包

* mvn clean package -Dmaven.test.skip=true



## 中二服务器

### 登录

密码：34071102

南院西药库：34071221

- ip地址：192.168.7.114


- 账号：root
- 密码：aoka20!*

###  rabbitMQ

- 地址：192.168.7.114:15672
- 账号：rabbitmq_admin
- 密码：aoka20!*

###  pm2-webshell

* 地址 ：https://10.1.1.131:8080
* 用户：aoka
* 密码：aoka2018

### HIS数据库(SQL)

#### 中间库

* IP地址：192.168.8.8
* 数据库名：wis20
* 用户名：pis_user
* 密码：pis_user
* URL:192.168.8.8:1433:database=wis20


正式库

* ip地址：192.168.7.102

#### 海思林科SPD访问地址

*  192.168.7.102:8081/SPD/tologin




### ORQCLE

* 用户名：z2_spd
* 密码：aokA2018
* ip:192.168.7.114
* 端口：1521
* SID：orcl11g




### 公司SQL

oracle 
实例名:orcl
密码:ak123456

账号：SYS 
密码：ak123456

账号：SYSTEM

密码：ak123456


teamviewer

ID：896 018 625
密码：7770808

系统登录密码

SQL密码
ak1234！



### FTP

#### SPD团队ftp地址：

* 内网：ftp://192.168.3.102
* 外网：ftp://14.23.113.5
* 账号：spd
* 密码：aoka2018





###  10.1.1.45

* 用户：root
* 密码：aoka20!*
* 用户：oracle
* 密码：aoka20!*



### 远程服务器

* 登录云服务器120.77.2.93

* 远程连接

  ~~~shell
  ssh -p 19991 root@localhost --珠海金湾医院
  ssh -p 19999 root@localhost --广州中二医院
  ~~~

  ​

* sqlplus导入数据

  ~~~sql
  sqlplus loginID/passwd@serverIP/servcie_name @path/file.name
  ~~~

* ​


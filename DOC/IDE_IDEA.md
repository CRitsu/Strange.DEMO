# IntelliJ IDEA 配置
*2017年8月15日00:02:27*  
*IntelliJ IDEA 2017.2.1*

git 配置十分简单，登录GitHub即可。

## Tomcat 配置

Tomcat配置，需要把root文件夹deploy才能使用服务器的管理页面。  

``
Run/Debug Configurations > [Tomcat Server] > Deployment > + [Plus button] > External Source > [Select Tomcat's ROOT folder]
``  

热部署Tomcat需要勾中``Deploy applications configured as Tomcat instance``。``On 'Update' action`` 和 ``On frame deactivation`` 需要选择 ``Update classes and resources``。

## Java Compiler 设置

将java compiler设置成eclipse。tomcat选择 build，on errors check。  
* [Why you should use the Eclipse compiler in Intellij IDEA](http://blog.dripstat.com/why-you-should-use-the-eclipse-compiler-in/)

## 遇到问题。

* 缺失.iml / 重新生成.iml 文件

将当前module重新import，就会自动生成。  

``
Project Structure > Modules > + [Plus button] > Import Module  
``
## 备忘

需要准备一下idea常用热键中英对照方便查阅。自带的find action功能需要英文的action名字。

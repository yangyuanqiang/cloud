# cloud

1、	变量名：CLASSPATH
	值：.;%JAVA_HOME%\lib\dt.jar
2、	变量名：JAVA_HOME
	值：D:\Develop\Java\jdk1.7.0_55
3、	名：Path
	值:;%JAVA_HOME%\bin

Linux下： /etc/.profile这是所有用户的全局的文件
主目录下的vi .bash_profile这是当前的用户的配置文件

JAVA_HOME=/opt/jdk1.6.0_03      指向java的安装目录
PATH=$JAVA_HOME/bin:$PATH       指向安装目录下的bin子目录
CLASSPATH=.:$JAVA_HOME/lib      类路径
export JAVA_HOME PATH CLASSPATH

保存退出。运行 #source /etc/profile

oracle客户端：
NLS_LANG： SIMPLIFIED CHINESE_CHINA.ZHS16GBK
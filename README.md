#hibernate3-maven-plugin插件入门
#必须配置好hibernate.properties和reveng.xml


#在Goals框中输入：hibernate3:hbm2java 生成Dao文件
#执行maven命令：mvn hibernate3:hbm2java 生成Dao文件
#---ejb3---如果设置为true则生成的Dao文件带JPA注解

#在Goals框中输入：hibernate3:hbm2hbmxml 生成hbml.xml文件
#执行maven命令：mvn hibernate3:hbm2hbmxml 生成hbml.xml文件

#执行maven命令：mvn hibernate3:hbm2cfgxml 生成cfg.xml文件

#执行maven命令：mvn hibernate3:hbm2doc 生成数据库对应的接口文档

#执行maven命令：mvn hibernate3:hbm2ddl 根据配置文件生成数据库表
#根据hibernate.cfg.xml映射的mapping resource，即hbm.xml文件来生成数据库表
#必须配置hibernate.dialect


#查看日志的简单工具

建议在每个虚拟机上都安装一份,非部署人员可以不登录到系统就可查看特定目录下的日志。


####配置
修改 config/log_dir.yml 添加允许查看的日志目录.

####日志查询
查询可用正则表达式,默认忽略大小写


#####支持文件
+ plain
+ *. bz2
+ *.gz
+ *.tar.gz

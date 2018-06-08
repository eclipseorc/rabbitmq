# rabbitmq
install require

1、erlang可在官网直接下载，安装时使用yum解决依赖问题，rpm -ivh可直接安装
2、rabbitmq在官网下载对应erlang的rpm包，安装时用yum解决socat依赖，然后使用rpm -ivh安装时会提示找不到erlang，此时加入选项--nodeps即可安装成功
3、使用rabbitmqctl命令行来管理插件和用户

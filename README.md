shop72hour
==========

使用Medoo-MVC开发的PHP开源微型导购系统，简单的瀑布流方式展示商品，每件商品展示时间为72小时。

## 安装说明

1.下载源码解压后，先创建数据库并导入'/data/shop72hour.sql',
并在shop_user表中添加一个用户作为后台登陆用户，password需要MD5加密后的值。

2.修改'/config/db.config.php'中的配置信息，建议使用mysql数据库，
这样的话需要修改的信息为"username"，"password"，"dbname"。

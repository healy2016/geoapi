###首页面中分享的应用开发
![](/assets/QQ图片20171207155657.png)

###控制台接口开发文档--用户信息
####1.账号信息

>* 位置：routes/users.js
>* table：用户表gty_user  用户购买记录：gty_user_buy

####2.套餐使用情况

>* 位置：routes/users.js
>* table：
    数据字段名称表：gty_data_columnvalue 
    用户购买记录： gty_data_column
    用户地图数据表：gty_user_data
>* seafile：common.getLibInfo 获取文件的详细信息

####3.退出账号
>* 位置：routes/users.js
>* 操作：清空cookie即可


###控制台接口开发文档--我的数据

####1.我的数据
>* 位置：routes/mydata.js
>* table：
    数据字段名称表：gty_data_columnvalue 
    用户购买记录： gty_data_column
    用户地图数据表：gty_user_data
>* 操作：数据的删除和查询,
        数据上传（技术核心）和 数据预览








































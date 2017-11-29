###1.前端Vue脚手架开发注意事项

 > * 1.运算符前后都必须使用字空格
 > * 2.if 等语句开启后前面必须有空格
 > * 3.每行代码结束不需要写分号；
 > * 4.不能随便定义一个空行  br
 > * 5.不支持双引号“”，都必须写成单引号‘’
 > * 6.包含的代码开始必须只有两个空格
 > * 7.定义一个变量，但是必须使用或者赋值
 > * 8.每个js的文件，结尾要多出一个空行
 
 ###2.后端+数据库的架构
 
 >* express：中间件
 >* morgan：日志记录
 >* cookie-parser：cookie管理
 >* sequelize:数据库的ORM映射管理
 >* postgres:后台数据库支持gis函数

###3.接口规范管理

####返回一个json数据，里面自带三个参数如下：
>* flag: 返回Boolean类型，true or false;
>* obj: 返回一个对象，可以包含数组等。
>* message: 返回一个对应的消息，字符型。

####示例：
```json
{
    "flag": true,
    "obj": {
        "user_id": "DEpikfExyWNj6wHsBWX42npbNYA8JzWZ",
        "user_name": "000",
        "user_pwd": "1111",
        "user_phone": "18311338843",
        "user_token": "2222",
        "user_createtime": "2017-11-23",
        "user_role": "1"
    },
    "message": success
}
```




 


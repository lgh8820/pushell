#PUSHELL 
前段时间公司做三级等保的时候，穷渣渣公司没买堡垒机，就让自己想办法解决！ 网上找到了jumpserver(感谢原作者)。于是改了下代码，就有了pushell.运行环境 python2.7.x,mysql<br>
####添加功能如下：
 1.角色: 管理员，审计管理员，监控管理员,配置管理员，普通用户 <br>
 2.二次验证:增加了token进行验证，令牌生成密码<br>
 3.增加了URL监控，主机监控 <br>
 4.集成saltstack <br>

###使用
pushell启动 <br>
>![pushelld.py --help](https://github.com/ymc023/pushell/blob/master/screenshot/start_help.jpg)
>![pushell启动](https://github.com/ymc023/PUSHELL/blob/master/screenshot/start_examples.jpg)
<br>
pushell token安装<br>
>![](https://github.com/ymc023/pushell/blob/master/screenshot/pushell_token_apk.jpg)
<br>
pusehll web登录<br>
>![](https://github.com/ymc023/pushell/blob/master/screenshot/pushell_web.jpg)
>![](https://github.com/ymc023/pushell/blob/master/screenshot/pushell_admin_privileges.jpg)
###安装
1.git 代码 <br>
>![git clone](https://github.com/ymc023/pushell/blob/master/screenshot/11.jpg) 
2.cd install/python install.py<br>
>![cd instll &&python install.py](https://github.com/ymc023/pushell/blob/master/screenshot/2.jpg)
>![](https://github.com/ymc023/pushell/blob/master/screenshot/3.jpg)
>![](https://github.com/ymc023/pushell/blob/master/screenshot/4.jpg)
>![](https://github.com/ymc023/pushell/blob/master/screenshot/5.jpg)
<br>


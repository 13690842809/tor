# tor
安装及使用


## 1.vpn的购买及搭建   
#### 1.1推荐的vpn有：   
>aws   
gigitalocean (https://www.digitalocean.com/) 支付方式比较麻烦，需要绑定信用卡   
host1plus (https://www.host1plus.com) 本人在用，效果凑合，没对比过  
>##### 网速较慢耐心等待............
  
#### 1.2host1plus的购买  
>教程：http://www.14vps.com/52.html
-------------------------------------------------
## 2.ss搭建及shadowsocks使用
>教程: https://www.textarea.com/ExpectoPatronum/shiyong-shadowsocks-kexue-shangwang-265/  
>window-shadowsocks: 链接：https://pan.baidu.com/s/1jJogrWi 密码：zs23   
>ubuntu-shadowsocks: 教程：http://blog.csdn.net/bingyu9875/article/details/54600691
-------------------------------------------------
## 3.tor的使用
在启动了vpn的前提下
#### 3.1下载tor
>tor文件链接：https://pan.baidu.com/s/1efPw7c 密码：q75z   
>tor浏览器链接：https://pan.baidu.com/s/1pMrZSqJ 密码：dbb8
#### 3.2下载vidalia
>链接：https://pan.baidu.com/s/1mjPVVwW 密码：1hau
#### 3.3网桥的申请--只要ip和端口（最好是新鲜的）
##### 可以用gmail发正文为getbridges的邮件到bridges@torproject.org索取 
>34.196.229.131:8443 C591748159A19B2761968B76AF0285A6958CB328  
>173.198.254.252:992 A4169A200691EA67F799442D7F6D1C508FC09C10  
>78.46.187.5:9001 F1A800765664CA7D983897D133C825945C288745
##### bridgeDB申请
>https://bridges.torproject.org/bridges?transport=obfs4
#### 3.4假如vidalia连接成功
>测试tor成功后获得的Ip:https://check.torproject.org/
----------------------------------------------------
## 4.问题
#### 由于被墙，一直连接不是tor网络   
>1.单独使用网桥？（本地开着vpn）
>2.单独使用代理？
>3.网桥和代理一起使用？
----------------------------------------------------
## 5.结论
本地使用了shadowsocks翻墙，直接用tor浏览器，设置代理即可：  
tor浏览器里配置代理sock5 127.0.0.1 1080  
切换ip:打开洋葱头 然后 点击change an new identity  
经过实验，tor browser成功打开不代表终端可以tor，但是vidalia连接成功就终端可行
## 6.一些好文章
http://www.yuuzle.com/use-tor-specified-exporting-countries-ip.html  
https://zhuanlan.zhihu.com/p/24261906

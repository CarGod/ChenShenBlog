# ChenShenBlog

> 声明
>
> 本项目线上地址：http://www.cheshen.wiki
>
> 大家可以随意使用，修改。
>
> 如果可以，大家可以增加友情链接，车神在这里谢过了~



## 使用说明

项目需要安装node.js，git，hexo。

参考地址：

https://nodejs.org/en/

https://hexo.io/

安装完成以后，把这个项目所有文件覆盖到hexo的安装目录下。

自己写的md格式的博客文件，放置在`source\_posts`目录下。

然后输入：

hexo clean // 清空静态文件

hexo g // 生成静态文件

hexo s // 运行本地测试服务器

当看到：

INFO Start processing

INFO Hexo is running at http://localhost:4000/, Press Ctrl + C to stop.

说明运行成功，访问地址就可以了。



如果需要部署上线，只需要把项目根目录下的public文件夹的内容，上传到本人Github的以本人昵称命名的项目中即可。



如：我的用户名是zeusw，新建项目zeusw.github.io，这是固定写法，一定要叫这个名字，每个账号只能建一个这种项目。



然后项目就会被github的静态页面托管，通过http://zeusw.github.io即可访问。

如果需要使用自己的域名，可以自己注册，然后修改zeusw.github.io项目下的CNAME文件，并且域名解析采用CNAME方式，具体请百度，注意，CNAME域名下面一定要加一个回车，不然无法解析。



注：这个地址可能需要翻墙。

附带教程一发：https://wsgzao.github.io/post/hexo-guide/
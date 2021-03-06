# RewrZ Project

这是个人利用业余时间，尽力抽空捣鼓出来的项目，基于 Python + Django 开发的，开源个人博客网站系统。

DEMO: <https://rewrz.com/>

- RewrZ ，名字灵感是来自《 Rewrite 》（改写）及其 OP 「 Philosophyz 」(最终的哲学)。

- RewrZ ，即最终的改写（ Rewritez ），最后重写的意思， Python 本身也是一种哲学语言。（虽然如今都被炒得烂大街了，一点都不 Pythonic 。）

- RewrZ ，除去这些字面的意思，同时也用以告诫自己：人的精力总是有限的，特别是只有一个人的时候。

- RewrZ Project ，可能是我这个曾经的 IT 爱好者、中二的二次元迷、最后的一个开源项目。

偶然有点什么新想法，我就忍不住新建项目。游戏、网站、小说等等，皆是如此，最终都在萌芽或者发展之中就宣告放弃，导致一个完整的都没能做出来。

所以我要告诉我自己，这是我最后的个人网站项目，已经没有能力再挖坑去做什么 WordPress 主题，去折腾 Flask 等等只是纯粹浪费时间精力的事情，以后只维护这个项目就算了。

# RewrZ 项目背景

我很感谢这些年 WordPress 和 Blogger 的陪伴，曾经连续写了好几年的博客，用的就是这两个博客系统。当然，也用过 Tumblr 作为微博替代品。

如今互联网上的网站系统多如牛毛，成熟且有名气的数不胜数，特别是有 WordPress 这样的已经发展多年的超级成熟的博客程序，是否就没有必要再去挖坑自己去做一个呢？

我觉得不是的。

在我使用中，我遇到很多不满意的地方，不断地去寻找改善的方式。
- 一些我想要的功能没有，需要自己自定义加上去或者装插件，有时候装插件又可能会带来新的问题。
- 有些我不想要的功能又要想办法去关闭，甚至有时候根本关闭不了。
- 太多的插件以及网友的提供的推荐设置，也是容易让人产生困难选择症。
- 频繁对大多数用户而言无感知的无用升级，调用函数的改动等等，一些长时间不更新的主题和插件可能就无法使用了。
- 功能的强大带来的臃肿、性能的瓶颈，以及搭建需要的各种各样的依赖，主机配置要求越来越高。
- 以及一些国内虽然无法三言两语能说清楚，但奇怪的是大家都懂的问题。

于是我就想，反正用现成的博客系统还是要折腾来折腾去，都是要捣鼓折腾，倒不如干脆自己开发一个吧！按照自己的想法去设计就好啦！而且还不用去学习那些特定的东西，自己开发的话就有印象啦，改动都比较好改。

于是，这个项目就诞生了。

（虽然后来事实证明，开发一个网站系统并不是一件简单的事，比折腾现成的成熟系统更累更麻烦，而且也同样未必就好用，这都是后话了。）

# RewrZ 基本功能清单

- [x] 文章发布
- [x] 文章评论
- [x] 文章分类
- [x] 文章标签
- [x] 文章搜索
- [x] 博客 RSS 订阅
- [x] 文章按月归档
- [x] 后台管理

# RewrZ 持续性工作

- 持续的前端优化（调整合并 js/css 、减少体积等）
- 持续的前端美化（持续修改调整外观）
- 持续的问题发现与修复

# RewrZ 附加功能想法与后续可能性计划

- [x] 二级评论功能
- [x] 评论验证码
- [x] 自动生成文章导航（引用 autocjs ）
- [x] 添加年月归档页面
- [ ] 评论开放 HTML/MD 探讨
- [ ] 增加网站可视化设置功能
- [ ] 增加推文功能
- [ ] 增加相册功能
- [ ] 增加新增页面功能
- [ ] 增加自定义菜单功能
- [ ] 增加个人主页功能
- [ ] 更加地中二化
- [ ] Ajax 评论与回复
- [x] 使用 Akismet 自动过滤垃圾评论
- [ ] 多域名访问
- [ ] 探索自动化部署与更新的实现

# RewrZ 版本与预览

- 1.0 版本

后端框架 Django 1.x ，前端主题使用基于 now-ui-kit 的 MIT 开源版本进行二次修改
```
beautifulsoup4==4.6.0
cssselect==1.0.1
Django==1.11.5
django-appconf==1.0.2
django-axes==2.3.3
django-ckeditor==5.3.0
django-haystack==2.6.1
django-htmlmin==0.10.0
django-jet==1.0.6
django-js-asset==0.1.1
django-otp==0.4.1.1
feedparser==5.2.1
google-api-python-client==1.4.1
html5lib==0.999999999
httplib2==0.10.3
jieba==0.39
Jinja2==2.9.6
lxml==4.0.0
MarkupSafe==1.0
oauth2client==4.1.2
olefile==0.44
Pillow==4.2.1
pyasn1==0.3.6
pyasn1-modules==0.1.4
pyquery==1.2.17
pytz==2017.2
qrcode==4.0.4
rsa==3.4.2
six==1.11.0
uritemplate==3.0.0
utils==0.9.0
webencodings==0.5.1
Whoosh==2.7.4
```

- 2.0 beta 版本

后端框架 Django 2.x ，前端主题采用开源前端框架 Materialize 进行重新制作。

算是一个比较大的版本升级更新，后端本来想直接用 Django 3.x ，结果发现不能无缝升级切换，有点小坑，暂时不搞。前端则更换框架，完全改头换面了。

![主页](https://cdn.jsdelivr.net/gh/rewrz/rp@master/rewrz-preview/20200501114519.jpg)

![博客页](https://cdn.jsdelivr.net/gh/rewrz/rp@master/rewrz-preview/20200501114544.jpg)

![文章页1](https://cdn.jsdelivr.net/gh/rewrz/rp@master/rewrz-preview/20200501114543.jpg)

![文章页2](https://cdn.jsdelivr.net/gh/rewrz/rp@master/rewrz-preview/20200501114545.jpg)

2020/05/02 由于大量来自欧洲的IP地址不断地发垃圾信息，验证码都无法阻挡，紧急提前开发增加 Akismet 自动过滤垃圾评论功能。

```
akismet==1.1
asgiref==3.2.7
beautifulsoup4==4.9.0
cachetools==4.1.0
colorama==0.4.3
cssselect==1.1.0
Django==2.2.12
django-appconf==1.0.4
django-axes==5.3.1
django-ckeditor==5.9.0
django-cors-headers==3.2.1
django-haystack==2.8.1
django-htmlmin==0.11.0
django-ipware==2.1.0
django-jet==1.0.8
django-js-asset==1.2.2
django-mptt==0.11.0
django-otp==0.9.0
django-ranged-response==0.2.0
django-simple-captcha==0.5.12
feedparser==5.2.1
html5lib==1.0.1
httplib2==0.17.3
jieba==0.39
Jinja2==2.11.2
lxml==4.5.0
MarkupSafe==1.1.1
oauth2client==4.1.3
olefile==0.46
Pillow==7.1.2
pyasn1==0.4.8
pyasn1-modules==0.2.8
pyquery==1.4.1
pytz==2019.1
rsa==4.0
six==1.12.0
soupsieve==1.9.2
sqlparse==0.3.0
uritemplate==3.0.1
utils==1.0.1
webencodings==0.5.1
Whoosh==2.7.4
```

# RewrZ 升级

## 1.x 升级到 2.x
请注意目前 2.x 还只是个测试版本，还有很多地方没有完全开发完，本地（Windows10）测试环境下还行，但上线（Debian）正式环境后发现存在较多 Bug ……
> 虽然最后发现这些都不是 Bug 是升级姿势不对造成的不兼容问题，捂脸……

升级还算简单，除了数据库、 media 文件夹、 uwsgi.ini 、 nginx.conf 可继续使用，其他删除，换成新的。

跟第一次部署的方式差不了多少。

```
# 安装依赖
pip install -r requirements.txt
# 收集静态文件
python manage.py collectstatic
# 迁移数据库
python manage.py makemigrations
# 自动创建数据库
python manage.py migrate
# 启动 uwsgi
uwsgi –i uwsgi.ini
```
但有三个坑需要注意：

+ Python 版本太低会不支持安装部分新版本的依赖库， pip 安装时会出现无相关版本的报错信息。
> 我原本用的是 Python3.5 ，就出现此问题了，重新编译安装当前最新版本 Python 3.8.2 后解决。3.7 版本应该也支持，因为此前我是用 3.7 的版本在本地开发的。

+ 低版本会出现 axes 中间件报错信息，以及静态文件 500 错误的问题，建议升级版本解决。

+ 注意上传的文件保持原来的权限设置，否则会出现各种权限不足的奇怪问题。

**如果还有出现其他奇怪问题，可临时把调试模式开启，看看报错信息……**

# RewrZ 的设计思想

我虽然喜欢简洁，但并不喜欢“极简”，极端在大多数时候都不会让人喜欢的。

RewrZ 的设计原则是——简洁中庸，拥有少量的功能，同时也存在无限的可能。只要你懂 Django ，就有无限的可能进行自由地扩充功能。

RewrZ 并不提倡或者说鼓励收集访客的任何信息，这在评论模块上面没有记录访客的 IP 地址，浏览器 UA 可以体现出来，仅保留访客主动提供的用于联系和头像展示使用的邮箱地址，而且是不公开的。

三个社交图标的选择和排序，仅仅是为了集齐“ What The Fuck? ”( WTF )，用来玩梗的，别无他意。

另外之所以有七个互联网各类社交应用的图标排成一排，而且还有七种颜色，也仅仅是为了向《七龙珠》、《七色彩虹天使》……等童年时代的二次元 ACG 致敬。

Logo 是自己用 PS 做出来的，“ RewrZ ”的“ R ”和“ Z ”叠在一起，一黑一白，一阴一阳，有点像太极、阴阳、周易的中国古代哲学的意思，当然也可以理解为一男一女，有点点浪漫、情侣恋爱的意味。

# RewrZ 的注意事项

固定链接、网站标题、描述、后台尝试登陆次数限制等设置，均可以在 setting.py 文件自行修改，很多地方都加了中文注释，应该不会有不明白的地方存在。

二步验证功能建议登录后台设置好用于验证的设备之后再启用，否则一旦启用，你就登录不了后台了。

改完这些之后就可以将其上传到你的服务器上面进行部署了。

部署方法可参照此篇文章：<https://rewrz.com/archive/nginx-uwsgi-virtualenv-flask-django-rewrz/>

# RewrZ 的开源协议

RewrZ 使用的是 AGPL 开源协议，这主要是因为 RewrZ 使用的后台扩展使用了 AGPL 协议。

也就是说，只要是基于 RewrZ 开发的网站，无论是否有所修改，都必须有公开声明，并且附上源代码，注意这并不包括非程序一部分的各类文件数据。不必将自己的个人文件或者数据库都开源了，当然如果你喜欢，你也可以这么做。
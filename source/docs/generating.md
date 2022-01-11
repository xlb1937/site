---
title: Generating
---
Generating static files with Hexo is quite easy and fast.

``` bash
$ {{生日祝福|12月21日|描述=配音演员|人称=谢老师}}
{{中国配音演员TOP|image=Weiyou.jpg}}
{{声优信息
|image=Xieying01.jpg
|姓名=谢莹
|其它艺名=甘蔗
|昵称=小谢、大甘蔗、谢老师
|生日=1995年12月21日
|星座={{星座|12|21}}
|年龄={{年龄|1995|12|21}}
|配演語言=中文
|出身地区=广东佛山
|所属公司=[[宸垣文化]]
|代表角色=[[渡鸦(崩坏系列)|渡鸦]]《[[崩坏3]]》<br />[[王者荣耀:镜|镜]]《[[王者荣耀]]》<br />[[厄斐琉斯|拉露恩]]《[[英雄联盟]]》<br />[[刻晴]]《[[原神]]》
|相关人士=恩师：[[孟祥龙]]
}}

'''谢莹'''是中国内地的女性配音演员。
```

{% youtube viEJQPVCoLU %}

### Watch for File Changes

Hexo can watch for file changes and regenerate files immediately. Hexo will compare the SHA1 checksum of your files and only write if file changes are detected.

``` bash
$ hexo generate --watch
```

### Deploy After Generating

To deploy after generating, you can run one of the following commands. There is no difference between the two.

``` bash
$ hexo generate --deploy
$ hexo deploy --generate
```

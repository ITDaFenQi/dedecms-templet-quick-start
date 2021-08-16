# index.htm Tags

## DedeCMS 模板标签的特征

和 `HTML` 标签类比。

`<div> </div>` `<span> </span>`

`<img />` `<br />` `<hr />`

单标签、成对标签。

`{dede} {dede /}`

`{dede /}`



## 全局变量标签

`{dede:global.cfg_soft_lang/}`

输出网站字符编码；例如：`UTF-8`

`{dede:global.cfg_webname/}`

输出网站名称；如图：

![image-20210816213050851](index.htm.assets/image-20210816213050851.png)

`{dede:global.cfg_description/}`

输出站点描述；

`{dede:global.cfg_keywords/}`

输出站点关键词；

`{dede:global.cfg_basehost/}`

输出站点根网址；

`{dede:global.cfg_indexurl/}`

输出网站主页链接；

`{dede:global.cfg_indexname/}`

输出主页链接名

`{dede:global.cfg_mobileurl/}`

输出网站手机端主页链接；

`{dede:global.cfg_cmsurl/}`



`{dede:global.cfg_cmspath/}`



`{dede:global.cfg_templeturl/}`



`{dede:global.cfg_templets_skin/}`



`{dede:global.cfg_powerby/}`

输出网站版权信息；

`{dede:global.cfg_beian/}`

输出网站备案号；

`{dede:global.cfg_memberurl/}`



`{dede:global.cfg_arcdir/}`



`{dede:global.cfg_medias_dir/}`



`{dede:global.cfg_fck_xhtml/}`



`{dede:global.cfg_df_style/}`



### 全局变量的自定义演示

手机号码；QQ号码；公司地址...



## 引其它模板文件

`{dede:include filename="head.htm"/}`

引用页眉；

`{dede:include filename="footer.htm"/}`

引用页脚；

可以引用任意同一目录下的其它模板文件。比如：

`{dede:include filename="sidebar.htm"/}`





## 其它标签

### arclist



### channelartlist



{dede:php}



feedback

{dede:memberlist row=6 signlen=30}

{dede:flinktype type="dedecms"}

`{dede:qrcode/}`







## 补充

调用 栏目封面内容

调用 栏目名称、英文名称、链接、封面图（单个、循环）

调用 轮播图

....................

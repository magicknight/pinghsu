##更新

更新版本为**v1.2.0**

 - 添加了评论无限嵌套
 - 修复了缩略图自定义字段无法cdn的问题
 - 修复用户评论链接无法跳转问题
 - 改善了表格样式，归档页样式等
 - 其他细节的东西

更新版本为**v1.1.0**，添加了文章色块设置功能，修复和改善其他细节的东西。

其中文章色块设置功能在主题外观设置那开启，开启则可以通过文章字段控制色块的颜色，支持的颜色字段如下：

`blue`、`purple`、`green`、`yellow`、`red`

同时这个更新版本，跟我现在用的是一模一样了···

##主题梗概

Pinghsu是一款以前端性能优化为出发点而制作的Typecho主题，同时又兼顾设计美学和视觉传达。主题命名取自作者姓名和其女朋友姓名的最后一个字的港式英文，挣扎于Hsuping还是Pinghsu，最后取为Pinghsu，意为一切都是Ping先Hsu后，即系要听女朋友的话。

主题是我从2017年年初开始计划设计与编程至今，修改了无数次，许多地方重写了无数次，做到自己满意为止才放出来~

下载地址：

https://github.com/chakhsu/pinghsu

主题预览：

https://www.linpx.com

图片预览：

![pinghsu-theme-preview.jpg][1]

##主题亮点

 - 页面预加载与DNS预解析保证极快访问速度
 - 无JQuery，无前端框架，轻量级
 - HighlightJS代码高亮，支持20种编程代码
 - 响应式设计，支持平板与手机，访问体验甚至优于桌面
 - 支持图片CDN镜像，支持多种文章缩略图设置
 - 支持文章个性化标徽设置，10种标徽选择
 - 支持文章目录、相关文章与数学公式渲染
 - 支持个人社交按钮，但无社交分享
 - 主题设置添加XSS检测，评论提交防止触发多次
 - 还有更多亮点等你去发现~

##主题使用

主题使用分为主题激活，主题外观设置，页面设置，文章缩略图、个性化标徽

###主题激活

到Github下载，重命名文件夹为`pinghsu`，然后放到typecho里的theme目录内，依次进入typecho控制台，更换外观，选择Pinghsu主题，启用即可。

###主题外观设置

外观设置主要分为四部分，分别为logo、icon的设置，功能开关，社交按钮设置，图片CDN镜像

使用注意事项都在设置里写得比较清楚了，如果遇到不明白的地方，可以评论留言给我

#####logo、icon的设置

![logo设置.png][2]

#####功能开关

![功能开关.png][3]

#####社交按钮设置

![社交按钮设置.png][4]

#####图片CDN镜像

肯定支持七牛CDN，理论上也支持有镜像服务的CDN

![图片CDN镜像.png][5]

###页面设置

主题内置了两个自定义页面，分别是文章时间线归档页和文章分类归档页

设置步骤有两步，创建页面，自定义模板选择，自定义字段`archive`，如下图所示

![页面设置.png][6]

###文章缩略图

文章设置缩略图方法有四种，自定义字段`thumb`，文章附件第一张图片，文章内图片，默认缩略图

优先级顺序 ：自定义字段thumb -> 附件第一张图片 -> 文章图片 -> 默认缩略图 -> 无

缩略图尺寸大小，高度至少有250px，宽度大于高度，推荐高度为400px的

###个性化标徽

个性化标徽出现的地方有首页、分类页，标签页，作者页和相关文章

设置方法是在文章编辑内，自定义字段，支持的字段如下

`book` 、 `game` 、 `note` 、 `chat` 、 `code` 、 `image` 、 `web` 、 `link` 、 `design` 、 `lock`

##浏览器兼容情况

这个····现代浏览器都兼容····

##License

Open sourced under the MIT license.


  [1]: https://ws1.sinaimg.cn/large/7c98397dgy1fcsfm231j9j20rk0ipwhy
  [2]: https://ws1.sinaimg.cn/large/7c98397dgy1fcsflqsec3j20m80bbmxe
  [3]: https://ws1.sinaimg.cn/large/7c98397dgy1fcsflt4gc6j20m80lxq3t
  [4]: https://ws1.sinaimg.cn/large/7c98397dgy1fcsflokwmsj20m80ba74d
  [5]: https://ws1.sinaimg.cn/large/7c98397dgy1fcsflpdtuoj20m808dwem
  [6]: https://ws1.sinaimg.cn/large/7c98397dgy1fcsflrkphkj20rs0i9dgb

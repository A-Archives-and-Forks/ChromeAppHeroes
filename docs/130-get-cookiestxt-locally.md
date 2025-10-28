---
title: 130《Get cookies.txt LOCALLY》 获取油管cookies，自动化下载油管视频
---

油管包含了大量的优质视频，如果想下载到本地反复观看，就需要依赖经典开源项目 https://github.com/yt-dlp/yt-dlp 这个开源项目使用起来非常方便，可以批量搜刮频道或音乐列表。

油管为了防爬虫，需要用户提供当前登陆用户的cookies才可以获取视频流，手动保存cookies对普通人而言并非易事，本文推荐一个好用的扩展工具《Get cookies.txt LOCALLY》可以快速保存油管的cookies


取油管的cookies其实也很讲究，不能从已经登陆的浏览器里直接取，不然你取出的cookies很快就会被刷新失效，这里我们参考这个教程的方法 https://github.com/yt-dlp/yt-dlp/wiki/Extractors#exporting-youtube-cookies

1. 打开一个无痕标签页面

![image-20251028131927593](https://cdn.fangyuanxiaozhan.com/assets/1761631270222E5ywnd2m.png)

2. 允许扩展工具在无痕模式中显示

![image-20251028132717163](https://cdn.fangyuanxiaozhan.com/assets/1761631278877BYERh8WR.png)



![image-20251028132508071](https://cdn.fangyuanxiaozhan.com/assets/1761631289237KWKQ0BBf.png)

3. 完成油管登录

![image-20251028132826481](https://cdn.fangyuanxiaozhan.com/assets/1761631298137xwz64d1N.png)

4. 前往 https://www.youtube.com/robots.txt 使用扩展工具获取cookies文件后，立刻关闭浏览器

![2025-10-28 13.31.27](https://cdn.fangyuanxiaozhan.com/assets/17616313074085BiMnXxi.gif)

5. 使用yt-dlp 配合 cookies下载youtube视频

![2025-10-28 13.40.46](https://cdn.fangyuanxiaozhan.com/assets/17616313179410KF0erzK.gif)

如果你感觉命令行太麻烦，可以在树莓派这种小型家庭服务器或者家用nas上，使用docker启动一个容器，提供图形化界面的下载与视频观看 https://github.com/alexta69/metube 树莓派折腾教程 https://github.com/zhaoolee/pi

![image-20251028135748242](https://cdn.fangyuanxiaozhan.com/assets/1761631326050dwTcFT13.png)



## 《Get cookies.txt LOCALLY》 下载链接

<table style="table-layout: fixed;">
<tbody>
<tr>
<td><div style="text-align: center;"><div style="font-weight: bold">Chrome</div><br/><div style="text-align: center;"><img  style="width:50px; height:auto;" src="https://v2fy.com/asset/0i/ChromeAppHeroes/page/001_markdown_here.assets/chromeappheroes-chrome-icon.png"/></div></div></td>
<td><div style="text-align: center;" ><div style="font-weight: bold">Edge</div><br/><div><img style="width:50px; height:auto;" src="https://v2fy.com/asset/0i/ChromeAppHeroes/page/001_markdown_here.assets/chromeappheroes-edge-icon.png"/></div></div></td>
<td><div style="text-align: center;" ><div style="font-weight: bold">FireFox</div><br/><div style="text-align: center;"><img  style="width:50px; height:auto;" src="https://v2fy.com/asset/0i/ChromeAppHeroes/page/001_markdown_here.assets/chromeappheroes-firefox-icon.png"/></div></div></td>
<td><div style="text-align: center;" ><div style="font-weight: bold">离线安装包</div><br/><div style="text-align: center;"><img  style="width:50px; height:auto;" src="https://v2fy.com/asset/0i/ChromeAppHeroes/page/001_markdown_here.assets/chromeappheroes-github-download.png"/></div></div></td>
</tr>
<tr>
<td>
<div style="text-align: center;"><a  href="https://chromewebstore.google.com/detail/get-cookiestxt-locally/cclelndahbckbenkjhflpdbgdldlbecc">下载链接 / Download link</a></div>
</td>
<td>
<div style="text-align: center;">暂无</div>
</td>
<td>
<div style="text-align: center;">暂无</div>
</td>
<td>
<div style="text-align: center;"><a  href="https://cdn.jsdelivr.net/gh/zhaoolee/ChromeAppHeroes/backup/130-get-cookiestxt-locally.zip">下载链接 / Download link</a></div>
</td>
</tbody>
</table>



## 小结

Cookies，是互联网时代最小的记忆单元。在上世纪九十年代，工程师 Lou Montulli 发明 Cookie，只为解决一个朴素的问题——让网页“记住”你是谁。

我们用《Get cookies.txt LOCALLY》导出油管 Cookie，只是为了让 yt-dlp 能识别出我们的身份，这一刻，我们既在借助技术的力量突破下载的壁垒，也在复刻互联网最初的浪漫：在无状态的世界中，让程序认得你。

技术本无善恶，全在如何使用。我们获取 Cookie 下载视频，是为了珍藏那些触动心灵的优质内容，在碎片化的时代里构建属于自己的知识体系。这既是对创作者辛勤付出的尊重——通过反复研习让内容价值最大化，也是在学习路上为自己搭建的私人图书馆（其实是视频仓鼠囤积合集）。

当 Cookie 从身份凭证变成了学习工具，技术便完成了它最美好的使命：让优质内容突破平台的限制，在更广阔的空间里持续发光发热。这或许就是数字时代里，我们与技术最和谐的相处之道。






## 写在最后(我需要你的支持) / At the end (I need your support)

- 本文属于**Chrome插件英雄榜** 项目的一部分, 项目Github地址: [https://github.com/zhaoolee/ChromeAppHeroes](https://github.com/zhaoolee/ChromeAppHeroes)


- This article is part of the **ChromeAppHeroes** project. Github link : [https://github.com/zhaoolee/ChromeAppHeroes](https://github.com/zhaoolee/ChromeAppHeroes) 

- **Chrome插件英雄榜**, 为优秀的Chrome插件写一本中文说明书, 让Chrome插件英雄们造福人类, 如果你喜欢这个项目, 希望你能为本项目添加一颗 🌟星.

- ChromeAppHeroes, Write a Chinese manual for the excellent Chrome plugin, let the Chrome plugin heroes benefit the human, If you like this project, I hope you can add a star 🌟 to this project.

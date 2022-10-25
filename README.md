# 📑简介
猫抓(cat-catch) 资源嗅探扩展，能够帮你筛选列出当前页面的资源。

# 📖安装地址
## 🐴Chrome
https://chrome.google.com/webstore/detail/jfedfbgedapdagkghmgibemcoggfppbb
## 🦄Edge
https://microsoftedge.microsoft.com/addons/detail/oohmdefbjalncfplafanlagojlakmjci
## 🦊Firefox
https://addons.mozilla.org/addon/cat-catch/

💔猫抓是开源的，任何人都可以下载修改上架到应用商店，已经有不少加上广告代码后上架的伪猫抓，请注意自己的数据安全。所有安装地址以github和用户文档为准。

# 📒用户文档
https://o2bmm.gitbook.io/cat-catch/

# 📘Crhome/Edge等Chromium内核浏览器 源码加载方法
1. https://github.com/xifangczy/cat-catch/releases 下载 Source code 并解压。
2. 扩展管理页面 打开 "开发者模式"。
3. 点击 "加载已解压的扩展程序" 选中你解压好的目录即可。

# 📚兼容性说明
1.0.17版本之后需要Chromium内核版本93以上。
低于93请使用1.0.16版本。

# 👻幽灵数据？
一个Chromium的BUG 不明原因的某资源不会标记来自哪个网页，1.0.17之前版本会直接丢弃该数据。之后得到修复并称这部分数据称为“幽灵数据”。
2.2.8版之后 幽灵数据标签改为其他页面，幽灵数据都归类其他页面内。

# 🔍界面
![界面](https://raw.githubusercontent.com/xifangczy/cat-catch/master/README/popup.png)

# 🤚🏻免责
扩展是通用嗅探工具和浏览器DevTools功能一致，没有针对任何一家网站进行解密操作，用户下载任何内容与扩展无关，请注意下载资源的权限和版权。

# 💖鸣谢
- [hls.js](https://github.com/video-dev/hls.js)
- [jQuery](https://github.com/jquery/jquery)
- [mux.js](https://github.com/videojs/mux.js)
- [js-base64](https://github.com/dankogai/js-base64)
- [jquery.json-viewer](https://github.com/abodelot/jquery.json-viewer)
- [Momo707577045](https://github.com/Momo707577045)
- [mpd-parser](https://github.com/videojs/mpd-parser)

# 📜License
GPL-3.0 license

1.0版 使用 MIT许可

2.0版 更改为GPL v3许可

为了资源嗅探扩展有良好发展，希望使用猫抓源码的扩展仍然保持开源。
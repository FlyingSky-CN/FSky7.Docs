# CDN 设置

MDr 本身不内置任何 [框架和库](../helper/frameworks.md) 文件，所有文件从外部地址获取。

## MDUI 静态资源来源

MDUI 静态资源包含 `mdui.min.css` 和 `mdui.min.js` 两个文件。

## MDUI 静态资源自建地址

当 `MDUI 静态资源来源` 选择自建时需要填写此项，否则无法正常使用 MDr 。

在这个输入框内你需要填写两行内容，第一行为 `mdui.min.css` 文件的绝对 URL ，第二行为 `mdui.min.js` 文件的绝对 URL 。

**此处的 URL 都不需要包含协议。**

!!! note "获取这些文件"
    你可以前往 [MDUI 官网](https://www.mdui.org/) 下载这些文件并部署。**除了上述提到的两个文件外，字体文件等也需要不改变目录结构部署，否则无法正常使用 MDr 。** 

## 其他公共静态资源来源

[框架和库](../helper/frameworks.md) 中提到的**除了 MDUI 框架外**，都属于其他公共静态资源。

## 其他公共静态资源自建地址

当 `其他公共静态资源来源` 选择自建时需要填写此项，否则无法正常使用 MDr 。

在这个输入框内你需要填写五行内容，依照顺序为以下文件的绝对 URL :

    jquery.min.js
    jquery.pjax.min.js
    jquery.qrcode.min.js
    jquery.fancybox.min.css
    jquery.fancybox.min.js

**此处的 URL 都不需要包含协议。**

!!! note "获取这些文件"
    这些库文件你都可以在 [GitHub](https://github.com) 上搜索到，具体链接待补充。
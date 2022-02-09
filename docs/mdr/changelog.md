# 更新日志

## 1.1.1

!!! success "最新版本"

!!! note
    [FlyingSky-CN](https://github.com/FlyingSky-CN) released [this](https://github.com/FlyingSky-CN/MDr/releases/tag/1.1.1) on October 1st, 2020.

!!! warning
    注意，本次更新涉及自动更新功能，建议手动更新，或者多次运行更新程序（即访问 `https://[你的博客域名]/usr/themes/MDr/update.php`）。

### 新增功能

- 现在有短代码用了

### 界面设计

- 给评论区 Pingback 重新设计了样式

### 错误修复

- 加上了 `gtag.js` 的 Pjax 回调

### 其他修改

- 更改了代码文件目录结构
- 自动更新程序对新目录结构的适配

## 1.1.0

!!! note
    [FlyingSky-CN](https://github.com/FlyingSky-CN) released [this](https://github.com/FlyingSky-CN/MDr/releases/tag/1.1.0) on July 13th, 2020.

### 新增功能

- 文章标题有超链接了
- 可以显示文章作者了
- 右侧边栏有总开关了

### 界面设计

- 新的文章目录设计
- 搜索框移位
- 背景音乐按钮移位
- 密码保护文章密码框
- 一些界面元素移位

### 错误修复

- 密码保护文章无法正常访问

### 体验优化

- 优化了主题设置面板访问速度
- 重写了 Dark Mode 机制
- Pjax 请求时部分渲染
- 提升了手机端访问体验

### 其他修改

- 优化代码写法
- 整理了 CSS 代码
- 修复一些微小的问题

## 1.0.4

!!! note
    [FlyingSky-CN](https://github.com/FlyingSky-CN) released [this](https://github.com/FlyingSky-CN/MDr/releases/tag/1.0.4) on March 12th, 2020.

### 新增功能

- “状态” 文章
- 主题设置备份
- 当前页面二维码
- 安装 & 更新统计
- 页面打印样式适配
- MDr docs 站点入口
- 支持自建静态资源地址
- 更新主题区分了正式版与测试版

### 界面设计

- 表格样式更改
- 发表评论样式更改
- 侧边栏友链样式更改
- 首页 & 侧边栏轻语样式更改
- 侧边栏统计样式更改
- 轻语页面样式更改
- 标签样式更改

### 错误修复

- 修复了不开 Pjax 灯箱无用的问题
- 修复了国内部署可能无法更新的问题
- 修复了不开启 Pjax 没有缩略图的问题
- 修复了 Dark Mode 的一项顺序错位问题
- 修复了全站黑白色调时绝对定位失效的问题

### 其他修改

- 优化代码写法
- 整理了 CSS 代码
- 更改了版本号获取方式

### 已知问题

- Pjax 完成后没有 `gtag.js` 的回调 ( [临时解决方案](https://github.com/FlyingSky-CN/MDr/issues/28#issuecomment-576495591) )

## 1.0.3

!!! note
    [FlyingSky-CN](https://github.com/FlyingSky-CN) released [this](https://github.com/FlyingSky-CN/MDr/releases/tag/1.0.3) on January 21st, 2020.

### 新增功能

- 检查并更新主题
- 文章内页缩略图显示
- 黑暗模式适配了 `prefers-color-scheme` 草案

### 界面设计

- 独立页面样式更改
- 归档界面样式更改
- 主题设置界面样式更改

### 错误修复

- 修复了主题设置界面报错的问题
- 修复了动态显示侧边栏干扰的问题
- 修复了旧版灯箱不兼容不可用的问题
- 修复了特定情况下黑暗模式不可用的问题
- 修复了 Ajax 翻页会把面包屑重复输出的问题

### 已知问题

- Pjax 完成后没有 `gtag.js` 的回调

## 1.0.2

!!! note
    [FlyingSky-CN](https://github.com/FlyingSky-CN) released [this](https://github.com/FlyingSky-CN/MDr/releases/tag/1.0.2) on January 12th, 2020.

### 新增功能

- Chrome 主题色适配
- Snackbar 位置设置

### 界面设计

- 音乐播放器样式更改
- Whisper 样式更改
- 文章目录样式更改
- 侧边栏样式更改
- 评论样式更改

### 错误修复

- 修复了一处拼写错误和写下它的程序员
- 修复了友链卡片随机排序没用的问题
- 修复了动态显示侧边栏功能的问题
- 修复了侧边栏双层滚动条的问题
- 修复了音乐播放器按钮冲突的问题
- 修复了文章目录按钮变成矩形的问题
- 修复了 Ajax 评论回复位置错误的问题
- 更改了 Hitokoto API

## 1.0.1

!!! note 
    [FlyingSky-CN](https://github.com/FlyingSky-CN) released [this](https://github.com/FlyingSky-CN/MDr/releases/tag/1.0.1) on October 25th, 2019.

!!! warning
    注意，这个版本是 `Pre-release` ( 预览版 ) ，可能会有各种BUG或不稳定不兼容等问题，请谨慎使用。

### 新增功能

- 网页滚动条开关
- Hitokoto API 
- 友链卡片随机排序
- ICP备案指向链接
- 公网安备案设置

### 界面设计

- 评论样式更改
- 主页样式更改
- 面包屑样式更改
- 轻语页样式更改
- 存档页样式更改
- 文章页样式更改
- 页面页样式更改
- 侧边栏样式更改
- 文章目录样式更改
- 首页文章信息的显示方式更改

### 体验优化

- 小屏幕 Pjax 完成后自动关闭抽屉栏
- 通知方式改用了 MDUI Snackbar
- 后台主题色设置方式更改

### 错误修复

- 修复了应用栏背景没用的问题
- 修复了搜索没有 Ajax 支持的问题
- 修复了夜间模式按钮与文章目录按钮冲突的问题

### 内容移除

- 删除了 `notie.js` ( 其功能已被代替 )
- 删除了 `viewimage.js` ( 不兼容当前版本 )
- 删除了 `style.min.css` ( 在该版本没有实际用处 )

### 已知问题

- 背景音乐功能按钮冲突 ( 已在 `1.0.2` 中解决 )
- 图片灯箱功能不可用 ( 已在 `1.0.3` 中解决 )
- 部分界面样式仍未更改 ( 已在 `1.0.2` 中解决 )

## 1.0.0

!!! note 
    [FlyingSky-CN](https://github.com/FlyingSky-CN) released [this](https://github.com/FlyingSky-CN/MDr/releases/tag/1.0.0) on September 7th, 2019.

!!! warning
    注意，这个版本是 `Pre-release` ( 预览版 ) ，可能会有各种BUG或不稳定不兼容等问题，请谨慎使用。

!!! question "更新日志呢？"
    没人写。
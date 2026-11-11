# 102 M区公关部管理系统 PWA V1.5

## 功能
- 活动新增、编辑、删除、搜索；自动活动编号 GG-年份-流水号
- 活动状态、日期日历、近期活动及统计
- 图片、海报、视频等素材上传并关联活动
- Facebook、WhatsApp、WeChat、新闻稿模板
- JSON 完整备份与恢复（包含已上传素材）
- 活动报告打印，可在打印对话框选择「另存为 PDF」
- IndexedDB 本机储存；Service Worker 离线缓存

## 本机测试
PWA 安装及 Service Worker 需要 HTTPS 或 localhost。解压后在电脑安装 Python 3，进入此文件夹执行：
`python -m http.server 8000`
然后浏览器打开 `http://localhost:8000`。这适合电脑本机测试；手机安装请部署到 HTTPS 静态托管（例如 GitHub Pages）。

## 手机安装
将整个文件夹内容部署到 HTTPS 网站。Android Chrome：菜单 → 安装应用程式／加入主画面。
iPhone Safari：分享 → 加入主画面。

## 数据说明
这是单机本地版，资料不会自动同步到其他设备。请定期下载 JSON 备份。大型视频可能超过浏览器可用储存空间；建议原视频另存云端或电脑，只将精选素材上传到系统。

## 文件
index.html / style.css / app.js / manifest.json / service-worker.js / icons/

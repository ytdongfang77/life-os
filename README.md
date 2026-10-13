# Life OS · 人生行动工作台

公开访问：https://ytdongfang77.github.io/life-os/

无需登录。包含 34 章、690 条生活建议和行动清单、21 天计划、个人复盘等功能。

## 数据保存

个人清单、完成记录、打卡、21 天计划、人生阶段及主题偏好保存在访问者自己的浏览器 localStorage 中，不上传到服务器。同一浏览器、同一网址刷新或重新打开可继续使用。不同浏览器或设备不会自动同步；共用同一浏览器配置文件会共用本地数据。清除网站数据或使用隐私模式可能导致记录丢失。

在「设置 → 数据管理」中导出 JSON 备份，或导入备份迁移数据。从旧预览地址或其他域名迁移时也需要导出/导入。

## 发布与更新

GitHub Pages 从 main 分支根目录发布。index.html 是完整自包含生产构建，.nojekyll 禁用 Jekyll 处理。更新时在原项目 life-os 目录运行 SINGLE_FILE=1 npm run build，把 dist-single/index.html 替换为本仓库根目录的 index.html 并提交，Pages 会自动重新发布。

当前采用免费的 GitHub Pages 固定网址。未来绑定自有域名需要实际拥有该域名，并在 GitHub Pages 设置和域名 DNS 中完成配置。网址的持续可用依赖 GitHub 服务和仓库保留。

## 来源与许可

基于 [HowToLiveBetter](https://github.com/eternity4719/HowToLiveBetter)。正文按 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.zh-hans) 授权，代码按 MIT 授权，详见 LICENSE。

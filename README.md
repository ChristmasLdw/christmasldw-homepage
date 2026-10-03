# Homepage - ChristmasLdw 工具集首页

## 项目简介
这是 christmasldw.com 的首页，展示所有工具的导航入口。

## 功能
- 工具导航展示
- 搜索功能
- 响应式设计
- 深色主题

## 技术栈
- 纯 HTML/CSS/JavaScript
- 无需构建工具

## 本地运行
```bash
# 直接用浏览器打开
open index.html

# 或使用任意静态服务器
python3 -m http.server 8080
```

## 部署
静态文件，直接复制到服务器 `/var/www/homepage/`

## 猫猫数独

- 入口：`/cat-sudoku/`，首页新增同名功能卡片。
- 完整源码、关卡和测试位于 `cat-sudoku/`。游戏不需要数据库或后端。
- 发布游戏时，仅需上传 `index.html`、`styles.css`、`engine.js`、`trial.js`、`levels.js`、`hints.js`、`tutorial.js`、`journey.js`、`app.js` 到站点的 `cat-sudoku/` 子目录；首页上传根目录的 `index.html`。
- 网站根目录以服务器实际配置为准。更新前备份首页；先发布游戏，再更新入口，避免出现打不开的卡片。
- 本次首页以 2026-10-03 的线上版本为基准，保留已有工具、项目入口和备案信息。

## 修改指南
- `index.html` - 主页面
- `icons/` - 图标资源

## 注意事项
- 添加新工具时需要在首页添加对应的卡片链接
- 保持图标风格统一

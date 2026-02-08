# OnTheWay（到了吗？）

一个超轻量的聚会碰面点 MVP 网页：输入多人出发地，给出建议碰面点，并在高德地图上展示。

## MVP 功能
- 输入 3-8 人出发地、聚会时间、口味偏好
- 调用 DeepSeek API 生成 1 个推荐碰面点（名称 + 理由）
- 用高德地图展示推荐点和出发点

## 技术栈
- 前端：HTML + JavaScript
- 分析：DeepSeek API
- 地图：高德地图 JavaScript API

## 快速开始
1. 准备两个 Key：
- `DEEPSEEK_API_KEY`
- `AMAP_API_KEY`

2. 按 `PRD.md` 开发 `index.html`（当前仓库只有文档，代码待实现）。

3. 本地运行静态文件（示例）：
```powershell
cd D:\Project\map\OnTheWay
python -m http.server 5500
```

4. 浏览器打开：
`http://localhost:5500`

## 当前文件
- `PRD.md`：极简 MVP 产品需求
- `README.md`：项目说明与启动指引

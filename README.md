# 多媒体处理平台（Multimedia Processing Platform）

本项目为多媒体处理平台，支持图片、音频和视频的压缩与格式转换。

## 目录结构
- backend/   Python FastAPI 后端服务（集成 FFmpeg 与 SQLite）
- frontend/  Vue.js 前端多页面应用
- requirements.txt  后端依赖
- memory/    日常知识与记录

## 本地运行指南
1. 后端：
   - 安装依赖：pip install -r requirements.txt
   - 启动服务：uvicorn backend.main:app --reload
2. 前端：
   - 进入 frontend 目录，安装依赖并启动：npm install && npm run serve

具体功能与子模块会持续完善，详情见各自目录及文档.
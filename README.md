# 抖音推荐系统

## 部署要求

环境需求:需要安装golang和postgresql和nodejs,并且把视频的mp4解压到movies文件夹下.

1. 运行`go mod tidy`下载go依赖
2. 运行`go run main.go`启动后端服务,此时会生成.configyaml文件,不出意外会爆错退出
3. 修改.configyaml文件中的数据库配置
4. 运行`go run main.go`再次启动后端服务
5. 进入titoke-web下运行`npm install`安装前端依赖
6. 运行`npm run dev`启动前端服务

## 项目分工

- 许一涵:
  - 项目管理
  - 后端主体架构搭建即功能实现
  - 数据库设计
- 张明垚:
  - 爬取并处理视频数据
- 郭金翰
  - 文档撰写
- 贺天骐:
  - 前端界面实现
- 苏雷:
  - 推荐算法实现
  - 点赞功能实现

## 分数配比

|学号|姓名|分数配比|职位|
|---|---|---|---|
|21301172|许一涵|n%|队长|
|21301174|张明垚|n%|队员|
|21301149|郭金翰|n%|队员|
|21301151|贺天骐|n%|队员|
|21301137|苏雷|n%|队员|

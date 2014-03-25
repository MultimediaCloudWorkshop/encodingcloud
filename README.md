# 云编码 Encoding Cloud  

### 特点  

- 简单  
- 稳定  
  - Auto Scaling & Load Balance
  - AWS Cloud Native
  - FFmpeg Core
  - Video Cache
  - Open Source   
- 多种编码方式

### API  

- 开始编码
  - http://multimediacloud.elasticbeanstalk.com/encode/start
  - POST 方法
  - 参数  
    - url: 原始视频URL
    - mode: 编码方式
  - 返回
    - task: 编码任务
- 停止编码
  - http://multimediacloud.elasticbeanstalk.com/encode/stop
  - POST 方法
  - 参数
    - id: 编码任务ID
  - 返回
    - task: 编码任务
- 查看编码状态
  - http://multimediacloud.elasticbeanstalk.com/encode/status
  - GET 方法
  - 参数
    - id: 编码任务ID
  - 返回
    - task: 编码任务

### 价格  

- 免费编码5分钟  
- 按照编码后的视频时长收费  

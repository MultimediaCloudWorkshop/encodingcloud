# 云编码  
Encoding Cloud  

### 特点  
- 简单  
- 稳定  
  - Auto Scaling & Load Balance
  - AWS Cloud Native
  - FFmpeg Core
  - Video Cache
  - Open Source   
- 多种编码方式

### 价格  
- 免费编码5分钟  
- 按照编码后的视频时长收费  

### APIs  

##### 开始编码
- POST http://multimediaapi.elasticbeanstalk.com/encode/start
- 参数  
  - url: 原始视频URL
  - mode: 编码方式
- 返回
  - task: 编码任务

##### 停止编码
- POST http://multimediaapi.elasticbeanstalk.com/encode/stop
- 参数
  - id: 编码任务ID
- 返回
  - task: 编码任务

##### 查看编码状态
- GET http://multimediaapi.elasticbeanstalk.com/encode/status
- 参数
  - id: 编码任务ID
- 返回
  - task: 编码任务

### 联系  
- 邮件：multimediacloudworkshop@gmail.com  

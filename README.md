## 电商平台实时监控系统

- ### 预览地址: [点击预览](http://visual.sakuramk.cn/#/home)

- ### 项目前端地址：[点击前往](https://github.com/HackerMac/visualization_real_time_monitoring_system_front)

- ### 后端地址（当前）：[点击前往](https://github.com/HackerMac/visualization_real_time_monitoring_system_backend)



## 项目结构

```
│   app.js   是后台服务器的入口文件
├───data     存放所有模块的json文件数据
├───middleware   存放所有的中间件代码
│       response_data.js     业务逻辑中间件
│       response_duration.js 计算服务器处理时长的中间件
│       response_header.js   专门设置响应头的中间件
├───service	
│       web_socket_service.js  客户端与服务端的ws连接
└───utils	工具包  
```



## 说明

如果对您对此项目有兴趣，可以点 "Star" 支持一下 谢谢！ ^_^

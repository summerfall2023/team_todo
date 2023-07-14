# team_todo

## 前端页面
- 注册页面
    用户名+密码+邮箱+验证码      
    邮箱和验证码返回后端      
- 登录页面     
    用户名+密码    
- 找回密码页面   
    邮箱+验证码   
    重置密码     
- 群组    
    任务列表    
    成员列表       
    任务提醒     
    任务详情    

## 后端框架    
见仓库    

## api文档  
[api文档](api.md)    

## 数据库设计  
- 用户表   
    1. 用户名  
    2. 密码(经过加密)   
    3. 邮箱   
    4. 加入的群组id   
    5. 头像    
- 群组表
    1. 群组名        
    2. 群组id      
    3. 群组成员id      
    4. 群组任务id     
- 任务表
    1. 任务id      
    2. 任务名     
    3. 任务内容     
    4. 任务描述    
    5. 任务负责人    
    6. ddl      
    7. 任务状态TODO/DOING/DONE    
- 提醒表
    1. 任务id    
    2. 提醒时间     
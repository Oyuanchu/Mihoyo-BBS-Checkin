# Mihoyo-BBS-Checkin
米游社每日任务自动完成
# 使用
获取米游社的cookie
## 腾讯云函数
上传项目所有文件，环境选择Python3.6，执行超时时间设为300秒，创建触发器，设为定时触发，根据自己需求设置时间。
### 设置环境变量
key填入mysCookie 
value填入获取到的cookie  例如：{'login_ticket': 'xxxxxxx', 'stuid': '0123456', 'stoken': 'xxxxxxxxxxxxxxxxxxxx'}
## 本地使用
1.在Global.py中的mysCookie里填入获取到的cookie保存即可
2.执行index.py

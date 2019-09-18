# 智慧校园考试系统
##### 功能：
1. 用户管理：注册，登陆，退出

2. 邮件激活

3. 分类选择，选择答题类型

4. 机构注册：机构注册之后可以自主出题

5. 快速出题：机构用户可以下载试题模板，创建题目，上传题库

6. 配置考试：机构用户配置考试内容，题目，时间等

7. 答题：用户参与考试，可以选择上一题，下一题，交卷

8. 评分：用户交卷后，自动显示考试结果和分数

9. 排行榜： 查看排行榜，分数

   

##### 主要库：

​	Django,  Bootstrap,   Jquery



##### 依赖：

​	requirements.txt



#### 配置：

​	config/local_settings.py



##### quick start

​	python manage.py makemigrations   创建迁移脚本

​	python manage.py migrate    迁移数据库

​	python manage.py  runserver    开始

![image](https://github.com/MRStonedb/Examination-System/blob/master/images/school_index.jpg)
![image](https://github.com/MRStonedb/Examination-System/blob/master/images/school_system.jpg)
![image](https://github.com/MRStonedb/Examination-System/blob/master/images/school_list.jpg)
![image](https://github.com/MRStonedb/Examination-System/blob/master/images/school_config.jpg)
![image](https://github.com/MRStonedb/Examination-System/blob/master/images/school_test.jpg)



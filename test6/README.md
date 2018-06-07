# 基于GitHub的实验管理平台的分析与设计

### 成都大学信息科学与工程学院

|学号|班级|姓名|照片|
|:-------:|:-------------: | :----------:|:---:|
|201510414301|软件(本)15-3|程鑫凯|![flow1](../images/孙笑川.png)|

## 1. 概述
- 基于GitHub的实验管理平台的作用是在线管理实验成绩的Web应用系统。学生和老师的实验内容均存放在GitHUB
页面上。
- 学生的功能主要有：一是设置自己的GitHub用户名，二是查询自己的实验成绩。学生的GitHub用户名是公开的，但成绩不公开。
- 老师的功能主要有：一是批改每个学生的成绩，二是查看每个学生的成绩。
- 老师和学生都能通过本系统的链接方便地跳转到学生的每个GitHUB实验目录，以便批改实验或者查看实验情况。
- 实验成绩按数字分数计算，每项实验的满分为100分，最低为0分。
- 系统自动计算每个学生的所有实验的平均分。
    
## 2. 系统总体结构
![](../images/系统总体结构.png)

界面设计参见：https://chengxinkaicxk.github.io/is_analysis/test6/UI/index.html
    
## 3. 用例图设计 [源码](src/case.puml)
![](../images/case.png)

## 4. 类图设计 [源码](src/class.puml)
![](../images/class.png)

## 5. 数据库设计
- ### [参见数据库设计](./数据库设计.md)

## 6. 用例及界面详细设计
- ### [“个人信息管理”用例](./用例/个人信息管理.md),[界面](https://chengxinkaicxk.github.io/is_analysis/test6/UI/student.html)
- ### [“发布实验课题”用例](./用例/发布实验课题用例.md),[界面](https://chengxinkaicxk.github.io/is_analysis/test6/UI/punishlab.html)
- ### [“学生查看成绩”用例](./用例/学生查看成绩用例.md),[界面](https://chengxinkaicxk.github.io/is_analysis/test6/UI/studentquerygrades.html)
- ### [“评定成绩”用例](./用例/按评分项评定成绩用例.md),[界面](https://chengxinkaicxk.github.io/is_analysis/test6/UI/reviewgrade.html)
- ### [“查看学生列表”用例](./用例/查看学生列表用例.md),[学生界面](https://chengxinkaicxk.github.io/is_analysis/test6/UI/studentlist.html),[老师界面](https://chengxinkaicxk.github.io/is_analysis/test6/UI/teastudentlist.html)
- ### [“查看学生成绩”用例](./用例/查看学生成绩用例.md),[界面](https://chengxinkaicxk.github.io/is_analysis/test6/UI/teastudentlist.html)
- ### [“查看实验课题”用例](./用例/查看实验课题用例.md),[界面](https://chengxinkaicxk.github.io/is_analysis/test6/UI/querylabtitle.html)
- ### [“登出”用例](./用例/登出用例.md),[界面](https://chengxinkaicxk.github.io/is_analysis/test6/UI/student.html)
- ### [“登录”用例](./用例/登录用例.md),[界面](https://chengxinkaicxk.github.io/is_analysis/test6/UI/index.html)
- ### [“选择学期”用例](./用例/选择学期用例.md),[学生界面](https://chengxinkaicxk.github.io/is_analysis/test6/UI/stuchoosesubject.html),[老师界面](https://chengxinkaicxk.github.io/is_analysis/test6/UI/teachoosesubject.html)
- ### [“选择课程”用例](./用例/选择课程用例.md),[学生界面](https://chengxinkaicxk.github.io/is_analysis/test6/UI/stuchoosesubject.html),[老师界面](https://chengxinkaicxk.github.io/is_analysis/test6/UI/teachoosesubject.html)
    
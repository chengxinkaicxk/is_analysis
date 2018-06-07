# 接口:queryStudentGrades [返回](../用例/查看学生成绩用例.md)

* 功能:老师查看某一课程某一实验所有学生实验的成绩 
* API请求地址:接口基本地址/cxk/api/queryStudentGrades
* 请求方式:GET
* 请求参数说明:无
* 返回实例:
<pre>
{
      "code": 200,
      "msg": null,
      "data": [
          {
            "test_id":"1",
            "title":"实验1",
            "student_id":"201510414301",
            "name":"程鑫凯",
            "class_name":"软件三班",
            "github_address":"chengxinkaicxk",
            "result":"95",
            "update_date":"2018.6.2"
            },{
                其它学生...
            }
        ]
  }
</pre>

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:-------------------------|
  |code|返回的状态码，200为正常|
  |msg|返回的信息|
  |test_id|返回的实验编号|
  |title|返回的实验课题|
  |student_id|学生的学号|
  |name|学生真实姓名|
  |class_name|班级|
  |github_address|GITHUB地址|
  |update_time|最新更新日期|
  |result|实验成绩|


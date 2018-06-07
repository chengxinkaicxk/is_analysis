# 接口:getStudents [返回](../用例/查看学生列表用例.md)

* 权限:学生:只能看见学生信息,不能看到成绩;老师:可以看到成绩
* 功能:返回所有学生的列表
* API请求地址:接口基本地址/cxk/api/getStudents
* 请求方式:GET
* 请求参数说明:无
* 返回实例:
<pre>
{
      "code": 200,
      "msg": null,
      "total": 30,
      "data": [
          {
            "student_id":"201510414301",
            "name":"程鑫凯",
            "class_name":"软件三班",
            "github_address":"chengxinkaicxk",
            "update_time":"2018.05.20",
            "grade": xxxxxx
            },{
              ...其他学生
          }
      ]
  }
</pre>

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:-------------------------|
  |code|返回的状态码，200为正常|
  |msg|返回的信息|
  |total|返回学生人数|
  |data|所有学生的数组|
  |student_id|学生的学号|
  |student_name|学生姓名|
  |class_name|班级|
  |github_address|GITHUB地址|
  |update_time|最新更新日期|
  |grade|成绩，当查询用户为老师时才会显示|

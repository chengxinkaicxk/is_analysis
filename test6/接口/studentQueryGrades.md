# 接口:studentQueryGrades [返回](../用例/学生查看成绩用例.md)

* 功能:返回某一课程某一实验的成绩（可查看详细得分情况）
* API请求地址:接口基本地址/cxk/api/studentQueryGrades
* 请求方式:GET
* 请求参数说明:无
* 返回实例:
<pre>
{
      "code": 200,
      "msg": null,
      "data": 
          {
            "test_id":"1",
            "title":"实验1",
            "result":"80.5",
            "memo":"UI界面设计完好......",
            "update_date":"2018.6.2"
            },
  }
</pre>

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:-------------------------|
  |code|返回的状态码，200为正常|
  |msg|返回的信息|
  |test_id|返回的实验编号|
  |title|返回的实验课题|
  |result|返回的实验总成绩|
  |memo|返回的教师评语|
  |update_date|返回的教师评定日期|


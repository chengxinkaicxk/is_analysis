# 接口:punishNewLab [返回](../用例/发布实验课题用例.md)

* 功能:用于老师发布新的实验课题
* API请求地址:接口基本地址/cxk/api/punishNewLab
* 请求方式:GET
* 请求参数说明:无
* 返回实例:
<pre>
{
      "code": 200,
      "msg": null,
      "data": 
          {
            "test_id":"2",
            "title":"实验二",
            "content":"实验要求......",
            "end_time":"2018.6.15"
       }
  }
</pre>

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:-------------------------|
  |code|返回的状态码，200为正常|
  |msg|返回的信息|
  |test_id|返回的实验编号|
  |title|返回的实验课题|
  |content|返回的实验的实验要求|
  |end_time|返回的实验的截止日期|


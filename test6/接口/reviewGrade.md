# 接口:reviewGrades [返回](../用例/按评分项评定成绩用例.md)

* 功能:老师对学生实验成绩进行打分
* API请求地址:接口基本地址/cxk/api/reviewGrades
* 请求方式:GET
* 请求参数说明:无
* 返回实例:
<pre>
{
      "code": 200,
      "msg": null,
      "itemsArr": [
          {
            "items_id":"1",
            "items":"UI界面设计",
            "items_weight":"0.6",
            "items_score":"96"
            },{
              ...其他实验
          }
      ]
      "data":{
            "test_id":"1"
            "title":"实验一",
            "result":"87.5",
            "memo":"总体设计不错",
            "update_date":"2018.06.02"
      }
  }
</pre>

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:-------------------------|
  |code|返回的状态码，200为正常|
  |msg|返回的信息|
  |itemsArr|评分项数组|
  |items_id|评分项编号|
  |items|评分项名称|
  |items_weight|该评分项权重|
  |items_score|该评分项得分|
  |test_id|实验编号|
  |title|实验课题|
  |result|该实验最终得分，由系统根据每个评分项得分以及各项权重计算得出|
  |memo|老师评语|
  |update_date|评定日期|


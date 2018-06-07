# 接口:changeUserInfo [返回](../用例/个人信息管理.md)

* 功能:用户可以自行修改自己的信息（密码，github地址等）
* API请求地址:接口基本地址/cxk/api/changeUserInfo
* 请求方式:GET
* 请求参数说明:无
* 返回实例:
<pre>
{
      "code": 200,
      "msg": null,
      "data": 
          {
            "github_username":"chengxinkaicxk",
            "update_date":"2018/6/1",
            "status":"修改成功"
            },
  }
</pre>

- 返回参数说明：

  |参数名称|说明|
  |:---------:|:-------------------------|
  |code|返回的状态码，200为正常|
  |msg|返回的信息|
  |github_username|github的账号（若修改为其它项，这里返回变为其它项。如：修改密码，返回password）|
  |update_date|用户最新修改信息的日期|
  |status|修改信息是否成功|


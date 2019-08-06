添加LED的邮件地址列表
===


	http://han.feature.com/wp-json/led/v2/monitor/limit?led_id=471


`HTTP PUT`


`Authorization BASIC`

## Request Params

* led_id 需要开启的led_id

* body 内容(json格式),和监控设置使用同一个接口

example:

```json
"offlineSwitch":{
    "name":"offlineSwitch",
    "operator":1
  },
```


## Response

`format` : JSON


` 成功`  

TriggerEmails属性中返回当前LED的邮件列表,[]为空.

```json
{
    "data": {
        "led_id": 65,
        "insert": 0
    },
    "headers": [],
    "status": 200
}
```



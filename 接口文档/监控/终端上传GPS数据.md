终端上传GPS数据
===


	http://han.colorlightcloud.com/wp-json/led/v2/monitor

`HTTP POST`


`Authorization BASIC`


## Request Params

空


## Json Params

* date 上报时间 (datetime String)

* sensorId  传感器ID (Integer)  没有则传-1或者其他数值

* sensorType  传感器类型(String)  必须是gps

* longitude   经度,精度支持８位小数 (double)

* latitude    纬度,精度支持８位小数 (double)

```json
[  
   {  
      "date":"2017-12-15 10:48:57",
      "sensorId":"1",
      "sensorType":"gps",
      "longitude":119.213123,
      "latitude":121.123123
   }
]
```



## Response

`format` : JSON

` 成功`

`HTTP STATUS 200`

```json
{
    "data": 1,
    "headers": [],
    "status": 200
}

```

`失败`
`HTTP STATUS 403 400 500`

```json
```



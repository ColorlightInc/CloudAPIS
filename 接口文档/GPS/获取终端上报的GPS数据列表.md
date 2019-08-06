获取终端上报的GPS坐标数据列表
===

	http://han.colorlightcloud.com/wp-json/led/v2/monitor/gps?led_id=5209&before=2018-03-23%2008%3A10%3A00&after=2018-03-23%2008%3A10%3A00

`HTTP GET `

`Authorization BASIC`


## Request Params

* led_id 

> 指定查询的led号，必填。没有该参数返回403

* before 

> 默认值是当前时间
> 获取某时间之前的数据,注意，时分秒不能全0，至少要走一分钟
> format (url string): 2018-03-23%2008%3A10%3A00

*after 

> 默认值是昨天的当前时刻
> 获取某时间之后的数据，注意，时分秒不能全0，至少要走一分钟
> format (url string): 2018-03-23%2008%3A10%3A00




## Response

`format` : JSON

`成功`


```json
    data{
        [
            "time,lng,lat",
			"time,lng,lat"
        ]
    }
```

`fields`

* time
> 时间戳

* lng 
> 经度坐标

* lat
> 纬度坐标



* example
```json
   {
    "data": [
        [
            "1513820052,42.0793511495,91.5273437500"
        ],
        [
            "1513820058,43.0793511495,92.5273437500"
        ],
        [
            "1513820064,44.0793511495,93.5273437500"
        ],
        [
            "1513820070,45.0793511495,94.5273437500"
        ],
	]
}
```



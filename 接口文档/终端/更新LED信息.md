更新LED信息.md
===


	http://han.feature.com/wp-json/wp/v2/leds/{led_id}


`HTTP PUT`


`Authorization BASIC`

## Request Params

* extra  更新LED的额外信息

	1.pixel_dimen
	2.physical_dimen
	3.geo_coordinate

* emails 设置用户警报邮箱（添加，删除，清空三个操作）
   action: 
		1.add     
		2.del	  
		3.clean	 

```example
http://han.feature.com/wp-json/wp/v2/leds/471?emails=1

{
	"action":"add",
	"EmailTriggers":[
		"hanxiaoxin@lednets.com"
	]	
}

```


## Response

`format` : JSON


` 成功`



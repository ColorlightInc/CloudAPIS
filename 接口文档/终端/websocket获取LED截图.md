推送用户获取LED截图信息
===

	ws://192.168.1.69:1234  wss://192.168.1.69:1234 

`websocket`

`wp-config.php   define('WEBSOCKET_SERVER','127.0.0.1:1234');`

`test terminal account wb Colorlight1`


`Authorization NULL`


## Request Params

* action  请求动作

auth  --  认证(前端发起连接需要使用auth参数)

* lid

 需要获取截图的led_id 

 DEMO(json)::

 {
	 "action":"auth",
	 "lid":15
 }



## Response

`format` : msg


` 成功`
返回推送的数据


`失败`



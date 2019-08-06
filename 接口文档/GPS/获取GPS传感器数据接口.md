获取GPS传感器数据接口
===


`URL`

	http://han.feature.com/wp-json/led/v2/monitor/gps?led_id=240

`HTTP GET`

`Authorization BASIC`

> Basic aGFubGluYm86MTk5NDEwNTU0NQ==

## Request Params

没有参数则默认返回最新的一条数据

*id
 
> LED id 号 (required)

* before 

> 默认值是当前时间
获取某时间之前的数据,注意，时分秒不能全0，至少要走一分钟
format (url string): 2018-03-23%2008%3A10%3A00

* after 

> 默认值是昨天的当前时刻
获取某时间之后的数据，注意，时分秒不能全0，至少要走一分钟
format (url string): 2018-03-23%2008%3A10%3A00

* page 
> 获取第几页数据
format (int) : 1

* per_page 
> 一页获取多少数据
format (int) : 12

* orderby 
> 根据某个属性排序
排序 : id

* order
> 排序方式
可选desc,asc


## Response

`format` : JSON

> 默认返回一天的gps数据


```json
{
    "data": [
        {
            "server_time": "2018-04-12 09:32:00",
            "longitude": "0",
            "latitude": "0"
        },
        {
            "server_time": "2018-04-12 09:33:01",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:34:01",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:35:01",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:36:01",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:37:01",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:38:01",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:39:01",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:40:01",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:41:01",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:42:02",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:43:02",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:44:02",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:45:02",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:46:01",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:47:02",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:48:02",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:49:02",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:51:25",
            "longitude": "0",
            "latitude": "0"
        },
        {
            "server_time": "2018-04-12 09:52:25",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:53:25",
            "longitude": "22.375",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:56:19",
            "longitude": "0",
            "latitude": "0"
        },
        {
            "server_time": "2018-04-12 09:57:19",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 09:58:19",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:05:09",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:06:09",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:07:09",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:08:09",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:09:09",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:10:09",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:11:09",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:12:09",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:13:09",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:14:09",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:15:09",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:16:09",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:17:09",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:18:09",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:19:09",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:20:10",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:21:10",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:22:10",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:23:10",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:24:10",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:25:10",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:26:10",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:27:10",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:28:10",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:29:10",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:30:14",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:31:10",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:32:10",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:33:11",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:34:11",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:35:14",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:36:11",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:37:11",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:38:11",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:39:11",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:40:11",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:41:11",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:42:11",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:43:11",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:44:11",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:45:12",
            "longitude": "22.3749",
            "latitude": "113.561"
        },
        {
            "server_time": "2018-04-12 10:46:11",
            "longitude": "22.3749",
            "latitude": "113.561"
        }
    ],
    "headers": [],
    "status": 200
}
```
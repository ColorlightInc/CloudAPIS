终端组所有终端excel下载
===
	http://d2.colorlightcloud.com:8880/wp-json/led/doc/term/{term_id}?before=2018-03-23%2008%3A10%3A00&after=2018-03-23%2008%3A10%3A00

`HTTP GET`

`Authorization BASIC`

> Basic aGFubGluYm86MTk5NDEwNTU0NQ==


## Request Params

* term_id (example 612)

  > int 终端组ID


* before 

> 默认值是当前时间
> 获取某时间之前的数据,注意，时分秒不能全0，至少要走一分钟
> format (url string): 2018-03-23%2008%3A10%3A00

*after 

> 默认值是昨天的当前时刻
> 获取某时间之后的数据，注意，时分秒不能全0，至少要走一分钟
> format (url string): 2018-03-23%2008%3A10%3A00

* limit 

> 获取多少条数据，默认最多1万条

## Response

`format` : JSON

> 默认无时间参数则返回两天数据的excel

```json
{
	"data":"http:\/\/www.hanxiaoxin.cn\/wp-content\/uploads\/documents\/statistic_led13_2018-04-28.xlsx",
	"headers":[],
	"status":200
}
```




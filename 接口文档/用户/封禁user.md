创建用户
===


	http://192.168.1.70/wp-json/wp/ip/login

`HTTP PUT`


`Authorization BASIC`


## Request Params

```json

{ips: ["username"]}

```
* username  用户名

* forbidden  true/false   判断封禁的状态

*  解禁   解除用户名封禁


```
用户登录错误4次后 封禁用户  封禁次数可以修改设定

用户状态显示封禁中  封禁时间可以设定

解锁用户  在用户封禁时间内 手动解锁封禁用户


```

* term_id   分配到的终端组id


## Response

`format` : JSON

` 成功`

`HTTP STATUS 200`

```json
{
	
	data: true
    headers: []
   status: 200
}
```

`失败`
`HTTP STATUS 403 400 500`

```json

```



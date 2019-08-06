wordpress密码重置接口(已废弃)
===

	http://han.feature.com/wp-json/wp/v2/users/reset_pw

`HTTP POST`


`Authorization BASIC`


## Request Params

```
{
	"user_login":"hanlinbo"
}


{
	"user_login":"hanxiaoxin@lednets.com"
}
```
* user_login  用户名 或者邮箱地址 都可以


## Response

`format` : JSON


` 成功`

```json
{
	"success":"1"
}
```

`失败`

```json
{
   "code": "invalid_email",
   "message": "<strong>ERROR</strong>: There is no user registered with  that email address.",
   "data": null
}
```
获取LED列表的GPS
===
	http://han.feature.com/wp-json/wp/v2/leds?&download_status=true&page=1&per_page=8&context=view

`HTTP GET`

`Authorization BASIC`

> Basic aGFubGluYm86MTk5NDEwNTU0NQ==


## Request Params

该接口与标准终端获取接口一致.

geo_coordinate属性默认为空，只有盒子上报GPS数据才会显示.

* download_status=true  是否获取节目下载数据

* page=1&per_page=8   每页获取的值和页码

## Json Params

空

## Response

`format` : JSON

> 返回LED列表

GPS属性在每个LED对象的post_meta属性的geo_coordinate属性中.

```json
[{
	"id": 21619,
	"date": "2018-07-27T18:52:15",
	"date_gmt": "2018-07-27T10:52:15",
	"slug": "234",
	"status": "publish",
	"type": "led",
	"title": {
		"raw": "234",
		"rendered": "234"
	},
	"excerpt": {
		"raw": "234",
		"rendered": "<p>234<\/p>\n",
		"protected": false
	},
	"author": 197,
	"comment_status": "open",
	"terminalgroup": [{
		"id": 645,
		"name": "multidocs"
	}],
	"TriggerEmails": [],
	"post_meta": {
		"physical_dimen": "",
		"pixel_dimen": "",
		"geo_coordinate": {
			"longitude": 113.56099701,
			"latitude": 22.37490082
		},
		"_led_status": {
			"terminal": {
				"name": "234",
				"leddescription": "",
				"_report_time": 1532939219
			},
			"powerstatus": {
				"powerstatus": 1,
				"_report_time": 1532939219
			},
			"info": {
				"info": {
					"vername": "1.50.8",
					"serialno": "CLCC400005CE",
					"model": "c4",
					"up": 119171,
					"mem": {
						"total": 1073741824,
						"free": 778850304
					},
					"storage": {
						"total": 5878841344,
						"free": 5878349824
					},
					"playing": {
						"name": "contents9978_8082C02B278F95EF818FEE0E5A747CD0_901.vsn",
						"path": "\/mnt\/sdcard\/Android\/data\/com.color.home\/files\/Download",
						"source": "internet"
					}
				},
				"_report_time": 1532939280
			},
			"vsns": {
				"playing": {
					"name": "contents9978_8082C02B278F95EF818FEE0E5A747CD0_901.vsn",
					"type": "internet"
				},
				"contents": [{
					"type": "internet",
					"ressize": 358749,
					"unused": 0,
					"content": [{
						"name": "contents9978_8082C02B278F95EF818FEE0E5A747CD0_901.vsn",
						"size": 359650,
						"md5": "",
						"publishedmd5": ""
					}]
				}],
				"_report_time": 1532939280
			},
			"rtc": {
				"time": "2018-07-30 16:26:56",
				"timezone": "+08",
				"isautotimezone": 1,
				"isautotime": 1,
				"_report_time": 1532939219
			},
			"dimension": {
				"dclk": 42666666,
				"fps": 60,
				"height": 512,
				"hsync": 12,
				"real_dclk": 42666664,
				"real_height": 512,
				"real_width": 1280,
				"width": 1280,
				"_report_time": 1532939219
			},
			"volume": {
				"musicvolume": 12,
				"_report_time": 1532939219
			},
			"inputmode": {
				"inputmode": "hdmi",
				"inputmodeactive": "dvi",
				"_report_time": 1532939219
			},
			"ifstatus": {
				"types": [{
					"peers": [],
					"SSID": "c4-05CE",
					"pass": "*",
					"channel": 0,
					"ips": {
						"broadcast": "192.168.43.255",
						"ip": "192.168.43.1",
						"mask": "255.255.255.0"
					},
					"type": "wifi ap",
					"carrier": 0,
					"connected": 0,
					"enabled": 0
				}, {
					"currentap": "dd-wrt-01-2.4G",
					"ssids": [{
						"SSID": "\"dd-wrt-01-2.4G\"",
						"pass": "*",
						"priority": 0
					}],
					"state": "COMPLETED",
					"speed": 39,
					"ips": {
						"broadcast": "192.168.1.255",
						"ip": "192.168.1.164",
						"mask": "255.255.255.0"
					},
					"mac": "a8:ab:40:00:05:ce",
					"operstate": "up",
					"type": "wifi",
					"carrier": 1,
					"connected": 0,
					"enabled": 1
				}, {
					"mac": "a8:aa:40:00:05:ce",
					"operstate": "down",
					"type": "lan",
					"carrier": 0,
					"connected": 0,
					"enabled": 0
				}, {
					"strength": 0,
					"mode": "UNKNOWN",
					"type": "4G",
					"carrier": 0,
					"connected": 0,
					"enabled": 0
				}]
			},
			"brightnessandcolortemp": {
				"brightness": 77,
				"colortemperature": 3100,
				"_report_time": 1532939219
			},
			"reporttime": {
				"gps_report_interval": 0,
				"sensor_report_interval": 24,
				"ber_report_interval": 24
			},
			"cmdinterval": {
				"command_interval": 5000
			},
			"reportswitch": {
				"log_report": "off",
				"complete_screen_status_report": "on",
				"not_rotate_program_screenshot_report": "on",
				"rotate_program_screenshot_report": "off",
				"command_screenshot_report": "on",
				"auto_vsns_report": "on",
				"manual_vsns_report": "on",
				"rotate_program_vsns_report": "off",
				"auto_info_report": "on",
				"manual_info_report": "on"
			},
			"contentreport": {
				"content_report_status": 1
			},
			"contentreportinterval": {
				"content_report_interval": 60000
			},
			"newrtc": {
				"time": "2018-07-30 16:26:59",
				"timezoneId": "Asia\/Shanghai",
				"timezone": 8,
				"isautotime": 1
			},
			"locale": {
				"language": "zh",
				"country": "CN"
			}
		},
		"_led_latest_screenshot_time": 1532939281,
		"_led_latest_camerashot_time": 0,
		"_led_latest_report_time": 1532941129,
		"shared_to": [],
		"shared_to_names": [],
		"download_status": {
			"programs": [{
				"files": [{
					"name": "F_B24F9F3D312AB3EC4CD494763BFD7700_358749.png",
					"downloaded": 358749,
					"programId": 22333,
					"total": 358749
				}, {
					"name": "contents9978_8082C02B278F95EF818FEE0E5A747CD0_901.vsn",
					"downloaded": 901,
					"programId": 22333,
					"total": 901
				}],
				"name": "contents9978",
				"id": 22333
			}],
			"download_status_time": 1532939279
		},
		"update_status": []
	},
	"extra": {
		"author_display_name": "csz"
	}
}, {
	"id": 22331,
	"date": "2018-07-30T16:24:45",
	"date_gmt": "2018-07-30T08:24:45",
	"slug": "terminal05ec-4",
	"status": "publish",
	"type": "led",
	"title": {
		"raw": "Terminal05EC",
		"rendered": "Terminal05EC"
	},
	"excerpt": {
		"raw": "Terminal05EC",
		"rendered": "<p>Terminal05EC<\/p>\n",
		"protected": false
	},
	"author": 411,
	"comment_status": "open",
	"terminalgroup": [{
		"id": 645,
		"name": "multidocs"
	}],
	"TriggerEmails": [],
	"post_meta": {
		"physical_dimen": "",
		"pixel_dimen": "",
		"_led_status": "",
		"_led_latest_screenshot_time": 0,
		"_led_latest_camerashot_time": 0,
		"_led_latest_report_time": 0,
		"shared_to": [],
		"shared_to_names": [],
		"download_status": [],
		"update_status": []
	},
	"extra": {
		"author_display_name": "multydoc"
	}
}]
```




添加LED的邮件地址列表
===


	http://han.feature.com/wp-json/wp/v2/leds/{led_id}?emails=1


`HTTP PUT`


`Authorization BASIC`

## Request Params

* 重复的邮件不会添加，添加列表暂时没有上限

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

TriggerEmails属性中返回当前LED的邮件列表,[]为空.

```json
{
    "id": 65,
    "date": "2018-07-24T15:19:40",
    "date_gmt": "2018-07-24T07:19:40",
    "slug": "terminal05ec",
    "status": "publish",
    "type": "led",
    "title": {
        "raw": "Terminal05EC",
        "rendered": "Terminal05EC"
    },
    "excerpt": {
        "raw": "Terminal05EC",
        "rendered": "<p>Terminal05EC</p>\n",
        "protected": false
    },
    "author": 2,
    "comment_status": "open",
    "terminalgroup": [
        {
            "id": 4,
            "name": "hanxiaoxin"
        }
    ],
    "TriggerEmails": [
        [
            "hanxiaoxin@lednets.com"
        ]
    ],
    "post_meta": {
        "physical_dimen": "",
        "pixel_dimen": "",
        "_led_status": {
            "terminal": {
                "name": "Terminal05EC",
                "leddescription": " ",
                "_report_time": 1532417091
            },
            "powerstatus": {
                "powerstatus": 1,
                "_report_time": 1532417091
            },
            "info": {
                "info": {
                    "vername": "1.51.0",
                    "serialno": "CLCC400005EC",
                    "model": "c4",
                    "up": 1639007,
                    "mem": {
                        "total": 1073741824,
                        "free": 779407360
                    },
                    "storage": {
                        "total": 5878841344,
                        "free": 5643755520
                    },
                    "playing": {
                        "name": "contents6126_83B6C4E9AA239E008559CCC686A2AF01_1296.vsn",
                        "path": "/mnt/sdcard/Android/data/com.color.home/files/Download",
                        "source": "internet"
                    }
                },
                "_report_time": 1532417091
            },
            "vsns": {
                "playing": {
                    "type": "internet",
                    "name": "contents6126_83B6C4E9AA239E008559CCC686A2AF01_1296.vsn"
                },
                "contents": [
                    {
                        "type": "internet",
                        "ressize": 3598962,
                        "unused": 3558763,
                        "content": [
                            {
                                "name": "contents4236_2B4ABE98575D8AC89433BC5EBFF06D1F_2088.vsn",
                                "size": 42287,
                                "md5": "",
                                "publishedmd5": ""
                            },
                            {
                                "name": "contents6126_83B6C4E9AA239E008559CCC686A2AF01_1296.vsn",
                                "size": 21101,
                                "md5": "",
                                "publishedmd5": ""
                            }
                        ]
                    }
                ],
                "_report_time": 1532417091
            },
            "rtc": {
                "time": "2018-07-24 15:23:50",
                "timezone": "+08",
                "isautotimezone": 1,
                "isautotime": 1,
                "_report_time": 1532417091
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
                "_report_time": 1532417091
            },
            "volume": {
                "musicvolume": 3,
                "_report_time": 1532417091
            },
            "inputmode": {
                "inputmode": "hdmi",
                "inputmodeactive": "dvi",
                "_report_time": 1532417091
            },
            "ifstatus": {
                "types": [
                    {
                        "peers": [],
                        "SSID": "c4-05EC",
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
                    },
                    {
                        "currentap": "dd-wrt-01-2.4G",
                        "ssids": [
                            {
                                "SSID": "\"dd-wrt-01-2.4G\"",
                                "pass": "*",
                                "priority": 0
                            }
                        ],
                        "state": "COMPLETED",
                        "speed": 1,
                        "ips": {
                            "broadcast": "192.168.1.255",
                            "ip": "192.168.1.203",
                            "mask": "255.255.255.0"
                        },
                        "mac": "a8:ab:40:00:05:ec",
                        "operstate": "up",
                        "type": "wifi",
                        "carrier": 1,
                        "connected": 0,
                        "enabled": 1
                    },
                    {
                        "mac": "a8:aa:40:00:05:ec",
                        "operstate": "down",
                        "type": "lan",
                        "carrier": 0,
                        "connected": 0,
                        "enabled": 0
                    },
                    {
                        "strength": 0,
                        "mode": "UNKNOWN",
                        "type": "4G",
                        "carrier": 0,
                        "connected": 0,
                        "enabled": 0
                    }
                ]
            },
            "brightnessandcolortemp": {
                "brightness": 50,
                "colortemperature": 6500,
                "_report_time": 1532417091
            },
            "reporttime": {
                "gps_report_interval": 0,
                "sensor_report_interval": 1,
                "ber_report_interval": 1
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
                "content_report_interval": 0
            },
            "newrtc": {
                "time": "2018-07-24 15:23:53",
                "timezoneId": "Asia/Shanghai",
                "timezone": 8,
                "isautotime": 1
            },
            "locale": {
                "language": "zh",
                "country": "CN"
            },
            "sync_program_mode": {
                "sync_program_gps_enable": 0,
                "sync_program_ntp_enable": 0,
                "sync_program_ntp_server": "2.android.pool.ntp.org",
                "sync_program_ntp_interval": 60000,
                "sync_program_ntp_threshold": 15,
                "sync_program_lan_enable": 1,
                "sync_program_lan_role": "master"
            }
        },
        "_led_latest_screenshot_time": 1532417375,
        "_led_latest_camerashot_time": 0,
        "_led_latest_report_time": 1532417531,
        "shared_to": [],
        "shared_to_names": []
    },
    "extra": {
        "author_display_name": "hanxiaoxin"
    }
}
```



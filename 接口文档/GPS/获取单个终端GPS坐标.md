获取单个终端GPS坐标
===
	http://han.feature.com/wp-json/wp/v2/leds/{led_id}

`HTTP GET`

`Authorization BASIC`

> Basic aGFubGluYm86MTk5NDEwNTU0NQ==


## Request Params

该接口与标准终端获取接口相同.

geo_coordinate默认为空，只有盒子上报GPS数据才会显示.

* led_id  led_id 必填,指定LED

## Json Params

空

## Response

`format` : JSON

> 返回单个LED数据

GPS属性在每个LED对象的post_meta属性的geo_coordinate属性中.

```json
{
	"id": 201196,
	"date": "2018-07-28T14:43:45",
	"date_gmt": "2018-07-28T06:43:45",
	"slug": "terminala003-3",
	"type": "led",
	"title": {
		"rendered": "kevin"
	},
	"excerpt": {
		"rendered": "<p>TerminalA003<\/p>\n",
		"protected": false
	},
	"author": 2,
	"comment_status": "open",
	"terminalgroup": [{
		"id": 14,
		"name": "kevin"
	}],
	"TriggerEmails": [],
	"post_meta": {
		"physical_dimen": "",
		"pixel_dimen": "",
		"geo_coordinate": {
			"longitude": 113.5608902,
			"latitude": 22.37493706
		},
		"_led_status": {
			"terminal": {
				"name": "TerminalA003",
				"leddescription": "",
				"_report_time": 1532913961
			},
			"powerstatus": {
				"powerstatus": 1,
				"_report_time": 1532913961
			},
			"info": {
				"info": {
					"vername": "1.51.7",
					"serialno": "CLCC4000A003",
					"model": "c4",
					"up": 2550877,
					"mem": {
						"total": 1073741824,
						"free": 768327680
					},
					"storage": {
						"total": 5878841344,
						"free": 5823799296
					},
					"playing": {
						"name": "宣传片片片_DEED2DDBC1172FE09AFC77D8941A709B_918.vsn",
						"path": "\/mnt\/sdcard\/Android\/data\/com.color.home\/files\/Download",
						"source": "internet"
					}
				},
				"_report_time": 1532913961
			},
			"vsns": {
				"playing": {
					"type": "internet",
					"name": "宣传片片片_DEED2DDBC1172FE09AFC77D8941A709B_918.vsn"
				},
				"contents": [{
					"type": "lan",
					"content": [{
						"name": "时钟3.vsn",
						"size": 8210,
						"md5": "",
						"publishedmd5": "86A2EDD6B4F5ACE8136F8181D754EF02"
					}]
				}, {
					"type": "internet",
					"ressize": 54188437,
					"unused": 0,
					"content": [{
						"name": "12-单位_ED3D278D8155C4D8C7960088658826F3_1980.vsn",
						"size": 1980,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "4PB_966C337B0C498CBAFC51EA8D789EA132_2293.vsn",
						"size": 2293,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Analog-Clock_C0904B5400DE2A1FC2C3B0B7F399172A_1979.vsn",
						"size": 1979,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Colok_41C344BA6BEFEA2C4B87B4AD2F817CE2_5350.vsn",
						"size": 5350,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Environment_ECA1246E9FC3131C26034BDCF7D82FB5_7600.vsn",
						"size": 7600,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Humidity_6A09BA35DA1D957886209D54CCE7DC32_5791.vsn",
						"size": 5791,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Humidity_F79D1DED5634AA804A2040D5D6FBB6FB_5788.vsn",
						"size": 5788,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Humidity_F8A9335A700BDC7772E0D3B253A161FB_5791.vsn",
						"size": 5791,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_30725432D27645C3AEDC9159BE930A54_2041.vsn",
						"size": 2041,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_3133E88DB54BD625D9B0A1B6DC408572_5536.vsn",
						"size": 5536,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_354BBA00ECF55232DDEDB5A137A0E6DF_3788.vsn",
						"size": 3788,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_46FE7FD462F93FF6ABB87D5F528E9521_3789.vsn",
						"size": 3789,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_5398B7A0AE1C4FBDF7A529277A812C97_3788.vsn",
						"size": 3788,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_546C12C18E3E689F9A0E0B4B64DA5204_3789.vsn",
						"size": 3789,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_91BDAD8A39EC1E31AEF49EB5BBEECBCD_3786-1.vsn",
						"size": 3786,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_91BDAD8A39EC1E31AEF49EB5BBEECBCD_3786.vsn",
						"size": 3786,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_966376752C80FCC06F00993FD6559D26_2041.vsn",
						"size": 2041,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_98F49433DD760C7DE9368EEE48EA2E01_3788.vsn",
						"size": 3788,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_A5646C86C3F1412E23B0A98BABB25111_3788.vsn",
						"size": 3788,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_B5EA1B5D29FC723F6DECC7BE177C063F_3789.vsn",
						"size": 3789,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_C97150224DE6C3ADE23B97953805393B_3786.vsn",
						"size": 3786,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_E318E3ECB376E090FFE162DEB2DF6F1C_3788.vsn",
						"size": 3788,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_E419C02D12C8F33E153C7FF5DB4DDC07_5536.vsn",
						"size": 5536,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_E96FAEA577CA86F813CDF44BBCF720AB_5536.vsn",
						"size": 5536,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Multi-line_F0E1B89BE28130F7D69029EF4628E870_5536.vsn",
						"size": 5536,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "RSS_F4D13A2709F52F045F76730F571B20FF_923.vsn",
						"size": 923,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Scroll-Top-Multi-line_FD627C0670AE79E133A9EBDA9E0711D1_2041.vsn",
						"size": 2041,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Single-line_9DE3065D240D99A77B2F00EDBE47CB90_5645.vsn",
						"size": 5645,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Single-line_DDE7171BEBD3920E4D9EEA62023E8394_2068.vsn",
						"size": 2068,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Temperature_2071C6C87537D19A1D55F6F862967952_3957.vsn",
						"size": 3957,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Temperature_30016C2DDD0C7666C2524271FAC190F5_3958.vsn",
						"size": 3958,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Temperature_5208C242A508D12166F35CEC8F8D3283_3958.vsn",
						"size": 3958,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Temperature_733CC4C91905501395BA6E309B00D58C_3955.vsn",
						"size": 3955,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Temperature_9C1F39A3CA5B39FA90FF10B224B530E5_3959.vsn",
						"size": 3959,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Temperature_C0904B5400DE2A1FC2C3B0B7F399172A_1979.vsn",
						"size": 1979,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Temperature_F9287283A1892B7E5843FBF04CE24138_3955-1.vsn",
						"size": 3955,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Temperature_F9287283A1892B7E5843FBF04CE24138_3955-2.vsn",
						"size": 3955,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Temperature_F9287283A1892B7E5843FBF04CE24138_3955.vsn",
						"size": 3955,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Temperature_FDF710BA67511BC8CA60B1B0E1789128_3953.vsn",
						"size": 3953,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Timer-Multi-line_5CB5A37D8B861B753879F32B7A102E0D_1271.vsn",
						"size": 1271,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "Weather_D715FBDBE6DA6F26759F57CE0F009253_1597.vsn",
						"size": 1597,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "clock_ED3D278D8155C4D8C7960088658826F3_1980.vsn",
						"size": 1980,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "contents1307_476BE5086895999E9020F4C24A236AF5_2041.vsn",
						"size": 2041,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "contents2784_289F366A4AA879851C566125C4CF1F9B_3788.vsn",
						"size": 3788,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "contents2784_F647F318942D4B55C2433DE3E83274A6_3788.vsn",
						"size": 3788,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "contents3948_F4D13A2709F52F045F76730F571B20FF_923.vsn",
						"size": 923,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "contents4373_92E8243ECE84529C9F72E0357313BD7E_2041.vsn",
						"size": 2041,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "contents4958_28761E1F8F63DBCC97AC0144111B1C86_935.vsn",
						"size": 11715,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "contents5101_A76ACF4D68C34D20F1423E58F7272716_2006.vsn",
						"size": 2006,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "contents526_0D652D93892A8B5ED64433C583DBEF17_1979.vsn",
						"size": 1979,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "contents526_7F5DE1EE2E87AAA8665179EDA3F4A8D1_1979-1.vsn",
						"size": 1979,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "contents526_7F5DE1EE2E87AAA8665179EDA3F4A8D1_1979.vsn",
						"size": 1979,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "contents5350_34999D9FE5C2BAAC33F27BCBB9819561_956.vsn",
						"size": 849175,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "contents5621_5D3A76831CE99BA7854BF449CBB04711_1227.vsn",
						"size": 41733255,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "contents6081_CACF045A2EDA368EAD1B86FD1A531296_5783.vsn",
						"size": 5783,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "contents6813_C5CA9C1EBFFD59F4A6E27ECD64921F2B_1980.vsn",
						"size": 1980,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "contents6813_ED3D278D8155C4D8C7960088658826F3_1980.vsn",
						"size": 1980,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "contents6999_ED3D278D8155C4D8C7960088658826F3_1980.vsn",
						"size": 1980,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "timer_1DDDA1FC910156A39EE8CA0A0F939783_2254.vsn",
						"size": 2254,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "video-and-picture_0A841847D9672083D003B50E6C31A94F_1240.vsn",
						"size": 1500589,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "weather_B61CB0C9975A78517E7169649DBEFC73_2872.vsn",
						"size": 2872,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "web_8F006BE5ABF9F402539A364B43D11EE1_774.vsn",
						"size": 774,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "web_E6054A20FFF6A04FEF7FE8CF57D01EFA_774.vsn",
						"size": 774,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "宣传片片片_DEED2DDBC1172FE09AFC77D8941A709B_918.vsn",
						"size": 6590543,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "时钟12小时带单位4_5D80C91DC6D040B7DB37A082B840144B_1981.vsn",
						"size": 1981,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "背景色测试_9010FC0CA409EA5F55A0FA7092173853_4021.vsn",
						"size": 4021,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "计费上报节目1_C1F9D09EE492DFF5239191F9C96276B0_959.vsn",
						"size": 497497,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "计费上报节目2_6F2CE6C593E22EDA9C76ECCD42EE726B_964.vsn",
						"size": 1811496,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "计费上报节目3_3646A3FB7110E7F03E59264443BDACCC_924.vsn",
						"size": 873256,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "计费上报节目4_226AD4D20990CFCCE94EEDCB00DF0112_2201.vsn",
						"size": 2201,
						"md5": "",
						"publishedmd5": ""
					}, {
						"name": "计费节目综合_3EAEF6F70CA2B919D70E68C662567BA9_9496.vsn",
						"size": 1732533,
						"md5": "",
						"publishedmd5": ""
					}]
				}],
				"_report_time": 1532913961
			},
			"rtc": {
				"time": "2018-07-30 09:25:59",
				"timezone": "+08",
				"isautotimezone": 0,
				"isautotime": 1,
				"_report_time": 1532913961
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
				"_report_time": 1532913961
			},
			"volume": {
				"musicvolume": 1,
				"_report_time": 1532913961
			},
			"inputmode": {
				"inputmode": "hdmi",
				"inputmodeactive": "dvi",
				"_report_time": 1532913961
			},
			"ifstatus": {
				"types": [{
					"peers": [],
					"SSID": "c4-A003",
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
					"ssids": [],
					"state": "UNINITIALIZED",
					"speed": -1,
					"type": "wifi",
					"carrier": 0,
					"connected": 0,
					"enabled": 0
				}, {
					"ips": {
						"dns1": "192.168.10.1",
						"dns2": "",
						"gateway": "192.168.10.1",
						"ip": "192.168.10.189",
						"mask": "255.255.255.0"
					},
					"mac": "a8:aa:40:00:a0:03",
					"mode": "dhcp",
					"operstate": "up",
					"type": "lan",
					"carrier": 1,
					"connected": 0,
					"enabled": 1
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
				"brightness": 10,
				"colortemperature": 6500,
				"_report_time": 1532913961
			},
			"reporttime": {
				"gps_report_interval": 0,
				"sensor_report_interval": 120,
				"ber_report_interval": 120
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
				"content_report_status": 0
			},
			"contentreportinterval": {
				"content_report_interval": 600000
			},
			"newrtc": {
				"time": "2018-07-30 09:26:01",
				"timezoneId": "Asia\/Shanghai",
				"timezone": 8,
				"isautotime": 1
			},
			"locale": {
				"language": "en",
				"country": "GB"
			},
			"sync_program_mode": {
				"sync_program_gps_enable": 1,
				"sync_program_ntp_enable": 0,
				"sync_program_ntp_server": "2.android.pool.ntp.org",
				"sync_program_ntp_interval": 120000,
				"sync_program_ntp_threshold": 10,
				"sync_program_lan_enable": 0,
				"sync_program_lan_role": "slave"
			}
		},
		"_led_latest_screenshot_time": 1532761026,
		"_led_latest_camerashot_time": 0,
		"_led_latest_report_time": 1532913987,
		"shared_to": [],
		"shared_to_names": []
	},
	"extra": {
		"author_display_name": "kevin"
	}
}
```




## 指令控制

发送指令
### Path
GET /server/send
#### Protected. Auth needed
### Tags
    - SuKe
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| instruct_type | string |  |  [required]  | 指令类型ZXQB:读表 ,MMSQ:购电,SKSKM:购负电,MMYQ:强制断电,KSQB:上电,ZXQK:卡授权,SKSKM:远程开锁 ,KSQB:卡型注消 ,RDXX :读开门记录 |
| hardware_auth | string |  |  [required]  | 授权码 |
| hardware_number | string |  |  [required]  | 设备编号 |
| hardware_path | string |  |  [required]  | 设备路径 |
| instruct_id | string |  |  [required]  | 指令ID |
| instruct_paras | string |  |  [required]  | 指令参数 |

*request usage*
```javascript
// 指令控制
let requestParams = {}
requestParams.instructType =  null  // 指令类型ZXQB:读表 ,MMSQ:购电,SKSKM:购负电,MMYQ:强制断电,KSQB:上电,ZXQK:卡授权,SKSKM:远程开锁 ,KSQB:卡型注消 ,RDXX :读开门记录 required
requestParams.hardwareAuth =  null  // 授权码 required
requestParams.hardwareNumber =  null  // 设备编号 required
requestParams.hardwarePath =  null  // 设备路径 required
requestParams.instructId =  null  // 指令ID required
requestParams.instructParas =  null  // 指令参数 required
let res = await api.get_server_send(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_server_send_TYPE()
api.get_server_send_RAW_URL()
api.get_server_sendURL(requestParams)
```

## Responses
### Returns instance data

#### Status Code
200



### object not found

#### Status Code
404




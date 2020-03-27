## 查询设备类型信息

查询设备类型信息
### Path
GET /suke/query_zl_info

### Tags
    - SuKe
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| hardwareType | string |  |  [optional]  | 设备类型 |
| name | string |  |  [optional]  | 指令 |
| nameEncrypt | string |  |  [optional]  | 加密指令 |
| needReply | integer |  |  [optional]  | 指令回复类型 9全部 1 需要 0 不需要 |
| enable | integer | 1 |  [optional]  | 指令状态 9全部 启动:1,废弃:0 |
| skip | integer |  |  [optional]  | 起始查询位 |
| limit | integer |  |  [optional]  | 查询条数 |

*request usage*
```javascript
// 查询设备类型信息
let requestParams = {}
requestParams.hardwareType =  null  // 设备类型 optional
requestParams.name =  null  // 指令 optional
requestParams.nameEncrypt =  null  // 加密指令 optional
requestParams.needReply =  null  // 指令回复类型 9全部 1 需要 0 不需要 optional
requestParams.enable =  null  // 指令状态 9全部 启动:1,废弃:0 optional
requestParams.skip =  null  // 起始查询位 optional
requestParams.limit =  null  // 查询条数 optional
let res = await api.get_suke_query_zl_info(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_suke_query_zl_info_TYPE()
api.get_suke_query_zl_info_RAW_URL()
api.get_suke_query_zl_infoURL(requestParams)
```

## Responses
### Returns instance data

#### Status Code
200



### object not found

#### Status Code
404


#### Response object
* [error](../models/error.md)


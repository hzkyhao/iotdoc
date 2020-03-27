## 查询设备类型信息

查询设备类型信息
### Path
GET /suke/query_devtype_info

### Tags
    - SuKe
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| name | string |  |  [optional]  | 设备类型名称 |
| number | string |  |  [optional]  | 设备类型编码 |
| enable | integer | 1 |  [optional]  | 设备类型状态 9全部,启动:1,废弃:0 |
| skip | integer |  |  [optional]  | 起始查询位 |
| limit | integer |  |  [optional]  | 查询条数 |

*request usage*
```javascript
// 查询设备类型信息
let requestParams = {}
requestParams.name =  null  // 设备类型名称 optional
requestParams.number =  null  // 设备类型编码 optional
requestParams.enable =  null  // 设备类型状态 9全部,启动:1,废弃:0 optional
requestParams.skip =  null  // 起始查询位 optional
requestParams.limit =  null  // 查询条数 optional
let res = await api.get_suke_query_devtype_info(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_suke_query_devtype_info_TYPE()
api.get_suke_query_devtype_info_RAW_URL()
api.get_suke_query_devtype_infoURL(requestParams)
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


## 查询信息

查询信息
### Path
GET /suke/query_info

### Tags
    - SuKe
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| type | string |  |  [required]  | 信息类型 suke_cmd :指令 suke_devtype:设备类型 suke_yys :软件应用商 |
| skip | integer |  |  [optional]  | 起始查询位 |
| limit | integer |  |  [optional]  | 查询条数 |

*request usage*
```javascript
// 查询信息
let requestParams = {}
requestParams.type =  null  // 信息类型 suke_cmd :指令 suke_devtype:设备类型 suke_yys :软件应用商 required
requestParams.skip =  null  // 起始查询位 optional
requestParams.limit =  null  // 查询条数 optional
let res = await api.get_suke_query_info(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_suke_query_info_TYPE()
api.get_suke_query_info_RAW_URL()
api.get_suke_query_infoURL(requestParams)
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


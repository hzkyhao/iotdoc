## 查询设备

查询设备
### Path
GET /suke/query_suke_dev

### Tags
    - SuKe
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| customerId | string |  |  [optional]  | 客户 |
| hardwareType | string |  |  [optional]  | 设备类型 |
| hardware_number | string |  |  [optional]  | 设备编号 |
| status | integer |  |  [optional]  | 使用状况 9全部, 1 在使用,0弃用 |
| ol_status | integer |  |  [optional]  | 在线情况9全部,1在线,0离线 |
| auth | integer |  |  [optional]  | 授权状态 9全部,1已授权, 0未授权 |
| skip | integer |  |  [optional]  | 起始查询位 |
| limit | integer |  |  [optional]  | 查询条数 |

*request usage*
```javascript
// 查询设备
let requestParams = {}
requestParams.customerId =  null  // 客户 optional
requestParams.hardwareType =  null  // 设备类型 optional
requestParams.hardwareNumber =  null  // 设备编号 optional
requestParams.status =  null  // 使用状况 9全部, 1 在使用,0弃用 optional
requestParams.olStatus =  null  // 在线情况9全部,1在线,0离线 optional
requestParams.auth =  null  // 授权状态 9全部,1已授权, 0未授权 optional
requestParams.skip =  null  // 起始查询位 optional
requestParams.limit =  null  // 查询条数 optional
let res = await api.get_suke_query_suke_dev(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_suke_query_suke_dev_TYPE()
api.get_suke_query_suke_dev_RAW_URL()
api.get_suke_query_suke_devURL(requestParams)
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


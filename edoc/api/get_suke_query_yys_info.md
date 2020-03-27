## 查询应用商

查询应用商
### Path
GET /suke/query_yys_info

### Tags
    - SuKe
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| name | string |  |  [optional]  | 应用商名称 |
| id | string |  |  [optional]  | 应用商代号 |
| url | string |  |  [optional]  | 应用商接口地址 |
| para | string |  |  [optional]  | 应用商接口para |
| skip | integer |  |  [optional]  | 起始查询位 |
| limit | integer |  |  [optional]  | 查询条数 |

*request usage*
```javascript
// 查询应用商
let requestParams = {}
requestParams.name =  null  // 应用商名称 optional
requestParams.id =  null  // 应用商代号 optional
requestParams.url =  null  // 应用商接口地址 optional
requestParams.para =  null  // 应用商接口para optional
requestParams.skip =  null  // 起始查询位 optional
requestParams.limit =  null  // 查询条数 optional
let res = await api.get_suke_query_yys_info(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_suke_query_yys_info_TYPE()
api.get_suke_query_yys_info_RAW_URL()
api.get_suke_query_yys_infoURL(requestParams)
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


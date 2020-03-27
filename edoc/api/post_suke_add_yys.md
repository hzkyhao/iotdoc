## 增加运营商

增加应用商
### Path
POST /suke/add_yys

### Tags
    - SuKe
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| name | string |  |  [required]  | 应用商名称 |
| id | string |  |  [required]  | 应用商代号 |
| url | string |  |  [required]  | 应用商接口地址 |
| para | string |  |  [required]  | 应用商接口para |
| status_url | string |  |  [optional]  | 应用商设备状态接口地址 |
| status_para | string |  |  [optional]  | 应用商设备状态接口para |
| default | boolean |  |  [optional]  | 是否是默认供应商 |

*request usage*
```javascript
// 增加运营商
let requestParams = {}
requestParams.name =  null  // 应用商名称 required
requestParams.id =  null  // 应用商代号 required
requestParams.url =  null  // 应用商接口地址 required
requestParams.para =  null  // 应用商接口para required
requestParams.statusUrl =  null  // 应用商设备状态接口地址 optional
requestParams.statusPara =  null  // 应用商设备状态接口para optional
requestParams.default =  null  // 是否是默认供应商 optional
let res = await api.post_suke_add_yys(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_suke_add_yys_TYPE()
api.post_suke_add_yys_RAW_URL()
api.post_suke_add_yysURL(requestParams)
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


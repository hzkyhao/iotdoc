## deploy iot database

部署IOT平台数据库
### Path
GET /iotapp
#### Protected. Auth needed
### Tags
    - License
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| type | string |  |  [optional]  | 产品类型 |
| license | string |  |  [required]  | 授权文件 |

*request usage*
```javascript
// deploy iot database
let requestParams = {}
requestParams.type =  null  // 产品类型 optional
requestParams.license =  null  // 授权文件 required
let res = await api.get_iotapp(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_iotapp_TYPE()
api.get_iotapp_RAW_URL()
api.get_iotappURL(requestParams)
```

## Responses
### Returns operation status

#### Status Code
200



### Bad Request

#### Status Code
400



### Unauthorized

#### Status Code
401



### Forbidden

#### Status Code
403



### Server Internal error

#### Status Code
500




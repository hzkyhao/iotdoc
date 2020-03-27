## start iot hub

启动物联网网关
### Path
GET /iothub
#### Protected. Auth needed
### Tags
    - License
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| type | string |  |  [optional]  | 产品类型 |
| license | string |  |  [required]  | 授权文件 |
| addr | string |  |  [required]  | 数据中心地址 |

*request usage*
```javascript
// start iot hub
let requestParams = {}
requestParams.type =  null  // 产品类型 optional
requestParams.license =  null  // 授权文件 required
requestParams.addr =  null  // 数据中心地址 required
let res = await api.get_iothub(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_iothub_TYPE()
api.get_iothub_RAW_URL()
api.get_iothubURL(requestParams)
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




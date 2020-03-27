## verify SignData

验证签名数据
### Path
GET /verifysigndata

### Tags
    - License
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| ukey | string |  |  [required]  | Ukey |
| data | string |  |  [required]  | 数据 |
| sign | string |  |  [required]  | 签名 |

*request usage*
```javascript
// verify SignData
let requestParams = {}
requestParams.ukey =  null  // Ukey required
requestParams.data =  null  // 数据 required
requestParams.sign =  null  // 签名 required
let res = await api.get_verifysigndata(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_verifysigndata_TYPE()
api.get_verifysigndata_RAW_URL()
api.get_verifysigndataURL(requestParams)
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




## sign Data

数据签名
### Path
GET /signdata

### Tags
    - License
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| data | string |  |  [required]  | 数据 |

*request usage*
```javascript
// sign Data
let requestParams = {}
requestParams.data =  null  // 数据 required
let res = await api.get_signdata(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_signdata_TYPE()
api.get_signdata_RAW_URL()
api.get_signdataURL(requestParams)
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




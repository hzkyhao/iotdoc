## 获取Crond表的权限级别和结构

获取Crond表的权限级别和结构
### Path
GET /schema/Crond

### Tags
    - Crond
### Parameters


*request usage*
```javascript
// 获取Crond表的权限级别和结构
let requestParams = {}
let res = await api.get_schema_crond(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_schema_crond_TYPE()
api.get_schema_crond_RAW_URL()
api.get_schema_crondURL(requestParams)
```

## Responses
### 获取成功

#### Status Code
200



### Bad Request

#### Status Code
400


#### Response object
* [error](../models/error.md)

### Unauthorized

#### Status Code
401


#### Response object
* [error](../models/error.md)

### Forbidden

#### Status Code
403



### Server Internal error

#### Status Code
500


#### Response object
* [error](../models/error.md)


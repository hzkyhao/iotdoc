## 获取会话表的权限级别和结构

获取会话表的权限级别和结构
### Path
GET /schema/_Session

### Tags
    - _Session
### Parameters


*request usage*
```javascript
// 获取会话表的权限级别和结构
let requestParams = {}
let res = await api.get_schema_session(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_schema_session_TYPE()
api.get_schema_session_RAW_URL()
api.get_schema_sessionURL(requestParams)
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


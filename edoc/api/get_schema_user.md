## 获取_User表的权限级别和结构

获取_User表的权限级别和结构
### Path
GET /schema/_User

### Tags
    - _User
### Parameters


*request usage*
```javascript
// 获取_User表的权限级别和结构
let requestParams = {}
let res = await api.get_schema_user(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_schema_user_TYPE()
api.get_schema_user_RAW_URL()
api.get_schema_userURL(requestParams)
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


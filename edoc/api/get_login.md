## 用户登录

用户登录
### Path
GET /login
#### Protected. Auth needed
### Tags
    - User
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| username | string |  |  [required]  |  |
| password | string |  |  [required]  |  |

*request usage*
```javascript
// 用户登录
let requestParams = {}
requestParams.username =  null  //  required
requestParams.password =  null  //  required
let res = await api.get_login(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_login_TYPE()
api.get_login_RAW_URL()
api.get_loginURL(requestParams)
```

## Responses
### Returns success

#### Status Code
200


#### Response object
* [_User](../models/_User.md)

### Bad Request

#### Status Code
400



### Forbidden

#### Status Code
404


#### Response object
* [error](../models/error.md)

### Server Internal error

#### Status Code
500


#### Response object
* [error](../models/error.md)


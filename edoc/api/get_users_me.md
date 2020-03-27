## 检查会话是否有效

检查会话是否有效,用于判断是否登录
### Path
GET /users/me

### Tags
    - User
### Parameters


#### Headers

| Header name |
| ----------- |
| [object Object] |
*request usage*
```javascript
// 检查会话是否有效
let requestParams = {}
requestParams.sessionToken =  null  //  required
let res = await api.get_users_me(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_users_me_TYPE()
api.get_users_me_RAW_URL()
api.get_users_meURL(requestParams)
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




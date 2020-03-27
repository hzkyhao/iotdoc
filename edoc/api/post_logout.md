## 退出登录

退出登录
### Path
POST /logout
#### Protected. Auth needed
### Tags
    - User
### Parameters


#### Headers

| Header name |
| ----------- |
| [object Object] |
*request usage*
```javascript
// 退出登录
let requestParams = {}
requestParams.sessionToken =  null  //  required
let res = await api.post_logout(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_logout_TYPE()
api.post_logout_RAW_URL()
api.post_logoutURL(requestParams)
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




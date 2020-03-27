## 重置密码

重置密码
### Path
POST /requestPasswordReset

### Tags
    - User
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// 重置密码
let requestParams = {}
requestParams.account =  null  // 帐号绑定的邮箱/手机号码,填入绑定的邮箱或手机号 required
let res = await api.post_requestpasswordreset(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_requestpasswordreset_TYPE()
api.post_requestpasswordreset_RAW_URL()
api.post_requestpasswordresetURL(requestParams)
```

## Responses
### Returns success

#### Status Code
201



### Bad Request

#### Status Code
400


#### Response object
* [error](../models/error.md)

### Unauthorized

#### Status Code
401



### Server Internal error

#### Status Code
500




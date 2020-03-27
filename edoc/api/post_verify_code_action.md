## 验证手机号/邮箱是否通过

验证手机号/邮箱是否通过
### Path
POST /verify_code/{Action}
#### Protected. Auth needed
### Tags
    - System
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| Action | string |  |  true  | 验证操作类型 |
*request usage*
```javascript
// 验证手机号/邮箱是否通过
let requestParams = {}
requestParams.action =  null  // 验证操作类型 required
requestParams.account =  null  // 邮箱或手机号 required
requestParams.code =  null  // 验证码 required
requestParams.callback =  null  // 验证成功回调 optional
let res = await api.post_verify_code_action(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_verify_code_action_TYPE()
api.post_verify_code_action_RAW_URL()
api.post_verify_code_actionURL(requestParams)
```

## Responses
### Returns operation status

#### Status Code
200



### Returns operation status

#### Status Code
302



### Bad Request

#### Status Code
400



### Forbidden

#### Status Code
403



### Server Internal error

#### Status Code
500




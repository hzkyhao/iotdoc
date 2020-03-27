## 用户注册

用户注册
### Path
POST /users
#### Protected. Auth needed
### Tags
    - User
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// 用户注册
let requestParams = {}
requestParams.user =  null  // 用户信息 required
let res = await api.post_users(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_users_TYPE()
api.post_users_RAW_URL()
api.post_usersURL(requestParams)
```

## Responses
### Returns success

#### Status Code
201


#### Response object
| Name | Type | Format | Example | Description |
| ---- | ---- | ------ | ------- | ----------- |
| createdAt | string |  date-time  |  | 创建时间 |
| nick | string |  -  |  | 昵称 |
| objectId | string |  -  |  | 用户ID |

### Bad Request

#### Status Code
400



### Forbidden

#### Status Code
403



### Server Internal error

#### Status Code
500




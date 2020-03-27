## 获取用户信息

获取用户信息
### Path
GET /users/{id}

### Tags
    - User
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | 获取用户信息 |
*request usage*
```javascript
// 获取用户信息
let requestParams = {}
requestParams.id =  null  // 获取用户信息 required
let res = await api.get_users_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_users_id_TYPE()
api.get_users_id_RAW_URL()
api.get_users_idURL(requestParams)
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



### Unauthorized

#### Status Code
401



### Forbidden

#### Status Code
403



### Server Internal error

#### Status Code
500




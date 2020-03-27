## 获取调用API凭证

登录开发者中心，获取为企业分配的访问平台API的账号与秘钥
### Path
GET /get_token
#### Protected. Auth needed
### Tags
    - User
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| appid | string |  |  [required]  | 管理后台分配appid |
| secret | string |  |  [required]  | 管理后台配置 |

*request usage*
```javascript
// 获取调用API凭证
let requestParams = {}
requestParams.appid =  null  // 管理后台分配appid required
requestParams.secret =  null  // 管理后台配置 required
let res = await api.get_token(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_token_TYPE()
api.get_token_RAW_URL()
api.get_tokenURL(requestParams)
```

## Responses
### Returns success

#### Status Code
200


#### Response object
| Name | Type | Format | Example | Description |
| ---- | ---- | ------ | ------- | ----------- |
| createdAt | string |  date-time  |  | 创建时间 |
| sessionToken | string |  -  |  | 调用api凭证 |

### Bad Request

#### Status Code
400



### object not found

#### Status Code
404


#### Response object
* [error](../models/error.md)

### Server Internal error

#### Status Code
500




## 发送短信验证码

发送短信,短信验证码发送成功后,则会在缓存中以mobile为键写入, 用户下一步提交时，可以根据此键查询验证通过
### Path
POST /sendsms
#### Protected. Auth needed
### Tags
    - System
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| nationcode | string |  |  [required]  | 国家/地区 |
| account | string |  |  [required]  | 大陆手机号码 |

*request usage*
```javascript
// 发送短信验证码
let requestParams = {}
requestParams.nationcode =  null  // 国家/地区 required
requestParams.account =  null  // 大陆手机号码 required
let res = await api.post_sendsms(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_sendsms_TYPE()
api.post_sendsms_RAW_URL()
api.post_sendsmsURL(requestParams)
```

## Responses
### Returns operation status

#### Status Code
200


#### Response object
| Name | Type | Format | Example | Description |
| ---- | ---- | ------ | ------- | ----------- |
| expire | number |  -  |  |  |

### Bad Request

#### Status Code
400



### Forbidden

#### Status Code
403



### Server Internal error

#### Status Code
500




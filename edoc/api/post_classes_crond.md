## 新增Crond

新增一条Crond记录
### Path
POST /classes/Crond

### Tags
    - Crond
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// 新增Crond
let requestParams = {}
requestParams.body =  null  // 新增的字段 required
let res = await api.post_classes_crond(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_classes_crond_TYPE()
api.post_classes_crond_RAW_URL()
api.post_classes_crondURL(requestParams)
```

## Responses
### Returns success

#### Status Code
201


#### Response object
| Name | Type | Format | Example | Description |
| ---- | ---- | ------ | ------- | ----------- |
| createdAt | string |  date-time  |  | 创建时间 |
| objectId | string |  -  |  | objectId |

### Bad Request

#### Status Code
400



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


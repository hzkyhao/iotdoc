## 获取会话详情

根据ID获取会话详情
### Path
GET /classes/_Session/{id}

### Tags
    - _Session
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | 会话的ID |
*request usage*
```javascript
// 获取会话详情
let requestParams = {}
requestParams.id =  null  // 会话的ID required
let res = await api.get_classes_session_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_classes_session_id_TYPE()
api.get_classes_session_id_RAW_URL()
api.get_classes_session_idURL(requestParams)
```

## Responses
### 返回会话数据

#### Status Code
200


#### Response object
* [_Session](../models/_Session.md)

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



### object not found

#### Status Code
404


#### Response object
* [error](../models/error.md)

### Server Internal error

#### Status Code
500


#### Response object
* [error](../models/error.md)


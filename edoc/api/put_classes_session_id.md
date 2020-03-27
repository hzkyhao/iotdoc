## 更新会话

通过ID更新会话
### Path
PUT /classes/_Session/{id}

### Tags
    - _Session
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | 更新会话的ID |
*request usage*
```javascript
// 更新会话
let requestParams = {}
requestParams.id =  null  // 更新会话的ID required
requestParams.body =  null  // 数据更新的内容. required
let res = await api.put_classes_session_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.put_classes_session_id_TYPE()
api.put_classes_session_id_RAW_URL()
api.put_classes_session_idURL(requestParams)
```

## Responses
### 更新成功

#### Status Code
200


#### Response object
| Name | Type | Format | Example | Description |
| ---- | ---- | ------ | ------- | ----------- |
| objectId | string |  -  |  | objectId |
| updatedAt | string |  date-time  |  | 更新时间 |

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


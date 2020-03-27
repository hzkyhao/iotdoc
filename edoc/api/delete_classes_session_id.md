## 删除会话

通过ID删除会话记录
### Path
DELETE /classes/_Session/{id}

### Tags
    - _Session
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | 删除会话的ID |
*request usage*
```javascript
// 删除会话
let requestParams = {}
requestParams.id =  null  // 删除会话的ID required
let res = await api.delete_classes_session_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.delete_classes_session_id_TYPE()
api.delete_classes_session_id_RAW_URL()
api.delete_classes_session_idURL(requestParams)
```

## Responses
### Returns a confirmation message

#### Status Code
200



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


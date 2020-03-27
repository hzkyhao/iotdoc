## 获取_User详情

根据ID获取_User详情
### Path
GET /classes/_User/{id}

### Tags
    - _User
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | _User的ID |
*request usage*
```javascript
// 获取_User详情
let requestParams = {}
requestParams.id =  null  // _User的ID required
let res = await api.get_classes_user_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_classes_user_id_TYPE()
api.get_classes_user_id_RAW_URL()
api.get_classes_user_idURL(requestParams)
```

## Responses
### 返回_User数据

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


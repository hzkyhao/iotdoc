## 获取角色详情

根据ID获取角色详情
### Path
GET /classes/_Role/{id}

### Tags
    - _Role
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | 角色的ID |
*request usage*
```javascript
// 获取角色详情
let requestParams = {}
requestParams.id =  null  // 角色的ID required
let res = await api.get_classes_role_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_classes_role_id_TYPE()
api.get_classes_role_id_RAW_URL()
api.get_classes_role_idURL(requestParams)
```

## Responses
### 返回角色数据

#### Status Code
200


#### Response object
* [_Role](../models/_Role.md)

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


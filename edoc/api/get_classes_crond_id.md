## 获取Crond详情

根据ID获取Crond详情
### Path
GET /classes/Crond/{id}

### Tags
    - Crond
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | Crond的ID |
*request usage*
```javascript
// 获取Crond详情
let requestParams = {}
requestParams.id =  null  // Crond的ID required
let res = await api.get_classes_crond_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_classes_crond_id_TYPE()
api.get_classes_crond_id_RAW_URL()
api.get_classes_crond_idURL(requestParams)
```

## Responses
### 返回Crond数据

#### Status Code
200


#### Response object
* [Crond](../models/Crond.md)

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


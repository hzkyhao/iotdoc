## 获取应用详情

根据ID获取应用详情
### Path
GET /classes/App/{id}

### Tags
    - App
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | 应用的ID |
*request usage*
```javascript
// 获取应用详情
let requestParams = {}
requestParams.id =  null  // 应用的ID required
let res = await api.get_classes_app_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_classes_app_id_TYPE()
api.get_classes_app_id_RAW_URL()
api.get_classes_app_idURL(requestParams)
```

## Responses
### 返回应用数据

#### Status Code
200


#### Response object
* [App](../models/App.md)

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


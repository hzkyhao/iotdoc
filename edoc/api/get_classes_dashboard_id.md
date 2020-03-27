## 获取Dashboard详情

根据ID获取Dashboard详情
### Path
GET /classes/Dashboard/{id}

### Tags
    - Dashboard
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | Dashboard的ID |
*request usage*
```javascript
// 获取Dashboard详情
let requestParams = {}
requestParams.id =  null  // Dashboard的ID required
let res = await api.get_classes_dashboard_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_classes_dashboard_id_TYPE()
api.get_classes_dashboard_id_RAW_URL()
api.get_classes_dashboard_idURL(requestParams)
```

## Responses
### 返回Dashboard数据

#### Status Code
200


#### Response object
* [Dashboard](../models/Dashboard.md)

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


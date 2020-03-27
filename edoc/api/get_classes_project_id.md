## 获取Project详情

根据ID获取Project详情
### Path
GET /classes/Project/{id}

### Tags
    - Project
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | Project的ID |
*request usage*
```javascript
// 获取Project详情
let requestParams = {}
requestParams.id =  null  // Project的ID required
let res = await api.get_classes_project_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_classes_project_id_TYPE()
api.get_classes_project_id_RAW_URL()
api.get_classes_project_idURL(requestParams)
```

## Responses
### 返回Project数据

#### Status Code
200


#### Response object
* [Project](../models/Project.md)

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


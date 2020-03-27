## 新增部门

新增一条部门记录
### Path
POST /classes/Department

### Tags
    - Department
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// 新增部门
let requestParams = {}
requestParams.body =  null  // 新增的字段 required
let res = await api.post_classes_department(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_classes_department_TYPE()
api.post_classes_department_RAW_URL()
api.post_classes_departmentURL(requestParams)
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


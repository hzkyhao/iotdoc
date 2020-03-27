## 获取SukeDev详情

根据ID获取SukeDev详情
### Path
GET /classes/SukeDev/{id}

### Tags
    - SukeDev
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | SukeDev的ID |
*request usage*
```javascript
// 获取SukeDev详情
let requestParams = {}
requestParams.id =  null  // SukeDev的ID required
let res = await api.get_classes_sukedev_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_classes_sukedev_id_TYPE()
api.get_classes_sukedev_id_RAW_URL()
api.get_classes_sukedev_idURL(requestParams)
```

## Responses
### 返回SukeDev数据

#### Status Code
200


#### Response object
* [SukeDev](../models/SukeDev.md)

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


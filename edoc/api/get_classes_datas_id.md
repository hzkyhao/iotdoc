## 获取数据字典详情

根据ID获取数据字典详情
### Path
GET /classes/Datas/{id}

### Tags
    - Datas
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | 数据字典的ID |
*request usage*
```javascript
// 获取数据字典详情
let requestParams = {}
requestParams.id =  null  // 数据字典的ID required
let res = await api.get_classes_datas_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_classes_datas_id_TYPE()
api.get_classes_datas_id_RAW_URL()
api.get_classes_datas_idURL(requestParams)
```

## Responses
### 返回数据字典数据

#### Status Code
200


#### Response object
* [Datas](../models/Datas.md)

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


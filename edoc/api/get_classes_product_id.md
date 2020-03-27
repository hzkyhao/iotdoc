## 获取产品详情

根据ID获取产品详情
### Path
GET /classes/Product/{id}

### Tags
    - Product
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | 产品的ID |
*request usage*
```javascript
// 获取产品详情
let requestParams = {}
requestParams.id =  null  // 产品的ID required
let res = await api.get_classes_product_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_classes_product_id_TYPE()
api.get_classes_product_id_RAW_URL()
api.get_classes_product_idURL(requestParams)
```

## Responses
### 返回产品数据

#### Status Code
200


#### Response object
* [Product](../models/Product.md)

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


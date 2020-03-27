## 获取菜单详情

根据ID获取菜单详情
### Path
GET /classes/Menu/{id}

### Tags
    - Menu
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | 菜单的ID |
*request usage*
```javascript
// 获取菜单详情
let requestParams = {}
requestParams.id =  null  // 菜单的ID required
let res = await api.get_classes_menu_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_classes_menu_id_TYPE()
api.get_classes_menu_id_RAW_URL()
api.get_classes_menu_idURL(requestParams)
```

## Responses
### 返回菜单数据

#### Status Code
200


#### Response object
* [Menu](../models/Menu.md)

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


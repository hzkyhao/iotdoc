## 获取应用信息

获取应用信息
### Path
GET /classes/Site/{Id}
#### Protected. Auth needed
### Tags
    - Project
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| Id | string |  |  true  | 应用标识 |
*request usage*
```javascript
// 获取应用信息
let requestParams = {}
requestParams.id =  null  // 应用标识 required
let res = await api.get_classes_site_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_classes_site_id_TYPE()
api.get_classes_site_id_RAW_URL()
api.get_classes_site_idURL(requestParams)
```

## Responses
### Returns operation status

#### Status Code
200



### Bad Request

#### Status Code
400



### Unauthorized

#### Status Code
401



### Forbidden

#### Status Code
403



### Server Internal error

#### Status Code
500




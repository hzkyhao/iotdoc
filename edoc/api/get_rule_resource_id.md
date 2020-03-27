## 根据资源ID获取资源

根据资源ID获取资源
### Path
GET /rule_resource/{id}
#### Protected. Auth needed
### Tags
    - Rule
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | 资源ID |
*request usage*
```javascript
// 根据资源ID获取资源
let requestParams = {}
requestParams.id =  null  // 资源ID required
let res = await api.get_rule_resource_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_rule_resource_id_TYPE()
api.get_rule_resource_id_RAW_URL()
api.get_rule_resource_idURL(requestParams)
```

## Responses
### Returns operation status

#### Status Code
200


#### Response object
* [Resource](../models/Resource.md)

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




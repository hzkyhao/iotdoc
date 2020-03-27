## 删除规则引擎

删除规则引擎
### Path
DELETE /rule/{id}
#### Protected. Auth needed
### Tags
    - Rule
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | 规则引擎名称 |
*request usage*
```javascript
// 删除规则引擎
let requestParams = {}
requestParams.id =  null  // 规则引擎名称 required
let res = await api.delete_rule_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.delete_rule_id_TYPE()
api.delete_rule_id_RAW_URL()
api.delete_rule_idURL(requestParams)
```

## Responses
### Returns operation status

#### Status Code
200


#### Response object
| Name | Type | Format | Example | Description |
| ---- | ---- | ------ | ------- | ----------- |
| code | number |  -  |  |  |
| data | array |  -  |  |  |

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




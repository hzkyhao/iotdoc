## 获取规则引擎列表

获取规则引擎列表
### Path
GET /rules
#### Protected. Auth needed
### Tags
    - Rule
### Parameters


*request usage*
```javascript
// 获取规则引擎列表
let requestParams = {}
let res = await api.get_rules(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_rules_TYPE()
api.get_rules_RAW_URL()
api.get_rulesURL(requestParams)
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




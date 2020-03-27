## 获取动作列表

获取动作列表
### Path
GET /rule_actions
#### Protected. Auth needed
### Tags
    - Rule
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| name | string |  |  [optional]  | 动作名称 |

*request usage*
```javascript
// 获取动作列表
let requestParams = {}
requestParams.name =  null  // 动作名称 optional
let res = await api.get_rule_actions(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_rule_actions_TYPE()
api.get_rule_actions_RAW_URL()
api.get_rule_actionsURL(requestParams)
```

## Responses
### Returns operation status

#### Status Code
200


#### Response object

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




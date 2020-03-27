## 获取资源列表

获取资源列表
### Path
GET /rule_resource
#### Protected. Auth needed
### Tags
    - Rule
### Parameters


*request usage*
```javascript
// 获取资源列表
let requestParams = {}
let res = await api.get_rule_resource(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_rule_resource_TYPE()
api.get_rule_resource_RAW_URL()
api.get_rule_resourceURL(requestParams)
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




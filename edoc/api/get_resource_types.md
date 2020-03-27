## 获取资源类型列表

获取资源类型列表
### Path
GET /resource_types
#### Protected. Auth needed
### Tags
    - Rule
### Parameters


*request usage*
```javascript
// 获取资源类型列表
let requestParams = {}
let res = await api.get_resource_types(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_resource_types_TYPE()
api.get_resource_types_RAW_URL()
api.get_resource_typesURL(requestParams)
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




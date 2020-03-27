## 获取插件

获取插件
### Path
GET /plugin

### Tags
    - System
### Parameters


*request usage*
```javascript
// 获取插件
let requestParams = {}
let res = await api.get_plugin(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_plugin_TYPE()
api.get_plugin_RAW_URL()
api.get_pluginURL(requestParams)
```

## Responses
### Returns operation status

#### Status Code
201



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




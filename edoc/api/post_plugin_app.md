## 对插件启动/停止/热更新/获取

对插件启动/停止/热更新/获取
### Path
POST /plugin/{App}

### Tags
    - System
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| App | string |  |  true  | 插件名 |
*request usage*
```javascript
// 对插件启动/停止/热更新/获取
let requestParams = {}
requestParams.app =  null  // 插件名 required
requestParams.action =  null  // 启动/停止/热更新/获取 required
let res = await api.post_plugin_app(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_plugin_app_TYPE()
api.post_plugin_app_RAW_URL()
api.post_plugin_appURL(requestParams)
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




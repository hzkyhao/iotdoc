## 获取日志配置

获取日志配置
### Path
GET /log/level

### Tags
    - System
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| Handle | string |  |  [required]  | 日志模块 |
| level | string |  |  [required]  | 日志级别 |

*request usage*
```javascript
// 获取日志配置
let requestParams = {}
requestParams.handle =  null  // 日志模块 required
requestParams.level =  null  // 日志级别 required
let res = await api.get_log_level(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_log_level_TYPE()
api.get_log_level_RAW_URL()
api.get_log_levelURL(requestParams)
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




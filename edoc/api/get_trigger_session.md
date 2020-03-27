## 获取会话表触发器

获取会话表触发器
### Path
GET /trigger/_Session

### Tags
    - _Session
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| triggerName | string |  |  [required]  | 触发器名 |

*request usage*
```javascript
// 获取会话表触发器
let requestParams = {}
requestParams.triggerName =  null  // 触发器名 required
let res = await api.get_trigger_session(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_trigger_session_TYPE()
api.get_trigger_session_RAW_URL()
api.get_trigger_sessionURL(requestParams)
```

## Responses
### Returns success

#### Status Code
200



### Bad Request

#### Status Code
400



### object not found

#### Status Code
404


#### Response object
* [error](../models/error.md)

### Server Internal error

#### Status Code
500




## 获取SukeLog表触发器

获取SukeLog表触发器
### Path
GET /trigger/SukeLog

### Tags
    - SukeLog
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| triggerName | string |  |  [required]  | 触发器名 |

*request usage*
```javascript
// 获取SukeLog表触发器
let requestParams = {}
requestParams.triggerName =  null  // 触发器名 required
let res = await api.get_trigger_sukelog(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_trigger_sukelog_TYPE()
api.get_trigger_sukelog_RAW_URL()
api.get_trigger_sukelogURL(requestParams)
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




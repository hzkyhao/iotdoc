## 删除/编辑SukeLog表触发器

删除/编辑SukeLog表触发器,用于数据同步
### Path
PUT /trigger/SukeLog

### Tags
    - SukeLog
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| triggerName | string |  |  [required]  | 触发器名 |

*request usage*
```javascript
// 删除/编辑SukeLog表触发器
let requestParams = {}
requestParams.triggerName =  null  // 触发器名 required
requestParams.op =  null  // 删除时,body为{"__op":"Delete"},编辑时,body为{"url":"http://example.com/trigger"} required
let res = await api.put_trigger_sukelog(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.put_trigger_sukelog_TYPE()
api.put_trigger_sukelog_RAW_URL()
api.put_trigger_sukelogURL(requestParams)
```

## Responses
### Returns success

#### Status Code
201



### Bad Request

#### Status Code
400



### Unauthorized

#### Status Code
401



### Server Internal error

#### Status Code
500




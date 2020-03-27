## 删除/编辑_User表触发器

删除/编辑_User表触发器,用于数据同步
### Path
PUT /trigger/_User

### Tags
    - _User
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| triggerName | string |  |  [required]  | 触发器名 |

*request usage*
```javascript
// 删除/编辑_User表触发器
let requestParams = {}
requestParams.triggerName =  null  // 触发器名 required
requestParams.op =  null  // 删除时,body为{"__op":"Delete"},编辑时,body为{"url":"http://example.com/trigger"} required
let res = await api.put_trigger_user(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.put_trigger_user_TYPE()
api.put_trigger_user_RAW_URL()
api.put_trigger_userURL(requestParams)
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




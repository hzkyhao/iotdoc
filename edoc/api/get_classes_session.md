## 查询会话

参考parse文档 https://docs.parseplatform.org/rest/guide/#queries,<br/><br/>where支持：[$lt, $lte, $gt, $gte, $ne, $in, $nin, $exists, $select, $dontSelect, $all, $regex, $text]
### Path
GET /classes/_Session

### Tags
    - _Session
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| order | string | createdAt |  [optional]  | 排序方式, 负为降序, eg: score,-name |
| limit | integer | 10 |  [optional]  | limit, 显示多少条记录，显示100条记录 eg:100 |
| skip | integer | 0 |  [optional]  | skip |
| keys | string |  |  [optional]  | 需要显示的字段,加count(*)则结果里面会显示总记录数, eg: username,email |
| include | string |  |  [optional]  | include |
| where | string |  |  [optional]  | 过滤条件，eg: {"objectId":{"$in":["BGS3BFgcZN"]}} |

*request usage*
```javascript
// 查询会话
let requestParams = {}
requestParams.order =  null  // 排序方式, 负为降序, eg: score,-name optional
requestParams.limit =  null  // limit, 显示多少条记录，显示100条记录 eg:100 optional
requestParams.skip =  null  // skip optional
requestParams.keys =  null  // 需要显示的字段,加count(*)则结果里面会显示总记录数, eg: username,email optional
requestParams.include =  null  // include optional
requestParams.where =  null  // 过滤条件，eg: {"objectId":{"$in":["BGS3BFgcZN"]}} optional
let res = await api.get_classes_session(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_classes_session_TYPE()
api.get_classes_session_RAW_URL()
api.get_classes_sessionURL(requestParams)
```

## Responses
### 返回会话记录数

#### Status Code
200


#### Response object
| Name | Type | Format | Example | Description |
| ---- | ---- | ------ | ------- | ----------- |
| results | array |  -  |  |  |

### Bad Request

#### Status Code
400



### Unauthorized

#### Status Code
401


#### Response object
* [error](../models/error.md)

### Forbidden

#### Status Code
403



### Server Internal error

#### Status Code
500


#### Response object
* [error](../models/error.md)


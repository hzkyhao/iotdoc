## 统计获取

调用Grafanfa查询曲线
### Path
GET /chart/{version}
#### Protected. Auth needed
### Tags
    - System
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| version | string |  |  true  | 版本号,默认为v1 |
*request usage*
```javascript
// 统计获取
let requestParams = {}
requestParams.version =  null  // 版本号,默认为v1 required
requestParams.query =  null  // 查询语句 required
requestParams.start =  null  // 开始时间 required
requestParams.end =  null  // 结束时间 required
requestParams.step =  null  // 步长,单位秒 required
let res = await api.get_chart_version(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_chart_version_TYPE()
api.get_chart_version_RAW_URL()
api.get_chart_versionURL(requestParams)
```

## Responses
### Returns operation status

#### Status Code
200


#### Response object
| Name | Type | Format | Example | Description |
| ---- | ---- | ------ | ------- | ----------- |
| data | object |  -  |  |  |
| status | string |  -  |  |  |

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




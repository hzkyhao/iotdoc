## 获取顶部导航

查询顶部导航菜单
### Path
GET /classes/Navigation

### Tags
    - Menu
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| order | string |  |  [optional]  | 排序方式 |
| limit | number |  |  [optional]  | 显示数量 |

*request usage*
```javascript
// 获取顶部导航
let requestParams = {}
requestParams.order =  null  // 排序方式 optional
requestParams.limit =  null  // 显示数量 optional
let res = await api.get_classes_navigation(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_classes_navigation_TYPE()
api.get_classes_navigation_RAW_URL()
api.get_classes_navigationURL(requestParams)
```

## Responses
### Returns operation status

#### Status Code
200



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




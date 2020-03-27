## 根据swagger产生API代码

根据swagger产生API代码
### Path
POST /generate_api/{type}

### Tags
    - System
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| type | string |  |  true  | 编译出对应的代码模块 |
*request usage*
```javascript
// 根据swagger产生API代码
let requestParams = {}
requestParams.mod =  null  // 模块名 required
requestParams.swagger =  null  // swagger描述 required
let res = await api.generate_api(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.generate_api_TYPE()
api.generate_api_RAW_URL()
api.generate_apiURL(requestParams)
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




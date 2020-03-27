## 云函数

云函数
### Path
POST /functions/{func}

### Tags
    - DB
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| func | string |  |  true  | 函数名称 |
*request usage*
```javascript
// 云函数
let requestParams = {}
requestParams.func =  null  // 函数名称 required
requestParams.func =  null  // 提交内容 required
let res = await api.post_functions_func(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_functions_func_TYPE()
api.post_functions_func_RAW_URL()
api.post_functions_funcURL(requestParams)
```

## Responses
### Returns success

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




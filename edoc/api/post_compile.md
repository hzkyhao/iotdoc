## 编译代码

在线编译代码
### Path
POST /compile

### Tags
    - System
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// 编译代码
let requestParams = {}
requestParams.body =  null  // 在线编译代码 required
let res = await api.post_compile(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_compile_TYPE()
api.post_compile_RAW_URL()
api.post_compileURL(requestParams)
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




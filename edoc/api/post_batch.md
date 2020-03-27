## 数据批处理

为了减少网络往返的时间，可以使用批处理端点在一次调用中创建、更新或删除多达50个对象。
### Path
POST /batch

### Tags
    - DB
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// 数据批处理
let requestParams = {}
requestParams.batch =  null  // 批处理 required
let res = await api.post_batch(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_batch_TYPE()
api.post_batch_RAW_URL()
api.post_batchURL(requestParams)
```

## Responses
### Returns success

#### Status Code
200



### Bad Request

#### Status Code
400


#### Response object
* [error](../models/error.md)

### Unauthorized

#### Status Code
401



### Forbidden

#### Status Code
403



### Server Internal error

#### Status Code
500




## 更新配置

更新配置，如果配置值为 "__op": "Delete"，则为删除, 例： {"params":{"test":{"__op":"Delete"}}}
### Path
PUT /config

### Tags
    - DB
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// 更新配置
let requestParams = {}
requestParams.config =  null  // 更新配置 required
let res = await api.put_config(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.put_config_TYPE()
api.put_config_RAW_URL()
api.put_configURL(requestParams)
```

## Responses
### Returns success

#### Status Code
201



### Bad Request

#### Status Code
400


#### Response object
* [error](../models/error.md)

### Unauthorized

#### Status Code
401


#### Response object
* [error](../models/error.md)

### Forbidden

#### Status Code
403


#### Response object
* [error](../models/error.md)

### Server Internal error

#### Status Code
500




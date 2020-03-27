## 获取通道详情

根据ID获取通道详情
### Path
GET /classes/Channel/{id}

### Tags
    - Channel
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | 通道的ID |
*request usage*
```javascript
// 获取通道详情
let requestParams = {}
requestParams.id =  null  // 通道的ID required
let res = await api.get_classes_channel_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_classes_channel_id_TYPE()
api.get_classes_channel_id_RAW_URL()
api.get_classes_channel_idURL(requestParams)
```

## Responses
### 返回通道数据

#### Status Code
200


#### Response object
* [Channel](../models/Channel.md)

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



### object not found

#### Status Code
404


#### Response object
* [error](../models/error.md)

### Server Internal error

#### Status Code
500


#### Response object
* [error](../models/error.md)


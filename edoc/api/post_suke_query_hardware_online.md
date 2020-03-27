## 查询设备在线状态

查询设备在线状态
### Path
POST /suke/query_hardware_online

### Tags
    - SuKe
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// 查询设备在线状态
let requestParams = {}
requestParams.body =  null  // 查询设备在线状态 required
let res = await api.post_suke_query_hardware_online(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_suke_query_hardware_online_TYPE()
api.post_suke_query_hardware_online_RAW_URL()
api.post_suke_query_hardware_onlineURL(requestParams)
```

## Responses
### Returns instance data

#### Status Code
200



### object not found

#### Status Code
404


#### Response object
* [error](../models/error.md)


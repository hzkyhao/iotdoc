## 获取设备当前状态

设备查询
### Path
GET /dev/{addr}

### Tags
    - Devices
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| addr | string |  |  true  | 设备地址 |
*request usage*
```javascript
// 获取设备当前状态
let requestParams = {}
requestParams.addr =  null  // 设备地址 required
requestParams.productId =  null  // 设备类型 required
let res = await api.get_dev_addr(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_dev_addr_TYPE()
api.get_dev_addr_RAW_URL()
api.get_dev_addrURL(requestParams)
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


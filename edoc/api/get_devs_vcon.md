## 查询设备列表

根据网关查询设备列表
### Path
GET /devs/{vcon}

### Tags
    - Devices
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| vcon | string |  |  true  | 网关地址 |
*request usage*
```javascript
// 查询设备列表
let requestParams = {}
requestParams.vcon =  null  // 网关地址 required
requestParams.devType =  null  // 设备类型 required
requestParams.nodeType =  null  // 设备:devs | 网关:vcons required
requestParams.start =  null  // 起始行数 required
requestParams.length =  null  // 从起始开始查找几条 required
requestParams.keyword =  null  // 模糊条件查找 optional
let res = await api.get_devs_vcon(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_devs_vcon_TYPE()
api.get_devs_vcon_RAW_URL()
api.get_devs_vconURL(requestParams)
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


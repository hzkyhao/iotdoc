## 查询设备列表

查询设备列表
### Path
GET /devs

### Tags
    - Devices
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| devType | string |  |  [required]  | 设备类型 |
| nodeType | string |  |  [required]  | 设备:devs | 网关/集中器:vcons |
| start | number |  |  [required]  | 起始行数 |
| length | number |  |  [required]  | 从起始开始查找几条 |
| keyword | string |  |  [optional]  | 模糊条件查找 |

*request usage*
```javascript
// 查询设备列表
let requestParams = {}
requestParams.devType =  null  // 设备类型 required
requestParams.nodeType =  null  // 设备:devs | 网关/集中器:vcons required
requestParams.start =  null  // 起始行数 required
requestParams.length =  null  // 从起始开始查找几条 required
requestParams.keyword =  null  // 模糊条件查找 optional
let res = await api.get_devs(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_devs_TYPE()
api.get_devs_RAW_URL()
api.get_devsURL(requestParams)
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


## 增加设备类型

增加设备类型
### Path
POST /suke/add_devtype

### Tags
    - SuKe
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| name | string |  |  [required]  | 设备类型名称 |
| number | string |  |  [required]  | 设备类型编码 |
| remark | string |  |  [optional]  | 备注 |
| enable | integer | 1 |  [required]  | 设备类型状态 启动:1,废弃:0 |

*request usage*
```javascript
// 增加设备类型
let requestParams = {}
requestParams.name =  null  // 设备类型名称 required
requestParams.number =  null  // 设备类型编码 required
requestParams.remark =  null  // 备注 optional
requestParams.enable =  null  // 设备类型状态 启动:1,废弃:0 required
let res = await api.post_suke_add_devtype(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_suke_add_devtype_TYPE()
api.post_suke_add_devtype_RAW_URL()
api.post_suke_add_devtypeURL(requestParams)
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


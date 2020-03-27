## 编辑设备类型

编辑设备类型
### Path
PUT /suke/edit_devtype

### Tags
    - SuKe
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| objectId | string |  |  [required]  | 设备类型id |
| name | string |  |  [required]  | 设备类型名称 |
| number | string |  |  [required]  | 设备类型编码 |
| remark | string |  |  [optional]  | 备注 |
| enable | integer | 1 |  [required]  | 设备类型状态 启动:1,废弃:0 |

*request usage*
```javascript
// 编辑设备类型
let requestParams = {}
requestParams.objectId =  null  // 设备类型id required
requestParams.name =  null  // 设备类型名称 required
requestParams.number =  null  // 设备类型编码 required
requestParams.remark =  null  // 备注 optional
requestParams.enable =  null  // 设备类型状态 启动:1,废弃:0 required
let res = await api.put_suke_edit_devtype(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.put_suke_edit_devtype_TYPE()
api.put_suke_edit_devtype_RAW_URL()
api.put_suke_edit_devtypeURL(requestParams)
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


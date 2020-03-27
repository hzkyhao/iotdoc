## 编辑指令

编辑指令
### Path
PUT /suke/edit_zl

### Tags
    - SuKe
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| objectId | string |  |  [required]  | 指令id |
| hardwareType | string |  |  [required]  | 设备类型 |
| name | string |  |  [required]  | 指令 |
| nameEncrypt | string |  |  [required]  | 加密指令 |
| needReply | integer |  |  [required]  | 指令回复类型 不需要回复 0  需要回复 1 |
| remark | string |  |  [optional]  | 备注 |
| enable | integer | 1 |  [required]  | 指令状态 启动:1,废弃:0 |

*request usage*
```javascript
// 编辑指令
let requestParams = {}
requestParams.objectId =  null  // 指令id required
requestParams.hardwareType =  null  // 设备类型 required
requestParams.name =  null  // 指令 required
requestParams.nameEncrypt =  null  // 加密指令 required
requestParams.needReply =  null  // 指令回复类型 不需要回复 0  需要回复 1 required
requestParams.remark =  null  // 备注 optional
requestParams.enable =  null  // 指令状态 启动:1,废弃:0 required
let res = await api.put_suke_edit_zl(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.put_suke_edit_zl_TYPE()
api.put_suke_edit_zl_RAW_URL()
api.put_suke_edit_zlURL(requestParams)
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


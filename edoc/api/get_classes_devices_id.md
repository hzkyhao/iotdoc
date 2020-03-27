## 获取设备管理详情

根据ID获取设备管理详情
### Path
GET /classes/Devices/{id}

### Tags
    - Devices
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | 设备管理的ID |
*request usage*
```javascript
// 获取设备管理详情
let requestParams = {}
requestParams.id =  null  // 设备管理的ID required
let res = await api.get_classes_devices_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_classes_devices_id_TYPE()
api.get_classes_devices_id_RAW_URL()
api.get_classes_devices_idURL(requestParams)
```

## Responses
### 返回设备管理数据

#### Status Code
200


#### Response object
* [Devices](../models/Devices.md)

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


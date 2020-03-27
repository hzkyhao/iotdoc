## 删除设备管理

通过ID删除设备管理记录
### Path
DELETE /classes/Devices/{id}

### Tags
    - Devices
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | 删除设备管理的ID |
*request usage*
```javascript
// 删除设备管理
let requestParams = {}
requestParams.id =  null  // 删除设备管理的ID required
let res = await api.delete_classes_devices_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.delete_classes_devices_id_TYPE()
api.delete_classes_devices_id_RAW_URL()
api.delete_classes_devices_idURL(requestParams)
```

## Responses
### Returns a confirmation message

#### Status Code
200



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


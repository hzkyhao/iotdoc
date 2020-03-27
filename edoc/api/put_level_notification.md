## 设置通知表级别

设置通知表的级别
### Path
PUT /level/Notification

### Tags
    - Notification
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// 设置通知表级别
let requestParams = {}
requestParams.permissions =  null  // 表操作权限. required
let res = await api.put_level_notification(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.put_level_notification_TYPE()
api.put_level_notification_RAW_URL()
api.put_level_notificationURL(requestParams)
```

## Responses
### 设置通知表成功

#### Status Code
200



### object not found

#### Status Code
400


#### Response object
* [error](../models/error.md)

### Unauthorized

#### Status Code
401


#### Response object
* [error](../models/error.md)

### Forbidden

#### Status Code
403



### Server Internal error

#### Status Code
500


#### Response object
* [error](../models/error.md)


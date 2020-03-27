## 删除通知

通过ID删除通知记录
### Path
DELETE /classes/Notification/{id}

### Tags
    - Notification
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  true  | 删除通知的ID |
*request usage*
```javascript
// 删除通知
let requestParams = {}
requestParams.id =  null  // 删除通知的ID required
let res = await api.delete_classes_notification_id(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.delete_classes_notification_id_TYPE()
api.delete_classes_notification_id_RAW_URL()
api.delete_classes_notification_idURL(requestParams)
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


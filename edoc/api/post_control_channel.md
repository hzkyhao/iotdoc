## 更新通道

通道控制
### Path
POST /control/channel
#### Protected. Auth needed
### Tags
    - Channel
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| id | string |  |  [required]  | 通道ID |
| action | string |  |  [required]  | 更新通道 |

*request usage*
```javascript
// 更新通道
let requestParams = {}
requestParams.id =  null  // 通道ID required
requestParams.action =  null  // 更新通道 required
let res = await api.post_control_channel(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_control_channel_TYPE()
api.post_control_channel_RAW_URL()
api.post_control_channelURL(requestParams)
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


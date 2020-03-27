## 创建应用表触发器

应用表数据变化前后都会触发，用于数据同步
### Path
POST /trigger/App

### Tags
    - App
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// 创建应用表触发器
let requestParams = {}
requestParams.应用 =  null  // 触发器参数 optional
let res = await api.post_trigger_app(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_trigger_app_TYPE()
api.post_trigger_app_RAW_URL()
api.post_trigger_appURL(requestParams)
```

## Responses
### Returns success

#### Status Code
201



### Bad Request

#### Status Code
400



### Unauthorized

#### Status Code
401



### Server Internal error

#### Status Code
500




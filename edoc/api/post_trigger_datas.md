## 创建数据字典表触发器

数据字典表数据变化前后都会触发，用于数据同步
### Path
POST /trigger/Datas

### Tags
    - Datas
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// 创建数据字典表触发器
let requestParams = {}
requestParams.数据字典 =  null  // 触发器参数 optional
let res = await api.post_trigger_datas(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_trigger_datas_TYPE()
api.post_trigger_datas_RAW_URL()
api.post_trigger_datasURL(requestParams)
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




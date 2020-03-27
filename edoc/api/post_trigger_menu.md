## 创建菜单表触发器

菜单表数据变化前后都会触发，用于数据同步
### Path
POST /trigger/Menu

### Tags
    - Menu
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// 创建菜单表触发器
let requestParams = {}
requestParams.菜单 =  null  // 触发器参数 optional
let res = await api.post_trigger_menu(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_trigger_menu_TYPE()
api.post_trigger_menu_RAW_URL()
api.post_trigger_menuURL(requestParams)
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




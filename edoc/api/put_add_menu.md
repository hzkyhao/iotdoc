## 分配菜单

给角色分配菜单
### Path
PUT /add_menu

### Tags
    - Menu
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// 分配菜单
let requestParams = {}
requestParams.menu =  null  //  required
let res = await api.put_add_menu(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.put_add_menu_TYPE()
api.put_add_menu_RAW_URL()
api.put_add_menuURL(requestParams)
```

## Responses
### Returns success

#### Status Code
200



### Bad Request

#### Status Code
400



### Unauthorized

#### Status Code
401



### Forbidden

#### Status Code
403



### Server Internal error

#### Status Code
500




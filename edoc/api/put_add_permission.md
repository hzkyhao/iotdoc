## 分配权限

给角色分配权限
### Path
PUT /add_permission

### Tags
    - Permission
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// 分配权限
let requestParams = {}
requestParams.permission =  null  //  required
let res = await api.put_add_permission(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.put_add_permission_TYPE()
api.put_add_permission_RAW_URL()
api.put_add_permissionURL(requestParams)
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




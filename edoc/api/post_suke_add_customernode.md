## 增加客户节点

增加客户节点
### Path
POST /suke/add_customernode

### Tags
    - SuKe
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| parentId | string |  |  [required]  | 父节点objectId |
| name | string |  |  [required]  | 节点名称 |

*request usage*
```javascript
// 增加客户节点
let requestParams = {}
requestParams.parentId =  null  // 父节点objectId required
requestParams.name =  null  // 节点名称 required
let res = await api.post_suke_add_customernode(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_suke_add_customernode_TYPE()
api.post_suke_add_customernode_RAW_URL()
api.post_suke_add_customernodeURL(requestParams)
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


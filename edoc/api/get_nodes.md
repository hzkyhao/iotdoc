## 获取节点

获取节点
### Path
GET /nodes

### Tags
    - System
### Parameters


*request usage*
```javascript
// 获取节点
let requestParams = {}
let res = await api.get_nodes(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_nodes_TYPE()
api.get_nodes_RAW_URL()
api.get_nodesURL(requestParams)
```

## Responses
### Returns operation status

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




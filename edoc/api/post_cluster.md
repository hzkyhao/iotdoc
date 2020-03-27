## 集群操作

加入,退出集群
### Path
POST /cluster

### Tags
    - System
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| action | string |  |  [required]  | 操作类型 |

*request usage*
```javascript
// 集群操作
let requestParams = {}
requestParams.action =  null  // 操作类型 required
requestParams.body =  null  // 相关参数 required
let res = await api.post_cluster(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_cluster_TYPE()
api.post_cluster_RAW_URL()
api.post_clusterURL(requestParams)
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




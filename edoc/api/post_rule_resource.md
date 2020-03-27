## 创建资源

创建资源
### Path
POST /rule_resource
#### Protected. Auth needed
### Tags
    - Rule
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// 创建资源
let requestParams = {}
requestParams.resource =  null  // 请求参数 optional
let res = await api.post_rule_resource(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_rule_resource_TYPE()
api.post_rule_resource_RAW_URL()
api.post_rule_resourceURL(requestParams)
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




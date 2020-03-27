## 测试规则引擎

创建规则引擎
### Path
POST /rule_test
#### Protected. Auth needed
### Tags
    - Rule
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// 测试规则引擎
let requestParams = {}
requestParams.rule =  null  // 规则引擎配置 optional
let res = await api.post_rule_test(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_rule_test_TYPE()
api.post_rule_test_RAW_URL()
api.post_rule_testURL(requestParams)
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




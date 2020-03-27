## setup_result

部署结果
### Path
GET /setup_result
#### Protected. Auth needed
### Tags
    - License
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| license | string |  |  [required]  | license |
| result | string |  |  [required]  | result |

*request usage*
```javascript
// setup_result
let requestParams = {}
requestParams.license =  null  // license required
requestParams.result =  null  // result required
let res = await api.get_setup_result(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_setup_result_TYPE()
api.get_setup_result_RAW_URL()
api.get_setup_resultURL(requestParams)
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




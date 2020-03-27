## licsetup

下载部署脚本
### Path
GET /licsetup
#### Protected. Auth needed
### Tags
    - License
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| license | string |  |  [required]  | license |

*request usage*
```javascript
// licsetup
let requestParams = {}
requestParams.license =  null  // license required
let res = await api.get_licsetup(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_licsetup_TYPE()
api.get_licsetup_RAW_URL()
api.get_licsetupURL(requestParams)
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




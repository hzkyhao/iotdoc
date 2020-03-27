## lictool

下载license辅助小工具
### Path
GET /lictool
#### Protected. Auth needed
### Tags
    - License
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| appid | string |  |  [required]  | appid |
| appsecret | string |  |  [required]  | appsecret |

*request usage*
```javascript
// lictool
let requestParams = {}
requestParams.appid =  null  // appid required
requestParams.appsecret =  null  // appsecret required
let res = await api.get_lictool(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_lictool_TYPE()
api.get_lictool_RAW_URL()
api.get_lictoolURL(requestParams)
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




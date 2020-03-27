## 获取license

获取license
### Path
GET /license
#### Protected. Auth needed
### Tags
    - License
### Parameters


*request usage*
```javascript
// 获取license
let requestParams = {}
let res = await api.get_license(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_license_TYPE()
api.get_license_RAW_URL()
api.get_licenseURL(requestParams)
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




## 获取硬件key

获取硬件key
### Path
GET /hardinfo
#### Protected. Auth needed
### Tags
    - License
### Parameters


*request usage*
```javascript
// 获取硬件key
let requestParams = {}
let res = await api.get_hardinfo(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_hardinfo_TYPE()
api.get_hardinfo_RAW_URL()
api.get_hardinfoURL(requestParams)
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




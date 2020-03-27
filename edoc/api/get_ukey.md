## get ukey

获取ukey信息
### Path
GET /ukey

### Tags
    - License
### Parameters


*request usage*
```javascript
// get ukey
let requestParams = {}
let res = await api.get_ukey(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_ukey_TYPE()
api.get_ukey_RAW_URL()
api.get_ukeyURL(requestParams)
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




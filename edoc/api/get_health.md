## health

检测是启动
### Path
GET /health
#### Protected. Auth needed
### Tags
    - License
### Parameters


*request usage*
```javascript
// health
let requestParams = {}
let res = await api.get_health(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_health_TYPE()
api.get_health_RAW_URL()
api.get_healthURL(requestParams)
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




## 获取配置

获取配置
### Path
GET /config

### Tags
    - DB
### Parameters


*request usage*
```javascript
// 获取配置
let requestParams = {}
let res = await api.get_config(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_config_TYPE()
api.get_config_RAW_URL()
api.get_configURL(requestParams)
```

## Responses
### Returns success

#### Status Code
200


#### Response object
| Name | Type | Format | Example | Description |
| ---- | ---- | ------ | ------- | ----------- |
| params | object |  -  |  |  |

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




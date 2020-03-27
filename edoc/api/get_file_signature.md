## 获得文件操作权限

获得文件操作权限
### Path
GET /file/signature

### Tags
    - System
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| type | string |  |  [required]  | 权限来源 |

*request usage*
```javascript
// 获得文件操作权限
let requestParams = {}
let res = await api.get_file_signature(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.get_file_signature_TYPE()
api.get_file_signature_RAW_URL()
api.get_file_signatureURL(requestParams)
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




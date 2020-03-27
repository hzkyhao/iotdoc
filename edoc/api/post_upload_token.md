## 获取上传文件Token

获取上传文件Token
### Path
POST /upload_token
#### Protected. Auth needed
### Tags
    - System
### Parameters

#### Query parameters

| Name | Type | Example Value | Notes | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| from | string |  |  [optional]  |  |

*request usage*
```javascript
// 获取上传文件Token
let requestParams = {}
requestParams.from =  null  //  optional
let res = await api.post_upload_token(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_upload_token_TYPE()
api.post_upload_token_RAW_URL()
api.post_upload_tokenURL(requestParams)
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




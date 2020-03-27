## 服务器文件上传

文件上传到服务器
### Path
POST /upload

### Tags
    - System
### Parameters


#### Multipart form data parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| file | file |  |  false  |  |
*request usage*
```javascript
// 服务器文件上传
let requestParams = {}
requestParams.file =  null  //  optional
let res = await api.post_upload(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_upload_TYPE()
api.post_upload_RAW_URL()
api.post_uploadURL(requestParams)
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




## 数据库文件上传

要将文件上传，请向文件URL发送POST请求，后缀为文件名。请求必须包含与Content-Type文件关联的标头。请记住，文件限制为10兆字节。
### Path
POST /files/{filename}

### Tags
    - DB
### Parameters


#### Path parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| filename | string |  |  true  | 要上载的文件的文件名。 |
*request usage*
```javascript
// 数据库文件上传
let requestParams = {}
requestParams.filename =  null  // 要上载的文件的文件名。 required
requestParams.content =  null  //  required
let res = await api.post_files_filename(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_files_filename_TYPE()
api.post_files_filename_RAW_URL()
api.post_files_filenameURL(requestParams)
```

## Responses
### Returns success

#### Status Code
201


#### Response object
| Name | Type | Format | Example | Description |
| ---- | ---- | ------ | ------- | ----------- |
| name | string |  -  |  | 文件名 |
| url | string |  -  |  | 文件路径 |

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




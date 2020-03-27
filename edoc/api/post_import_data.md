## 导库

json文件导库
### Path
POST /import_data

### Tags
    - DB
### Parameters


#### Multipart form data parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
| className | string |  |  false  | 表名 |
| file | file |  |  false  | 数据文件 |
*request usage*
```javascript
// 导库
let requestParams = {}
requestParams.className =  null  // 表名 optional
requestParams.file =  null  // 数据文件 optional
let res = await api.post_import_data(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_import_data_TYPE()
api.post_import_data_RAW_URL()
api.post_import_dataURL(requestParams)
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




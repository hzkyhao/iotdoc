## graphql

graphql
### Path
POST /graphql

### Tags
    - DB
### Parameters


#### Body parameters

| Name | Type | Example Value | Required | Description |
| ---- | ---- | ------------- | -------- | ----------- |
*request usage*
```javascript
// graphql
let requestParams = {}
requestParams.graphql =  null  //  required
let res = await api.post_graphql(requestParams)
if (res) {
// Success
} else {
// Error
}
```
*other usage*
```javascript
api.post_graphql_TYPE()
api.post_graphql_RAW_URL()
api.post_graphqlURL(requestParams)
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




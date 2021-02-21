# vctr
## Version: v1

### /api/ApiKey

#### POST
##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

#### GET
##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

#### DELETE
##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /api/Auth/Login

#### POST
##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /api/Auth/Logout

#### POST
##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /api/Links

#### GET
##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| offset | query |  | No | integer |
| limit | query |  | No | integer |

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

#### POST
##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /api/Links/search

#### GET
##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| query | query |  | No | string |
| offset | query |  | No | integer |
| limit | query |  | No | integer |

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /api/Links/{id}

#### GET
##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path |  | Yes | string (uuid) |

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

#### POST
##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path |  | Yes | string (uuid) |

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

#### DELETE
##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path |  | Yes | string (uuid) |

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /

#### GET
##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /{ident}

#### GET
##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| ident | path |  | Yes | string |
| password | query |  | No | string |

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /api/Users

#### GET
##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| offset | query |  | No | integer |
| limit | query |  | No | integer |

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

#### POST
##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /api/Users/me

#### GET
##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

#### POST
##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /api/Users/search

#### GET
##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| query | query |  | No | string |
| offset | query |  | No | integer |
| limit | query |  | No | integer |

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /api/Users/{id}

#### GET
##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path |  | Yes | string (uuid) |

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

#### POST
##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path |  | Yes | string (uuid) |

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

#### DELETE
##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path |  | Yes | string (uuid) |

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /api/Users/me/links

#### GET
##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| offset | query |  | No | integer |
| limit | query |  | No | integer |

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /api/Users/{id}/links

#### GET
##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path |  | Yes | string (uuid) |
| offset | query |  | No | integer |
| limit | query |  | No | integer |

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /api/Users/me/links/count

#### GET
##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /api/Users/{id}/links/count

#### GET
##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path |  | Yes | string (uuid) |

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /api/Users/me/links/search

#### GET
##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| query | query |  | No | string |
| offset | query |  | No | integer |
| limit | query |  | No | integer |

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### /api/Users/{id}/links/search

#### GET
##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path |  | Yes | string (uuid) |
| query | query |  | No | string |
| offset | query |  | No | integer |
| limit | query |  | No | integer |

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 | Success |

### Models

#### ApiKeyCreatedViewModel

| Name | Type | Description | Required |
| ---- | ---- | ----------- | -------- |
| guid | string (uuid) |  | No |
| created | dateTime |  | No |
| last_access | dateTime |  | No |
| access_count | integer |  | No |
| key | string |  | No |

#### ApiKeyViewModel

| Name | Type | Description | Required |
| ---- | ---- | ----------- | -------- |
| guid | string (uuid) |  | No |
| created | dateTime |  | No |
| last_access | dateTime |  | No |
| access_count | integer |  | No |

#### LoginModel

| Name | Type | Description | Required |
| ---- | ---- | ----------- | -------- |
| ident | string |  | Yes |
| password | string |  | Yes |
| remember | boolean |  | No |

#### Permissions

| Name | Type | Description | Required |
| ---- | ---- | ----------- | -------- |
| Permissions | integer |  |  |

#### UserViewModel

| Name | Type | Description | Required |
| ---- | ---- | ----------- | -------- |
| guid | string (uuid) |  | No |
| created | dateTime |  | No |
| username | string |  | No |
| permissions | integer | _Enum:_ `2`, `4`, `8`, `16`, `32`, `64`, `128`, `256`, `512`, `1024`, `2147483647`, `-1` | No |
| last_login | dateTime |  | No |

#### LinkViewModel

| Name | Type | Description | Required |
| ---- | ---- | ----------- | -------- |
| guid | string (uuid) |  | No |
| created | dateTime |  | No |
| ident | string |  | No |
| destination | string |  | No |
| creator | object |  | No |
| enabled | boolean |  | No |
| permanent_redirect | boolean |  | No |
| password_required | boolean |  | No |
| last_access | dateTime |  | No |
| access_count | integer |  | No |
| unique_access_count | integer |  | No |
| total_access_limit | integer |  | No |
| expires | dateTime |  | No |

#### LinkCreateModel

| Name | Type | Description | Required |
| ---- | ---- | ----------- | -------- |
| ident | string |  | No |
| destination | string |  | Yes |
| enabled | boolean |  | No |
| permanent_redirect | boolean |  | No |
| password | string |  | No |
| total_access_limit | integer |  | No |
| expires | dateTime |  | No |

#### LinkUpdateModel

| Name | Type | Description | Required |
| ---- | ---- | ----------- | -------- |
| ident | string |  | No |
| enabled | boolean |  | No |
| permanent_redirect | boolean |  | No |
| password | string |  | No |
| total_access_limit | integer |  | No |
| expires | dateTime |  | No |
| destination | string |  | No |

#### UserCreateModel

| Name | Type | Description | Required |
| ---- | ---- | ----------- | -------- |
| username | string |  | Yes |
| password | string |  | Yes |
| permissions | integer | _Enum:_ `2`, `4`, `8`, `16`, `32`, `64`, `128`, `256`, `512`, `1024`, `2147483647`, `-1` | No |

#### UpdateSelfUserModel

| Name | Type | Description | Required |
| ---- | ---- | ----------- | -------- |
| username | string |  | No |
| current_password | string |  | No |
| new_password | string |  | No |

#### UserUpdateModel

| Name | Type | Description | Required |
| ---- | ---- | ----------- | -------- |
| username | string |  | No |
| password | string |  | No |
| permissions | integer | _Enum:_ `2`, `4`, `8`, `16`, `32`, `64`, `128`, `256`, `512`, `1024`, `2147483647`, `-1` | No |

#### CountResponseModel

| Name | Type | Description | Required |
| ---- | ---- | ----------- | -------- |
| count | integer |  | No |

# \UsersAPI

All URIs are relative to *http://localhost/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateUser**](UsersAPI.md#CreateUser) | **Post** /users | Create a User
[**DeleteUser**](UsersAPI.md#DeleteUser) | **Delete** /users/{userID} | Delete a User
[**DisableUser2fa**](UsersAPI.md#DisableUser2fa) | **Delete** /users/{userID}/2fa | Disable 2fa for user
[**EnableUser2fa**](UsersAPI.md#EnableUser2fa) | **Post** /users/{userID}/2fa/enable | Verify code and enable 2FA
[**GetUser**](UsersAPI.md#GetUser) | **Get** /users/{userID} | Get a user
[**GetUser2faStatus**](UsersAPI.md#GetUser2faStatus) | **Get** /users/{userID}/2fa | Get user 2fa Status
[**GetUsers**](UsersAPI.md#GetUsers) | **Get** /users | Get all users
[**LoginAsUser**](UsersAPI.md#LoginAsUser) | **Post** /users/{userID}/login | Login as this user
[**RegenUser2faCodes**](UsersAPI.md#RegenUser2faCodes) | **Post** /users/{userID}/2fa/backup-codes | Regenerate 2FA backup codes
[**SetupUser2fa**](UsersAPI.md#SetupUser2fa) | **Post** /users/{userID}/2fa | Start 2FA setup, returns QR code URL
[**UpdateUser**](UsersAPI.md#UpdateUser) | **Put** /users/{userID} | Update a User
[**UpdateUserAuth**](UsersAPI.md#UpdateUserAuth) | **Put** /users/{userID}/auth | Update a User&#39;s Authentication
[**UpdateUserPermissions**](UsersAPI.md#UpdateUserPermissions) | **Put** /users/{userID}/permissions | Update a User&#39;s Permissions



## CreateUser

> GetAuditLogs200ResponseInnerUser CreateUser(ctx).CreateUserRequest(createUserRequest).Execute()

Create a User

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sander0542/nginxproxymanager-go"
)

func main() {
	createUserRequest := *openapiclient.NewCreateUserRequest("Jamie Curnow", "James", "jc@jc21.com") // CreateUserRequest | User Payload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.CreateUser(context.Background()).CreateUserRequest(createUserRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.CreateUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateUser`: GetAuditLogs200ResponseInnerUser
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.CreateUser`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createUserRequest** | [**CreateUserRequest**](CreateUserRequest.md) | User Payload | 

### Return type

[**GetAuditLogs200ResponseInnerUser**](GetAuditLogs200ResponseInnerUser.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteUser

> bool DeleteUser(ctx, userID).Execute()

Delete a User

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sander0542/nginxproxymanager-go"
)

func main() {
	userID := int64(2) // int64 | User ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.DeleteUser(context.Background(), userID).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.DeleteUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteUser`: bool
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.DeleteUser`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userID** | **int64** | User ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**bool**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DisableUser2fa

> bool DisableUser2fa(ctx, userID).Code(code).Execute()

Disable 2fa for user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sander0542/nginxproxymanager-go"
)

func main() {
	userID := int64(2) // int64 | User ID
	code := "012345" // string | 2fa Code

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.DisableUser2fa(context.Background(), userID).Code(code).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.DisableUser2fa``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DisableUser2fa`: bool
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.DisableUser2fa`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userID** | **int64** | User ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDisableUser2faRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **code** | **string** | 2fa Code | 

### Return type

**bool**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EnableUser2fa

> EnableUser2fa200Response EnableUser2fa(ctx, userID).EnableUser2faRequest(enableUser2faRequest).Execute()

Verify code and enable 2FA

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sander0542/nginxproxymanager-go"
)

func main() {
	userID := int64(2) // int64 | User ID
	enableUser2faRequest := *openapiclient.NewEnableUser2faRequest("123456") // EnableUser2faRequest | Verification Payload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.EnableUser2fa(context.Background(), userID).EnableUser2faRequest(enableUser2faRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.EnableUser2fa``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EnableUser2fa`: EnableUser2fa200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.EnableUser2fa`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userID** | **int64** | User ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiEnableUser2faRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **enableUser2faRequest** | [**EnableUser2faRequest**](EnableUser2faRequest.md) | Verification Payload | 

### Return type

[**EnableUser2fa200Response**](EnableUser2fa200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUser

> GetAuditLogs200ResponseInnerUser GetUser(ctx, userID).Execute()

Get a user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sander0542/nginxproxymanager-go"
)

func main() {
	userID := openapiclient.getUser_userID_parameter{Int64: new(int64)} // GetUserUserIDParameter | User ID or 'me' for yourself

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.GetUser(context.Background(), userID).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.GetUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUser`: GetAuditLogs200ResponseInnerUser
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.GetUser`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userID** | [**GetUserUserIDParameter**](.md) | User ID or &#39;me&#39; for yourself | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetAuditLogs200ResponseInnerUser**](GetAuditLogs200ResponseInnerUser.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUser2faStatus

> GetUser2faStatus200Response GetUser2faStatus(ctx, userID).Execute()

Get user 2fa Status

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sander0542/nginxproxymanager-go"
)

func main() {
	userID := int64(2) // int64 | User ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.GetUser2faStatus(context.Background(), userID).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.GetUser2faStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUser2faStatus`: GetUser2faStatus200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.GetUser2faStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userID** | **int64** | User ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUser2faStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetUser2faStatus200Response**](GetUser2faStatus200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUsers

> []GetAuditLogs200ResponseInnerUser GetUsers(ctx).Expand(expand).Execute()

Get all users

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sander0542/nginxproxymanager-go"
)

func main() {
	expand := "expand_example" // string | Expansions (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.GetUsers(context.Background()).Expand(expand).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.GetUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUsers`: []GetAuditLogs200ResponseInnerUser
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.GetUsers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **expand** | **string** | Expansions | 

### Return type

[**[]GetAuditLogs200ResponseInnerUser**](GetAuditLogs200ResponseInnerUser.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LoginAsUser

> LoginAsUser200Response LoginAsUser(ctx, userID).Execute()

Login as this user

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sander0542/nginxproxymanager-go"
)

func main() {
	userID := int64(2) // int64 | User ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.LoginAsUser(context.Background(), userID).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.LoginAsUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LoginAsUser`: LoginAsUser200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.LoginAsUser`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userID** | **int64** | User ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiLoginAsUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**LoginAsUser200Response**](LoginAsUser200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegenUser2faCodes

> EnableUser2fa200Response RegenUser2faCodes(ctx, userID).EnableUser2faRequest(enableUser2faRequest).Execute()

Regenerate 2FA backup codes

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sander0542/nginxproxymanager-go"
)

func main() {
	userID := int64(2) // int64 | User ID
	enableUser2faRequest := *openapiclient.NewEnableUser2faRequest("123456") // EnableUser2faRequest | Verification Payload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.RegenUser2faCodes(context.Background(), userID).EnableUser2faRequest(enableUser2faRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.RegenUser2faCodes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegenUser2faCodes`: EnableUser2fa200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.RegenUser2faCodes`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userID** | **int64** | User ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiRegenUser2faCodesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **enableUser2faRequest** | [**EnableUser2faRequest**](EnableUser2faRequest.md) | Verification Payload | 

### Return type

[**EnableUser2fa200Response**](EnableUser2fa200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetupUser2fa

> SetupUser2fa200Response SetupUser2fa(ctx, userID).Execute()

Start 2FA setup, returns QR code URL

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sander0542/nginxproxymanager-go"
)

func main() {
	userID := int64(2) // int64 | User ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.SetupUser2fa(context.Background(), userID).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.SetupUser2fa``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetupUser2fa`: SetupUser2fa200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.SetupUser2fa`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userID** | **int64** | User ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetupUser2faRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SetupUser2fa200Response**](SetupUser2fa200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateUser

> GetAuditLogs200ResponseInnerUser UpdateUser(ctx, userID).UpdateUserRequest(updateUserRequest).Execute()

Update a User

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sander0542/nginxproxymanager-go"
)

func main() {
	userID := openapiclient.getUser_userID_parameter{Int64: new(int64)} // GetUserUserIDParameter | User ID or 'me' for yourself
	updateUserRequest := *openapiclient.NewUpdateUserRequest() // UpdateUserRequest | User Payload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.UpdateUser(context.Background(), userID).UpdateUserRequest(updateUserRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.UpdateUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateUser`: GetAuditLogs200ResponseInnerUser
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.UpdateUser`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userID** | [**GetUserUserIDParameter**](.md) | User ID or &#39;me&#39; for yourself | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateUserRequest** | [**UpdateUserRequest**](UpdateUserRequest.md) | User Payload | 

### Return type

[**GetAuditLogs200ResponseInnerUser**](GetAuditLogs200ResponseInnerUser.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateUserAuth

> bool UpdateUserAuth(ctx, userID).UpdateUserAuthRequest(updateUserAuthRequest).Execute()

Update a User's Authentication

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sander0542/nginxproxymanager-go"
)

func main() {
	userID := openapiclient.getUser_userID_parameter{Int64: new(int64)} // GetUserUserIDParameter | User ID or 'me' for yourself
	updateUserAuthRequest := *openapiclient.NewUpdateUserAuthRequest("password", "mySuperN3wP@ssword!") // UpdateUserAuthRequest | Auth Payload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.UpdateUserAuth(context.Background(), userID).UpdateUserAuthRequest(updateUserAuthRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.UpdateUserAuth``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateUserAuth`: bool
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.UpdateUserAuth`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userID** | [**GetUserUserIDParameter**](.md) | User ID or &#39;me&#39; for yourself | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateUserAuthRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateUserAuthRequest** | [**UpdateUserAuthRequest**](UpdateUserAuthRequest.md) | Auth Payload | 

### Return type

**bool**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateUserPermissions

> bool UpdateUserPermissions(ctx, userID).UpdateUserPermissionsRequest(updateUserPermissionsRequest).Execute()

Update a User's Permissions

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sander0542/nginxproxymanager-go"
)

func main() {
	userID := int64(2) // int64 | User ID
	updateUserPermissionsRequest := *openapiclient.NewUpdateUserPermissionsRequest() // UpdateUserPermissionsRequest | Permissions Payload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.UpdateUserPermissions(context.Background(), userID).UpdateUserPermissionsRequest(updateUserPermissionsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.UpdateUserPermissions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateUserPermissions`: bool
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.UpdateUserPermissions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userID** | **int64** | User ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateUserPermissionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateUserPermissionsRequest** | [**UpdateUserPermissionsRequest**](UpdateUserPermissionsRequest.md) | Permissions Payload | 

### Return type

**bool**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


# \TokensAPI

All URIs are relative to *http://localhost/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**LoginWith2FA**](TokensAPI.md#LoginWith2FA) | **Post** /tokens/2fa | Verify 2FA code and get full token
[**RefreshToken**](TokensAPI.md#RefreshToken) | **Get** /tokens | Refresh your access token
[**RequestToken**](TokensAPI.md#RequestToken) | **Post** /tokens | Request a new access token from credentials



## LoginWith2FA

> RefreshToken200Response LoginWith2FA(ctx).LoginWith2FARequest(loginWith2FARequest).Execute()

Verify 2FA code and get full token

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
	loginWith2FARequest := *openapiclient.NewLoginWith2FARequest("eyJhbGciOiJSUzUxMiIsInR5cCI6IkpXVCJ9.ey...xaHKYr3Kk6MvkUjcC4", "012345") // LoginWith2FARequest | 2fa Challenge Payload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TokensAPI.LoginWith2FA(context.Background()).LoginWith2FARequest(loginWith2FARequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TokensAPI.LoginWith2FA``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LoginWith2FA`: RefreshToken200Response
	fmt.Fprintf(os.Stdout, "Response from `TokensAPI.LoginWith2FA`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLoginWith2FARequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **loginWith2FARequest** | [**LoginWith2FARequest**](LoginWith2FARequest.md) | 2fa Challenge Payload | 

### Return type

[**RefreshToken200Response**](RefreshToken200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RefreshToken

> RefreshToken200Response RefreshToken(ctx).Execute()

Refresh your access token

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TokensAPI.RefreshToken(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TokensAPI.RefreshToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RefreshToken`: RefreshToken200Response
	fmt.Fprintf(os.Stdout, "Response from `TokensAPI.RefreshToken`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRefreshTokenRequest struct via the builder pattern


### Return type

[**RefreshToken200Response**](RefreshToken200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RequestToken

> RequestToken200Response RequestToken(ctx).RequestTokenRequest(requestTokenRequest).Execute()

Request a new access token from credentials

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
	requestTokenRequest := *openapiclient.NewRequestTokenRequest("me@example.com", "bigredhorsebanana") // RequestTokenRequest | Credentials Payload

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TokensAPI.RequestToken(context.Background()).RequestTokenRequest(requestTokenRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TokensAPI.RequestToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RequestToken`: RequestToken200Response
	fmt.Fprintf(os.Stdout, "Response from `TokensAPI.RequestToken`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRequestTokenRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestTokenRequest** | [**RequestTokenRequest**](RequestTokenRequest.md) | Credentials Payload | 

### Return type

[**RequestToken200Response**](RequestToken200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


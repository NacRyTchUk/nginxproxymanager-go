# RequestToken200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Expires** | **string** | Token Expiry ISO Time String | 
**Token** | **string** | JWT Token | 
**Requires2fa** | **bool** | Whether this token request requires two-factor authentication | 
**ChallengeToken** | **string** | Challenge Token used in subsequent 2FA verification | 

## Methods

### NewRequestToken200Response

`func NewRequestToken200Response(expires string, token string, requires2fa bool, challengeToken string, ) *RequestToken200Response`

NewRequestToken200Response instantiates a new RequestToken200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRequestToken200ResponseWithDefaults

`func NewRequestToken200ResponseWithDefaults() *RequestToken200Response`

NewRequestToken200ResponseWithDefaults instantiates a new RequestToken200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExpires

`func (o *RequestToken200Response) GetExpires() string`

GetExpires returns the Expires field if non-nil, zero value otherwise.

### GetExpiresOk

`func (o *RequestToken200Response) GetExpiresOk() (*string, bool)`

GetExpiresOk returns a tuple with the Expires field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpires

`func (o *RequestToken200Response) SetExpires(v string)`

SetExpires sets Expires field to given value.


### GetToken

`func (o *RequestToken200Response) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *RequestToken200Response) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *RequestToken200Response) SetToken(v string)`

SetToken sets Token field to given value.


### GetRequires2fa

`func (o *RequestToken200Response) GetRequires2fa() bool`

GetRequires2fa returns the Requires2fa field if non-nil, zero value otherwise.

### GetRequires2faOk

`func (o *RequestToken200Response) GetRequires2faOk() (*bool, bool)`

GetRequires2faOk returns a tuple with the Requires2fa field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequires2fa

`func (o *RequestToken200Response) SetRequires2fa(v bool)`

SetRequires2fa sets Requires2fa field to given value.


### GetChallengeToken

`func (o *RequestToken200Response) GetChallengeToken() string`

GetChallengeToken returns the ChallengeToken field if non-nil, zero value otherwise.

### GetChallengeTokenOk

`func (o *RequestToken200Response) GetChallengeTokenOk() (*string, bool)`

GetChallengeTokenOk returns a tuple with the ChallengeToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChallengeToken

`func (o *RequestToken200Response) SetChallengeToken(v string)`

SetChallengeToken sets ChallengeToken field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



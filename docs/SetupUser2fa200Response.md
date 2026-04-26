# SetupUser2fa200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Secret** | **string** | TOTP Secret | 
**OtpauthUrl** | **string** | OTP Auth URL for QR Code generation | 

## Methods

### NewSetupUser2fa200Response

`func NewSetupUser2fa200Response(secret string, otpauthUrl string, ) *SetupUser2fa200Response`

NewSetupUser2fa200Response instantiates a new SetupUser2fa200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSetupUser2fa200ResponseWithDefaults

`func NewSetupUser2fa200ResponseWithDefaults() *SetupUser2fa200Response`

NewSetupUser2fa200ResponseWithDefaults instantiates a new SetupUser2fa200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSecret

`func (o *SetupUser2fa200Response) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *SetupUser2fa200Response) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *SetupUser2fa200Response) SetSecret(v string)`

SetSecret sets Secret field to given value.


### GetOtpauthUrl

`func (o *SetupUser2fa200Response) GetOtpauthUrl() string`

GetOtpauthUrl returns the OtpauthUrl field if non-nil, zero value otherwise.

### GetOtpauthUrlOk

`func (o *SetupUser2fa200Response) GetOtpauthUrlOk() (*string, bool)`

GetOtpauthUrlOk returns a tuple with the OtpauthUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtpauthUrl

`func (o *SetupUser2fa200Response) SetOtpauthUrl(v string)`

SetOtpauthUrl sets OtpauthUrl field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



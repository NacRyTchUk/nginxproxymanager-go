# LoginWith2FARequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ChallengeToken** | **string** |  | 
**Code** | **string** |  | 

## Methods

### NewLoginWith2FARequest

`func NewLoginWith2FARequest(challengeToken string, code string, ) *LoginWith2FARequest`

NewLoginWith2FARequest instantiates a new LoginWith2FARequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoginWith2FARequestWithDefaults

`func NewLoginWith2FARequestWithDefaults() *LoginWith2FARequest`

NewLoginWith2FARequestWithDefaults instantiates a new LoginWith2FARequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChallengeToken

`func (o *LoginWith2FARequest) GetChallengeToken() string`

GetChallengeToken returns the ChallengeToken field if non-nil, zero value otherwise.

### GetChallengeTokenOk

`func (o *LoginWith2FARequest) GetChallengeTokenOk() (*string, bool)`

GetChallengeTokenOk returns a tuple with the ChallengeToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChallengeToken

`func (o *LoginWith2FARequest) SetChallengeToken(v string)`

SetChallengeToken sets ChallengeToken field to given value.


### GetCode

`func (o *LoginWith2FARequest) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *LoginWith2FARequest) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *LoginWith2FARequest) SetCode(v string)`

SetCode sets Code field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



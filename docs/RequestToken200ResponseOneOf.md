# RequestToken200ResponseOneOf

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Requires2fa** | **bool** | Whether this token request requires two-factor authentication | 
**ChallengeToken** | **string** | Challenge Token used in subsequent 2FA verification | 

## Methods

### NewRequestToken200ResponseOneOf

`func NewRequestToken200ResponseOneOf(requires2fa bool, challengeToken string, ) *RequestToken200ResponseOneOf`

NewRequestToken200ResponseOneOf instantiates a new RequestToken200ResponseOneOf object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRequestToken200ResponseOneOfWithDefaults

`func NewRequestToken200ResponseOneOfWithDefaults() *RequestToken200ResponseOneOf`

NewRequestToken200ResponseOneOfWithDefaults instantiates a new RequestToken200ResponseOneOf object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRequires2fa

`func (o *RequestToken200ResponseOneOf) GetRequires2fa() bool`

GetRequires2fa returns the Requires2fa field if non-nil, zero value otherwise.

### GetRequires2faOk

`func (o *RequestToken200ResponseOneOf) GetRequires2faOk() (*bool, bool)`

GetRequires2faOk returns a tuple with the Requires2fa field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequires2fa

`func (o *RequestToken200ResponseOneOf) SetRequires2fa(v bool)`

SetRequires2fa sets Requires2fa field to given value.


### GetChallengeToken

`func (o *RequestToken200ResponseOneOf) GetChallengeToken() string`

GetChallengeToken returns the ChallengeToken field if non-nil, zero value otherwise.

### GetChallengeTokenOk

`func (o *RequestToken200ResponseOneOf) GetChallengeTokenOk() (*string, bool)`

GetChallengeTokenOk returns a tuple with the ChallengeToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChallengeToken

`func (o *RequestToken200ResponseOneOf) SetChallengeToken(v string)`

SetChallengeToken sets ChallengeToken field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



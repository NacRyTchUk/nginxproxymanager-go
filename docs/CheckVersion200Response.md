# CheckVersion200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Current** | **NullableString** | Current version string | 
**Latest** | **NullableString** | Latest version string | 
**UpdateAvailable** | **bool** | Whether there&#39;s an update available | 

## Methods

### NewCheckVersion200Response

`func NewCheckVersion200Response(current NullableString, latest NullableString, updateAvailable bool, ) *CheckVersion200Response`

NewCheckVersion200Response instantiates a new CheckVersion200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCheckVersion200ResponseWithDefaults

`func NewCheckVersion200ResponseWithDefaults() *CheckVersion200Response`

NewCheckVersion200ResponseWithDefaults instantiates a new CheckVersion200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrent

`func (o *CheckVersion200Response) GetCurrent() string`

GetCurrent returns the Current field if non-nil, zero value otherwise.

### GetCurrentOk

`func (o *CheckVersion200Response) GetCurrentOk() (*string, bool)`

GetCurrentOk returns a tuple with the Current field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrent

`func (o *CheckVersion200Response) SetCurrent(v string)`

SetCurrent sets Current field to given value.


### SetCurrentNil

`func (o *CheckVersion200Response) SetCurrentNil(b bool)`

 SetCurrentNil sets the value for Current to be an explicit nil

### UnsetCurrent
`func (o *CheckVersion200Response) UnsetCurrent()`

UnsetCurrent ensures that no value is present for Current, not even an explicit nil
### GetLatest

`func (o *CheckVersion200Response) GetLatest() string`

GetLatest returns the Latest field if non-nil, zero value otherwise.

### GetLatestOk

`func (o *CheckVersion200Response) GetLatestOk() (*string, bool)`

GetLatestOk returns a tuple with the Latest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatest

`func (o *CheckVersion200Response) SetLatest(v string)`

SetLatest sets Latest field to given value.


### SetLatestNil

`func (o *CheckVersion200Response) SetLatestNil(b bool)`

 SetLatestNil sets the value for Latest to be an explicit nil

### UnsetLatest
`func (o *CheckVersion200Response) UnsetLatest()`

UnsetLatest ensures that no value is present for Latest, not even an explicit nil
### GetUpdateAvailable

`func (o *CheckVersion200Response) GetUpdateAvailable() bool`

GetUpdateAvailable returns the UpdateAvailable field if non-nil, zero value otherwise.

### GetUpdateAvailableOk

`func (o *CheckVersion200Response) GetUpdateAvailableOk() (*bool, bool)`

GetUpdateAvailableOk returns a tuple with the UpdateAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdateAvailable

`func (o *CheckVersion200Response) SetUpdateAvailable(v bool)`

SetUpdateAvailable sets UpdateAvailable field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



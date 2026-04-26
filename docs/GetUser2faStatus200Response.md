# GetUser2faStatus200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** | Is 2FA enabled for this user | 
**BackupCodesRemaining** | **int64** | Number of remaining backup codes for this user | 

## Methods

### NewGetUser2faStatus200Response

`func NewGetUser2faStatus200Response(enabled bool, backupCodesRemaining int64, ) *GetUser2faStatus200Response`

NewGetUser2faStatus200Response instantiates a new GetUser2faStatus200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetUser2faStatus200ResponseWithDefaults

`func NewGetUser2faStatus200ResponseWithDefaults() *GetUser2faStatus200Response`

NewGetUser2faStatus200ResponseWithDefaults instantiates a new GetUser2faStatus200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *GetUser2faStatus200Response) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *GetUser2faStatus200Response) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *GetUser2faStatus200Response) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetBackupCodesRemaining

`func (o *GetUser2faStatus200Response) GetBackupCodesRemaining() int64`

GetBackupCodesRemaining returns the BackupCodesRemaining field if non-nil, zero value otherwise.

### GetBackupCodesRemainingOk

`func (o *GetUser2faStatus200Response) GetBackupCodesRemainingOk() (*int64, bool)`

GetBackupCodesRemainingOk returns a tuple with the BackupCodesRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackupCodesRemaining

`func (o *GetUser2faStatus200Response) SetBackupCodesRemaining(v int64)`

SetBackupCodesRemaining sets BackupCodesRemaining field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



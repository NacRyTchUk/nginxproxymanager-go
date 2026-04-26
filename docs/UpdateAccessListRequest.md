# UpdateAccessListRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**SatisfyAny** | Pointer to **bool** |  | [optional] 
**PassAuth** | Pointer to **bool** |  | [optional] 
**Items** | Pointer to [**[]CreateAccessListRequestItemsInner**](CreateAccessListRequestItemsInner.md) |  | [optional] 
**Clients** | Pointer to [**[]CreateAccessListRequestClientsInner**](CreateAccessListRequestClientsInner.md) |  | [optional] 

## Methods

### NewUpdateAccessListRequest

`func NewUpdateAccessListRequest() *UpdateAccessListRequest`

NewUpdateAccessListRequest instantiates a new UpdateAccessListRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateAccessListRequestWithDefaults

`func NewUpdateAccessListRequestWithDefaults() *UpdateAccessListRequest`

NewUpdateAccessListRequestWithDefaults instantiates a new UpdateAccessListRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateAccessListRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateAccessListRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateAccessListRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateAccessListRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSatisfyAny

`func (o *UpdateAccessListRequest) GetSatisfyAny() bool`

GetSatisfyAny returns the SatisfyAny field if non-nil, zero value otherwise.

### GetSatisfyAnyOk

`func (o *UpdateAccessListRequest) GetSatisfyAnyOk() (*bool, bool)`

GetSatisfyAnyOk returns a tuple with the SatisfyAny field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSatisfyAny

`func (o *UpdateAccessListRequest) SetSatisfyAny(v bool)`

SetSatisfyAny sets SatisfyAny field to given value.

### HasSatisfyAny

`func (o *UpdateAccessListRequest) HasSatisfyAny() bool`

HasSatisfyAny returns a boolean if a field has been set.

### GetPassAuth

`func (o *UpdateAccessListRequest) GetPassAuth() bool`

GetPassAuth returns the PassAuth field if non-nil, zero value otherwise.

### GetPassAuthOk

`func (o *UpdateAccessListRequest) GetPassAuthOk() (*bool, bool)`

GetPassAuthOk returns a tuple with the PassAuth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassAuth

`func (o *UpdateAccessListRequest) SetPassAuth(v bool)`

SetPassAuth sets PassAuth field to given value.

### HasPassAuth

`func (o *UpdateAccessListRequest) HasPassAuth() bool`

HasPassAuth returns a boolean if a field has been set.

### GetItems

`func (o *UpdateAccessListRequest) GetItems() []CreateAccessListRequestItemsInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *UpdateAccessListRequest) GetItemsOk() (*[]CreateAccessListRequestItemsInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *UpdateAccessListRequest) SetItems(v []CreateAccessListRequestItemsInner)`

SetItems sets Items field to given value.

### HasItems

`func (o *UpdateAccessListRequest) HasItems() bool`

HasItems returns a boolean if a field has been set.

### GetClients

`func (o *UpdateAccessListRequest) GetClients() []CreateAccessListRequestClientsInner`

GetClients returns the Clients field if non-nil, zero value otherwise.

### GetClientsOk

`func (o *UpdateAccessListRequest) GetClientsOk() (*[]CreateAccessListRequestClientsInner, bool)`

GetClientsOk returns a tuple with the Clients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClients

`func (o *UpdateAccessListRequest) SetClients(v []CreateAccessListRequestClientsInner)`

SetClients sets Clients field to given value.

### HasClients

`func (o *UpdateAccessListRequest) HasClients() bool`

HasClients returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



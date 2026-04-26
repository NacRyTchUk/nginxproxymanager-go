# GetStreams200ResponseInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int64** | Unique identifier | [readonly] 
**CreatedOn** | **string** | Date and time of creation | [readonly] 
**ModifiedOn** | **string** | Date and time of last update | [readonly] 
**OwnerUserId** | **int64** | User ID | 
**IncomingPort** | **int64** |  | 
**ForwardingHost** | [**GetStreams200ResponseInnerForwardingHost**](GetStreams200ResponseInnerForwardingHost.md) |  | 
**ForwardingPort** | **int64** |  | 
**TcpForwarding** | **bool** |  | 
**UdpForwarding** | **bool** |  | 
**Enabled** | **bool** | Is Enabled | 
**CertificateId** | Pointer to [**GetProxyHosts200ResponseInnerCertificateId**](GetProxyHosts200ResponseInnerCertificateId.md) |  | [optional] 
**Meta** | **map[string]interface{}** |  | 
**Certificate** | Pointer to [**NullableGetProxyHosts200ResponseInnerCertificate**](GetProxyHosts200ResponseInnerCertificate.md) |  | [optional] 
**Owner** | Pointer to [**GetAuditLogs200ResponseInnerUser**](GetAuditLogs200ResponseInnerUser.md) |  | [optional] 

## Methods

### NewGetStreams200ResponseInner

`func NewGetStreams200ResponseInner(id int64, createdOn string, modifiedOn string, ownerUserId int64, incomingPort int64, forwardingHost GetStreams200ResponseInnerForwardingHost, forwardingPort int64, tcpForwarding bool, udpForwarding bool, enabled bool, meta map[string]interface{}, ) *GetStreams200ResponseInner`

NewGetStreams200ResponseInner instantiates a new GetStreams200ResponseInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetStreams200ResponseInnerWithDefaults

`func NewGetStreams200ResponseInnerWithDefaults() *GetStreams200ResponseInner`

NewGetStreams200ResponseInnerWithDefaults instantiates a new GetStreams200ResponseInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetStreams200ResponseInner) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetStreams200ResponseInner) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetStreams200ResponseInner) SetId(v int64)`

SetId sets Id field to given value.


### GetCreatedOn

`func (o *GetStreams200ResponseInner) GetCreatedOn() string`

GetCreatedOn returns the CreatedOn field if non-nil, zero value otherwise.

### GetCreatedOnOk

`func (o *GetStreams200ResponseInner) GetCreatedOnOk() (*string, bool)`

GetCreatedOnOk returns a tuple with the CreatedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedOn

`func (o *GetStreams200ResponseInner) SetCreatedOn(v string)`

SetCreatedOn sets CreatedOn field to given value.


### GetModifiedOn

`func (o *GetStreams200ResponseInner) GetModifiedOn() string`

GetModifiedOn returns the ModifiedOn field if non-nil, zero value otherwise.

### GetModifiedOnOk

`func (o *GetStreams200ResponseInner) GetModifiedOnOk() (*string, bool)`

GetModifiedOnOk returns a tuple with the ModifiedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedOn

`func (o *GetStreams200ResponseInner) SetModifiedOn(v string)`

SetModifiedOn sets ModifiedOn field to given value.


### GetOwnerUserId

`func (o *GetStreams200ResponseInner) GetOwnerUserId() int64`

GetOwnerUserId returns the OwnerUserId field if non-nil, zero value otherwise.

### GetOwnerUserIdOk

`func (o *GetStreams200ResponseInner) GetOwnerUserIdOk() (*int64, bool)`

GetOwnerUserIdOk returns a tuple with the OwnerUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerUserId

`func (o *GetStreams200ResponseInner) SetOwnerUserId(v int64)`

SetOwnerUserId sets OwnerUserId field to given value.


### GetIncomingPort

`func (o *GetStreams200ResponseInner) GetIncomingPort() int64`

GetIncomingPort returns the IncomingPort field if non-nil, zero value otherwise.

### GetIncomingPortOk

`func (o *GetStreams200ResponseInner) GetIncomingPortOk() (*int64, bool)`

GetIncomingPortOk returns a tuple with the IncomingPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncomingPort

`func (o *GetStreams200ResponseInner) SetIncomingPort(v int64)`

SetIncomingPort sets IncomingPort field to given value.


### GetForwardingHost

`func (o *GetStreams200ResponseInner) GetForwardingHost() GetStreams200ResponseInnerForwardingHost`

GetForwardingHost returns the ForwardingHost field if non-nil, zero value otherwise.

### GetForwardingHostOk

`func (o *GetStreams200ResponseInner) GetForwardingHostOk() (*GetStreams200ResponseInnerForwardingHost, bool)`

GetForwardingHostOk returns a tuple with the ForwardingHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardingHost

`func (o *GetStreams200ResponseInner) SetForwardingHost(v GetStreams200ResponseInnerForwardingHost)`

SetForwardingHost sets ForwardingHost field to given value.


### GetForwardingPort

`func (o *GetStreams200ResponseInner) GetForwardingPort() int64`

GetForwardingPort returns the ForwardingPort field if non-nil, zero value otherwise.

### GetForwardingPortOk

`func (o *GetStreams200ResponseInner) GetForwardingPortOk() (*int64, bool)`

GetForwardingPortOk returns a tuple with the ForwardingPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardingPort

`func (o *GetStreams200ResponseInner) SetForwardingPort(v int64)`

SetForwardingPort sets ForwardingPort field to given value.


### GetTcpForwarding

`func (o *GetStreams200ResponseInner) GetTcpForwarding() bool`

GetTcpForwarding returns the TcpForwarding field if non-nil, zero value otherwise.

### GetTcpForwardingOk

`func (o *GetStreams200ResponseInner) GetTcpForwardingOk() (*bool, bool)`

GetTcpForwardingOk returns a tuple with the TcpForwarding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTcpForwarding

`func (o *GetStreams200ResponseInner) SetTcpForwarding(v bool)`

SetTcpForwarding sets TcpForwarding field to given value.


### GetUdpForwarding

`func (o *GetStreams200ResponseInner) GetUdpForwarding() bool`

GetUdpForwarding returns the UdpForwarding field if non-nil, zero value otherwise.

### GetUdpForwardingOk

`func (o *GetStreams200ResponseInner) GetUdpForwardingOk() (*bool, bool)`

GetUdpForwardingOk returns a tuple with the UdpForwarding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUdpForwarding

`func (o *GetStreams200ResponseInner) SetUdpForwarding(v bool)`

SetUdpForwarding sets UdpForwarding field to given value.


### GetEnabled

`func (o *GetStreams200ResponseInner) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *GetStreams200ResponseInner) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *GetStreams200ResponseInner) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetCertificateId

`func (o *GetStreams200ResponseInner) GetCertificateId() GetProxyHosts200ResponseInnerCertificateId`

GetCertificateId returns the CertificateId field if non-nil, zero value otherwise.

### GetCertificateIdOk

`func (o *GetStreams200ResponseInner) GetCertificateIdOk() (*GetProxyHosts200ResponseInnerCertificateId, bool)`

GetCertificateIdOk returns a tuple with the CertificateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateId

`func (o *GetStreams200ResponseInner) SetCertificateId(v GetProxyHosts200ResponseInnerCertificateId)`

SetCertificateId sets CertificateId field to given value.

### HasCertificateId

`func (o *GetStreams200ResponseInner) HasCertificateId() bool`

HasCertificateId returns a boolean if a field has been set.

### GetMeta

`func (o *GetStreams200ResponseInner) GetMeta() map[string]interface{}`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetStreams200ResponseInner) GetMetaOk() (*map[string]interface{}, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetStreams200ResponseInner) SetMeta(v map[string]interface{})`

SetMeta sets Meta field to given value.


### GetCertificate

`func (o *GetStreams200ResponseInner) GetCertificate() GetProxyHosts200ResponseInnerCertificate`

GetCertificate returns the Certificate field if non-nil, zero value otherwise.

### GetCertificateOk

`func (o *GetStreams200ResponseInner) GetCertificateOk() (*GetProxyHosts200ResponseInnerCertificate, bool)`

GetCertificateOk returns a tuple with the Certificate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificate

`func (o *GetStreams200ResponseInner) SetCertificate(v GetProxyHosts200ResponseInnerCertificate)`

SetCertificate sets Certificate field to given value.

### HasCertificate

`func (o *GetStreams200ResponseInner) HasCertificate() bool`

HasCertificate returns a boolean if a field has been set.

### SetCertificateNil

`func (o *GetStreams200ResponseInner) SetCertificateNil(b bool)`

 SetCertificateNil sets the value for Certificate to be an explicit nil

### UnsetCertificate
`func (o *GetStreams200ResponseInner) UnsetCertificate()`

UnsetCertificate ensures that no value is present for Certificate, not even an explicit nil
### GetOwner

`func (o *GetStreams200ResponseInner) GetOwner() GetAuditLogs200ResponseInnerUser`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *GetStreams200ResponseInner) GetOwnerOk() (*GetAuditLogs200ResponseInnerUser, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *GetStreams200ResponseInner) SetOwner(v GetAuditLogs200ResponseInnerUser)`

SetOwner sets Owner field to given value.

### HasOwner

`func (o *GetStreams200ResponseInner) HasOwner() bool`

HasOwner returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



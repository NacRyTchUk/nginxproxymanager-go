# UpdateProxyHostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DomainNames** | Pointer to **[]string** | Domain Names separated by a comma | [optional] 
**ForwardScheme** | Pointer to **string** |  | [optional] 
**ForwardHost** | Pointer to **string** |  | [optional] 
**ForwardPort** | Pointer to **int64** |  | [optional] 
**CertificateId** | Pointer to [**GetProxyHosts200ResponseInnerCertificateId**](GetProxyHosts200ResponseInnerCertificateId.md) |  | [optional] 
**SslForced** | Pointer to **bool** | Is SSL Forced | [optional] 
**HstsEnabled** | Pointer to **bool** | Is HSTS Enabled | [optional] 
**HstsSubdomains** | Pointer to **bool** | Is HSTS applicable to all subdomains | [optional] 
**TrustForwardedProto** | Pointer to **bool** | Trust the forwarded headers | [optional] 
**Http2Support** | Pointer to **bool** | HTTP2 Protocol Support | [optional] 
**BlockExploits** | Pointer to **bool** | Should we block common exploits | [optional] 
**CachingEnabled** | Pointer to **bool** | Should we cache assets | [optional] 
**AllowWebsocketUpgrade** | Pointer to **bool** | Allow Websocket Upgrade for all paths | [optional] 
**AccessListId** | Pointer to **int64** | Access List ID | [optional] 
**AdvancedConfig** | Pointer to **string** |  | [optional] 
**Enabled** | Pointer to **bool** | Is Enabled | [optional] 
**Meta** | Pointer to **map[string]interface{}** |  | [optional] 
**Locations** | Pointer to [**[]GetProxyHosts200ResponseInnerLocationsInner**](GetProxyHosts200ResponseInnerLocationsInner.md) |  | [optional] 

## Methods

### NewUpdateProxyHostRequest

`func NewUpdateProxyHostRequest() *UpdateProxyHostRequest`

NewUpdateProxyHostRequest instantiates a new UpdateProxyHostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateProxyHostRequestWithDefaults

`func NewUpdateProxyHostRequestWithDefaults() *UpdateProxyHostRequest`

NewUpdateProxyHostRequestWithDefaults instantiates a new UpdateProxyHostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomainNames

`func (o *UpdateProxyHostRequest) GetDomainNames() []string`

GetDomainNames returns the DomainNames field if non-nil, zero value otherwise.

### GetDomainNamesOk

`func (o *UpdateProxyHostRequest) GetDomainNamesOk() (*[]string, bool)`

GetDomainNamesOk returns a tuple with the DomainNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainNames

`func (o *UpdateProxyHostRequest) SetDomainNames(v []string)`

SetDomainNames sets DomainNames field to given value.

### HasDomainNames

`func (o *UpdateProxyHostRequest) HasDomainNames() bool`

HasDomainNames returns a boolean if a field has been set.

### GetForwardScheme

`func (o *UpdateProxyHostRequest) GetForwardScheme() string`

GetForwardScheme returns the ForwardScheme field if non-nil, zero value otherwise.

### GetForwardSchemeOk

`func (o *UpdateProxyHostRequest) GetForwardSchemeOk() (*string, bool)`

GetForwardSchemeOk returns a tuple with the ForwardScheme field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardScheme

`func (o *UpdateProxyHostRequest) SetForwardScheme(v string)`

SetForwardScheme sets ForwardScheme field to given value.

### HasForwardScheme

`func (o *UpdateProxyHostRequest) HasForwardScheme() bool`

HasForwardScheme returns a boolean if a field has been set.

### GetForwardHost

`func (o *UpdateProxyHostRequest) GetForwardHost() string`

GetForwardHost returns the ForwardHost field if non-nil, zero value otherwise.

### GetForwardHostOk

`func (o *UpdateProxyHostRequest) GetForwardHostOk() (*string, bool)`

GetForwardHostOk returns a tuple with the ForwardHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardHost

`func (o *UpdateProxyHostRequest) SetForwardHost(v string)`

SetForwardHost sets ForwardHost field to given value.

### HasForwardHost

`func (o *UpdateProxyHostRequest) HasForwardHost() bool`

HasForwardHost returns a boolean if a field has been set.

### GetForwardPort

`func (o *UpdateProxyHostRequest) GetForwardPort() int64`

GetForwardPort returns the ForwardPort field if non-nil, zero value otherwise.

### GetForwardPortOk

`func (o *UpdateProxyHostRequest) GetForwardPortOk() (*int64, bool)`

GetForwardPortOk returns a tuple with the ForwardPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardPort

`func (o *UpdateProxyHostRequest) SetForwardPort(v int64)`

SetForwardPort sets ForwardPort field to given value.

### HasForwardPort

`func (o *UpdateProxyHostRequest) HasForwardPort() bool`

HasForwardPort returns a boolean if a field has been set.

### GetCertificateId

`func (o *UpdateProxyHostRequest) GetCertificateId() GetProxyHosts200ResponseInnerCertificateId`

GetCertificateId returns the CertificateId field if non-nil, zero value otherwise.

### GetCertificateIdOk

`func (o *UpdateProxyHostRequest) GetCertificateIdOk() (*GetProxyHosts200ResponseInnerCertificateId, bool)`

GetCertificateIdOk returns a tuple with the CertificateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateId

`func (o *UpdateProxyHostRequest) SetCertificateId(v GetProxyHosts200ResponseInnerCertificateId)`

SetCertificateId sets CertificateId field to given value.

### HasCertificateId

`func (o *UpdateProxyHostRequest) HasCertificateId() bool`

HasCertificateId returns a boolean if a field has been set.

### GetSslForced

`func (o *UpdateProxyHostRequest) GetSslForced() bool`

GetSslForced returns the SslForced field if non-nil, zero value otherwise.

### GetSslForcedOk

`func (o *UpdateProxyHostRequest) GetSslForcedOk() (*bool, bool)`

GetSslForcedOk returns a tuple with the SslForced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSslForced

`func (o *UpdateProxyHostRequest) SetSslForced(v bool)`

SetSslForced sets SslForced field to given value.

### HasSslForced

`func (o *UpdateProxyHostRequest) HasSslForced() bool`

HasSslForced returns a boolean if a field has been set.

### GetHstsEnabled

`func (o *UpdateProxyHostRequest) GetHstsEnabled() bool`

GetHstsEnabled returns the HstsEnabled field if non-nil, zero value otherwise.

### GetHstsEnabledOk

`func (o *UpdateProxyHostRequest) GetHstsEnabledOk() (*bool, bool)`

GetHstsEnabledOk returns a tuple with the HstsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHstsEnabled

`func (o *UpdateProxyHostRequest) SetHstsEnabled(v bool)`

SetHstsEnabled sets HstsEnabled field to given value.

### HasHstsEnabled

`func (o *UpdateProxyHostRequest) HasHstsEnabled() bool`

HasHstsEnabled returns a boolean if a field has been set.

### GetHstsSubdomains

`func (o *UpdateProxyHostRequest) GetHstsSubdomains() bool`

GetHstsSubdomains returns the HstsSubdomains field if non-nil, zero value otherwise.

### GetHstsSubdomainsOk

`func (o *UpdateProxyHostRequest) GetHstsSubdomainsOk() (*bool, bool)`

GetHstsSubdomainsOk returns a tuple with the HstsSubdomains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHstsSubdomains

`func (o *UpdateProxyHostRequest) SetHstsSubdomains(v bool)`

SetHstsSubdomains sets HstsSubdomains field to given value.

### HasHstsSubdomains

`func (o *UpdateProxyHostRequest) HasHstsSubdomains() bool`

HasHstsSubdomains returns a boolean if a field has been set.

### GetTrustForwardedProto

`func (o *UpdateProxyHostRequest) GetTrustForwardedProto() bool`

GetTrustForwardedProto returns the TrustForwardedProto field if non-nil, zero value otherwise.

### GetTrustForwardedProtoOk

`func (o *UpdateProxyHostRequest) GetTrustForwardedProtoOk() (*bool, bool)`

GetTrustForwardedProtoOk returns a tuple with the TrustForwardedProto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrustForwardedProto

`func (o *UpdateProxyHostRequest) SetTrustForwardedProto(v bool)`

SetTrustForwardedProto sets TrustForwardedProto field to given value.

### HasTrustForwardedProto

`func (o *UpdateProxyHostRequest) HasTrustForwardedProto() bool`

HasTrustForwardedProto returns a boolean if a field has been set.

### GetHttp2Support

`func (o *UpdateProxyHostRequest) GetHttp2Support() bool`

GetHttp2Support returns the Http2Support field if non-nil, zero value otherwise.

### GetHttp2SupportOk

`func (o *UpdateProxyHostRequest) GetHttp2SupportOk() (*bool, bool)`

GetHttp2SupportOk returns a tuple with the Http2Support field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHttp2Support

`func (o *UpdateProxyHostRequest) SetHttp2Support(v bool)`

SetHttp2Support sets Http2Support field to given value.

### HasHttp2Support

`func (o *UpdateProxyHostRequest) HasHttp2Support() bool`

HasHttp2Support returns a boolean if a field has been set.

### GetBlockExploits

`func (o *UpdateProxyHostRequest) GetBlockExploits() bool`

GetBlockExploits returns the BlockExploits field if non-nil, zero value otherwise.

### GetBlockExploitsOk

`func (o *UpdateProxyHostRequest) GetBlockExploitsOk() (*bool, bool)`

GetBlockExploitsOk returns a tuple with the BlockExploits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockExploits

`func (o *UpdateProxyHostRequest) SetBlockExploits(v bool)`

SetBlockExploits sets BlockExploits field to given value.

### HasBlockExploits

`func (o *UpdateProxyHostRequest) HasBlockExploits() bool`

HasBlockExploits returns a boolean if a field has been set.

### GetCachingEnabled

`func (o *UpdateProxyHostRequest) GetCachingEnabled() bool`

GetCachingEnabled returns the CachingEnabled field if non-nil, zero value otherwise.

### GetCachingEnabledOk

`func (o *UpdateProxyHostRequest) GetCachingEnabledOk() (*bool, bool)`

GetCachingEnabledOk returns a tuple with the CachingEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCachingEnabled

`func (o *UpdateProxyHostRequest) SetCachingEnabled(v bool)`

SetCachingEnabled sets CachingEnabled field to given value.

### HasCachingEnabled

`func (o *UpdateProxyHostRequest) HasCachingEnabled() bool`

HasCachingEnabled returns a boolean if a field has been set.

### GetAllowWebsocketUpgrade

`func (o *UpdateProxyHostRequest) GetAllowWebsocketUpgrade() bool`

GetAllowWebsocketUpgrade returns the AllowWebsocketUpgrade field if non-nil, zero value otherwise.

### GetAllowWebsocketUpgradeOk

`func (o *UpdateProxyHostRequest) GetAllowWebsocketUpgradeOk() (*bool, bool)`

GetAllowWebsocketUpgradeOk returns a tuple with the AllowWebsocketUpgrade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowWebsocketUpgrade

`func (o *UpdateProxyHostRequest) SetAllowWebsocketUpgrade(v bool)`

SetAllowWebsocketUpgrade sets AllowWebsocketUpgrade field to given value.

### HasAllowWebsocketUpgrade

`func (o *UpdateProxyHostRequest) HasAllowWebsocketUpgrade() bool`

HasAllowWebsocketUpgrade returns a boolean if a field has been set.

### GetAccessListId

`func (o *UpdateProxyHostRequest) GetAccessListId() int64`

GetAccessListId returns the AccessListId field if non-nil, zero value otherwise.

### GetAccessListIdOk

`func (o *UpdateProxyHostRequest) GetAccessListIdOk() (*int64, bool)`

GetAccessListIdOk returns a tuple with the AccessListId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessListId

`func (o *UpdateProxyHostRequest) SetAccessListId(v int64)`

SetAccessListId sets AccessListId field to given value.

### HasAccessListId

`func (o *UpdateProxyHostRequest) HasAccessListId() bool`

HasAccessListId returns a boolean if a field has been set.

### GetAdvancedConfig

`func (o *UpdateProxyHostRequest) GetAdvancedConfig() string`

GetAdvancedConfig returns the AdvancedConfig field if non-nil, zero value otherwise.

### GetAdvancedConfigOk

`func (o *UpdateProxyHostRequest) GetAdvancedConfigOk() (*string, bool)`

GetAdvancedConfigOk returns a tuple with the AdvancedConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdvancedConfig

`func (o *UpdateProxyHostRequest) SetAdvancedConfig(v string)`

SetAdvancedConfig sets AdvancedConfig field to given value.

### HasAdvancedConfig

`func (o *UpdateProxyHostRequest) HasAdvancedConfig() bool`

HasAdvancedConfig returns a boolean if a field has been set.

### GetEnabled

`func (o *UpdateProxyHostRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *UpdateProxyHostRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *UpdateProxyHostRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *UpdateProxyHostRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetMeta

`func (o *UpdateProxyHostRequest) GetMeta() map[string]interface{}`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *UpdateProxyHostRequest) GetMetaOk() (*map[string]interface{}, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *UpdateProxyHostRequest) SetMeta(v map[string]interface{})`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *UpdateProxyHostRequest) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### GetLocations

`func (o *UpdateProxyHostRequest) GetLocations() []GetProxyHosts200ResponseInnerLocationsInner`

GetLocations returns the Locations field if non-nil, zero value otherwise.

### GetLocationsOk

`func (o *UpdateProxyHostRequest) GetLocationsOk() (*[]GetProxyHosts200ResponseInnerLocationsInner, bool)`

GetLocationsOk returns a tuple with the Locations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocations

`func (o *UpdateProxyHostRequest) SetLocations(v []GetProxyHosts200ResponseInnerLocationsInner)`

SetLocations sets Locations field to given value.

### HasLocations

`func (o *UpdateProxyHostRequest) HasLocations() bool`

HasLocations returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



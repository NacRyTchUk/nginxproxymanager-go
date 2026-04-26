# CreateProxyHostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DomainNames** | **[]string** | Domain Names separated by a comma | 
**ForwardScheme** | **string** |  | 
**ForwardHost** | **string** |  | 
**ForwardPort** | **int64** |  | 
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

### NewCreateProxyHostRequest

`func NewCreateProxyHostRequest(domainNames []string, forwardScheme string, forwardHost string, forwardPort int64, ) *CreateProxyHostRequest`

NewCreateProxyHostRequest instantiates a new CreateProxyHostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateProxyHostRequestWithDefaults

`func NewCreateProxyHostRequestWithDefaults() *CreateProxyHostRequest`

NewCreateProxyHostRequestWithDefaults instantiates a new CreateProxyHostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomainNames

`func (o *CreateProxyHostRequest) GetDomainNames() []string`

GetDomainNames returns the DomainNames field if non-nil, zero value otherwise.

### GetDomainNamesOk

`func (o *CreateProxyHostRequest) GetDomainNamesOk() (*[]string, bool)`

GetDomainNamesOk returns a tuple with the DomainNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainNames

`func (o *CreateProxyHostRequest) SetDomainNames(v []string)`

SetDomainNames sets DomainNames field to given value.


### GetForwardScheme

`func (o *CreateProxyHostRequest) GetForwardScheme() string`

GetForwardScheme returns the ForwardScheme field if non-nil, zero value otherwise.

### GetForwardSchemeOk

`func (o *CreateProxyHostRequest) GetForwardSchemeOk() (*string, bool)`

GetForwardSchemeOk returns a tuple with the ForwardScheme field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardScheme

`func (o *CreateProxyHostRequest) SetForwardScheme(v string)`

SetForwardScheme sets ForwardScheme field to given value.


### GetForwardHost

`func (o *CreateProxyHostRequest) GetForwardHost() string`

GetForwardHost returns the ForwardHost field if non-nil, zero value otherwise.

### GetForwardHostOk

`func (o *CreateProxyHostRequest) GetForwardHostOk() (*string, bool)`

GetForwardHostOk returns a tuple with the ForwardHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardHost

`func (o *CreateProxyHostRequest) SetForwardHost(v string)`

SetForwardHost sets ForwardHost field to given value.


### GetForwardPort

`func (o *CreateProxyHostRequest) GetForwardPort() int64`

GetForwardPort returns the ForwardPort field if non-nil, zero value otherwise.

### GetForwardPortOk

`func (o *CreateProxyHostRequest) GetForwardPortOk() (*int64, bool)`

GetForwardPortOk returns a tuple with the ForwardPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardPort

`func (o *CreateProxyHostRequest) SetForwardPort(v int64)`

SetForwardPort sets ForwardPort field to given value.


### GetCertificateId

`func (o *CreateProxyHostRequest) GetCertificateId() GetProxyHosts200ResponseInnerCertificateId`

GetCertificateId returns the CertificateId field if non-nil, zero value otherwise.

### GetCertificateIdOk

`func (o *CreateProxyHostRequest) GetCertificateIdOk() (*GetProxyHosts200ResponseInnerCertificateId, bool)`

GetCertificateIdOk returns a tuple with the CertificateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateId

`func (o *CreateProxyHostRequest) SetCertificateId(v GetProxyHosts200ResponseInnerCertificateId)`

SetCertificateId sets CertificateId field to given value.

### HasCertificateId

`func (o *CreateProxyHostRequest) HasCertificateId() bool`

HasCertificateId returns a boolean if a field has been set.

### GetSslForced

`func (o *CreateProxyHostRequest) GetSslForced() bool`

GetSslForced returns the SslForced field if non-nil, zero value otherwise.

### GetSslForcedOk

`func (o *CreateProxyHostRequest) GetSslForcedOk() (*bool, bool)`

GetSslForcedOk returns a tuple with the SslForced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSslForced

`func (o *CreateProxyHostRequest) SetSslForced(v bool)`

SetSslForced sets SslForced field to given value.

### HasSslForced

`func (o *CreateProxyHostRequest) HasSslForced() bool`

HasSslForced returns a boolean if a field has been set.

### GetHstsEnabled

`func (o *CreateProxyHostRequest) GetHstsEnabled() bool`

GetHstsEnabled returns the HstsEnabled field if non-nil, zero value otherwise.

### GetHstsEnabledOk

`func (o *CreateProxyHostRequest) GetHstsEnabledOk() (*bool, bool)`

GetHstsEnabledOk returns a tuple with the HstsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHstsEnabled

`func (o *CreateProxyHostRequest) SetHstsEnabled(v bool)`

SetHstsEnabled sets HstsEnabled field to given value.

### HasHstsEnabled

`func (o *CreateProxyHostRequest) HasHstsEnabled() bool`

HasHstsEnabled returns a boolean if a field has been set.

### GetHstsSubdomains

`func (o *CreateProxyHostRequest) GetHstsSubdomains() bool`

GetHstsSubdomains returns the HstsSubdomains field if non-nil, zero value otherwise.

### GetHstsSubdomainsOk

`func (o *CreateProxyHostRequest) GetHstsSubdomainsOk() (*bool, bool)`

GetHstsSubdomainsOk returns a tuple with the HstsSubdomains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHstsSubdomains

`func (o *CreateProxyHostRequest) SetHstsSubdomains(v bool)`

SetHstsSubdomains sets HstsSubdomains field to given value.

### HasHstsSubdomains

`func (o *CreateProxyHostRequest) HasHstsSubdomains() bool`

HasHstsSubdomains returns a boolean if a field has been set.

### GetTrustForwardedProto

`func (o *CreateProxyHostRequest) GetTrustForwardedProto() bool`

GetTrustForwardedProto returns the TrustForwardedProto field if non-nil, zero value otherwise.

### GetTrustForwardedProtoOk

`func (o *CreateProxyHostRequest) GetTrustForwardedProtoOk() (*bool, bool)`

GetTrustForwardedProtoOk returns a tuple with the TrustForwardedProto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrustForwardedProto

`func (o *CreateProxyHostRequest) SetTrustForwardedProto(v bool)`

SetTrustForwardedProto sets TrustForwardedProto field to given value.

### HasTrustForwardedProto

`func (o *CreateProxyHostRequest) HasTrustForwardedProto() bool`

HasTrustForwardedProto returns a boolean if a field has been set.

### GetHttp2Support

`func (o *CreateProxyHostRequest) GetHttp2Support() bool`

GetHttp2Support returns the Http2Support field if non-nil, zero value otherwise.

### GetHttp2SupportOk

`func (o *CreateProxyHostRequest) GetHttp2SupportOk() (*bool, bool)`

GetHttp2SupportOk returns a tuple with the Http2Support field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHttp2Support

`func (o *CreateProxyHostRequest) SetHttp2Support(v bool)`

SetHttp2Support sets Http2Support field to given value.

### HasHttp2Support

`func (o *CreateProxyHostRequest) HasHttp2Support() bool`

HasHttp2Support returns a boolean if a field has been set.

### GetBlockExploits

`func (o *CreateProxyHostRequest) GetBlockExploits() bool`

GetBlockExploits returns the BlockExploits field if non-nil, zero value otherwise.

### GetBlockExploitsOk

`func (o *CreateProxyHostRequest) GetBlockExploitsOk() (*bool, bool)`

GetBlockExploitsOk returns a tuple with the BlockExploits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockExploits

`func (o *CreateProxyHostRequest) SetBlockExploits(v bool)`

SetBlockExploits sets BlockExploits field to given value.

### HasBlockExploits

`func (o *CreateProxyHostRequest) HasBlockExploits() bool`

HasBlockExploits returns a boolean if a field has been set.

### GetCachingEnabled

`func (o *CreateProxyHostRequest) GetCachingEnabled() bool`

GetCachingEnabled returns the CachingEnabled field if non-nil, zero value otherwise.

### GetCachingEnabledOk

`func (o *CreateProxyHostRequest) GetCachingEnabledOk() (*bool, bool)`

GetCachingEnabledOk returns a tuple with the CachingEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCachingEnabled

`func (o *CreateProxyHostRequest) SetCachingEnabled(v bool)`

SetCachingEnabled sets CachingEnabled field to given value.

### HasCachingEnabled

`func (o *CreateProxyHostRequest) HasCachingEnabled() bool`

HasCachingEnabled returns a boolean if a field has been set.

### GetAllowWebsocketUpgrade

`func (o *CreateProxyHostRequest) GetAllowWebsocketUpgrade() bool`

GetAllowWebsocketUpgrade returns the AllowWebsocketUpgrade field if non-nil, zero value otherwise.

### GetAllowWebsocketUpgradeOk

`func (o *CreateProxyHostRequest) GetAllowWebsocketUpgradeOk() (*bool, bool)`

GetAllowWebsocketUpgradeOk returns a tuple with the AllowWebsocketUpgrade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowWebsocketUpgrade

`func (o *CreateProxyHostRequest) SetAllowWebsocketUpgrade(v bool)`

SetAllowWebsocketUpgrade sets AllowWebsocketUpgrade field to given value.

### HasAllowWebsocketUpgrade

`func (o *CreateProxyHostRequest) HasAllowWebsocketUpgrade() bool`

HasAllowWebsocketUpgrade returns a boolean if a field has been set.

### GetAccessListId

`func (o *CreateProxyHostRequest) GetAccessListId() int64`

GetAccessListId returns the AccessListId field if non-nil, zero value otherwise.

### GetAccessListIdOk

`func (o *CreateProxyHostRequest) GetAccessListIdOk() (*int64, bool)`

GetAccessListIdOk returns a tuple with the AccessListId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessListId

`func (o *CreateProxyHostRequest) SetAccessListId(v int64)`

SetAccessListId sets AccessListId field to given value.

### HasAccessListId

`func (o *CreateProxyHostRequest) HasAccessListId() bool`

HasAccessListId returns a boolean if a field has been set.

### GetAdvancedConfig

`func (o *CreateProxyHostRequest) GetAdvancedConfig() string`

GetAdvancedConfig returns the AdvancedConfig field if non-nil, zero value otherwise.

### GetAdvancedConfigOk

`func (o *CreateProxyHostRequest) GetAdvancedConfigOk() (*string, bool)`

GetAdvancedConfigOk returns a tuple with the AdvancedConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdvancedConfig

`func (o *CreateProxyHostRequest) SetAdvancedConfig(v string)`

SetAdvancedConfig sets AdvancedConfig field to given value.

### HasAdvancedConfig

`func (o *CreateProxyHostRequest) HasAdvancedConfig() bool`

HasAdvancedConfig returns a boolean if a field has been set.

### GetEnabled

`func (o *CreateProxyHostRequest) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateProxyHostRequest) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateProxyHostRequest) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateProxyHostRequest) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetMeta

`func (o *CreateProxyHostRequest) GetMeta() map[string]interface{}`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *CreateProxyHostRequest) GetMetaOk() (*map[string]interface{}, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *CreateProxyHostRequest) SetMeta(v map[string]interface{})`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *CreateProxyHostRequest) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### GetLocations

`func (o *CreateProxyHostRequest) GetLocations() []GetProxyHosts200ResponseInnerLocationsInner`

GetLocations returns the Locations field if non-nil, zero value otherwise.

### GetLocationsOk

`func (o *CreateProxyHostRequest) GetLocationsOk() (*[]GetProxyHosts200ResponseInnerLocationsInner, bool)`

GetLocationsOk returns a tuple with the Locations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocations

`func (o *CreateProxyHostRequest) SetLocations(v []GetProxyHosts200ResponseInnerLocationsInner)`

SetLocations sets Locations field to given value.

### HasLocations

`func (o *CreateProxyHostRequest) HasLocations() bool`

HasLocations returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



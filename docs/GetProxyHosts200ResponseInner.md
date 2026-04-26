# GetProxyHosts200ResponseInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int64** | Unique identifier | [readonly] 
**CreatedOn** | **string** | Date and time of creation | [readonly] 
**ModifiedOn** | **string** | Date and time of last update | [readonly] 
**OwnerUserId** | **int64** | User ID | 
**DomainNames** | **[]string** | Domain Names separated by a comma | 
**ForwardHost** | **string** |  | 
**ForwardPort** | **int64** |  | 
**AccessListId** | **int64** | Access List ID | 
**CertificateId** | [**GetProxyHosts200ResponseInnerCertificateId**](GetProxyHosts200ResponseInnerCertificateId.md) |  | 
**SslForced** | **bool** | Is SSL Forced | 
**CachingEnabled** | **bool** | Should we cache assets | 
**BlockExploits** | **bool** | Should we block common exploits | 
**AdvancedConfig** | **string** |  | 
**Meta** | **map[string]interface{}** |  | 
**AllowWebsocketUpgrade** | **bool** | Allow Websocket Upgrade for all paths | 
**Http2Support** | **bool** | HTTP2 Protocol Support | 
**ForwardScheme** | **string** |  | 
**Enabled** | **bool** | Is Enabled | 
**Locations** | [**[]GetProxyHosts200ResponseInnerLocationsInner**](GetProxyHosts200ResponseInnerLocationsInner.md) |  | 
**HstsEnabled** | **bool** | Is HSTS Enabled | 
**HstsSubdomains** | **bool** | Is HSTS applicable to all subdomains | 
**TrustForwardedProto** | **bool** | Trust the forwarded headers | 
**Certificate** | Pointer to [**NullableGetProxyHosts200ResponseInnerCertificate**](GetProxyHosts200ResponseInnerCertificate.md) |  | [optional] 
**Owner** | Pointer to [**GetAuditLogs200ResponseInnerUser**](GetAuditLogs200ResponseInnerUser.md) |  | [optional] 
**AccessList** | Pointer to [**NullableGetProxyHosts200ResponseInnerAccessList**](GetProxyHosts200ResponseInnerAccessList.md) |  | [optional] 

## Methods

### NewGetProxyHosts200ResponseInner

`func NewGetProxyHosts200ResponseInner(id int64, createdOn string, modifiedOn string, ownerUserId int64, domainNames []string, forwardHost string, forwardPort int64, accessListId int64, certificateId GetProxyHosts200ResponseInnerCertificateId, sslForced bool, cachingEnabled bool, blockExploits bool, advancedConfig string, meta map[string]interface{}, allowWebsocketUpgrade bool, http2Support bool, forwardScheme string, enabled bool, locations []GetProxyHosts200ResponseInnerLocationsInner, hstsEnabled bool, hstsSubdomains bool, trustForwardedProto bool, ) *GetProxyHosts200ResponseInner`

NewGetProxyHosts200ResponseInner instantiates a new GetProxyHosts200ResponseInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetProxyHosts200ResponseInnerWithDefaults

`func NewGetProxyHosts200ResponseInnerWithDefaults() *GetProxyHosts200ResponseInner`

NewGetProxyHosts200ResponseInnerWithDefaults instantiates a new GetProxyHosts200ResponseInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetProxyHosts200ResponseInner) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetProxyHosts200ResponseInner) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetProxyHosts200ResponseInner) SetId(v int64)`

SetId sets Id field to given value.


### GetCreatedOn

`func (o *GetProxyHosts200ResponseInner) GetCreatedOn() string`

GetCreatedOn returns the CreatedOn field if non-nil, zero value otherwise.

### GetCreatedOnOk

`func (o *GetProxyHosts200ResponseInner) GetCreatedOnOk() (*string, bool)`

GetCreatedOnOk returns a tuple with the CreatedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedOn

`func (o *GetProxyHosts200ResponseInner) SetCreatedOn(v string)`

SetCreatedOn sets CreatedOn field to given value.


### GetModifiedOn

`func (o *GetProxyHosts200ResponseInner) GetModifiedOn() string`

GetModifiedOn returns the ModifiedOn field if non-nil, zero value otherwise.

### GetModifiedOnOk

`func (o *GetProxyHosts200ResponseInner) GetModifiedOnOk() (*string, bool)`

GetModifiedOnOk returns a tuple with the ModifiedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedOn

`func (o *GetProxyHosts200ResponseInner) SetModifiedOn(v string)`

SetModifiedOn sets ModifiedOn field to given value.


### GetOwnerUserId

`func (o *GetProxyHosts200ResponseInner) GetOwnerUserId() int64`

GetOwnerUserId returns the OwnerUserId field if non-nil, zero value otherwise.

### GetOwnerUserIdOk

`func (o *GetProxyHosts200ResponseInner) GetOwnerUserIdOk() (*int64, bool)`

GetOwnerUserIdOk returns a tuple with the OwnerUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerUserId

`func (o *GetProxyHosts200ResponseInner) SetOwnerUserId(v int64)`

SetOwnerUserId sets OwnerUserId field to given value.


### GetDomainNames

`func (o *GetProxyHosts200ResponseInner) GetDomainNames() []string`

GetDomainNames returns the DomainNames field if non-nil, zero value otherwise.

### GetDomainNamesOk

`func (o *GetProxyHosts200ResponseInner) GetDomainNamesOk() (*[]string, bool)`

GetDomainNamesOk returns a tuple with the DomainNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainNames

`func (o *GetProxyHosts200ResponseInner) SetDomainNames(v []string)`

SetDomainNames sets DomainNames field to given value.


### GetForwardHost

`func (o *GetProxyHosts200ResponseInner) GetForwardHost() string`

GetForwardHost returns the ForwardHost field if non-nil, zero value otherwise.

### GetForwardHostOk

`func (o *GetProxyHosts200ResponseInner) GetForwardHostOk() (*string, bool)`

GetForwardHostOk returns a tuple with the ForwardHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardHost

`func (o *GetProxyHosts200ResponseInner) SetForwardHost(v string)`

SetForwardHost sets ForwardHost field to given value.


### GetForwardPort

`func (o *GetProxyHosts200ResponseInner) GetForwardPort() int64`

GetForwardPort returns the ForwardPort field if non-nil, zero value otherwise.

### GetForwardPortOk

`func (o *GetProxyHosts200ResponseInner) GetForwardPortOk() (*int64, bool)`

GetForwardPortOk returns a tuple with the ForwardPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardPort

`func (o *GetProxyHosts200ResponseInner) SetForwardPort(v int64)`

SetForwardPort sets ForwardPort field to given value.


### GetAccessListId

`func (o *GetProxyHosts200ResponseInner) GetAccessListId() int64`

GetAccessListId returns the AccessListId field if non-nil, zero value otherwise.

### GetAccessListIdOk

`func (o *GetProxyHosts200ResponseInner) GetAccessListIdOk() (*int64, bool)`

GetAccessListIdOk returns a tuple with the AccessListId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessListId

`func (o *GetProxyHosts200ResponseInner) SetAccessListId(v int64)`

SetAccessListId sets AccessListId field to given value.


### GetCertificateId

`func (o *GetProxyHosts200ResponseInner) GetCertificateId() GetProxyHosts200ResponseInnerCertificateId`

GetCertificateId returns the CertificateId field if non-nil, zero value otherwise.

### GetCertificateIdOk

`func (o *GetProxyHosts200ResponseInner) GetCertificateIdOk() (*GetProxyHosts200ResponseInnerCertificateId, bool)`

GetCertificateIdOk returns a tuple with the CertificateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateId

`func (o *GetProxyHosts200ResponseInner) SetCertificateId(v GetProxyHosts200ResponseInnerCertificateId)`

SetCertificateId sets CertificateId field to given value.


### GetSslForced

`func (o *GetProxyHosts200ResponseInner) GetSslForced() bool`

GetSslForced returns the SslForced field if non-nil, zero value otherwise.

### GetSslForcedOk

`func (o *GetProxyHosts200ResponseInner) GetSslForcedOk() (*bool, bool)`

GetSslForcedOk returns a tuple with the SslForced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSslForced

`func (o *GetProxyHosts200ResponseInner) SetSslForced(v bool)`

SetSslForced sets SslForced field to given value.


### GetCachingEnabled

`func (o *GetProxyHosts200ResponseInner) GetCachingEnabled() bool`

GetCachingEnabled returns the CachingEnabled field if non-nil, zero value otherwise.

### GetCachingEnabledOk

`func (o *GetProxyHosts200ResponseInner) GetCachingEnabledOk() (*bool, bool)`

GetCachingEnabledOk returns a tuple with the CachingEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCachingEnabled

`func (o *GetProxyHosts200ResponseInner) SetCachingEnabled(v bool)`

SetCachingEnabled sets CachingEnabled field to given value.


### GetBlockExploits

`func (o *GetProxyHosts200ResponseInner) GetBlockExploits() bool`

GetBlockExploits returns the BlockExploits field if non-nil, zero value otherwise.

### GetBlockExploitsOk

`func (o *GetProxyHosts200ResponseInner) GetBlockExploitsOk() (*bool, bool)`

GetBlockExploitsOk returns a tuple with the BlockExploits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockExploits

`func (o *GetProxyHosts200ResponseInner) SetBlockExploits(v bool)`

SetBlockExploits sets BlockExploits field to given value.


### GetAdvancedConfig

`func (o *GetProxyHosts200ResponseInner) GetAdvancedConfig() string`

GetAdvancedConfig returns the AdvancedConfig field if non-nil, zero value otherwise.

### GetAdvancedConfigOk

`func (o *GetProxyHosts200ResponseInner) GetAdvancedConfigOk() (*string, bool)`

GetAdvancedConfigOk returns a tuple with the AdvancedConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdvancedConfig

`func (o *GetProxyHosts200ResponseInner) SetAdvancedConfig(v string)`

SetAdvancedConfig sets AdvancedConfig field to given value.


### GetMeta

`func (o *GetProxyHosts200ResponseInner) GetMeta() map[string]interface{}`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetProxyHosts200ResponseInner) GetMetaOk() (*map[string]interface{}, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetProxyHosts200ResponseInner) SetMeta(v map[string]interface{})`

SetMeta sets Meta field to given value.


### GetAllowWebsocketUpgrade

`func (o *GetProxyHosts200ResponseInner) GetAllowWebsocketUpgrade() bool`

GetAllowWebsocketUpgrade returns the AllowWebsocketUpgrade field if non-nil, zero value otherwise.

### GetAllowWebsocketUpgradeOk

`func (o *GetProxyHosts200ResponseInner) GetAllowWebsocketUpgradeOk() (*bool, bool)`

GetAllowWebsocketUpgradeOk returns a tuple with the AllowWebsocketUpgrade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowWebsocketUpgrade

`func (o *GetProxyHosts200ResponseInner) SetAllowWebsocketUpgrade(v bool)`

SetAllowWebsocketUpgrade sets AllowWebsocketUpgrade field to given value.


### GetHttp2Support

`func (o *GetProxyHosts200ResponseInner) GetHttp2Support() bool`

GetHttp2Support returns the Http2Support field if non-nil, zero value otherwise.

### GetHttp2SupportOk

`func (o *GetProxyHosts200ResponseInner) GetHttp2SupportOk() (*bool, bool)`

GetHttp2SupportOk returns a tuple with the Http2Support field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHttp2Support

`func (o *GetProxyHosts200ResponseInner) SetHttp2Support(v bool)`

SetHttp2Support sets Http2Support field to given value.


### GetForwardScheme

`func (o *GetProxyHosts200ResponseInner) GetForwardScheme() string`

GetForwardScheme returns the ForwardScheme field if non-nil, zero value otherwise.

### GetForwardSchemeOk

`func (o *GetProxyHosts200ResponseInner) GetForwardSchemeOk() (*string, bool)`

GetForwardSchemeOk returns a tuple with the ForwardScheme field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardScheme

`func (o *GetProxyHosts200ResponseInner) SetForwardScheme(v string)`

SetForwardScheme sets ForwardScheme field to given value.


### GetEnabled

`func (o *GetProxyHosts200ResponseInner) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *GetProxyHosts200ResponseInner) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *GetProxyHosts200ResponseInner) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetLocations

`func (o *GetProxyHosts200ResponseInner) GetLocations() []GetProxyHosts200ResponseInnerLocationsInner`

GetLocations returns the Locations field if non-nil, zero value otherwise.

### GetLocationsOk

`func (o *GetProxyHosts200ResponseInner) GetLocationsOk() (*[]GetProxyHosts200ResponseInnerLocationsInner, bool)`

GetLocationsOk returns a tuple with the Locations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocations

`func (o *GetProxyHosts200ResponseInner) SetLocations(v []GetProxyHosts200ResponseInnerLocationsInner)`

SetLocations sets Locations field to given value.


### GetHstsEnabled

`func (o *GetProxyHosts200ResponseInner) GetHstsEnabled() bool`

GetHstsEnabled returns the HstsEnabled field if non-nil, zero value otherwise.

### GetHstsEnabledOk

`func (o *GetProxyHosts200ResponseInner) GetHstsEnabledOk() (*bool, bool)`

GetHstsEnabledOk returns a tuple with the HstsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHstsEnabled

`func (o *GetProxyHosts200ResponseInner) SetHstsEnabled(v bool)`

SetHstsEnabled sets HstsEnabled field to given value.


### GetHstsSubdomains

`func (o *GetProxyHosts200ResponseInner) GetHstsSubdomains() bool`

GetHstsSubdomains returns the HstsSubdomains field if non-nil, zero value otherwise.

### GetHstsSubdomainsOk

`func (o *GetProxyHosts200ResponseInner) GetHstsSubdomainsOk() (*bool, bool)`

GetHstsSubdomainsOk returns a tuple with the HstsSubdomains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHstsSubdomains

`func (o *GetProxyHosts200ResponseInner) SetHstsSubdomains(v bool)`

SetHstsSubdomains sets HstsSubdomains field to given value.


### GetTrustForwardedProto

`func (o *GetProxyHosts200ResponseInner) GetTrustForwardedProto() bool`

GetTrustForwardedProto returns the TrustForwardedProto field if non-nil, zero value otherwise.

### GetTrustForwardedProtoOk

`func (o *GetProxyHosts200ResponseInner) GetTrustForwardedProtoOk() (*bool, bool)`

GetTrustForwardedProtoOk returns a tuple with the TrustForwardedProto field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrustForwardedProto

`func (o *GetProxyHosts200ResponseInner) SetTrustForwardedProto(v bool)`

SetTrustForwardedProto sets TrustForwardedProto field to given value.


### GetCertificate

`func (o *GetProxyHosts200ResponseInner) GetCertificate() GetProxyHosts200ResponseInnerCertificate`

GetCertificate returns the Certificate field if non-nil, zero value otherwise.

### GetCertificateOk

`func (o *GetProxyHosts200ResponseInner) GetCertificateOk() (*GetProxyHosts200ResponseInnerCertificate, bool)`

GetCertificateOk returns a tuple with the Certificate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificate

`func (o *GetProxyHosts200ResponseInner) SetCertificate(v GetProxyHosts200ResponseInnerCertificate)`

SetCertificate sets Certificate field to given value.

### HasCertificate

`func (o *GetProxyHosts200ResponseInner) HasCertificate() bool`

HasCertificate returns a boolean if a field has been set.

### SetCertificateNil

`func (o *GetProxyHosts200ResponseInner) SetCertificateNil(b bool)`

 SetCertificateNil sets the value for Certificate to be an explicit nil

### UnsetCertificate
`func (o *GetProxyHosts200ResponseInner) UnsetCertificate()`

UnsetCertificate ensures that no value is present for Certificate, not even an explicit nil
### GetOwner

`func (o *GetProxyHosts200ResponseInner) GetOwner() GetAuditLogs200ResponseInnerUser`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *GetProxyHosts200ResponseInner) GetOwnerOk() (*GetAuditLogs200ResponseInnerUser, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *GetProxyHosts200ResponseInner) SetOwner(v GetAuditLogs200ResponseInnerUser)`

SetOwner sets Owner field to given value.

### HasOwner

`func (o *GetProxyHosts200ResponseInner) HasOwner() bool`

HasOwner returns a boolean if a field has been set.

### GetAccessList

`func (o *GetProxyHosts200ResponseInner) GetAccessList() GetProxyHosts200ResponseInnerAccessList`

GetAccessList returns the AccessList field if non-nil, zero value otherwise.

### GetAccessListOk

`func (o *GetProxyHosts200ResponseInner) GetAccessListOk() (*GetProxyHosts200ResponseInnerAccessList, bool)`

GetAccessListOk returns a tuple with the AccessList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessList

`func (o *GetProxyHosts200ResponseInner) SetAccessList(v GetProxyHosts200ResponseInnerAccessList)`

SetAccessList sets AccessList field to given value.

### HasAccessList

`func (o *GetProxyHosts200ResponseInner) HasAccessList() bool`

HasAccessList returns a boolean if a field has been set.

### SetAccessListNil

`func (o *GetProxyHosts200ResponseInner) SetAccessListNil(b bool)`

 SetAccessListNil sets the value for AccessList to be an explicit nil

### UnsetAccessList
`func (o *GetProxyHosts200ResponseInner) UnsetAccessList()`

UnsetAccessList ensures that no value is present for AccessList, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



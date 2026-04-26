# GetRedirectionHosts200ResponseInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int64** | Unique identifier | [readonly] 
**CreatedOn** | **string** | Date and time of creation | [readonly] 
**ModifiedOn** | **string** | Date and time of last update | [readonly] 
**OwnerUserId** | **int64** | User ID | 
**DomainNames** | **[]string** | Domain Names separated by a comma | 
**ForwardHttpCode** | **int64** | Redirect HTTP Status Code | 
**ForwardScheme** | **string** |  | 
**ForwardDomainName** | **string** | Domain Name | 
**PreservePath** | **bool** | Should the path be preserved | 
**CertificateId** | [**GetProxyHosts200ResponseInnerCertificateId**](GetProxyHosts200ResponseInnerCertificateId.md) |  | 
**SslForced** | **bool** | Is SSL Forced | 
**HstsEnabled** | **bool** | Is HSTS Enabled | 
**HstsSubdomains** | **bool** | Is HSTS applicable to all subdomains | 
**Http2Support** | **bool** | HTTP2 Protocol Support | 
**BlockExploits** | **bool** | Should we block common exploits | 
**AdvancedConfig** | **string** |  | 
**Enabled** | **bool** | Is Enabled | 
**Meta** | **map[string]interface{}** |  | 
**Certificate** | Pointer to [**NullableGetProxyHosts200ResponseInnerCertificate**](GetProxyHosts200ResponseInnerCertificate.md) |  | [optional] 
**Owner** | Pointer to [**GetAuditLogs200ResponseInnerUser**](GetAuditLogs200ResponseInnerUser.md) |  | [optional] 

## Methods

### NewGetRedirectionHosts200ResponseInner

`func NewGetRedirectionHosts200ResponseInner(id int64, createdOn string, modifiedOn string, ownerUserId int64, domainNames []string, forwardHttpCode int64, forwardScheme string, forwardDomainName string, preservePath bool, certificateId GetProxyHosts200ResponseInnerCertificateId, sslForced bool, hstsEnabled bool, hstsSubdomains bool, http2Support bool, blockExploits bool, advancedConfig string, enabled bool, meta map[string]interface{}, ) *GetRedirectionHosts200ResponseInner`

NewGetRedirectionHosts200ResponseInner instantiates a new GetRedirectionHosts200ResponseInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetRedirectionHosts200ResponseInnerWithDefaults

`func NewGetRedirectionHosts200ResponseInnerWithDefaults() *GetRedirectionHosts200ResponseInner`

NewGetRedirectionHosts200ResponseInnerWithDefaults instantiates a new GetRedirectionHosts200ResponseInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetRedirectionHosts200ResponseInner) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetRedirectionHosts200ResponseInner) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetRedirectionHosts200ResponseInner) SetId(v int64)`

SetId sets Id field to given value.


### GetCreatedOn

`func (o *GetRedirectionHosts200ResponseInner) GetCreatedOn() string`

GetCreatedOn returns the CreatedOn field if non-nil, zero value otherwise.

### GetCreatedOnOk

`func (o *GetRedirectionHosts200ResponseInner) GetCreatedOnOk() (*string, bool)`

GetCreatedOnOk returns a tuple with the CreatedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedOn

`func (o *GetRedirectionHosts200ResponseInner) SetCreatedOn(v string)`

SetCreatedOn sets CreatedOn field to given value.


### GetModifiedOn

`func (o *GetRedirectionHosts200ResponseInner) GetModifiedOn() string`

GetModifiedOn returns the ModifiedOn field if non-nil, zero value otherwise.

### GetModifiedOnOk

`func (o *GetRedirectionHosts200ResponseInner) GetModifiedOnOk() (*string, bool)`

GetModifiedOnOk returns a tuple with the ModifiedOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiedOn

`func (o *GetRedirectionHosts200ResponseInner) SetModifiedOn(v string)`

SetModifiedOn sets ModifiedOn field to given value.


### GetOwnerUserId

`func (o *GetRedirectionHosts200ResponseInner) GetOwnerUserId() int64`

GetOwnerUserId returns the OwnerUserId field if non-nil, zero value otherwise.

### GetOwnerUserIdOk

`func (o *GetRedirectionHosts200ResponseInner) GetOwnerUserIdOk() (*int64, bool)`

GetOwnerUserIdOk returns a tuple with the OwnerUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerUserId

`func (o *GetRedirectionHosts200ResponseInner) SetOwnerUserId(v int64)`

SetOwnerUserId sets OwnerUserId field to given value.


### GetDomainNames

`func (o *GetRedirectionHosts200ResponseInner) GetDomainNames() []string`

GetDomainNames returns the DomainNames field if non-nil, zero value otherwise.

### GetDomainNamesOk

`func (o *GetRedirectionHosts200ResponseInner) GetDomainNamesOk() (*[]string, bool)`

GetDomainNamesOk returns a tuple with the DomainNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainNames

`func (o *GetRedirectionHosts200ResponseInner) SetDomainNames(v []string)`

SetDomainNames sets DomainNames field to given value.


### GetForwardHttpCode

`func (o *GetRedirectionHosts200ResponseInner) GetForwardHttpCode() int64`

GetForwardHttpCode returns the ForwardHttpCode field if non-nil, zero value otherwise.

### GetForwardHttpCodeOk

`func (o *GetRedirectionHosts200ResponseInner) GetForwardHttpCodeOk() (*int64, bool)`

GetForwardHttpCodeOk returns a tuple with the ForwardHttpCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardHttpCode

`func (o *GetRedirectionHosts200ResponseInner) SetForwardHttpCode(v int64)`

SetForwardHttpCode sets ForwardHttpCode field to given value.


### GetForwardScheme

`func (o *GetRedirectionHosts200ResponseInner) GetForwardScheme() string`

GetForwardScheme returns the ForwardScheme field if non-nil, zero value otherwise.

### GetForwardSchemeOk

`func (o *GetRedirectionHosts200ResponseInner) GetForwardSchemeOk() (*string, bool)`

GetForwardSchemeOk returns a tuple with the ForwardScheme field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardScheme

`func (o *GetRedirectionHosts200ResponseInner) SetForwardScheme(v string)`

SetForwardScheme sets ForwardScheme field to given value.


### GetForwardDomainName

`func (o *GetRedirectionHosts200ResponseInner) GetForwardDomainName() string`

GetForwardDomainName returns the ForwardDomainName field if non-nil, zero value otherwise.

### GetForwardDomainNameOk

`func (o *GetRedirectionHosts200ResponseInner) GetForwardDomainNameOk() (*string, bool)`

GetForwardDomainNameOk returns a tuple with the ForwardDomainName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardDomainName

`func (o *GetRedirectionHosts200ResponseInner) SetForwardDomainName(v string)`

SetForwardDomainName sets ForwardDomainName field to given value.


### GetPreservePath

`func (o *GetRedirectionHosts200ResponseInner) GetPreservePath() bool`

GetPreservePath returns the PreservePath field if non-nil, zero value otherwise.

### GetPreservePathOk

`func (o *GetRedirectionHosts200ResponseInner) GetPreservePathOk() (*bool, bool)`

GetPreservePathOk returns a tuple with the PreservePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreservePath

`func (o *GetRedirectionHosts200ResponseInner) SetPreservePath(v bool)`

SetPreservePath sets PreservePath field to given value.


### GetCertificateId

`func (o *GetRedirectionHosts200ResponseInner) GetCertificateId() GetProxyHosts200ResponseInnerCertificateId`

GetCertificateId returns the CertificateId field if non-nil, zero value otherwise.

### GetCertificateIdOk

`func (o *GetRedirectionHosts200ResponseInner) GetCertificateIdOk() (*GetProxyHosts200ResponseInnerCertificateId, bool)`

GetCertificateIdOk returns a tuple with the CertificateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateId

`func (o *GetRedirectionHosts200ResponseInner) SetCertificateId(v GetProxyHosts200ResponseInnerCertificateId)`

SetCertificateId sets CertificateId field to given value.


### GetSslForced

`func (o *GetRedirectionHosts200ResponseInner) GetSslForced() bool`

GetSslForced returns the SslForced field if non-nil, zero value otherwise.

### GetSslForcedOk

`func (o *GetRedirectionHosts200ResponseInner) GetSslForcedOk() (*bool, bool)`

GetSslForcedOk returns a tuple with the SslForced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSslForced

`func (o *GetRedirectionHosts200ResponseInner) SetSslForced(v bool)`

SetSslForced sets SslForced field to given value.


### GetHstsEnabled

`func (o *GetRedirectionHosts200ResponseInner) GetHstsEnabled() bool`

GetHstsEnabled returns the HstsEnabled field if non-nil, zero value otherwise.

### GetHstsEnabledOk

`func (o *GetRedirectionHosts200ResponseInner) GetHstsEnabledOk() (*bool, bool)`

GetHstsEnabledOk returns a tuple with the HstsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHstsEnabled

`func (o *GetRedirectionHosts200ResponseInner) SetHstsEnabled(v bool)`

SetHstsEnabled sets HstsEnabled field to given value.


### GetHstsSubdomains

`func (o *GetRedirectionHosts200ResponseInner) GetHstsSubdomains() bool`

GetHstsSubdomains returns the HstsSubdomains field if non-nil, zero value otherwise.

### GetHstsSubdomainsOk

`func (o *GetRedirectionHosts200ResponseInner) GetHstsSubdomainsOk() (*bool, bool)`

GetHstsSubdomainsOk returns a tuple with the HstsSubdomains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHstsSubdomains

`func (o *GetRedirectionHosts200ResponseInner) SetHstsSubdomains(v bool)`

SetHstsSubdomains sets HstsSubdomains field to given value.


### GetHttp2Support

`func (o *GetRedirectionHosts200ResponseInner) GetHttp2Support() bool`

GetHttp2Support returns the Http2Support field if non-nil, zero value otherwise.

### GetHttp2SupportOk

`func (o *GetRedirectionHosts200ResponseInner) GetHttp2SupportOk() (*bool, bool)`

GetHttp2SupportOk returns a tuple with the Http2Support field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHttp2Support

`func (o *GetRedirectionHosts200ResponseInner) SetHttp2Support(v bool)`

SetHttp2Support sets Http2Support field to given value.


### GetBlockExploits

`func (o *GetRedirectionHosts200ResponseInner) GetBlockExploits() bool`

GetBlockExploits returns the BlockExploits field if non-nil, zero value otherwise.

### GetBlockExploitsOk

`func (o *GetRedirectionHosts200ResponseInner) GetBlockExploitsOk() (*bool, bool)`

GetBlockExploitsOk returns a tuple with the BlockExploits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockExploits

`func (o *GetRedirectionHosts200ResponseInner) SetBlockExploits(v bool)`

SetBlockExploits sets BlockExploits field to given value.


### GetAdvancedConfig

`func (o *GetRedirectionHosts200ResponseInner) GetAdvancedConfig() string`

GetAdvancedConfig returns the AdvancedConfig field if non-nil, zero value otherwise.

### GetAdvancedConfigOk

`func (o *GetRedirectionHosts200ResponseInner) GetAdvancedConfigOk() (*string, bool)`

GetAdvancedConfigOk returns a tuple with the AdvancedConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdvancedConfig

`func (o *GetRedirectionHosts200ResponseInner) SetAdvancedConfig(v string)`

SetAdvancedConfig sets AdvancedConfig field to given value.


### GetEnabled

`func (o *GetRedirectionHosts200ResponseInner) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *GetRedirectionHosts200ResponseInner) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *GetRedirectionHosts200ResponseInner) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetMeta

`func (o *GetRedirectionHosts200ResponseInner) GetMeta() map[string]interface{}`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetRedirectionHosts200ResponseInner) GetMetaOk() (*map[string]interface{}, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetRedirectionHosts200ResponseInner) SetMeta(v map[string]interface{})`

SetMeta sets Meta field to given value.


### GetCertificate

`func (o *GetRedirectionHosts200ResponseInner) GetCertificate() GetProxyHosts200ResponseInnerCertificate`

GetCertificate returns the Certificate field if non-nil, zero value otherwise.

### GetCertificateOk

`func (o *GetRedirectionHosts200ResponseInner) GetCertificateOk() (*GetProxyHosts200ResponseInnerCertificate, bool)`

GetCertificateOk returns a tuple with the Certificate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificate

`func (o *GetRedirectionHosts200ResponseInner) SetCertificate(v GetProxyHosts200ResponseInnerCertificate)`

SetCertificate sets Certificate field to given value.

### HasCertificate

`func (o *GetRedirectionHosts200ResponseInner) HasCertificate() bool`

HasCertificate returns a boolean if a field has been set.

### SetCertificateNil

`func (o *GetRedirectionHosts200ResponseInner) SetCertificateNil(b bool)`

 SetCertificateNil sets the value for Certificate to be an explicit nil

### UnsetCertificate
`func (o *GetRedirectionHosts200ResponseInner) UnsetCertificate()`

UnsetCertificate ensures that no value is present for Certificate, not even an explicit nil
### GetOwner

`func (o *GetRedirectionHosts200ResponseInner) GetOwner() GetAuditLogs200ResponseInnerUser`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *GetRedirectionHosts200ResponseInner) GetOwnerOk() (*GetAuditLogs200ResponseInnerUser, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *GetRedirectionHosts200ResponseInner) SetOwner(v GetAuditLogs200ResponseInnerUser)`

SetOwner sets Owner field to given value.

### HasOwner

`func (o *GetRedirectionHosts200ResponseInner) HasOwner() bool`

HasOwner returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



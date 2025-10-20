# SslCertGet200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Certificate** | Pointer to **string** | The certificate in base64-encoded | [optional] [readonly] 
**PrivateKey** | Pointer to **string** | The private key in base64-encoded | [optional] [readonly] 
**Id** | Pointer to **string** |  | [optional] [readonly] 
**Type** | Pointer to **string** |  | [optional] [readonly] 
**Active** | Pointer to **bool** |  | [optional] [readonly] [default to false]
**KeyType** | Pointer to **NullableString** |  | [optional] [readonly] 
**DomainNames** | Pointer to **[]string** |  | [optional] [readonly] 
**Issuer** | Pointer to **string** |  | [optional] [readonly] 
**IsRevoked** | Pointer to **bool** |  | [optional] [readonly] 
**ExpiryDate** | Pointer to **time.Time** |  | [optional] [readonly] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] [readonly] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] [readonly] 

## Methods

### NewSslCertGet200ResponseData

`func NewSslCertGet200ResponseData() *SslCertGet200ResponseData`

NewSslCertGet200ResponseData instantiates a new SslCertGet200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSslCertGet200ResponseDataWithDefaults

`func NewSslCertGet200ResponseDataWithDefaults() *SslCertGet200ResponseData`

NewSslCertGet200ResponseDataWithDefaults instantiates a new SslCertGet200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCertificate

`func (o *SslCertGet200ResponseData) GetCertificate() string`

GetCertificate returns the Certificate field if non-nil, zero value otherwise.

### GetCertificateOk

`func (o *SslCertGet200ResponseData) GetCertificateOk() (*string, bool)`

GetCertificateOk returns a tuple with the Certificate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificate

`func (o *SslCertGet200ResponseData) SetCertificate(v string)`

SetCertificate sets Certificate field to given value.

### HasCertificate

`func (o *SslCertGet200ResponseData) HasCertificate() bool`

HasCertificate returns a boolean if a field has been set.

### GetPrivateKey

`func (o *SslCertGet200ResponseData) GetPrivateKey() string`

GetPrivateKey returns the PrivateKey field if non-nil, zero value otherwise.

### GetPrivateKeyOk

`func (o *SslCertGet200ResponseData) GetPrivateKeyOk() (*string, bool)`

GetPrivateKeyOk returns a tuple with the PrivateKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivateKey

`func (o *SslCertGet200ResponseData) SetPrivateKey(v string)`

SetPrivateKey sets PrivateKey field to given value.

### HasPrivateKey

`func (o *SslCertGet200ResponseData) HasPrivateKey() bool`

HasPrivateKey returns a boolean if a field has been set.

### GetId

`func (o *SslCertGet200ResponseData) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SslCertGet200ResponseData) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SslCertGet200ResponseData) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SslCertGet200ResponseData) HasId() bool`

HasId returns a boolean if a field has been set.

### GetType

`func (o *SslCertGet200ResponseData) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SslCertGet200ResponseData) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SslCertGet200ResponseData) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *SslCertGet200ResponseData) HasType() bool`

HasType returns a boolean if a field has been set.

### GetActive

`func (o *SslCertGet200ResponseData) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *SslCertGet200ResponseData) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *SslCertGet200ResponseData) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *SslCertGet200ResponseData) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetKeyType

`func (o *SslCertGet200ResponseData) GetKeyType() string`

GetKeyType returns the KeyType field if non-nil, zero value otherwise.

### GetKeyTypeOk

`func (o *SslCertGet200ResponseData) GetKeyTypeOk() (*string, bool)`

GetKeyTypeOk returns a tuple with the KeyType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyType

`func (o *SslCertGet200ResponseData) SetKeyType(v string)`

SetKeyType sets KeyType field to given value.

### HasKeyType

`func (o *SslCertGet200ResponseData) HasKeyType() bool`

HasKeyType returns a boolean if a field has been set.

### SetKeyTypeNil

`func (o *SslCertGet200ResponseData) SetKeyTypeNil(b bool)`

 SetKeyTypeNil sets the value for KeyType to be an explicit nil

### UnsetKeyType
`func (o *SslCertGet200ResponseData) UnsetKeyType()`

UnsetKeyType ensures that no value is present for KeyType, not even an explicit nil
### GetDomainNames

`func (o *SslCertGet200ResponseData) GetDomainNames() []string`

GetDomainNames returns the DomainNames field if non-nil, zero value otherwise.

### GetDomainNamesOk

`func (o *SslCertGet200ResponseData) GetDomainNamesOk() (*[]string, bool)`

GetDomainNamesOk returns a tuple with the DomainNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainNames

`func (o *SslCertGet200ResponseData) SetDomainNames(v []string)`

SetDomainNames sets DomainNames field to given value.

### HasDomainNames

`func (o *SslCertGet200ResponseData) HasDomainNames() bool`

HasDomainNames returns a boolean if a field has been set.

### GetIssuer

`func (o *SslCertGet200ResponseData) GetIssuer() string`

GetIssuer returns the Issuer field if non-nil, zero value otherwise.

### GetIssuerOk

`func (o *SslCertGet200ResponseData) GetIssuerOk() (*string, bool)`

GetIssuerOk returns a tuple with the Issuer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuer

`func (o *SslCertGet200ResponseData) SetIssuer(v string)`

SetIssuer sets Issuer field to given value.

### HasIssuer

`func (o *SslCertGet200ResponseData) HasIssuer() bool`

HasIssuer returns a boolean if a field has been set.

### GetIsRevoked

`func (o *SslCertGet200ResponseData) GetIsRevoked() bool`

GetIsRevoked returns the IsRevoked field if non-nil, zero value otherwise.

### GetIsRevokedOk

`func (o *SslCertGet200ResponseData) GetIsRevokedOk() (*bool, bool)`

GetIsRevokedOk returns a tuple with the IsRevoked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRevoked

`func (o *SslCertGet200ResponseData) SetIsRevoked(v bool)`

SetIsRevoked sets IsRevoked field to given value.

### HasIsRevoked

`func (o *SslCertGet200ResponseData) HasIsRevoked() bool`

HasIsRevoked returns a boolean if a field has been set.

### GetExpiryDate

`func (o *SslCertGet200ResponseData) GetExpiryDate() time.Time`

GetExpiryDate returns the ExpiryDate field if non-nil, zero value otherwise.

### GetExpiryDateOk

`func (o *SslCertGet200ResponseData) GetExpiryDateOk() (*time.Time, bool)`

GetExpiryDateOk returns a tuple with the ExpiryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryDate

`func (o *SslCertGet200ResponseData) SetExpiryDate(v time.Time)`

SetExpiryDate sets ExpiryDate field to given value.

### HasExpiryDate

`func (o *SslCertGet200ResponseData) HasExpiryDate() bool`

HasExpiryDate returns a boolean if a field has been set.

### GetCreatedAt

`func (o *SslCertGet200ResponseData) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SslCertGet200ResponseData) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SslCertGet200ResponseData) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *SslCertGet200ResponseData) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *SslCertGet200ResponseData) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SslCertGet200ResponseData) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SslCertGet200ResponseData) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *SslCertGet200ResponseData) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



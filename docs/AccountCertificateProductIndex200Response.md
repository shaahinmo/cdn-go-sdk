# AccountCertificateProductIndex200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]CertificateProduct**](CertificateProduct.md) |  | [optional] 
**Links** | Pointer to [**PaginatedResponseLinks**](PaginatedResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**PaginatedResponseMeta**](PaginatedResponseMeta.md) |  | [optional] 

## Methods

### NewAccountCertificateProductIndex200Response

`func NewAccountCertificateProductIndex200Response() *AccountCertificateProductIndex200Response`

NewAccountCertificateProductIndex200Response instantiates a new AccountCertificateProductIndex200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountCertificateProductIndex200ResponseWithDefaults

`func NewAccountCertificateProductIndex200ResponseWithDefaults() *AccountCertificateProductIndex200Response`

NewAccountCertificateProductIndex200ResponseWithDefaults instantiates a new AccountCertificateProductIndex200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *AccountCertificateProductIndex200Response) GetData() []CertificateProduct`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AccountCertificateProductIndex200Response) GetDataOk() (*[]CertificateProduct, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AccountCertificateProductIndex200Response) SetData(v []CertificateProduct)`

SetData sets Data field to given value.

### HasData

`func (o *AccountCertificateProductIndex200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetLinks

`func (o *AccountCertificateProductIndex200Response) GetLinks() PaginatedResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *AccountCertificateProductIndex200Response) GetLinksOk() (*PaginatedResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *AccountCertificateProductIndex200Response) SetLinks(v PaginatedResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *AccountCertificateProductIndex200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *AccountCertificateProductIndex200Response) GetMeta() PaginatedResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *AccountCertificateProductIndex200Response) GetMetaOk() (*PaginatedResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *AccountCertificateProductIndex200Response) SetMeta(v PaginatedResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *AccountCertificateProductIndex200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



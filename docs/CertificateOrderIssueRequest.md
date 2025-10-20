# CertificateOrderIssueRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domains** | [**[]CertificateOrderIssueRequestDomainsInner**](CertificateOrderIssueRequestDomainsInner.md) |  | 
**ProductId** | **string** |  | 

## Methods

### NewCertificateOrderIssueRequest

`func NewCertificateOrderIssueRequest(domains []CertificateOrderIssueRequestDomainsInner, productId string, ) *CertificateOrderIssueRequest`

NewCertificateOrderIssueRequest instantiates a new CertificateOrderIssueRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCertificateOrderIssueRequestWithDefaults

`func NewCertificateOrderIssueRequestWithDefaults() *CertificateOrderIssueRequest`

NewCertificateOrderIssueRequestWithDefaults instantiates a new CertificateOrderIssueRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomains

`func (o *CertificateOrderIssueRequest) GetDomains() []CertificateOrderIssueRequestDomainsInner`

GetDomains returns the Domains field if non-nil, zero value otherwise.

### GetDomainsOk

`func (o *CertificateOrderIssueRequest) GetDomainsOk() (*[]CertificateOrderIssueRequestDomainsInner, bool)`

GetDomainsOk returns a tuple with the Domains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomains

`func (o *CertificateOrderIssueRequest) SetDomains(v []CertificateOrderIssueRequestDomainsInner)`

SetDomains sets Domains field to given value.


### GetProductId

`func (o *CertificateOrderIssueRequest) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *CertificateOrderIssueRequest) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *CertificateOrderIssueRequest) SetProductId(v string)`

SetProductId sets ProductId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



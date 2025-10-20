# DomainClaimRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domain** | Pointer to **string** | name of claiming domain | [optional] 

## Methods

### NewDomainClaimRequest

`func NewDomainClaimRequest() *DomainClaimRequest`

NewDomainClaimRequest instantiates a new DomainClaimRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainClaimRequestWithDefaults

`func NewDomainClaimRequestWithDefaults() *DomainClaimRequest`

NewDomainClaimRequestWithDefaults instantiates a new DomainClaimRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomain

`func (o *DomainClaimRequest) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *DomainClaimRequest) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *DomainClaimRequest) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *DomainClaimRequest) HasDomain() bool`

HasDomain returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# AccountCertificateOrder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**OrderId** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**DomainNames** | Pointer to **[]string** |  | [optional] 
**Product** | Pointer to **string** |  | [optional] 
**Errors** | Pointer to **map[string]interface{}** |  | [optional] 
**ExpiryDate** | Pointer to **time.Time** |  | [optional] 
**IsRevoked** | Pointer to **bool** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewAccountCertificateOrder

`func NewAccountCertificateOrder() *AccountCertificateOrder`

NewAccountCertificateOrder instantiates a new AccountCertificateOrder object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountCertificateOrderWithDefaults

`func NewAccountCertificateOrderWithDefaults() *AccountCertificateOrder`

NewAccountCertificateOrderWithDefaults instantiates a new AccountCertificateOrder object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AccountCertificateOrder) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AccountCertificateOrder) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AccountCertificateOrder) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AccountCertificateOrder) HasId() bool`

HasId returns a boolean if a field has been set.

### GetOrderId

`func (o *AccountCertificateOrder) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *AccountCertificateOrder) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *AccountCertificateOrder) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *AccountCertificateOrder) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### GetStatus

`func (o *AccountCertificateOrder) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AccountCertificateOrder) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AccountCertificateOrder) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AccountCertificateOrder) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetDomainNames

`func (o *AccountCertificateOrder) GetDomainNames() []string`

GetDomainNames returns the DomainNames field if non-nil, zero value otherwise.

### GetDomainNamesOk

`func (o *AccountCertificateOrder) GetDomainNamesOk() (*[]string, bool)`

GetDomainNamesOk returns a tuple with the DomainNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainNames

`func (o *AccountCertificateOrder) SetDomainNames(v []string)`

SetDomainNames sets DomainNames field to given value.

### HasDomainNames

`func (o *AccountCertificateOrder) HasDomainNames() bool`

HasDomainNames returns a boolean if a field has been set.

### GetProduct

`func (o *AccountCertificateOrder) GetProduct() string`

GetProduct returns the Product field if non-nil, zero value otherwise.

### GetProductOk

`func (o *AccountCertificateOrder) GetProductOk() (*string, bool)`

GetProductOk returns a tuple with the Product field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProduct

`func (o *AccountCertificateOrder) SetProduct(v string)`

SetProduct sets Product field to given value.

### HasProduct

`func (o *AccountCertificateOrder) HasProduct() bool`

HasProduct returns a boolean if a field has been set.

### GetErrors

`func (o *AccountCertificateOrder) GetErrors() map[string]interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *AccountCertificateOrder) GetErrorsOk() (*map[string]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *AccountCertificateOrder) SetErrors(v map[string]interface{})`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *AccountCertificateOrder) HasErrors() bool`

HasErrors returns a boolean if a field has been set.

### SetErrorsNil

`func (o *AccountCertificateOrder) SetErrorsNil(b bool)`

 SetErrorsNil sets the value for Errors to be an explicit nil

### UnsetErrors
`func (o *AccountCertificateOrder) UnsetErrors()`

UnsetErrors ensures that no value is present for Errors, not even an explicit nil
### GetExpiryDate

`func (o *AccountCertificateOrder) GetExpiryDate() time.Time`

GetExpiryDate returns the ExpiryDate field if non-nil, zero value otherwise.

### GetExpiryDateOk

`func (o *AccountCertificateOrder) GetExpiryDateOk() (*time.Time, bool)`

GetExpiryDateOk returns a tuple with the ExpiryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryDate

`func (o *AccountCertificateOrder) SetExpiryDate(v time.Time)`

SetExpiryDate sets ExpiryDate field to given value.

### HasExpiryDate

`func (o *AccountCertificateOrder) HasExpiryDate() bool`

HasExpiryDate returns a boolean if a field has been set.

### GetIsRevoked

`func (o *AccountCertificateOrder) GetIsRevoked() bool`

GetIsRevoked returns the IsRevoked field if non-nil, zero value otherwise.

### GetIsRevokedOk

`func (o *AccountCertificateOrder) GetIsRevokedOk() (*bool, bool)`

GetIsRevokedOk returns a tuple with the IsRevoked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRevoked

`func (o *AccountCertificateOrder) SetIsRevoked(v bool)`

SetIsRevoked sets IsRevoked field to given value.

### HasIsRevoked

`func (o *AccountCertificateOrder) HasIsRevoked() bool`

HasIsRevoked returns a boolean if a field has been set.

### GetCreatedAt

`func (o *AccountCertificateOrder) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AccountCertificateOrder) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AccountCertificateOrder) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *AccountCertificateOrder) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *AccountCertificateOrder) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *AccountCertificateOrder) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *AccountCertificateOrder) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *AccountCertificateOrder) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



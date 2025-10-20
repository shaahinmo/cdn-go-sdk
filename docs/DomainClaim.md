# DomainClaim

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Domain** | Pointer to **string** | name of claimed domain | [optional] 
**NsKeys** | Pointer to **[]string** | Desired NS values for the domain | [optional] 
**Status** | Pointer to **string** | - PENDING: The domain claim is pending verification and waiting to set nameservers in the registrar. - EXPIRED: The pending status has a time limit and if not verified within that limit, it becomes expired. - VERIFIED: The system has successfully checked that the nameservers are set to ns_keys. - SUSPENDED: The current domain owner has contacted support and suspended the automatic claim. The claimer should contact support in this situation. - TRANSFERRED: The domain has been verified, the ownership transfer period is complete, and the domain has been successfully transferred to the claimer.  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewDomainClaim

`func NewDomainClaim() *DomainClaim`

NewDomainClaim instantiates a new DomainClaim object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainClaimWithDefaults

`func NewDomainClaimWithDefaults() *DomainClaim`

NewDomainClaimWithDefaults instantiates a new DomainClaim object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DomainClaim) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DomainClaim) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DomainClaim) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *DomainClaim) HasId() bool`

HasId returns a boolean if a field has been set.

### GetDomain

`func (o *DomainClaim) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *DomainClaim) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *DomainClaim) SetDomain(v string)`

SetDomain sets Domain field to given value.

### HasDomain

`func (o *DomainClaim) HasDomain() bool`

HasDomain returns a boolean if a field has been set.

### GetNsKeys

`func (o *DomainClaim) GetNsKeys() []string`

GetNsKeys returns the NsKeys field if non-nil, zero value otherwise.

### GetNsKeysOk

`func (o *DomainClaim) GetNsKeysOk() (*[]string, bool)`

GetNsKeysOk returns a tuple with the NsKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNsKeys

`func (o *DomainClaim) SetNsKeys(v []string)`

SetNsKeys sets NsKeys field to given value.

### HasNsKeys

`func (o *DomainClaim) HasNsKeys() bool`

HasNsKeys returns a boolean if a field has been set.

### GetStatus

`func (o *DomainClaim) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DomainClaim) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DomainClaim) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *DomainClaim) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *DomainClaim) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DomainClaim) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DomainClaim) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *DomainClaim) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



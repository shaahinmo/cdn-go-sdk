# Subproblem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** | A reference that identifies the problem type. | [optional] [readonly] 
**Detail** | Pointer to **string** | A human-readable explanation specific to this occurrence of the problem. | [optional] [readonly] 
**Identifier** | Pointer to [**SubproblemIdentifier**](SubproblemIdentifier.md) |  | [optional] 

## Methods

### NewSubproblem

`func NewSubproblem() *Subproblem`

NewSubproblem instantiates a new Subproblem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubproblemWithDefaults

`func NewSubproblemWithDefaults() *Subproblem`

NewSubproblemWithDefaults instantiates a new Subproblem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *Subproblem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Subproblem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Subproblem) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Subproblem) HasType() bool`

HasType returns a boolean if a field has been set.

### GetDetail

`func (o *Subproblem) GetDetail() string`

GetDetail returns the Detail field if non-nil, zero value otherwise.

### GetDetailOk

`func (o *Subproblem) GetDetailOk() (*string, bool)`

GetDetailOk returns a tuple with the Detail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetail

`func (o *Subproblem) SetDetail(v string)`

SetDetail sets Detail field to given value.

### HasDetail

`func (o *Subproblem) HasDetail() bool`

HasDetail returns a boolean if a field has been set.

### GetIdentifier

`func (o *Subproblem) GetIdentifier() SubproblemIdentifier`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *Subproblem) GetIdentifierOk() (*SubproblemIdentifier, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *Subproblem) SetIdentifier(v SubproblemIdentifier)`

SetIdentifier sets Identifier field to given value.

### HasIdentifier

`func (o *Subproblem) HasIdentifier() bool`

HasIdentifier returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



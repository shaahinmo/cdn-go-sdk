# AggregatedReportsFilterResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Pops** | Pointer to [**[]AggregatedReportsFilterResponsePopsInner**](AggregatedReportsFilterResponsePopsInner.md) |  | [optional] 
**Asns** | Pointer to **[]int32** |  | [optional] 

## Methods

### NewAggregatedReportsFilterResponse

`func NewAggregatedReportsFilterResponse() *AggregatedReportsFilterResponse`

NewAggregatedReportsFilterResponse instantiates a new AggregatedReportsFilterResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAggregatedReportsFilterResponseWithDefaults

`func NewAggregatedReportsFilterResponseWithDefaults() *AggregatedReportsFilterResponse`

NewAggregatedReportsFilterResponseWithDefaults instantiates a new AggregatedReportsFilterResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPops

`func (o *AggregatedReportsFilterResponse) GetPops() []AggregatedReportsFilterResponsePopsInner`

GetPops returns the Pops field if non-nil, zero value otherwise.

### GetPopsOk

`func (o *AggregatedReportsFilterResponse) GetPopsOk() (*[]AggregatedReportsFilterResponsePopsInner, bool)`

GetPopsOk returns a tuple with the Pops field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPops

`func (o *AggregatedReportsFilterResponse) SetPops(v []AggregatedReportsFilterResponsePopsInner)`

SetPops sets Pops field to given value.

### HasPops

`func (o *AggregatedReportsFilterResponse) HasPops() bool`

HasPops returns a boolean if a field has been set.

### GetAsns

`func (o *AggregatedReportsFilterResponse) GetAsns() []int32`

GetAsns returns the Asns field if non-nil, zero value otherwise.

### GetAsnsOk

`func (o *AggregatedReportsFilterResponse) GetAsnsOk() (*[]int32, bool)`

GetAsnsOk returns a tuple with the Asns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsns

`func (o *AggregatedReportsFilterResponse) SetAsns(v []int32)`

SetAsns sets Asns field to given value.

### HasAsns

`func (o *AggregatedReportsFilterResponse) HasAsns() bool`

HasAsns returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ReportsAggregatedDetails200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]AggregatedReportsResponse**](AggregatedReportsResponse.md) |  | [optional] 
**Links** | Pointer to [**PaginatedResponseLinks**](PaginatedResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**PaginatedResponseMeta**](PaginatedResponseMeta.md) |  | [optional] 

## Methods

### NewReportsAggregatedDetails200Response

`func NewReportsAggregatedDetails200Response() *ReportsAggregatedDetails200Response`

NewReportsAggregatedDetails200Response instantiates a new ReportsAggregatedDetails200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReportsAggregatedDetails200ResponseWithDefaults

`func NewReportsAggregatedDetails200ResponseWithDefaults() *ReportsAggregatedDetails200Response`

NewReportsAggregatedDetails200ResponseWithDefaults instantiates a new ReportsAggregatedDetails200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ReportsAggregatedDetails200Response) GetData() []AggregatedReportsResponse`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ReportsAggregatedDetails200Response) GetDataOk() (*[]AggregatedReportsResponse, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ReportsAggregatedDetails200Response) SetData(v []AggregatedReportsResponse)`

SetData sets Data field to given value.

### HasData

`func (o *ReportsAggregatedDetails200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetLinks

`func (o *ReportsAggregatedDetails200Response) GetLinks() PaginatedResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *ReportsAggregatedDetails200Response) GetLinksOk() (*PaginatedResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *ReportsAggregatedDetails200Response) SetLinks(v PaginatedResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *ReportsAggregatedDetails200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *ReportsAggregatedDetails200Response) GetMeta() PaginatedResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ReportsAggregatedDetails200Response) GetMetaOk() (*PaginatedResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ReportsAggregatedDetails200Response) SetMeta(v PaginatedResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ReportsAggregatedDetails200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



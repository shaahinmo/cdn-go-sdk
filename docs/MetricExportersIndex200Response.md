# MetricExportersIndex200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]MetricExporterSummary**](MetricExporterSummary.md) |  | [optional] 
**Links** | Pointer to [**PaginatedResponseLinks**](PaginatedResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**PaginatedResponseMeta**](PaginatedResponseMeta.md) |  | [optional] 

## Methods

### NewMetricExportersIndex200Response

`func NewMetricExportersIndex200Response() *MetricExportersIndex200Response`

NewMetricExportersIndex200Response instantiates a new MetricExportersIndex200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMetricExportersIndex200ResponseWithDefaults

`func NewMetricExportersIndex200ResponseWithDefaults() *MetricExportersIndex200Response`

NewMetricExportersIndex200ResponseWithDefaults instantiates a new MetricExportersIndex200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *MetricExportersIndex200Response) GetData() []MetricExporterSummary`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *MetricExportersIndex200Response) GetDataOk() (*[]MetricExporterSummary, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *MetricExportersIndex200Response) SetData(v []MetricExporterSummary)`

SetData sets Data field to given value.

### HasData

`func (o *MetricExportersIndex200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetLinks

`func (o *MetricExportersIndex200Response) GetLinks() PaginatedResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *MetricExportersIndex200Response) GetLinksOk() (*PaginatedResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *MetricExportersIndex200Response) SetLinks(v PaginatedResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *MetricExportersIndex200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *MetricExportersIndex200Response) GetMeta() PaginatedResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *MetricExportersIndex200Response) GetMetaOk() (*PaginatedResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *MetricExportersIndex200Response) SetMeta(v PaginatedResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *MetricExportersIndex200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# AggregatedReportsChartsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | Pointer to **string** |  | [optional] 
**Categories** | Pointer to **[]string** |  | [optional] 
**Series** | Pointer to [**[]AggregatedReportsChartsResponseSeriesInner**](AggregatedReportsChartsResponseSeriesInner.md) |  | [optional] 

## Methods

### NewAggregatedReportsChartsResponse

`func NewAggregatedReportsChartsResponse() *AggregatedReportsChartsResponse`

NewAggregatedReportsChartsResponse instantiates a new AggregatedReportsChartsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAggregatedReportsChartsResponseWithDefaults

`func NewAggregatedReportsChartsResponseWithDefaults() *AggregatedReportsChartsResponse`

NewAggregatedReportsChartsResponseWithDefaults instantiates a new AggregatedReportsChartsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *AggregatedReportsChartsResponse) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *AggregatedReportsChartsResponse) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *AggregatedReportsChartsResponse) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *AggregatedReportsChartsResponse) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetCategories

`func (o *AggregatedReportsChartsResponse) GetCategories() []string`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *AggregatedReportsChartsResponse) GetCategoriesOk() (*[]string, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *AggregatedReportsChartsResponse) SetCategories(v []string)`

SetCategories sets Categories field to given value.

### HasCategories

`func (o *AggregatedReportsChartsResponse) HasCategories() bool`

HasCategories returns a boolean if a field has been set.

### GetSeries

`func (o *AggregatedReportsChartsResponse) GetSeries() []AggregatedReportsChartsResponseSeriesInner`

GetSeries returns the Series field if non-nil, zero value otherwise.

### GetSeriesOk

`func (o *AggregatedReportsChartsResponse) GetSeriesOk() (*[]AggregatedReportsChartsResponseSeriesInner, bool)`

GetSeriesOk returns a tuple with the Series field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeries

`func (o *AggregatedReportsChartsResponse) SetSeries(v []AggregatedReportsChartsResponseSeriesInner)`

SetSeries sets Series field to given value.

### HasSeries

`func (o *AggregatedReportsChartsResponse) HasSeries() bool`

HasSeries returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



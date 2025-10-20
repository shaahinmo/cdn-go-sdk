# MetricExporter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] [readonly] 
**Name** | **string** |  | 
**Type** | **string** |  | 
**Interval** | **string** |  | 
**Status** | **bool** |  | 

## Methods

### NewMetricExporter

`func NewMetricExporter(name string, type_ string, interval string, status bool, ) *MetricExporter`

NewMetricExporter instantiates a new MetricExporter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMetricExporterWithDefaults

`func NewMetricExporterWithDefaults() *MetricExporter`

NewMetricExporterWithDefaults instantiates a new MetricExporter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *MetricExporter) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MetricExporter) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MetricExporter) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *MetricExporter) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *MetricExporter) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *MetricExporter) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *MetricExporter) SetName(v string)`

SetName sets Name field to given value.


### GetType

`func (o *MetricExporter) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *MetricExporter) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *MetricExporter) SetType(v string)`

SetType sets Type field to given value.


### GetInterval

`func (o *MetricExporter) GetInterval() string`

GetInterval returns the Interval field if non-nil, zero value otherwise.

### GetIntervalOk

`func (o *MetricExporter) GetIntervalOk() (*string, bool)`

GetIntervalOk returns a tuple with the Interval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterval

`func (o *MetricExporter) SetInterval(v string)`

SetInterval sets Interval field to given value.


### GetStatus

`func (o *MetricExporter) GetStatus() bool`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *MetricExporter) GetStatusOk() (*bool, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *MetricExporter) SetStatus(v bool)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



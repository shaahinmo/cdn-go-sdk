# MetricExporterResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to **map[string]interface{}** |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewMetricExporterResponse

`func NewMetricExporterResponse() *MetricExporterResponse`

NewMetricExporterResponse instantiates a new MetricExporterResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMetricExporterResponseWithDefaults

`func NewMetricExporterResponseWithDefaults() *MetricExporterResponse`

NewMetricExporterResponseWithDefaults instantiates a new MetricExporterResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *MetricExporterResponse) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *MetricExporterResponse) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *MetricExporterResponse) SetData(v map[string]interface{})`

SetData sets Data field to given value.

### HasData

`func (o *MetricExporterResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetMessage

`func (o *MetricExporterResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *MetricExporterResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *MetricExporterResponse) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *MetricExporterResponse) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *MetricExporterResponse) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *MetricExporterResponse) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



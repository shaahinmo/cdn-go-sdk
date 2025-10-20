# HealthCheckZone

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** | The name of the health check zone. If &#39;id&#39; is not provided, &#39;name&#39; will be used as the &#39;id&#39;. | [optional] 
**MonitoringLevel** | Pointer to **string** |  | [optional] 

## Methods

### NewHealthCheckZone

`func NewHealthCheckZone() *HealthCheckZone`

NewHealthCheckZone instantiates a new HealthCheckZone object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHealthCheckZoneWithDefaults

`func NewHealthCheckZoneWithDefaults() *HealthCheckZone`

NewHealthCheckZoneWithDefaults instantiates a new HealthCheckZone object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *HealthCheckZone) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *HealthCheckZone) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *HealthCheckZone) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *HealthCheckZone) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *HealthCheckZone) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *HealthCheckZone) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *HealthCheckZone) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *HealthCheckZone) HasName() bool`

HasName returns a boolean if a field has been set.

### GetMonitoringLevel

`func (o *HealthCheckZone) GetMonitoringLevel() string`

GetMonitoringLevel returns the MonitoringLevel field if non-nil, zero value otherwise.

### GetMonitoringLevelOk

`func (o *HealthCheckZone) GetMonitoringLevelOk() (*string, bool)`

GetMonitoringLevelOk returns a tuple with the MonitoringLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonitoringLevel

`func (o *HealthCheckZone) SetMonitoringLevel(v string)`

SetMonitoringLevel sets MonitoringLevel field to given value.

### HasMonitoringLevel

`func (o *HealthCheckZone) HasMonitoringLevel() bool`

HasMonitoringLevel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



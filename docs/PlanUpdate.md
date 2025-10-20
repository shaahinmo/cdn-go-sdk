# PlanUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PlanLevel** | **int32** | - &#x60;0&#x60; - Traffic - &#x60;1&#x60; - Basic - &#x60;2&#x60; - Growth - &#x60;3&#x60; - Professional - &#x60;4&#x60; - Enterprise - Subdomains require to have Growth plan or higher  | 
**PlanDuration** | Pointer to **int32** | - &#x60;0&#x60; - Normal - &#x60;6&#x60; - Six month prepaid - &#x60;12&#x60; - Twelve month prepaid - Prepaid subscription is available for Growth and Professional plan.  | [optional] 

## Methods

### NewPlanUpdate

`func NewPlanUpdate(planLevel int32, ) *PlanUpdate`

NewPlanUpdate instantiates a new PlanUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlanUpdateWithDefaults

`func NewPlanUpdateWithDefaults() *PlanUpdate`

NewPlanUpdateWithDefaults instantiates a new PlanUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlanLevel

`func (o *PlanUpdate) GetPlanLevel() int32`

GetPlanLevel returns the PlanLevel field if non-nil, zero value otherwise.

### GetPlanLevelOk

`func (o *PlanUpdate) GetPlanLevelOk() (*int32, bool)`

GetPlanLevelOk returns a tuple with the PlanLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanLevel

`func (o *PlanUpdate) SetPlanLevel(v int32)`

SetPlanLevel sets PlanLevel field to given value.


### GetPlanDuration

`func (o *PlanUpdate) GetPlanDuration() int32`

GetPlanDuration returns the PlanDuration field if non-nil, zero value otherwise.

### GetPlanDurationOk

`func (o *PlanUpdate) GetPlanDurationOk() (*int32, bool)`

GetPlanDurationOk returns a tuple with the PlanDuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanDuration

`func (o *PlanUpdate) SetPlanDuration(v int32)`

SetPlanDuration sets PlanDuration field to given value.

### HasPlanDuration

`func (o *PlanUpdate) HasPlanDuration() bool`

HasPlanDuration returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# LoadBalancerPoolStoreWithoutOrigin

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **bool** |  | [optional] 
**Priority** | Pointer to **int32** | Zero means the default pool | [optional] 
**Method** | Pointer to **string** |  | [optional] 
**Keepalive** | Pointer to **string** |  | [optional] [default to "off"]
**NextUpstreamTcp** | Pointer to **string** | Try another server when the first one failed if on | [optional] [default to "off"]
**NextUpstreamTcpCodes** | Pointer to [**NextUpstreamTcpCodes**](NextUpstreamTcpCodes.md) |  | [optional] 
**Regions** | Pointer to **[]string** |  | [optional] 

## Methods

### NewLoadBalancerPoolStoreWithoutOrigin

`func NewLoadBalancerPoolStoreWithoutOrigin() *LoadBalancerPoolStoreWithoutOrigin`

NewLoadBalancerPoolStoreWithoutOrigin instantiates a new LoadBalancerPoolStoreWithoutOrigin object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoadBalancerPoolStoreWithoutOriginWithDefaults

`func NewLoadBalancerPoolStoreWithoutOriginWithDefaults() *LoadBalancerPoolStoreWithoutOrigin`

NewLoadBalancerPoolStoreWithoutOriginWithDefaults instantiates a new LoadBalancerPoolStoreWithoutOrigin object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LoadBalancerPoolStoreWithoutOrigin) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *LoadBalancerPoolStoreWithoutOrigin) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *LoadBalancerPoolStoreWithoutOrigin) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *LoadBalancerPoolStoreWithoutOrigin) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LoadBalancerPoolStoreWithoutOrigin) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *LoadBalancerPoolStoreWithoutOrigin) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetStatus

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetStatus() bool`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetStatusOk() (*bool, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *LoadBalancerPoolStoreWithoutOrigin) SetStatus(v bool)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *LoadBalancerPoolStoreWithoutOrigin) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPriority

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *LoadBalancerPoolStoreWithoutOrigin) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *LoadBalancerPoolStoreWithoutOrigin) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetMethod

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *LoadBalancerPoolStoreWithoutOrigin) SetMethod(v string)`

SetMethod sets Method field to given value.

### HasMethod

`func (o *LoadBalancerPoolStoreWithoutOrigin) HasMethod() bool`

HasMethod returns a boolean if a field has been set.

### GetKeepalive

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetKeepalive() string`

GetKeepalive returns the Keepalive field if non-nil, zero value otherwise.

### GetKeepaliveOk

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetKeepaliveOk() (*string, bool)`

GetKeepaliveOk returns a tuple with the Keepalive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeepalive

`func (o *LoadBalancerPoolStoreWithoutOrigin) SetKeepalive(v string)`

SetKeepalive sets Keepalive field to given value.

### HasKeepalive

`func (o *LoadBalancerPoolStoreWithoutOrigin) HasKeepalive() bool`

HasKeepalive returns a boolean if a field has been set.

### GetNextUpstreamTcp

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetNextUpstreamTcp() string`

GetNextUpstreamTcp returns the NextUpstreamTcp field if non-nil, zero value otherwise.

### GetNextUpstreamTcpOk

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetNextUpstreamTcpOk() (*string, bool)`

GetNextUpstreamTcpOk returns a tuple with the NextUpstreamTcp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextUpstreamTcp

`func (o *LoadBalancerPoolStoreWithoutOrigin) SetNextUpstreamTcp(v string)`

SetNextUpstreamTcp sets NextUpstreamTcp field to given value.

### HasNextUpstreamTcp

`func (o *LoadBalancerPoolStoreWithoutOrigin) HasNextUpstreamTcp() bool`

HasNextUpstreamTcp returns a boolean if a field has been set.

### GetNextUpstreamTcpCodes

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetNextUpstreamTcpCodes() NextUpstreamTcpCodes`

GetNextUpstreamTcpCodes returns the NextUpstreamTcpCodes field if non-nil, zero value otherwise.

### GetNextUpstreamTcpCodesOk

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetNextUpstreamTcpCodesOk() (*NextUpstreamTcpCodes, bool)`

GetNextUpstreamTcpCodesOk returns a tuple with the NextUpstreamTcpCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextUpstreamTcpCodes

`func (o *LoadBalancerPoolStoreWithoutOrigin) SetNextUpstreamTcpCodes(v NextUpstreamTcpCodes)`

SetNextUpstreamTcpCodes sets NextUpstreamTcpCodes field to given value.

### HasNextUpstreamTcpCodes

`func (o *LoadBalancerPoolStoreWithoutOrigin) HasNextUpstreamTcpCodes() bool`

HasNextUpstreamTcpCodes returns a boolean if a field has been set.

### GetRegions

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetRegions() []string`

GetRegions returns the Regions field if non-nil, zero value otherwise.

### GetRegionsOk

`func (o *LoadBalancerPoolStoreWithoutOrigin) GetRegionsOk() (*[]string, bool)`

GetRegionsOk returns a tuple with the Regions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegions

`func (o *LoadBalancerPoolStoreWithoutOrigin) SetRegions(v []string)`

SetRegions sets Regions field to given value.

### HasRegions

`func (o *LoadBalancerPoolStoreWithoutOrigin) HasRegions() bool`

HasRegions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



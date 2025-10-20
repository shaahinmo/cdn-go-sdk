# LoadBalancerPoolStoreWithOrigin

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Origins** | Pointer to [**[]LoadBalancerOriginStore**](LoadBalancerOriginStore.md) |  | [optional] 
**Id** | Pointer to **string** |  | [optional] 
**Name** | **string** |  | 
**Description** | Pointer to **string** |  | [optional] 
**Status** | **bool** |  | 
**Priority** | Pointer to **int32** | Zero means the default pool | [optional] 
**Method** | **string** |  | 
**Keepalive** | **string** |  | [default to "off"]
**NextUpstreamTcp** | **string** | Try another server when the first one failed if on | [default to "off"]
**NextUpstreamTcpCodes** | Pointer to [**NextUpstreamTcpCodes**](NextUpstreamTcpCodes.md) |  | [optional] 
**Regions** | Pointer to **[]string** |  | [optional] 

## Methods

### NewLoadBalancerPoolStoreWithOrigin

`func NewLoadBalancerPoolStoreWithOrigin(name string, status bool, method string, keepalive string, nextUpstreamTcp string, ) *LoadBalancerPoolStoreWithOrigin`

NewLoadBalancerPoolStoreWithOrigin instantiates a new LoadBalancerPoolStoreWithOrigin object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoadBalancerPoolStoreWithOriginWithDefaults

`func NewLoadBalancerPoolStoreWithOriginWithDefaults() *LoadBalancerPoolStoreWithOrigin`

NewLoadBalancerPoolStoreWithOriginWithDefaults instantiates a new LoadBalancerPoolStoreWithOrigin object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrigins

`func (o *LoadBalancerPoolStoreWithOrigin) GetOrigins() []LoadBalancerOriginStore`

GetOrigins returns the Origins field if non-nil, zero value otherwise.

### GetOriginsOk

`func (o *LoadBalancerPoolStoreWithOrigin) GetOriginsOk() (*[]LoadBalancerOriginStore, bool)`

GetOriginsOk returns a tuple with the Origins field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrigins

`func (o *LoadBalancerPoolStoreWithOrigin) SetOrigins(v []LoadBalancerOriginStore)`

SetOrigins sets Origins field to given value.

### HasOrigins

`func (o *LoadBalancerPoolStoreWithOrigin) HasOrigins() bool`

HasOrigins returns a boolean if a field has been set.

### GetId

`func (o *LoadBalancerPoolStoreWithOrigin) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LoadBalancerPoolStoreWithOrigin) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LoadBalancerPoolStoreWithOrigin) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *LoadBalancerPoolStoreWithOrigin) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *LoadBalancerPoolStoreWithOrigin) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *LoadBalancerPoolStoreWithOrigin) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *LoadBalancerPoolStoreWithOrigin) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *LoadBalancerPoolStoreWithOrigin) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LoadBalancerPoolStoreWithOrigin) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LoadBalancerPoolStoreWithOrigin) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *LoadBalancerPoolStoreWithOrigin) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetStatus

`func (o *LoadBalancerPoolStoreWithOrigin) GetStatus() bool`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *LoadBalancerPoolStoreWithOrigin) GetStatusOk() (*bool, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *LoadBalancerPoolStoreWithOrigin) SetStatus(v bool)`

SetStatus sets Status field to given value.


### GetPriority

`func (o *LoadBalancerPoolStoreWithOrigin) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *LoadBalancerPoolStoreWithOrigin) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *LoadBalancerPoolStoreWithOrigin) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *LoadBalancerPoolStoreWithOrigin) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetMethod

`func (o *LoadBalancerPoolStoreWithOrigin) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *LoadBalancerPoolStoreWithOrigin) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *LoadBalancerPoolStoreWithOrigin) SetMethod(v string)`

SetMethod sets Method field to given value.


### GetKeepalive

`func (o *LoadBalancerPoolStoreWithOrigin) GetKeepalive() string`

GetKeepalive returns the Keepalive field if non-nil, zero value otherwise.

### GetKeepaliveOk

`func (o *LoadBalancerPoolStoreWithOrigin) GetKeepaliveOk() (*string, bool)`

GetKeepaliveOk returns a tuple with the Keepalive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeepalive

`func (o *LoadBalancerPoolStoreWithOrigin) SetKeepalive(v string)`

SetKeepalive sets Keepalive field to given value.


### GetNextUpstreamTcp

`func (o *LoadBalancerPoolStoreWithOrigin) GetNextUpstreamTcp() string`

GetNextUpstreamTcp returns the NextUpstreamTcp field if non-nil, zero value otherwise.

### GetNextUpstreamTcpOk

`func (o *LoadBalancerPoolStoreWithOrigin) GetNextUpstreamTcpOk() (*string, bool)`

GetNextUpstreamTcpOk returns a tuple with the NextUpstreamTcp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextUpstreamTcp

`func (o *LoadBalancerPoolStoreWithOrigin) SetNextUpstreamTcp(v string)`

SetNextUpstreamTcp sets NextUpstreamTcp field to given value.


### GetNextUpstreamTcpCodes

`func (o *LoadBalancerPoolStoreWithOrigin) GetNextUpstreamTcpCodes() NextUpstreamTcpCodes`

GetNextUpstreamTcpCodes returns the NextUpstreamTcpCodes field if non-nil, zero value otherwise.

### GetNextUpstreamTcpCodesOk

`func (o *LoadBalancerPoolStoreWithOrigin) GetNextUpstreamTcpCodesOk() (*NextUpstreamTcpCodes, bool)`

GetNextUpstreamTcpCodesOk returns a tuple with the NextUpstreamTcpCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextUpstreamTcpCodes

`func (o *LoadBalancerPoolStoreWithOrigin) SetNextUpstreamTcpCodes(v NextUpstreamTcpCodes)`

SetNextUpstreamTcpCodes sets NextUpstreamTcpCodes field to given value.

### HasNextUpstreamTcpCodes

`func (o *LoadBalancerPoolStoreWithOrigin) HasNextUpstreamTcpCodes() bool`

HasNextUpstreamTcpCodes returns a boolean if a field has been set.

### GetRegions

`func (o *LoadBalancerPoolStoreWithOrigin) GetRegions() []string`

GetRegions returns the Regions field if non-nil, zero value otherwise.

### GetRegionsOk

`func (o *LoadBalancerPoolStoreWithOrigin) GetRegionsOk() (*[]string, bool)`

GetRegionsOk returns a tuple with the Regions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegions

`func (o *LoadBalancerPoolStoreWithOrigin) SetRegions(v []string)`

SetRegions sets Regions field to given value.

### HasRegions

`func (o *LoadBalancerPoolStoreWithOrigin) HasRegions() bool`

HasRegions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



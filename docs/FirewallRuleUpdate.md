# FirewallRuleUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActionDetails** | Pointer to [**NullableFirewallActionDetails**](FirewallActionDetails.md) |  | [optional] 
**Id** | Pointer to **string** |  | [optional] [readonly] 
**Name** | Pointer to **string** |  | [optional] 
**FilterExpr** | Pointer to **string** | Wireshark-like filter expression | [optional] 
**Action** | Pointer to **string** |  | [optional] 
**Priority** | Pointer to **int32** | Priority of the firewall rule | [optional] 
**IsEnabled** | Pointer to **bool** |  | [optional] 
**Note** | Pointer to **string** |  | [optional] 

## Methods

### NewFirewallRuleUpdate

`func NewFirewallRuleUpdate() *FirewallRuleUpdate`

NewFirewallRuleUpdate instantiates a new FirewallRuleUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFirewallRuleUpdateWithDefaults

`func NewFirewallRuleUpdateWithDefaults() *FirewallRuleUpdate`

NewFirewallRuleUpdateWithDefaults instantiates a new FirewallRuleUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActionDetails

`func (o *FirewallRuleUpdate) GetActionDetails() FirewallActionDetails`

GetActionDetails returns the ActionDetails field if non-nil, zero value otherwise.

### GetActionDetailsOk

`func (o *FirewallRuleUpdate) GetActionDetailsOk() (*FirewallActionDetails, bool)`

GetActionDetailsOk returns a tuple with the ActionDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionDetails

`func (o *FirewallRuleUpdate) SetActionDetails(v FirewallActionDetails)`

SetActionDetails sets ActionDetails field to given value.

### HasActionDetails

`func (o *FirewallRuleUpdate) HasActionDetails() bool`

HasActionDetails returns a boolean if a field has been set.

### SetActionDetailsNil

`func (o *FirewallRuleUpdate) SetActionDetailsNil(b bool)`

 SetActionDetailsNil sets the value for ActionDetails to be an explicit nil

### UnsetActionDetails
`func (o *FirewallRuleUpdate) UnsetActionDetails()`

UnsetActionDetails ensures that no value is present for ActionDetails, not even an explicit nil
### GetId

`func (o *FirewallRuleUpdate) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FirewallRuleUpdate) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FirewallRuleUpdate) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *FirewallRuleUpdate) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *FirewallRuleUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *FirewallRuleUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *FirewallRuleUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *FirewallRuleUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### GetFilterExpr

`func (o *FirewallRuleUpdate) GetFilterExpr() string`

GetFilterExpr returns the FilterExpr field if non-nil, zero value otherwise.

### GetFilterExprOk

`func (o *FirewallRuleUpdate) GetFilterExprOk() (*string, bool)`

GetFilterExprOk returns a tuple with the FilterExpr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterExpr

`func (o *FirewallRuleUpdate) SetFilterExpr(v string)`

SetFilterExpr sets FilterExpr field to given value.

### HasFilterExpr

`func (o *FirewallRuleUpdate) HasFilterExpr() bool`

HasFilterExpr returns a boolean if a field has been set.

### GetAction

`func (o *FirewallRuleUpdate) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *FirewallRuleUpdate) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *FirewallRuleUpdate) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *FirewallRuleUpdate) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetPriority

`func (o *FirewallRuleUpdate) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *FirewallRuleUpdate) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *FirewallRuleUpdate) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *FirewallRuleUpdate) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetIsEnabled

`func (o *FirewallRuleUpdate) GetIsEnabled() bool`

GetIsEnabled returns the IsEnabled field if non-nil, zero value otherwise.

### GetIsEnabledOk

`func (o *FirewallRuleUpdate) GetIsEnabledOk() (*bool, bool)`

GetIsEnabledOk returns a tuple with the IsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEnabled

`func (o *FirewallRuleUpdate) SetIsEnabled(v bool)`

SetIsEnabled sets IsEnabled field to given value.

### HasIsEnabled

`func (o *FirewallRuleUpdate) HasIsEnabled() bool`

HasIsEnabled returns a boolean if a field has been set.

### GetNote

`func (o *FirewallRuleUpdate) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *FirewallRuleUpdate) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *FirewallRuleUpdate) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *FirewallRuleUpdate) HasNote() bool`

HasNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



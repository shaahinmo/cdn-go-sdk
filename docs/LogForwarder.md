# LogForwarder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] [readonly] 
**Name** | **string** |  | 
**Description** | **string** |  | 
**Type** | **string** |  | 
**ConnectionType** | **string** |  | 
**DataFormat** | Pointer to [**LogForwarderDataFormat**](LogForwarderDataFormat.md) |  | [optional] 
**DataFormatExpr** | Pointer to **string** | Expr expression language | [optional] 
**Settings** | [**LogForwarderSetting**](LogForwarderSetting.md) |  | 
**Status** | **bool** |  | 

## Methods

### NewLogForwarder

`func NewLogForwarder(name string, description string, type_ string, connectionType string, settings LogForwarderSetting, status bool, ) *LogForwarder`

NewLogForwarder instantiates a new LogForwarder object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLogForwarderWithDefaults

`func NewLogForwarderWithDefaults() *LogForwarder`

NewLogForwarderWithDefaults instantiates a new LogForwarder object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *LogForwarder) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LogForwarder) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LogForwarder) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *LogForwarder) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *LogForwarder) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *LogForwarder) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *LogForwarder) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *LogForwarder) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LogForwarder) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LogForwarder) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetType

`func (o *LogForwarder) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *LogForwarder) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *LogForwarder) SetType(v string)`

SetType sets Type field to given value.


### GetConnectionType

`func (o *LogForwarder) GetConnectionType() string`

GetConnectionType returns the ConnectionType field if non-nil, zero value otherwise.

### GetConnectionTypeOk

`func (o *LogForwarder) GetConnectionTypeOk() (*string, bool)`

GetConnectionTypeOk returns a tuple with the ConnectionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionType

`func (o *LogForwarder) SetConnectionType(v string)`

SetConnectionType sets ConnectionType field to given value.


### GetDataFormat

`func (o *LogForwarder) GetDataFormat() LogForwarderDataFormat`

GetDataFormat returns the DataFormat field if non-nil, zero value otherwise.

### GetDataFormatOk

`func (o *LogForwarder) GetDataFormatOk() (*LogForwarderDataFormat, bool)`

GetDataFormatOk returns a tuple with the DataFormat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataFormat

`func (o *LogForwarder) SetDataFormat(v LogForwarderDataFormat)`

SetDataFormat sets DataFormat field to given value.

### HasDataFormat

`func (o *LogForwarder) HasDataFormat() bool`

HasDataFormat returns a boolean if a field has been set.

### GetDataFormatExpr

`func (o *LogForwarder) GetDataFormatExpr() string`

GetDataFormatExpr returns the DataFormatExpr field if non-nil, zero value otherwise.

### GetDataFormatExprOk

`func (o *LogForwarder) GetDataFormatExprOk() (*string, bool)`

GetDataFormatExprOk returns a tuple with the DataFormatExpr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataFormatExpr

`func (o *LogForwarder) SetDataFormatExpr(v string)`

SetDataFormatExpr sets DataFormatExpr field to given value.

### HasDataFormatExpr

`func (o *LogForwarder) HasDataFormatExpr() bool`

HasDataFormatExpr returns a boolean if a field has been set.

### GetSettings

`func (o *LogForwarder) GetSettings() LogForwarderSetting`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *LogForwarder) GetSettingsOk() (*LogForwarderSetting, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *LogForwarder) SetSettings(v LogForwarderSetting)`

SetSettings sets Settings field to given value.


### GetStatus

`func (o *LogForwarder) GetStatus() bool`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *LogForwarder) GetStatusOk() (*bool, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *LogForwarder) SetStatus(v bool)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



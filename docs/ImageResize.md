# ImageResize

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** |  | [optional] [default to "off"]
**HeightBy** | Pointer to **string** |  | [optional] [default to "height"]
**WidthBy** | Pointer to **string** |  | [optional] [default to "width"]
**Mode** | Pointer to **string** | Whether needs to preserve aspect ratio based on the short/long side of the image (after transforming) | [optional] [default to "freely"]
**ModeBy** | Pointer to **string** | Name of the variable for overriding &#39;mode&#39; in query string. Acceptable values for that variable are &#39;f&#39;, &#39;s&#39;, and &#39;l&#39; | [optional] [default to ""]

## Methods

### NewImageResize

`func NewImageResize() *ImageResize`

NewImageResize instantiates a new ImageResize object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageResizeWithDefaults

`func NewImageResizeWithDefaults() *ImageResize`

NewImageResizeWithDefaults instantiates a new ImageResize object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *ImageResize) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ImageResize) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ImageResize) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ImageResize) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetHeightBy

`func (o *ImageResize) GetHeightBy() string`

GetHeightBy returns the HeightBy field if non-nil, zero value otherwise.

### GetHeightByOk

`func (o *ImageResize) GetHeightByOk() (*string, bool)`

GetHeightByOk returns a tuple with the HeightBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeightBy

`func (o *ImageResize) SetHeightBy(v string)`

SetHeightBy sets HeightBy field to given value.

### HasHeightBy

`func (o *ImageResize) HasHeightBy() bool`

HasHeightBy returns a boolean if a field has been set.

### GetWidthBy

`func (o *ImageResize) GetWidthBy() string`

GetWidthBy returns the WidthBy field if non-nil, zero value otherwise.

### GetWidthByOk

`func (o *ImageResize) GetWidthByOk() (*string, bool)`

GetWidthByOk returns a tuple with the WidthBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidthBy

`func (o *ImageResize) SetWidthBy(v string)`

SetWidthBy sets WidthBy field to given value.

### HasWidthBy

`func (o *ImageResize) HasWidthBy() bool`

HasWidthBy returns a boolean if a field has been set.

### GetMode

`func (o *ImageResize) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *ImageResize) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *ImageResize) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *ImageResize) HasMode() bool`

HasMode returns a boolean if a field has been set.

### GetModeBy

`func (o *ImageResize) GetModeBy() string`

GetModeBy returns the ModeBy field if non-nil, zero value otherwise.

### GetModeByOk

`func (o *ImageResize) GetModeByOk() (*string, bool)`

GetModeByOk returns a tuple with the ModeBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModeBy

`func (o *ImageResize) SetModeBy(v string)`

SetModeBy sets ModeBy field to given value.

### HasModeBy

`func (o *ImageResize) HasModeBy() bool`

HasModeBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



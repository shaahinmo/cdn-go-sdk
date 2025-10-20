# SslCertGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**SslCertGet200ResponseData**](SslCertGet200ResponseData.md) |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewSslCertGet200Response

`func NewSslCertGet200Response() *SslCertGet200Response`

NewSslCertGet200Response instantiates a new SslCertGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSslCertGet200ResponseWithDefaults

`func NewSslCertGet200ResponseWithDefaults() *SslCertGet200Response`

NewSslCertGet200ResponseWithDefaults instantiates a new SslCertGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *SslCertGet200Response) GetData() SslCertGet200ResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SslCertGet200Response) GetDataOk() (*SslCertGet200ResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SslCertGet200Response) SetData(v SslCertGet200ResponseData)`

SetData sets Data field to given value.

### HasData

`func (o *SslCertGet200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetMessage

`func (o *SslCertGet200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *SslCertGet200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *SslCertGet200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *SslCertGet200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *SslCertGet200Response) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *SslCertGet200Response) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# SslCertIndex200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]Certificate**](Certificate.md) |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewSslCertIndex200Response

`func NewSslCertIndex200Response() *SslCertIndex200Response`

NewSslCertIndex200Response instantiates a new SslCertIndex200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSslCertIndex200ResponseWithDefaults

`func NewSslCertIndex200ResponseWithDefaults() *SslCertIndex200Response`

NewSslCertIndex200ResponseWithDefaults instantiates a new SslCertIndex200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *SslCertIndex200Response) GetData() []Certificate`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SslCertIndex200Response) GetDataOk() (*[]Certificate, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SslCertIndex200Response) SetData(v []Certificate)`

SetData sets Data field to given value.

### HasData

`func (o *SslCertIndex200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetMessage

`func (o *SslCertIndex200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *SslCertIndex200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *SslCertIndex200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *SslCertIndex200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *SslCertIndex200Response) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *SslCertIndex200Response) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



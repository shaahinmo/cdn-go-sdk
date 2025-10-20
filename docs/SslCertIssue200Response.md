# SslCertIssue200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**CertificateOrder**](CertificateOrder.md) |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewSslCertIssue200Response

`func NewSslCertIssue200Response() *SslCertIssue200Response`

NewSslCertIssue200Response instantiates a new SslCertIssue200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSslCertIssue200ResponseWithDefaults

`func NewSslCertIssue200ResponseWithDefaults() *SslCertIssue200Response`

NewSslCertIssue200ResponseWithDefaults instantiates a new SslCertIssue200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *SslCertIssue200Response) GetData() CertificateOrder`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SslCertIssue200Response) GetDataOk() (*CertificateOrder, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SslCertIssue200Response) SetData(v CertificateOrder)`

SetData sets Data field to given value.

### HasData

`func (o *SslCertIssue200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetMessage

`func (o *SslCertIssue200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *SslCertIssue200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *SslCertIssue200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *SslCertIssue200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *SslCertIssue200Response) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *SslCertIssue200Response) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



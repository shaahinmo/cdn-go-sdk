# WafSettingsLogRedaction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cookies** | Pointer to **[]string** | List of cookie names to redact. | [optional] [default to []]
**Headers** | Pointer to **[]string** | List of header names to redact. | [optional] [default to ["authorization","proxy-authorization","cookie"]]
**AllHeaders** | Pointer to **bool** | Redact all headers if true. | [optional] [default to false]
**Body** | Pointer to **bool** | Redact the request body if true. | [optional] [default to true]
**Records** | Pointer to **bool** | Redacts specific log entries or entire log records. When enabled, fields within log records may be hidden or replaced with a placeholder.  | [optional] [default to false]
**ReplacementString** | Pointer to **string** | String to replace redacted values. | [optional] [default to "--REDACTED--"]

## Methods

### NewWafSettingsLogRedaction

`func NewWafSettingsLogRedaction() *WafSettingsLogRedaction`

NewWafSettingsLogRedaction instantiates a new WafSettingsLogRedaction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWafSettingsLogRedactionWithDefaults

`func NewWafSettingsLogRedactionWithDefaults() *WafSettingsLogRedaction`

NewWafSettingsLogRedactionWithDefaults instantiates a new WafSettingsLogRedaction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCookies

`func (o *WafSettingsLogRedaction) GetCookies() []string`

GetCookies returns the Cookies field if non-nil, zero value otherwise.

### GetCookiesOk

`func (o *WafSettingsLogRedaction) GetCookiesOk() (*[]string, bool)`

GetCookiesOk returns a tuple with the Cookies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCookies

`func (o *WafSettingsLogRedaction) SetCookies(v []string)`

SetCookies sets Cookies field to given value.

### HasCookies

`func (o *WafSettingsLogRedaction) HasCookies() bool`

HasCookies returns a boolean if a field has been set.

### GetHeaders

`func (o *WafSettingsLogRedaction) GetHeaders() []string`

GetHeaders returns the Headers field if non-nil, zero value otherwise.

### GetHeadersOk

`func (o *WafSettingsLogRedaction) GetHeadersOk() (*[]string, bool)`

GetHeadersOk returns a tuple with the Headers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeaders

`func (o *WafSettingsLogRedaction) SetHeaders(v []string)`

SetHeaders sets Headers field to given value.

### HasHeaders

`func (o *WafSettingsLogRedaction) HasHeaders() bool`

HasHeaders returns a boolean if a field has been set.

### GetAllHeaders

`func (o *WafSettingsLogRedaction) GetAllHeaders() bool`

GetAllHeaders returns the AllHeaders field if non-nil, zero value otherwise.

### GetAllHeadersOk

`func (o *WafSettingsLogRedaction) GetAllHeadersOk() (*bool, bool)`

GetAllHeadersOk returns a tuple with the AllHeaders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllHeaders

`func (o *WafSettingsLogRedaction) SetAllHeaders(v bool)`

SetAllHeaders sets AllHeaders field to given value.

### HasAllHeaders

`func (o *WafSettingsLogRedaction) HasAllHeaders() bool`

HasAllHeaders returns a boolean if a field has been set.

### GetBody

`func (o *WafSettingsLogRedaction) GetBody() bool`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *WafSettingsLogRedaction) GetBodyOk() (*bool, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *WafSettingsLogRedaction) SetBody(v bool)`

SetBody sets Body field to given value.

### HasBody

`func (o *WafSettingsLogRedaction) HasBody() bool`

HasBody returns a boolean if a field has been set.

### GetRecords

`func (o *WafSettingsLogRedaction) GetRecords() bool`

GetRecords returns the Records field if non-nil, zero value otherwise.

### GetRecordsOk

`func (o *WafSettingsLogRedaction) GetRecordsOk() (*bool, bool)`

GetRecordsOk returns a tuple with the Records field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecords

`func (o *WafSettingsLogRedaction) SetRecords(v bool)`

SetRecords sets Records field to given value.

### HasRecords

`func (o *WafSettingsLogRedaction) HasRecords() bool`

HasRecords returns a boolean if a field has been set.

### GetReplacementString

`func (o *WafSettingsLogRedaction) GetReplacementString() string`

GetReplacementString returns the ReplacementString field if non-nil, zero value otherwise.

### GetReplacementStringOk

`func (o *WafSettingsLogRedaction) GetReplacementStringOk() (*string, bool)`

GetReplacementStringOk returns a tuple with the ReplacementString field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplacementString

`func (o *WafSettingsLogRedaction) SetReplacementString(v string)`

SetReplacementString sets ReplacementString field to given value.

### HasReplacementString

`func (o *WafSettingsLogRedaction) HasReplacementString() bool`

HasReplacementString returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



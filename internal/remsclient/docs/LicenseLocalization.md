# LicenseLocalization

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | **string** |  | 
**Textcontent** | **string** |  | 
**AttachmentId** | Pointer to **NullableInt64** | For licenses of type attachment | [optional] 

## Methods

### NewLicenseLocalization

`func NewLicenseLocalization(title string, textcontent string, ) *LicenseLocalization`

NewLicenseLocalization instantiates a new LicenseLocalization object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLicenseLocalizationWithDefaults

`func NewLicenseLocalizationWithDefaults() *LicenseLocalization`

NewLicenseLocalizationWithDefaults instantiates a new LicenseLocalization object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *LicenseLocalization) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *LicenseLocalization) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *LicenseLocalization) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetTextcontent

`func (o *LicenseLocalization) GetTextcontent() string`

GetTextcontent returns the Textcontent field if non-nil, zero value otherwise.

### GetTextcontentOk

`func (o *LicenseLocalization) GetTextcontentOk() (*string, bool)`

GetTextcontentOk returns a tuple with the Textcontent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTextcontent

`func (o *LicenseLocalization) SetTextcontent(v string)`

SetTextcontent sets Textcontent field to given value.


### GetAttachmentId

`func (o *LicenseLocalization) GetAttachmentId() int64`

GetAttachmentId returns the AttachmentId field if non-nil, zero value otherwise.

### GetAttachmentIdOk

`func (o *LicenseLocalization) GetAttachmentIdOk() (*int64, bool)`

GetAttachmentIdOk returns a tuple with the AttachmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentId

`func (o *LicenseLocalization) SetAttachmentId(v int64)`

SetAttachmentId sets AttachmentId field to given value.

### HasAttachmentId

`func (o *LicenseLocalization) HasAttachmentId() bool`

HasAttachmentId returns a boolean if a field has been set.

### SetAttachmentIdNil

`func (o *LicenseLocalization) SetAttachmentIdNil(b bool)`

 SetAttachmentIdNil sets the value for AttachmentId to be an explicit nil

### UnsetAttachmentId
`func (o *LicenseLocalization) UnsetAttachmentId()`

UnsetAttachmentId ensures that no value is present for AttachmentId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



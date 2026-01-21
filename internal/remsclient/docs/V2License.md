# V2License

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LicenseAttachmentFilename** | Pointer to **map[string]string** | Text values keyed by languages | [optional] 
**LicenseText** | Pointer to **map[string]string** | Text values keyed by languages | [optional] 
**LicenseType** | **string** |  | 
**LicenseTitle** | **map[string]string** | Text values keyed by languages | 
**LicenseLink** | Pointer to **map[string]string** | Text values keyed by languages | [optional] 
**LicenseId** | **int64** |  | 
**LicenseAttachmentId** | Pointer to **map[string]int64** | Integers keyed by languages | [optional] 
**LicenseEnabled** | **bool** |  | 
**LicenseArchived** | **bool** |  | 

## Methods

### NewV2License

`func NewV2License(licenseType string, licenseTitle map[string]string, licenseId int64, licenseEnabled bool, licenseArchived bool, ) *V2License`

NewV2License instantiates a new V2License object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV2LicenseWithDefaults

`func NewV2LicenseWithDefaults() *V2License`

NewV2LicenseWithDefaults instantiates a new V2License object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLicenseAttachmentFilename

`func (o *V2License) GetLicenseAttachmentFilename() map[string]string`

GetLicenseAttachmentFilename returns the LicenseAttachmentFilename field if non-nil, zero value otherwise.

### GetLicenseAttachmentFilenameOk

`func (o *V2License) GetLicenseAttachmentFilenameOk() (*map[string]string, bool)`

GetLicenseAttachmentFilenameOk returns a tuple with the LicenseAttachmentFilename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseAttachmentFilename

`func (o *V2License) SetLicenseAttachmentFilename(v map[string]string)`

SetLicenseAttachmentFilename sets LicenseAttachmentFilename field to given value.

### HasLicenseAttachmentFilename

`func (o *V2License) HasLicenseAttachmentFilename() bool`

HasLicenseAttachmentFilename returns a boolean if a field has been set.

### GetLicenseText

`func (o *V2License) GetLicenseText() map[string]string`

GetLicenseText returns the LicenseText field if non-nil, zero value otherwise.

### GetLicenseTextOk

`func (o *V2License) GetLicenseTextOk() (*map[string]string, bool)`

GetLicenseTextOk returns a tuple with the LicenseText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseText

`func (o *V2License) SetLicenseText(v map[string]string)`

SetLicenseText sets LicenseText field to given value.

### HasLicenseText

`func (o *V2License) HasLicenseText() bool`

HasLicenseText returns a boolean if a field has been set.

### GetLicenseType

`func (o *V2License) GetLicenseType() string`

GetLicenseType returns the LicenseType field if non-nil, zero value otherwise.

### GetLicenseTypeOk

`func (o *V2License) GetLicenseTypeOk() (*string, bool)`

GetLicenseTypeOk returns a tuple with the LicenseType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseType

`func (o *V2License) SetLicenseType(v string)`

SetLicenseType sets LicenseType field to given value.


### GetLicenseTitle

`func (o *V2License) GetLicenseTitle() map[string]string`

GetLicenseTitle returns the LicenseTitle field if non-nil, zero value otherwise.

### GetLicenseTitleOk

`func (o *V2License) GetLicenseTitleOk() (*map[string]string, bool)`

GetLicenseTitleOk returns a tuple with the LicenseTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseTitle

`func (o *V2License) SetLicenseTitle(v map[string]string)`

SetLicenseTitle sets LicenseTitle field to given value.


### GetLicenseLink

`func (o *V2License) GetLicenseLink() map[string]string`

GetLicenseLink returns the LicenseLink field if non-nil, zero value otherwise.

### GetLicenseLinkOk

`func (o *V2License) GetLicenseLinkOk() (*map[string]string, bool)`

GetLicenseLinkOk returns a tuple with the LicenseLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseLink

`func (o *V2License) SetLicenseLink(v map[string]string)`

SetLicenseLink sets LicenseLink field to given value.

### HasLicenseLink

`func (o *V2License) HasLicenseLink() bool`

HasLicenseLink returns a boolean if a field has been set.

### GetLicenseId

`func (o *V2License) GetLicenseId() int64`

GetLicenseId returns the LicenseId field if non-nil, zero value otherwise.

### GetLicenseIdOk

`func (o *V2License) GetLicenseIdOk() (*int64, bool)`

GetLicenseIdOk returns a tuple with the LicenseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseId

`func (o *V2License) SetLicenseId(v int64)`

SetLicenseId sets LicenseId field to given value.


### GetLicenseAttachmentId

`func (o *V2License) GetLicenseAttachmentId() map[string]int64`

GetLicenseAttachmentId returns the LicenseAttachmentId field if non-nil, zero value otherwise.

### GetLicenseAttachmentIdOk

`func (o *V2License) GetLicenseAttachmentIdOk() (*map[string]int64, bool)`

GetLicenseAttachmentIdOk returns a tuple with the LicenseAttachmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseAttachmentId

`func (o *V2License) SetLicenseAttachmentId(v map[string]int64)`

SetLicenseAttachmentId sets LicenseAttachmentId field to given value.

### HasLicenseAttachmentId

`func (o *V2License) HasLicenseAttachmentId() bool`

HasLicenseAttachmentId returns a boolean if a field has been set.

### GetLicenseEnabled

`func (o *V2License) GetLicenseEnabled() bool`

GetLicenseEnabled returns the LicenseEnabled field if non-nil, zero value otherwise.

### GetLicenseEnabledOk

`func (o *V2License) GetLicenseEnabledOk() (*bool, bool)`

GetLicenseEnabledOk returns a tuple with the LicenseEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseEnabled

`func (o *V2License) SetLicenseEnabled(v bool)`

SetLicenseEnabled sets LicenseEnabled field to given value.


### GetLicenseArchived

`func (o *V2License) GetLicenseArchived() bool`

GetLicenseArchived returns the LicenseArchived field if non-nil, zero value otherwise.

### GetLicenseArchivedOk

`func (o *V2License) GetLicenseArchivedOk() (*bool, bool)`

GetLicenseArchivedOk returns a tuple with the LicenseArchived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseArchived

`func (o *V2License) SetLicenseArchived(v bool)`

SetLicenseArchived sets LicenseArchived field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



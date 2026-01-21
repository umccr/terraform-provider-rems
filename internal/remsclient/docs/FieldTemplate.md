# FieldTemplate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FieldInfoText** | Pointer to **map[string]string** | Text values keyed by languages | [optional] 
**FieldTitle** | **map[string]string** | Text values keyed by languages | 
**FieldColumns** | Pointer to [**[]FormTemplateFieldsColumns**](FormTemplateFieldsColumns.md) |  | [optional] 
**FieldMaxLength** | Pointer to **NullableInt64** |  | [optional] 
**FieldOptions** | Pointer to [**[]FormTemplateFieldsOptions**](FormTemplateFieldsOptions.md) |  | [optional] 
**FieldPrivacy** | Pointer to **string** | Public by default | [optional] 
**FieldVisibility** | Pointer to [**FormTemplateFieldsVisibility**](FormTemplateFieldsVisibility.md) |  | [optional] 
**FieldType** | **string** |  | 
**FieldId** | **string** |  | 
**FieldOptional** | **bool** |  | 
**FieldPlaceholder** | Pointer to **map[string]string** | Text values keyed by languages | [optional] 

## Methods

### NewFieldTemplate

`func NewFieldTemplate(fieldTitle map[string]string, fieldType string, fieldId string, fieldOptional bool, ) *FieldTemplate`

NewFieldTemplate instantiates a new FieldTemplate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFieldTemplateWithDefaults

`func NewFieldTemplateWithDefaults() *FieldTemplate`

NewFieldTemplateWithDefaults instantiates a new FieldTemplate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFieldInfoText

`func (o *FieldTemplate) GetFieldInfoText() map[string]string`

GetFieldInfoText returns the FieldInfoText field if non-nil, zero value otherwise.

### GetFieldInfoTextOk

`func (o *FieldTemplate) GetFieldInfoTextOk() (*map[string]string, bool)`

GetFieldInfoTextOk returns a tuple with the FieldInfoText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldInfoText

`func (o *FieldTemplate) SetFieldInfoText(v map[string]string)`

SetFieldInfoText sets FieldInfoText field to given value.

### HasFieldInfoText

`func (o *FieldTemplate) HasFieldInfoText() bool`

HasFieldInfoText returns a boolean if a field has been set.

### GetFieldTitle

`func (o *FieldTemplate) GetFieldTitle() map[string]string`

GetFieldTitle returns the FieldTitle field if non-nil, zero value otherwise.

### GetFieldTitleOk

`func (o *FieldTemplate) GetFieldTitleOk() (*map[string]string, bool)`

GetFieldTitleOk returns a tuple with the FieldTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldTitle

`func (o *FieldTemplate) SetFieldTitle(v map[string]string)`

SetFieldTitle sets FieldTitle field to given value.


### GetFieldColumns

`func (o *FieldTemplate) GetFieldColumns() []FormTemplateFieldsColumns`

GetFieldColumns returns the FieldColumns field if non-nil, zero value otherwise.

### GetFieldColumnsOk

`func (o *FieldTemplate) GetFieldColumnsOk() (*[]FormTemplateFieldsColumns, bool)`

GetFieldColumnsOk returns a tuple with the FieldColumns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldColumns

`func (o *FieldTemplate) SetFieldColumns(v []FormTemplateFieldsColumns)`

SetFieldColumns sets FieldColumns field to given value.

### HasFieldColumns

`func (o *FieldTemplate) HasFieldColumns() bool`

HasFieldColumns returns a boolean if a field has been set.

### GetFieldMaxLength

`func (o *FieldTemplate) GetFieldMaxLength() int64`

GetFieldMaxLength returns the FieldMaxLength field if non-nil, zero value otherwise.

### GetFieldMaxLengthOk

`func (o *FieldTemplate) GetFieldMaxLengthOk() (*int64, bool)`

GetFieldMaxLengthOk returns a tuple with the FieldMaxLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldMaxLength

`func (o *FieldTemplate) SetFieldMaxLength(v int64)`

SetFieldMaxLength sets FieldMaxLength field to given value.

### HasFieldMaxLength

`func (o *FieldTemplate) HasFieldMaxLength() bool`

HasFieldMaxLength returns a boolean if a field has been set.

### SetFieldMaxLengthNil

`func (o *FieldTemplate) SetFieldMaxLengthNil(b bool)`

 SetFieldMaxLengthNil sets the value for FieldMaxLength to be an explicit nil

### UnsetFieldMaxLength
`func (o *FieldTemplate) UnsetFieldMaxLength()`

UnsetFieldMaxLength ensures that no value is present for FieldMaxLength, not even an explicit nil
### GetFieldOptions

`func (o *FieldTemplate) GetFieldOptions() []FormTemplateFieldsOptions`

GetFieldOptions returns the FieldOptions field if non-nil, zero value otherwise.

### GetFieldOptionsOk

`func (o *FieldTemplate) GetFieldOptionsOk() (*[]FormTemplateFieldsOptions, bool)`

GetFieldOptionsOk returns a tuple with the FieldOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldOptions

`func (o *FieldTemplate) SetFieldOptions(v []FormTemplateFieldsOptions)`

SetFieldOptions sets FieldOptions field to given value.

### HasFieldOptions

`func (o *FieldTemplate) HasFieldOptions() bool`

HasFieldOptions returns a boolean if a field has been set.

### GetFieldPrivacy

`func (o *FieldTemplate) GetFieldPrivacy() string`

GetFieldPrivacy returns the FieldPrivacy field if non-nil, zero value otherwise.

### GetFieldPrivacyOk

`func (o *FieldTemplate) GetFieldPrivacyOk() (*string, bool)`

GetFieldPrivacyOk returns a tuple with the FieldPrivacy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldPrivacy

`func (o *FieldTemplate) SetFieldPrivacy(v string)`

SetFieldPrivacy sets FieldPrivacy field to given value.

### HasFieldPrivacy

`func (o *FieldTemplate) HasFieldPrivacy() bool`

HasFieldPrivacy returns a boolean if a field has been set.

### GetFieldVisibility

`func (o *FieldTemplate) GetFieldVisibility() FormTemplateFieldsVisibility`

GetFieldVisibility returns the FieldVisibility field if non-nil, zero value otherwise.

### GetFieldVisibilityOk

`func (o *FieldTemplate) GetFieldVisibilityOk() (*FormTemplateFieldsVisibility, bool)`

GetFieldVisibilityOk returns a tuple with the FieldVisibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldVisibility

`func (o *FieldTemplate) SetFieldVisibility(v FormTemplateFieldsVisibility)`

SetFieldVisibility sets FieldVisibility field to given value.

### HasFieldVisibility

`func (o *FieldTemplate) HasFieldVisibility() bool`

HasFieldVisibility returns a boolean if a field has been set.

### GetFieldType

`func (o *FieldTemplate) GetFieldType() string`

GetFieldType returns the FieldType field if non-nil, zero value otherwise.

### GetFieldTypeOk

`func (o *FieldTemplate) GetFieldTypeOk() (*string, bool)`

GetFieldTypeOk returns a tuple with the FieldType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldType

`func (o *FieldTemplate) SetFieldType(v string)`

SetFieldType sets FieldType field to given value.


### GetFieldId

`func (o *FieldTemplate) GetFieldId() string`

GetFieldId returns the FieldId field if non-nil, zero value otherwise.

### GetFieldIdOk

`func (o *FieldTemplate) GetFieldIdOk() (*string, bool)`

GetFieldIdOk returns a tuple with the FieldId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldId

`func (o *FieldTemplate) SetFieldId(v string)`

SetFieldId sets FieldId field to given value.


### GetFieldOptional

`func (o *FieldTemplate) GetFieldOptional() bool`

GetFieldOptional returns the FieldOptional field if non-nil, zero value otherwise.

### GetFieldOptionalOk

`func (o *FieldTemplate) GetFieldOptionalOk() (*bool, bool)`

GetFieldOptionalOk returns a tuple with the FieldOptional field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldOptional

`func (o *FieldTemplate) SetFieldOptional(v bool)`

SetFieldOptional sets FieldOptional field to given value.


### GetFieldPlaceholder

`func (o *FieldTemplate) GetFieldPlaceholder() map[string]string`

GetFieldPlaceholder returns the FieldPlaceholder field if non-nil, zero value otherwise.

### GetFieldPlaceholderOk

`func (o *FieldTemplate) GetFieldPlaceholderOk() (*map[string]string, bool)`

GetFieldPlaceholderOk returns a tuple with the FieldPlaceholder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldPlaceholder

`func (o *FieldTemplate) SetFieldPlaceholder(v map[string]string)`

SetFieldPlaceholder sets FieldPlaceholder field to given value.

### HasFieldPlaceholder

`func (o *FieldTemplate) HasFieldPlaceholder() bool`

HasFieldPlaceholder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



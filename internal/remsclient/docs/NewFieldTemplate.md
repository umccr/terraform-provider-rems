# NewFieldTemplate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FieldInfoText** | Pointer to **map[string]string** | Text values keyed by languages | [optional] 
**FieldTitle** | **map[string]string** | Text values keyed by languages | 
**FieldColumns** | Pointer to [**[]CreateFormCommandFieldsColumns**](CreateFormCommandFieldsColumns.md) |  | [optional] 
**FieldMaxLength** | Pointer to **NullableInt64** |  | [optional] 
**FieldOptions** | Pointer to [**[]CreateFormCommandFieldsOptions**](CreateFormCommandFieldsOptions.md) |  | [optional] 
**FieldPrivacy** | Pointer to **string** | Public by default | [optional] 
**FieldVisibility** | Pointer to [**CreateFormCommandFieldsVisibility**](CreateFormCommandFieldsVisibility.md) |  | [optional] 
**FieldType** | **string** |  | 
**FieldId** | Pointer to **string** |  | [optional] 
**FieldOptional** | **bool** |  | 
**FieldPlaceholder** | Pointer to **map[string]string** | Text values keyed by languages | [optional] 

## Methods

### NewNewFieldTemplate

`func NewNewFieldTemplate(fieldTitle map[string]string, fieldType string, fieldOptional bool, ) *NewFieldTemplate`

NewNewFieldTemplate instantiates a new NewFieldTemplate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNewFieldTemplateWithDefaults

`func NewNewFieldTemplateWithDefaults() *NewFieldTemplate`

NewNewFieldTemplateWithDefaults instantiates a new NewFieldTemplate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFieldInfoText

`func (o *NewFieldTemplate) GetFieldInfoText() map[string]string`

GetFieldInfoText returns the FieldInfoText field if non-nil, zero value otherwise.

### GetFieldInfoTextOk

`func (o *NewFieldTemplate) GetFieldInfoTextOk() (*map[string]string, bool)`

GetFieldInfoTextOk returns a tuple with the FieldInfoText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldInfoText

`func (o *NewFieldTemplate) SetFieldInfoText(v map[string]string)`

SetFieldInfoText sets FieldInfoText field to given value.

### HasFieldInfoText

`func (o *NewFieldTemplate) HasFieldInfoText() bool`

HasFieldInfoText returns a boolean if a field has been set.

### GetFieldTitle

`func (o *NewFieldTemplate) GetFieldTitle() map[string]string`

GetFieldTitle returns the FieldTitle field if non-nil, zero value otherwise.

### GetFieldTitleOk

`func (o *NewFieldTemplate) GetFieldTitleOk() (*map[string]string, bool)`

GetFieldTitleOk returns a tuple with the FieldTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldTitle

`func (o *NewFieldTemplate) SetFieldTitle(v map[string]string)`

SetFieldTitle sets FieldTitle field to given value.


### GetFieldColumns

`func (o *NewFieldTemplate) GetFieldColumns() []CreateFormCommandFieldsColumns`

GetFieldColumns returns the FieldColumns field if non-nil, zero value otherwise.

### GetFieldColumnsOk

`func (o *NewFieldTemplate) GetFieldColumnsOk() (*[]CreateFormCommandFieldsColumns, bool)`

GetFieldColumnsOk returns a tuple with the FieldColumns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldColumns

`func (o *NewFieldTemplate) SetFieldColumns(v []CreateFormCommandFieldsColumns)`

SetFieldColumns sets FieldColumns field to given value.

### HasFieldColumns

`func (o *NewFieldTemplate) HasFieldColumns() bool`

HasFieldColumns returns a boolean if a field has been set.

### GetFieldMaxLength

`func (o *NewFieldTemplate) GetFieldMaxLength() int64`

GetFieldMaxLength returns the FieldMaxLength field if non-nil, zero value otherwise.

### GetFieldMaxLengthOk

`func (o *NewFieldTemplate) GetFieldMaxLengthOk() (*int64, bool)`

GetFieldMaxLengthOk returns a tuple with the FieldMaxLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldMaxLength

`func (o *NewFieldTemplate) SetFieldMaxLength(v int64)`

SetFieldMaxLength sets FieldMaxLength field to given value.

### HasFieldMaxLength

`func (o *NewFieldTemplate) HasFieldMaxLength() bool`

HasFieldMaxLength returns a boolean if a field has been set.

### SetFieldMaxLengthNil

`func (o *NewFieldTemplate) SetFieldMaxLengthNil(b bool)`

 SetFieldMaxLengthNil sets the value for FieldMaxLength to be an explicit nil

### UnsetFieldMaxLength
`func (o *NewFieldTemplate) UnsetFieldMaxLength()`

UnsetFieldMaxLength ensures that no value is present for FieldMaxLength, not even an explicit nil
### GetFieldOptions

`func (o *NewFieldTemplate) GetFieldOptions() []CreateFormCommandFieldsOptions`

GetFieldOptions returns the FieldOptions field if non-nil, zero value otherwise.

### GetFieldOptionsOk

`func (o *NewFieldTemplate) GetFieldOptionsOk() (*[]CreateFormCommandFieldsOptions, bool)`

GetFieldOptionsOk returns a tuple with the FieldOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldOptions

`func (o *NewFieldTemplate) SetFieldOptions(v []CreateFormCommandFieldsOptions)`

SetFieldOptions sets FieldOptions field to given value.

### HasFieldOptions

`func (o *NewFieldTemplate) HasFieldOptions() bool`

HasFieldOptions returns a boolean if a field has been set.

### GetFieldPrivacy

`func (o *NewFieldTemplate) GetFieldPrivacy() string`

GetFieldPrivacy returns the FieldPrivacy field if non-nil, zero value otherwise.

### GetFieldPrivacyOk

`func (o *NewFieldTemplate) GetFieldPrivacyOk() (*string, bool)`

GetFieldPrivacyOk returns a tuple with the FieldPrivacy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldPrivacy

`func (o *NewFieldTemplate) SetFieldPrivacy(v string)`

SetFieldPrivacy sets FieldPrivacy field to given value.

### HasFieldPrivacy

`func (o *NewFieldTemplate) HasFieldPrivacy() bool`

HasFieldPrivacy returns a boolean if a field has been set.

### GetFieldVisibility

`func (o *NewFieldTemplate) GetFieldVisibility() CreateFormCommandFieldsVisibility`

GetFieldVisibility returns the FieldVisibility field if non-nil, zero value otherwise.

### GetFieldVisibilityOk

`func (o *NewFieldTemplate) GetFieldVisibilityOk() (*CreateFormCommandFieldsVisibility, bool)`

GetFieldVisibilityOk returns a tuple with the FieldVisibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldVisibility

`func (o *NewFieldTemplate) SetFieldVisibility(v CreateFormCommandFieldsVisibility)`

SetFieldVisibility sets FieldVisibility field to given value.

### HasFieldVisibility

`func (o *NewFieldTemplate) HasFieldVisibility() bool`

HasFieldVisibility returns a boolean if a field has been set.

### GetFieldType

`func (o *NewFieldTemplate) GetFieldType() string`

GetFieldType returns the FieldType field if non-nil, zero value otherwise.

### GetFieldTypeOk

`func (o *NewFieldTemplate) GetFieldTypeOk() (*string, bool)`

GetFieldTypeOk returns a tuple with the FieldType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldType

`func (o *NewFieldTemplate) SetFieldType(v string)`

SetFieldType sets FieldType field to given value.


### GetFieldId

`func (o *NewFieldTemplate) GetFieldId() string`

GetFieldId returns the FieldId field if non-nil, zero value otherwise.

### GetFieldIdOk

`func (o *NewFieldTemplate) GetFieldIdOk() (*string, bool)`

GetFieldIdOk returns a tuple with the FieldId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldId

`func (o *NewFieldTemplate) SetFieldId(v string)`

SetFieldId sets FieldId field to given value.

### HasFieldId

`func (o *NewFieldTemplate) HasFieldId() bool`

HasFieldId returns a boolean if a field has been set.

### GetFieldOptional

`func (o *NewFieldTemplate) GetFieldOptional() bool`

GetFieldOptional returns the FieldOptional field if non-nil, zero value otherwise.

### GetFieldOptionalOk

`func (o *NewFieldTemplate) GetFieldOptionalOk() (*bool, bool)`

GetFieldOptionalOk returns a tuple with the FieldOptional field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldOptional

`func (o *NewFieldTemplate) SetFieldOptional(v bool)`

SetFieldOptional sets FieldOptional field to given value.


### GetFieldPlaceholder

`func (o *NewFieldTemplate) GetFieldPlaceholder() map[string]string`

GetFieldPlaceholder returns the FieldPlaceholder field if non-nil, zero value otherwise.

### GetFieldPlaceholderOk

`func (o *NewFieldTemplate) GetFieldPlaceholderOk() (*map[string]string, bool)`

GetFieldPlaceholderOk returns a tuple with the FieldPlaceholder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldPlaceholder

`func (o *NewFieldTemplate) SetFieldPlaceholder(v map[string]string)`

SetFieldPlaceholder sets FieldPlaceholder field to given value.

### HasFieldPlaceholder

`func (o *NewFieldTemplate) HasFieldPlaceholder() bool`

HasFieldPlaceholder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



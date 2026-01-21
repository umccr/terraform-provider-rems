# Field

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FieldPrivate** | **bool** |  | 
**FieldInfoText** | Pointer to **map[string]string** | Text values keyed by languages | [optional] 
**FieldTitle** | **map[string]string** | Text values keyed by languages | 
**FieldColumns** | Pointer to [**[]ApplicationFormsFieldsColumns**](ApplicationFormsFieldsColumns.md) |  | [optional] 
**FieldMaxLength** | Pointer to **NullableInt64** |  | [optional] 
**FieldOptions** | Pointer to [**[]ApplicationFormsFieldsOptions**](ApplicationFormsFieldsOptions.md) |  | [optional] 
**FieldPrivacy** | Pointer to **string** | Public by default | [optional] 
**FieldVisible** | **bool** |  | 
**FieldVisibility** | Pointer to [**ApplicationFormsFieldsVisibility**](ApplicationFormsFieldsVisibility.md) |  | [optional] 
**FieldType** | **string** |  | 
**FieldValue** | **map[string]interface{}** | A string for most fields, or [[{\&quot;column\&quot;: string, \&quot;value\&quot;: string}]] for table fields | 
**FieldPreviousValue** | Pointer to **map[string]interface{}** | A string for most fields, or [[{\&quot;column\&quot;: string, \&quot;value\&quot;: string}]] for table fields | [optional] 
**FieldId** | **string** |  | 
**FieldOptional** | **bool** |  | 
**FieldPlaceholder** | Pointer to **map[string]string** | Text values keyed by languages | [optional] 

## Methods

### NewField

`func NewField(fieldPrivate bool, fieldTitle map[string]string, fieldVisible bool, fieldType string, fieldValue map[string]interface{}, fieldId string, fieldOptional bool, ) *Field`

NewField instantiates a new Field object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFieldWithDefaults

`func NewFieldWithDefaults() *Field`

NewFieldWithDefaults instantiates a new Field object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFieldPrivate

`func (o *Field) GetFieldPrivate() bool`

GetFieldPrivate returns the FieldPrivate field if non-nil, zero value otherwise.

### GetFieldPrivateOk

`func (o *Field) GetFieldPrivateOk() (*bool, bool)`

GetFieldPrivateOk returns a tuple with the FieldPrivate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldPrivate

`func (o *Field) SetFieldPrivate(v bool)`

SetFieldPrivate sets FieldPrivate field to given value.


### GetFieldInfoText

`func (o *Field) GetFieldInfoText() map[string]string`

GetFieldInfoText returns the FieldInfoText field if non-nil, zero value otherwise.

### GetFieldInfoTextOk

`func (o *Field) GetFieldInfoTextOk() (*map[string]string, bool)`

GetFieldInfoTextOk returns a tuple with the FieldInfoText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldInfoText

`func (o *Field) SetFieldInfoText(v map[string]string)`

SetFieldInfoText sets FieldInfoText field to given value.

### HasFieldInfoText

`func (o *Field) HasFieldInfoText() bool`

HasFieldInfoText returns a boolean if a field has been set.

### GetFieldTitle

`func (o *Field) GetFieldTitle() map[string]string`

GetFieldTitle returns the FieldTitle field if non-nil, zero value otherwise.

### GetFieldTitleOk

`func (o *Field) GetFieldTitleOk() (*map[string]string, bool)`

GetFieldTitleOk returns a tuple with the FieldTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldTitle

`func (o *Field) SetFieldTitle(v map[string]string)`

SetFieldTitle sets FieldTitle field to given value.


### GetFieldColumns

`func (o *Field) GetFieldColumns() []ApplicationFormsFieldsColumns`

GetFieldColumns returns the FieldColumns field if non-nil, zero value otherwise.

### GetFieldColumnsOk

`func (o *Field) GetFieldColumnsOk() (*[]ApplicationFormsFieldsColumns, bool)`

GetFieldColumnsOk returns a tuple with the FieldColumns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldColumns

`func (o *Field) SetFieldColumns(v []ApplicationFormsFieldsColumns)`

SetFieldColumns sets FieldColumns field to given value.

### HasFieldColumns

`func (o *Field) HasFieldColumns() bool`

HasFieldColumns returns a boolean if a field has been set.

### GetFieldMaxLength

`func (o *Field) GetFieldMaxLength() int64`

GetFieldMaxLength returns the FieldMaxLength field if non-nil, zero value otherwise.

### GetFieldMaxLengthOk

`func (o *Field) GetFieldMaxLengthOk() (*int64, bool)`

GetFieldMaxLengthOk returns a tuple with the FieldMaxLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldMaxLength

`func (o *Field) SetFieldMaxLength(v int64)`

SetFieldMaxLength sets FieldMaxLength field to given value.

### HasFieldMaxLength

`func (o *Field) HasFieldMaxLength() bool`

HasFieldMaxLength returns a boolean if a field has been set.

### SetFieldMaxLengthNil

`func (o *Field) SetFieldMaxLengthNil(b bool)`

 SetFieldMaxLengthNil sets the value for FieldMaxLength to be an explicit nil

### UnsetFieldMaxLength
`func (o *Field) UnsetFieldMaxLength()`

UnsetFieldMaxLength ensures that no value is present for FieldMaxLength, not even an explicit nil
### GetFieldOptions

`func (o *Field) GetFieldOptions() []ApplicationFormsFieldsOptions`

GetFieldOptions returns the FieldOptions field if non-nil, zero value otherwise.

### GetFieldOptionsOk

`func (o *Field) GetFieldOptionsOk() (*[]ApplicationFormsFieldsOptions, bool)`

GetFieldOptionsOk returns a tuple with the FieldOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldOptions

`func (o *Field) SetFieldOptions(v []ApplicationFormsFieldsOptions)`

SetFieldOptions sets FieldOptions field to given value.

### HasFieldOptions

`func (o *Field) HasFieldOptions() bool`

HasFieldOptions returns a boolean if a field has been set.

### GetFieldPrivacy

`func (o *Field) GetFieldPrivacy() string`

GetFieldPrivacy returns the FieldPrivacy field if non-nil, zero value otherwise.

### GetFieldPrivacyOk

`func (o *Field) GetFieldPrivacyOk() (*string, bool)`

GetFieldPrivacyOk returns a tuple with the FieldPrivacy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldPrivacy

`func (o *Field) SetFieldPrivacy(v string)`

SetFieldPrivacy sets FieldPrivacy field to given value.

### HasFieldPrivacy

`func (o *Field) HasFieldPrivacy() bool`

HasFieldPrivacy returns a boolean if a field has been set.

### GetFieldVisible

`func (o *Field) GetFieldVisible() bool`

GetFieldVisible returns the FieldVisible field if non-nil, zero value otherwise.

### GetFieldVisibleOk

`func (o *Field) GetFieldVisibleOk() (*bool, bool)`

GetFieldVisibleOk returns a tuple with the FieldVisible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldVisible

`func (o *Field) SetFieldVisible(v bool)`

SetFieldVisible sets FieldVisible field to given value.


### GetFieldVisibility

`func (o *Field) GetFieldVisibility() ApplicationFormsFieldsVisibility`

GetFieldVisibility returns the FieldVisibility field if non-nil, zero value otherwise.

### GetFieldVisibilityOk

`func (o *Field) GetFieldVisibilityOk() (*ApplicationFormsFieldsVisibility, bool)`

GetFieldVisibilityOk returns a tuple with the FieldVisibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldVisibility

`func (o *Field) SetFieldVisibility(v ApplicationFormsFieldsVisibility)`

SetFieldVisibility sets FieldVisibility field to given value.

### HasFieldVisibility

`func (o *Field) HasFieldVisibility() bool`

HasFieldVisibility returns a boolean if a field has been set.

### GetFieldType

`func (o *Field) GetFieldType() string`

GetFieldType returns the FieldType field if non-nil, zero value otherwise.

### GetFieldTypeOk

`func (o *Field) GetFieldTypeOk() (*string, bool)`

GetFieldTypeOk returns a tuple with the FieldType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldType

`func (o *Field) SetFieldType(v string)`

SetFieldType sets FieldType field to given value.


### GetFieldValue

`func (o *Field) GetFieldValue() map[string]interface{}`

GetFieldValue returns the FieldValue field if non-nil, zero value otherwise.

### GetFieldValueOk

`func (o *Field) GetFieldValueOk() (*map[string]interface{}, bool)`

GetFieldValueOk returns a tuple with the FieldValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldValue

`func (o *Field) SetFieldValue(v map[string]interface{})`

SetFieldValue sets FieldValue field to given value.


### GetFieldPreviousValue

`func (o *Field) GetFieldPreviousValue() map[string]interface{}`

GetFieldPreviousValue returns the FieldPreviousValue field if non-nil, zero value otherwise.

### GetFieldPreviousValueOk

`func (o *Field) GetFieldPreviousValueOk() (*map[string]interface{}, bool)`

GetFieldPreviousValueOk returns a tuple with the FieldPreviousValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldPreviousValue

`func (o *Field) SetFieldPreviousValue(v map[string]interface{})`

SetFieldPreviousValue sets FieldPreviousValue field to given value.

### HasFieldPreviousValue

`func (o *Field) HasFieldPreviousValue() bool`

HasFieldPreviousValue returns a boolean if a field has been set.

### GetFieldId

`func (o *Field) GetFieldId() string`

GetFieldId returns the FieldId field if non-nil, zero value otherwise.

### GetFieldIdOk

`func (o *Field) GetFieldIdOk() (*string, bool)`

GetFieldIdOk returns a tuple with the FieldId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldId

`func (o *Field) SetFieldId(v string)`

SetFieldId sets FieldId field to given value.


### GetFieldOptional

`func (o *Field) GetFieldOptional() bool`

GetFieldOptional returns the FieldOptional field if non-nil, zero value otherwise.

### GetFieldOptionalOk

`func (o *Field) GetFieldOptionalOk() (*bool, bool)`

GetFieldOptionalOk returns a tuple with the FieldOptional field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldOptional

`func (o *Field) SetFieldOptional(v bool)`

SetFieldOptional sets FieldOptional field to given value.


### GetFieldPlaceholder

`func (o *Field) GetFieldPlaceholder() map[string]string`

GetFieldPlaceholder returns the FieldPlaceholder field if non-nil, zero value otherwise.

### GetFieldPlaceholderOk

`func (o *Field) GetFieldPlaceholderOk() (*map[string]string, bool)`

GetFieldPlaceholderOk returns a tuple with the FieldPlaceholder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldPlaceholder

`func (o *Field) SetFieldPlaceholder(v map[string]string)`

SetFieldPlaceholder sets FieldPlaceholder field to given value.

### HasFieldPlaceholder

`func (o *Field) HasFieldPlaceholder() bool`

HasFieldPlaceholder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



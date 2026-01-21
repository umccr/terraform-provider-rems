# Form

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FormId** | **int64** |  | 
**FormTitle** | Pointer to **string** | DEPRECATED, will disappear, use either internal name or external title as you need | [optional] 
**FormInternalName** | **string** |  | 
**FormExternalTitle** | **map[string]string** | Text values keyed by languages | 
**FormFields** | [**[]Field**](Field.md) |  | 

## Methods

### NewForm

`func NewForm(formId int64, formInternalName string, formExternalTitle map[string]string, formFields []Field, ) *Form`

NewForm instantiates a new Form object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFormWithDefaults

`func NewFormWithDefaults() *Form`

NewFormWithDefaults instantiates a new Form object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFormId

`func (o *Form) GetFormId() int64`

GetFormId returns the FormId field if non-nil, zero value otherwise.

### GetFormIdOk

`func (o *Form) GetFormIdOk() (*int64, bool)`

GetFormIdOk returns a tuple with the FormId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormId

`func (o *Form) SetFormId(v int64)`

SetFormId sets FormId field to given value.


### GetFormTitle

`func (o *Form) GetFormTitle() string`

GetFormTitle returns the FormTitle field if non-nil, zero value otherwise.

### GetFormTitleOk

`func (o *Form) GetFormTitleOk() (*string, bool)`

GetFormTitleOk returns a tuple with the FormTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormTitle

`func (o *Form) SetFormTitle(v string)`

SetFormTitle sets FormTitle field to given value.

### HasFormTitle

`func (o *Form) HasFormTitle() bool`

HasFormTitle returns a boolean if a field has been set.

### GetFormInternalName

`func (o *Form) GetFormInternalName() string`

GetFormInternalName returns the FormInternalName field if non-nil, zero value otherwise.

### GetFormInternalNameOk

`func (o *Form) GetFormInternalNameOk() (*string, bool)`

GetFormInternalNameOk returns a tuple with the FormInternalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormInternalName

`func (o *Form) SetFormInternalName(v string)`

SetFormInternalName sets FormInternalName field to given value.


### GetFormExternalTitle

`func (o *Form) GetFormExternalTitle() map[string]string`

GetFormExternalTitle returns the FormExternalTitle field if non-nil, zero value otherwise.

### GetFormExternalTitleOk

`func (o *Form) GetFormExternalTitleOk() (*map[string]string, bool)`

GetFormExternalTitleOk returns a tuple with the FormExternalTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormExternalTitle

`func (o *Form) SetFormExternalTitle(v map[string]string)`

SetFormExternalTitle sets FormExternalTitle field to given value.


### GetFormFields

`func (o *Form) GetFormFields() []Field`

GetFormFields returns the FormFields field if non-nil, zero value otherwise.

### GetFormFieldsOk

`func (o *Form) GetFormFieldsOk() (*[]Field, bool)`

GetFormFieldsOk returns a tuple with the FormFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormFields

`func (o *Form) SetFormFields(v []Field)`

SetFormFields sets FormFields field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



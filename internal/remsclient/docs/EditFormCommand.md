# EditFormCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Organization** | [**OrganizationId**](OrganizationId.md) |  | 
**FormTitle** | Pointer to **NullableString** | DEPRECATED, use internal name and external title instead | [optional] 
**FormInternalName** | Pointer to **string** |  | [optional] 
**FormExternalTitle** | Pointer to **map[string]string** | Text values keyed by languages | [optional] 
**FormFields** | [**[]NewFieldTemplate**](NewFieldTemplate.md) |  | 
**FormId** | **int64** |  | 

## Methods

### NewEditFormCommand

`func NewEditFormCommand(organization OrganizationId, formFields []NewFieldTemplate, formId int64, ) *EditFormCommand`

NewEditFormCommand instantiates a new EditFormCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEditFormCommandWithDefaults

`func NewEditFormCommandWithDefaults() *EditFormCommand`

NewEditFormCommandWithDefaults instantiates a new EditFormCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganization

`func (o *EditFormCommand) GetOrganization() OrganizationId`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *EditFormCommand) GetOrganizationOk() (*OrganizationId, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *EditFormCommand) SetOrganization(v OrganizationId)`

SetOrganization sets Organization field to given value.


### GetFormTitle

`func (o *EditFormCommand) GetFormTitle() string`

GetFormTitle returns the FormTitle field if non-nil, zero value otherwise.

### GetFormTitleOk

`func (o *EditFormCommand) GetFormTitleOk() (*string, bool)`

GetFormTitleOk returns a tuple with the FormTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormTitle

`func (o *EditFormCommand) SetFormTitle(v string)`

SetFormTitle sets FormTitle field to given value.

### HasFormTitle

`func (o *EditFormCommand) HasFormTitle() bool`

HasFormTitle returns a boolean if a field has been set.

### SetFormTitleNil

`func (o *EditFormCommand) SetFormTitleNil(b bool)`

 SetFormTitleNil sets the value for FormTitle to be an explicit nil

### UnsetFormTitle
`func (o *EditFormCommand) UnsetFormTitle()`

UnsetFormTitle ensures that no value is present for FormTitle, not even an explicit nil
### GetFormInternalName

`func (o *EditFormCommand) GetFormInternalName() string`

GetFormInternalName returns the FormInternalName field if non-nil, zero value otherwise.

### GetFormInternalNameOk

`func (o *EditFormCommand) GetFormInternalNameOk() (*string, bool)`

GetFormInternalNameOk returns a tuple with the FormInternalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormInternalName

`func (o *EditFormCommand) SetFormInternalName(v string)`

SetFormInternalName sets FormInternalName field to given value.

### HasFormInternalName

`func (o *EditFormCommand) HasFormInternalName() bool`

HasFormInternalName returns a boolean if a field has been set.

### GetFormExternalTitle

`func (o *EditFormCommand) GetFormExternalTitle() map[string]string`

GetFormExternalTitle returns the FormExternalTitle field if non-nil, zero value otherwise.

### GetFormExternalTitleOk

`func (o *EditFormCommand) GetFormExternalTitleOk() (*map[string]string, bool)`

GetFormExternalTitleOk returns a tuple with the FormExternalTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormExternalTitle

`func (o *EditFormCommand) SetFormExternalTitle(v map[string]string)`

SetFormExternalTitle sets FormExternalTitle field to given value.

### HasFormExternalTitle

`func (o *EditFormCommand) HasFormExternalTitle() bool`

HasFormExternalTitle returns a boolean if a field has been set.

### GetFormFields

`func (o *EditFormCommand) GetFormFields() []NewFieldTemplate`

GetFormFields returns the FormFields field if non-nil, zero value otherwise.

### GetFormFieldsOk

`func (o *EditFormCommand) GetFormFieldsOk() (*[]NewFieldTemplate, bool)`

GetFormFieldsOk returns a tuple with the FormFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormFields

`func (o *EditFormCommand) SetFormFields(v []NewFieldTemplate)`

SetFormFields sets FormFields field to given value.


### GetFormId

`func (o *EditFormCommand) GetFormId() int64`

GetFormId returns the FormId field if non-nil, zero value otherwise.

### GetFormIdOk

`func (o *EditFormCommand) GetFormIdOk() (*int64, bool)`

GetFormIdOk returns a tuple with the FormId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormId

`func (o *EditFormCommand) SetFormId(v int64)`

SetFormId sets FormId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



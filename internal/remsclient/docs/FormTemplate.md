# FormTemplate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Archived** | **bool** |  | 
**FormInternalName** | **string** | The internal name of the form only visible to the administration. | 
**FormFields** | [**[]FieldTemplate**](FieldTemplate.md) |  | 
**FormTitle** | Pointer to **string** | DEPRECATED, will disappear, use either internal name or external title as you need | [optional] 
**Organization** | [**OrganizationOverview**](OrganizationOverview.md) |  | 
**FormErrors** | Pointer to [**FormTemplateErrors**](FormTemplateErrors.md) |  | [optional] 
**FormId** | **int64** |  | 
**FormExternalTitle** | **map[string]string** | Text values keyed by languages | 
**Enabled** | **bool** |  | 

## Methods

### NewFormTemplate

`func NewFormTemplate(archived bool, formInternalName string, formFields []FieldTemplate, organization OrganizationOverview, formId int64, formExternalTitle map[string]string, enabled bool, ) *FormTemplate`

NewFormTemplate instantiates a new FormTemplate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFormTemplateWithDefaults

`func NewFormTemplateWithDefaults() *FormTemplate`

NewFormTemplateWithDefaults instantiates a new FormTemplate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchived

`func (o *FormTemplate) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *FormTemplate) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *FormTemplate) SetArchived(v bool)`

SetArchived sets Archived field to given value.


### GetFormInternalName

`func (o *FormTemplate) GetFormInternalName() string`

GetFormInternalName returns the FormInternalName field if non-nil, zero value otherwise.

### GetFormInternalNameOk

`func (o *FormTemplate) GetFormInternalNameOk() (*string, bool)`

GetFormInternalNameOk returns a tuple with the FormInternalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormInternalName

`func (o *FormTemplate) SetFormInternalName(v string)`

SetFormInternalName sets FormInternalName field to given value.


### GetFormFields

`func (o *FormTemplate) GetFormFields() []FieldTemplate`

GetFormFields returns the FormFields field if non-nil, zero value otherwise.

### GetFormFieldsOk

`func (o *FormTemplate) GetFormFieldsOk() (*[]FieldTemplate, bool)`

GetFormFieldsOk returns a tuple with the FormFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormFields

`func (o *FormTemplate) SetFormFields(v []FieldTemplate)`

SetFormFields sets FormFields field to given value.


### GetFormTitle

`func (o *FormTemplate) GetFormTitle() string`

GetFormTitle returns the FormTitle field if non-nil, zero value otherwise.

### GetFormTitleOk

`func (o *FormTemplate) GetFormTitleOk() (*string, bool)`

GetFormTitleOk returns a tuple with the FormTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormTitle

`func (o *FormTemplate) SetFormTitle(v string)`

SetFormTitle sets FormTitle field to given value.

### HasFormTitle

`func (o *FormTemplate) HasFormTitle() bool`

HasFormTitle returns a boolean if a field has been set.

### GetOrganization

`func (o *FormTemplate) GetOrganization() OrganizationOverview`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *FormTemplate) GetOrganizationOk() (*OrganizationOverview, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *FormTemplate) SetOrganization(v OrganizationOverview)`

SetOrganization sets Organization field to given value.


### GetFormErrors

`func (o *FormTemplate) GetFormErrors() FormTemplateErrors`

GetFormErrors returns the FormErrors field if non-nil, zero value otherwise.

### GetFormErrorsOk

`func (o *FormTemplate) GetFormErrorsOk() (*FormTemplateErrors, bool)`

GetFormErrorsOk returns a tuple with the FormErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormErrors

`func (o *FormTemplate) SetFormErrors(v FormTemplateErrors)`

SetFormErrors sets FormErrors field to given value.

### HasFormErrors

`func (o *FormTemplate) HasFormErrors() bool`

HasFormErrors returns a boolean if a field has been set.

### GetFormId

`func (o *FormTemplate) GetFormId() int64`

GetFormId returns the FormId field if non-nil, zero value otherwise.

### GetFormIdOk

`func (o *FormTemplate) GetFormIdOk() (*int64, bool)`

GetFormIdOk returns a tuple with the FormId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormId

`func (o *FormTemplate) SetFormId(v int64)`

SetFormId sets FormId field to given value.


### GetFormExternalTitle

`func (o *FormTemplate) GetFormExternalTitle() map[string]string`

GetFormExternalTitle returns the FormExternalTitle field if non-nil, zero value otherwise.

### GetFormExternalTitleOk

`func (o *FormTemplate) GetFormExternalTitleOk() (*map[string]string, bool)`

GetFormExternalTitleOk returns a tuple with the FormExternalTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormExternalTitle

`func (o *FormTemplate) SetFormExternalTitle(v map[string]string)`

SetFormExternalTitle sets FormExternalTitle field to given value.


### GetEnabled

`func (o *FormTemplate) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *FormTemplate) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *FormTemplate) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



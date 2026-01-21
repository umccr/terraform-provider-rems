# FormTemplateOverview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Archived** | **bool** |  | 
**FormInternalName** | **string** | The internal name of the form only visible to the administration. | 
**FormTitle** | Pointer to **string** | DEPRECATED, will disappear, use either internal name or external title as you need | [optional] 
**Organization** | [**OrganizationOverview**](OrganizationOverview.md) |  | 
**FormErrors** | Pointer to [**Response8007Errors**](Response8007Errors.md) |  | [optional] 
**FormId** | **int64** |  | 
**FormExternalTitle** | **map[string]string** | Text values keyed by languages | 
**Enabled** | **bool** |  | 

## Methods

### NewFormTemplateOverview

`func NewFormTemplateOverview(archived bool, formInternalName string, organization OrganizationOverview, formId int64, formExternalTitle map[string]string, enabled bool, ) *FormTemplateOverview`

NewFormTemplateOverview instantiates a new FormTemplateOverview object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFormTemplateOverviewWithDefaults

`func NewFormTemplateOverviewWithDefaults() *FormTemplateOverview`

NewFormTemplateOverviewWithDefaults instantiates a new FormTemplateOverview object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchived

`func (o *FormTemplateOverview) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *FormTemplateOverview) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *FormTemplateOverview) SetArchived(v bool)`

SetArchived sets Archived field to given value.


### GetFormInternalName

`func (o *FormTemplateOverview) GetFormInternalName() string`

GetFormInternalName returns the FormInternalName field if non-nil, zero value otherwise.

### GetFormInternalNameOk

`func (o *FormTemplateOverview) GetFormInternalNameOk() (*string, bool)`

GetFormInternalNameOk returns a tuple with the FormInternalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormInternalName

`func (o *FormTemplateOverview) SetFormInternalName(v string)`

SetFormInternalName sets FormInternalName field to given value.


### GetFormTitle

`func (o *FormTemplateOverview) GetFormTitle() string`

GetFormTitle returns the FormTitle field if non-nil, zero value otherwise.

### GetFormTitleOk

`func (o *FormTemplateOverview) GetFormTitleOk() (*string, bool)`

GetFormTitleOk returns a tuple with the FormTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormTitle

`func (o *FormTemplateOverview) SetFormTitle(v string)`

SetFormTitle sets FormTitle field to given value.

### HasFormTitle

`func (o *FormTemplateOverview) HasFormTitle() bool`

HasFormTitle returns a boolean if a field has been set.

### GetOrganization

`func (o *FormTemplateOverview) GetOrganization() OrganizationOverview`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *FormTemplateOverview) GetOrganizationOk() (*OrganizationOverview, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *FormTemplateOverview) SetOrganization(v OrganizationOverview)`

SetOrganization sets Organization field to given value.


### GetFormErrors

`func (o *FormTemplateOverview) GetFormErrors() Response8007Errors`

GetFormErrors returns the FormErrors field if non-nil, zero value otherwise.

### GetFormErrorsOk

`func (o *FormTemplateOverview) GetFormErrorsOk() (*Response8007Errors, bool)`

GetFormErrorsOk returns a tuple with the FormErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormErrors

`func (o *FormTemplateOverview) SetFormErrors(v Response8007Errors)`

SetFormErrors sets FormErrors field to given value.

### HasFormErrors

`func (o *FormTemplateOverview) HasFormErrors() bool`

HasFormErrors returns a boolean if a field has been set.

### GetFormId

`func (o *FormTemplateOverview) GetFormId() int64`

GetFormId returns the FormId field if non-nil, zero value otherwise.

### GetFormIdOk

`func (o *FormTemplateOverview) GetFormIdOk() (*int64, bool)`

GetFormIdOk returns a tuple with the FormId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormId

`func (o *FormTemplateOverview) SetFormId(v int64)`

SetFormId sets FormId field to given value.


### GetFormExternalTitle

`func (o *FormTemplateOverview) GetFormExternalTitle() map[string]string`

GetFormExternalTitle returns the FormExternalTitle field if non-nil, zero value otherwise.

### GetFormExternalTitleOk

`func (o *FormTemplateOverview) GetFormExternalTitleOk() (*map[string]string, bool)`

GetFormExternalTitleOk returns a tuple with the FormExternalTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormExternalTitle

`func (o *FormTemplateOverview) SetFormExternalTitle(v map[string]string)`

SetFormExternalTitle sets FormExternalTitle field to given value.


### GetEnabled

`func (o *FormTemplateOverview) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *FormTemplateOverview) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *FormTemplateOverview) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# CatalogueItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Archived** | **bool** |  | 
**Localizations** | [**map[string]GetCatalogueResponseLocalizationsKeyword7967**](GetCatalogueResponseLocalizationsKeyword7967.md) |  | 
**ResourceId** | **int64** |  | 
**Start** | **time.Time** |  | 
**ResourceName** | Pointer to **string** |  | [optional] 
**FormName** | Pointer to **NullableString** |  | [optional] 
**Organization** | [**OrganizationId**](OrganizationId.md) |  | 
**Wfid** | **int64** |  | 
**Resid** | **string** |  | 
**Formid** | **NullableInt64** |  | 
**Categories** | Pointer to [**[]Category**](Category.md) |  | [optional] 
**WorkflowName** | Pointer to **string** |  | [optional] 
**Id** | **int64** |  | 
**Expired** | **bool** |  | 
**End** | **NullableTime** |  | 
**Enabled** | **bool** |  | 

## Methods

### NewCatalogueItem

`func NewCatalogueItem(archived bool, localizations map[string]GetCatalogueResponseLocalizationsKeyword7967, resourceId int64, start time.Time, organization OrganizationId, wfid int64, resid string, formid NullableInt64, id int64, expired bool, end NullableTime, enabled bool, ) *CatalogueItem`

NewCatalogueItem instantiates a new CatalogueItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCatalogueItemWithDefaults

`func NewCatalogueItemWithDefaults() *CatalogueItem`

NewCatalogueItemWithDefaults instantiates a new CatalogueItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchived

`func (o *CatalogueItem) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *CatalogueItem) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *CatalogueItem) SetArchived(v bool)`

SetArchived sets Archived field to given value.


### GetLocalizations

`func (o *CatalogueItem) GetLocalizations() map[string]GetCatalogueResponseLocalizationsKeyword7967`

GetLocalizations returns the Localizations field if non-nil, zero value otherwise.

### GetLocalizationsOk

`func (o *CatalogueItem) GetLocalizationsOk() (*map[string]GetCatalogueResponseLocalizationsKeyword7967, bool)`

GetLocalizationsOk returns a tuple with the Localizations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalizations

`func (o *CatalogueItem) SetLocalizations(v map[string]GetCatalogueResponseLocalizationsKeyword7967)`

SetLocalizations sets Localizations field to given value.


### GetResourceId

`func (o *CatalogueItem) GetResourceId() int64`

GetResourceId returns the ResourceId field if non-nil, zero value otherwise.

### GetResourceIdOk

`func (o *CatalogueItem) GetResourceIdOk() (*int64, bool)`

GetResourceIdOk returns a tuple with the ResourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceId

`func (o *CatalogueItem) SetResourceId(v int64)`

SetResourceId sets ResourceId field to given value.


### GetStart

`func (o *CatalogueItem) GetStart() time.Time`

GetStart returns the Start field if non-nil, zero value otherwise.

### GetStartOk

`func (o *CatalogueItem) GetStartOk() (*time.Time, bool)`

GetStartOk returns a tuple with the Start field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStart

`func (o *CatalogueItem) SetStart(v time.Time)`

SetStart sets Start field to given value.


### GetResourceName

`func (o *CatalogueItem) GetResourceName() string`

GetResourceName returns the ResourceName field if non-nil, zero value otherwise.

### GetResourceNameOk

`func (o *CatalogueItem) GetResourceNameOk() (*string, bool)`

GetResourceNameOk returns a tuple with the ResourceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceName

`func (o *CatalogueItem) SetResourceName(v string)`

SetResourceName sets ResourceName field to given value.

### HasResourceName

`func (o *CatalogueItem) HasResourceName() bool`

HasResourceName returns a boolean if a field has been set.

### GetFormName

`func (o *CatalogueItem) GetFormName() string`

GetFormName returns the FormName field if non-nil, zero value otherwise.

### GetFormNameOk

`func (o *CatalogueItem) GetFormNameOk() (*string, bool)`

GetFormNameOk returns a tuple with the FormName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormName

`func (o *CatalogueItem) SetFormName(v string)`

SetFormName sets FormName field to given value.

### HasFormName

`func (o *CatalogueItem) HasFormName() bool`

HasFormName returns a boolean if a field has been set.

### SetFormNameNil

`func (o *CatalogueItem) SetFormNameNil(b bool)`

 SetFormNameNil sets the value for FormName to be an explicit nil

### UnsetFormName
`func (o *CatalogueItem) UnsetFormName()`

UnsetFormName ensures that no value is present for FormName, not even an explicit nil
### GetOrganization

`func (o *CatalogueItem) GetOrganization() OrganizationId`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *CatalogueItem) GetOrganizationOk() (*OrganizationId, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *CatalogueItem) SetOrganization(v OrganizationId)`

SetOrganization sets Organization field to given value.


### GetWfid

`func (o *CatalogueItem) GetWfid() int64`

GetWfid returns the Wfid field if non-nil, zero value otherwise.

### GetWfidOk

`func (o *CatalogueItem) GetWfidOk() (*int64, bool)`

GetWfidOk returns a tuple with the Wfid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWfid

`func (o *CatalogueItem) SetWfid(v int64)`

SetWfid sets Wfid field to given value.


### GetResid

`func (o *CatalogueItem) GetResid() string`

GetResid returns the Resid field if non-nil, zero value otherwise.

### GetResidOk

`func (o *CatalogueItem) GetResidOk() (*string, bool)`

GetResidOk returns a tuple with the Resid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResid

`func (o *CatalogueItem) SetResid(v string)`

SetResid sets Resid field to given value.


### GetFormid

`func (o *CatalogueItem) GetFormid() int64`

GetFormid returns the Formid field if non-nil, zero value otherwise.

### GetFormidOk

`func (o *CatalogueItem) GetFormidOk() (*int64, bool)`

GetFormidOk returns a tuple with the Formid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormid

`func (o *CatalogueItem) SetFormid(v int64)`

SetFormid sets Formid field to given value.


### SetFormidNil

`func (o *CatalogueItem) SetFormidNil(b bool)`

 SetFormidNil sets the value for Formid to be an explicit nil

### UnsetFormid
`func (o *CatalogueItem) UnsetFormid()`

UnsetFormid ensures that no value is present for Formid, not even an explicit nil
### GetCategories

`func (o *CatalogueItem) GetCategories() []Category`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *CatalogueItem) GetCategoriesOk() (*[]Category, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *CatalogueItem) SetCategories(v []Category)`

SetCategories sets Categories field to given value.

### HasCategories

`func (o *CatalogueItem) HasCategories() bool`

HasCategories returns a boolean if a field has been set.

### GetWorkflowName

`func (o *CatalogueItem) GetWorkflowName() string`

GetWorkflowName returns the WorkflowName field if non-nil, zero value otherwise.

### GetWorkflowNameOk

`func (o *CatalogueItem) GetWorkflowNameOk() (*string, bool)`

GetWorkflowNameOk returns a tuple with the WorkflowName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowName

`func (o *CatalogueItem) SetWorkflowName(v string)`

SetWorkflowName sets WorkflowName field to given value.

### HasWorkflowName

`func (o *CatalogueItem) HasWorkflowName() bool`

HasWorkflowName returns a boolean if a field has been set.

### GetId

`func (o *CatalogueItem) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CatalogueItem) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CatalogueItem) SetId(v int64)`

SetId sets Id field to given value.


### GetExpired

`func (o *CatalogueItem) GetExpired() bool`

GetExpired returns the Expired field if non-nil, zero value otherwise.

### GetExpiredOk

`func (o *CatalogueItem) GetExpiredOk() (*bool, bool)`

GetExpiredOk returns a tuple with the Expired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpired

`func (o *CatalogueItem) SetExpired(v bool)`

SetExpired sets Expired field to given value.


### GetEnd

`func (o *CatalogueItem) GetEnd() time.Time`

GetEnd returns the End field if non-nil, zero value otherwise.

### GetEndOk

`func (o *CatalogueItem) GetEndOk() (*time.Time, bool)`

GetEndOk returns a tuple with the End field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnd

`func (o *CatalogueItem) SetEnd(v time.Time)`

SetEnd sets End field to given value.


### SetEndNil

`func (o *CatalogueItem) SetEndNil(b bool)`

 SetEndNil sets the value for End to be an explicit nil

### UnsetEnd
`func (o *CatalogueItem) UnsetEnd()`

UnsetEnd ensures that no value is present for End, not even an explicit nil
### GetEnabled

`func (o *CatalogueItem) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CatalogueItem) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CatalogueItem) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# CreateCatalogueItemCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Form** | Pointer to **NullableInt64** |  | [optional] 
**Resid** | **int64** |  | 
**Wfid** | **int64** |  | 
**Organization** | [**OrganizationId**](OrganizationId.md) |  | 
**Localizations** | [**map[string]CatalogueItemLocalization**](CatalogueItemLocalization.md) | Localizations keyed by language | 
**Enabled** | Pointer to **bool** |  | [optional] 
**Archived** | Pointer to **bool** |  | [optional] 
**Categories** | Pointer to [**[]CategoryId**](CategoryId.md) |  | [optional] 

## Methods

### NewCreateCatalogueItemCommand

`func NewCreateCatalogueItemCommand(resid int64, wfid int64, organization OrganizationId, localizations map[string]CatalogueItemLocalization, ) *CreateCatalogueItemCommand`

NewCreateCatalogueItemCommand instantiates a new CreateCatalogueItemCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCatalogueItemCommandWithDefaults

`func NewCreateCatalogueItemCommandWithDefaults() *CreateCatalogueItemCommand`

NewCreateCatalogueItemCommandWithDefaults instantiates a new CreateCatalogueItemCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetForm

`func (o *CreateCatalogueItemCommand) GetForm() int64`

GetForm returns the Form field if non-nil, zero value otherwise.

### GetFormOk

`func (o *CreateCatalogueItemCommand) GetFormOk() (*int64, bool)`

GetFormOk returns a tuple with the Form field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForm

`func (o *CreateCatalogueItemCommand) SetForm(v int64)`

SetForm sets Form field to given value.

### HasForm

`func (o *CreateCatalogueItemCommand) HasForm() bool`

HasForm returns a boolean if a field has been set.

### SetFormNil

`func (o *CreateCatalogueItemCommand) SetFormNil(b bool)`

 SetFormNil sets the value for Form to be an explicit nil

### UnsetForm
`func (o *CreateCatalogueItemCommand) UnsetForm()`

UnsetForm ensures that no value is present for Form, not even an explicit nil
### GetResid

`func (o *CreateCatalogueItemCommand) GetResid() int64`

GetResid returns the Resid field if non-nil, zero value otherwise.

### GetResidOk

`func (o *CreateCatalogueItemCommand) GetResidOk() (*int64, bool)`

GetResidOk returns a tuple with the Resid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResid

`func (o *CreateCatalogueItemCommand) SetResid(v int64)`

SetResid sets Resid field to given value.


### GetWfid

`func (o *CreateCatalogueItemCommand) GetWfid() int64`

GetWfid returns the Wfid field if non-nil, zero value otherwise.

### GetWfidOk

`func (o *CreateCatalogueItemCommand) GetWfidOk() (*int64, bool)`

GetWfidOk returns a tuple with the Wfid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWfid

`func (o *CreateCatalogueItemCommand) SetWfid(v int64)`

SetWfid sets Wfid field to given value.


### GetOrganization

`func (o *CreateCatalogueItemCommand) GetOrganization() OrganizationId`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *CreateCatalogueItemCommand) GetOrganizationOk() (*OrganizationId, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *CreateCatalogueItemCommand) SetOrganization(v OrganizationId)`

SetOrganization sets Organization field to given value.


### GetLocalizations

`func (o *CreateCatalogueItemCommand) GetLocalizations() map[string]CatalogueItemLocalization`

GetLocalizations returns the Localizations field if non-nil, zero value otherwise.

### GetLocalizationsOk

`func (o *CreateCatalogueItemCommand) GetLocalizationsOk() (*map[string]CatalogueItemLocalization, bool)`

GetLocalizationsOk returns a tuple with the Localizations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalizations

`func (o *CreateCatalogueItemCommand) SetLocalizations(v map[string]CatalogueItemLocalization)`

SetLocalizations sets Localizations field to given value.


### GetEnabled

`func (o *CreateCatalogueItemCommand) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateCatalogueItemCommand) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateCatalogueItemCommand) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateCatalogueItemCommand) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetArchived

`func (o *CreateCatalogueItemCommand) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *CreateCatalogueItemCommand) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *CreateCatalogueItemCommand) SetArchived(v bool)`

SetArchived sets Archived field to given value.

### HasArchived

`func (o *CreateCatalogueItemCommand) HasArchived() bool`

HasArchived returns a boolean if a field has been set.

### GetCategories

`func (o *CreateCatalogueItemCommand) GetCategories() []CategoryId`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *CreateCatalogueItemCommand) GetCategoriesOk() (*[]CategoryId, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *CreateCatalogueItemCommand) SetCategories(v []CategoryId)`

SetCategories sets Categories field to given value.

### HasCategories

`func (o *CreateCatalogueItemCommand) HasCategories() bool`

HasCategories returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# EditCatalogueItemCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int64** |  | 
**Localizations** | [**map[string]CatalogueItemLocalization**](CatalogueItemLocalization.md) | Localizations keyed by language | 
**Organization** | Pointer to [**OrganizationId**](OrganizationId.md) |  | [optional] 
**Categories** | Pointer to [**[]CategoryId**](CategoryId.md) |  | [optional] 

## Methods

### NewEditCatalogueItemCommand

`func NewEditCatalogueItemCommand(id int64, localizations map[string]CatalogueItemLocalization, ) *EditCatalogueItemCommand`

NewEditCatalogueItemCommand instantiates a new EditCatalogueItemCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEditCatalogueItemCommandWithDefaults

`func NewEditCatalogueItemCommandWithDefaults() *EditCatalogueItemCommand`

NewEditCatalogueItemCommandWithDefaults instantiates a new EditCatalogueItemCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EditCatalogueItemCommand) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EditCatalogueItemCommand) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EditCatalogueItemCommand) SetId(v int64)`

SetId sets Id field to given value.


### GetLocalizations

`func (o *EditCatalogueItemCommand) GetLocalizations() map[string]CatalogueItemLocalization`

GetLocalizations returns the Localizations field if non-nil, zero value otherwise.

### GetLocalizationsOk

`func (o *EditCatalogueItemCommand) GetLocalizationsOk() (*map[string]CatalogueItemLocalization, bool)`

GetLocalizationsOk returns a tuple with the Localizations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalizations

`func (o *EditCatalogueItemCommand) SetLocalizations(v map[string]CatalogueItemLocalization)`

SetLocalizations sets Localizations field to given value.


### GetOrganization

`func (o *EditCatalogueItemCommand) GetOrganization() OrganizationId`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *EditCatalogueItemCommand) GetOrganizationOk() (*OrganizationId, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *EditCatalogueItemCommand) SetOrganization(v OrganizationId)`

SetOrganization sets Organization field to given value.

### HasOrganization

`func (o *EditCatalogueItemCommand) HasOrganization() bool`

HasOrganization returns a boolean if a field has been set.

### GetCategories

`func (o *EditCatalogueItemCommand) GetCategories() []CategoryId`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *EditCatalogueItemCommand) GetCategoriesOk() (*[]CategoryId, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *EditCatalogueItemCommand) SetCategories(v []CategoryId)`

SetCategories sets Categories field to given value.

### HasCategories

`func (o *EditCatalogueItemCommand) HasCategories() bool`

HasCategories returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



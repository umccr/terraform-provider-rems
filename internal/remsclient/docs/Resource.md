# Resource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int64** |  | 
**Organization** | [**OrganizationOverview**](OrganizationOverview.md) |  | 
**Resid** | **string** |  | 
**Enabled** | **bool** |  | 
**Archived** | **bool** |  | 
**Licenses** | [**[]ResourceLicense**](ResourceLicense.md) |  | 
**ResourceDuo** | Pointer to [**ResourcesDuo**](ResourcesDuo.md) |  | [optional] 

## Methods

### NewResource

`func NewResource(id int64, organization OrganizationOverview, resid string, enabled bool, archived bool, licenses []ResourceLicense, ) *Resource`

NewResource instantiates a new Resource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResourceWithDefaults

`func NewResourceWithDefaults() *Resource`

NewResourceWithDefaults instantiates a new Resource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Resource) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Resource) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Resource) SetId(v int64)`

SetId sets Id field to given value.


### GetOrganization

`func (o *Resource) GetOrganization() OrganizationOverview`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *Resource) GetOrganizationOk() (*OrganizationOverview, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *Resource) SetOrganization(v OrganizationOverview)`

SetOrganization sets Organization field to given value.


### GetResid

`func (o *Resource) GetResid() string`

GetResid returns the Resid field if non-nil, zero value otherwise.

### GetResidOk

`func (o *Resource) GetResidOk() (*string, bool)`

GetResidOk returns a tuple with the Resid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResid

`func (o *Resource) SetResid(v string)`

SetResid sets Resid field to given value.


### GetEnabled

`func (o *Resource) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *Resource) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *Resource) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetArchived

`func (o *Resource) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *Resource) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *Resource) SetArchived(v bool)`

SetArchived sets Archived field to given value.


### GetLicenses

`func (o *Resource) GetLicenses() []ResourceLicense`

GetLicenses returns the Licenses field if non-nil, zero value otherwise.

### GetLicensesOk

`func (o *Resource) GetLicensesOk() (*[]ResourceLicense, bool)`

GetLicensesOk returns a tuple with the Licenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenses

`func (o *Resource) SetLicenses(v []ResourceLicense)`

SetLicenses sets Licenses field to given value.


### GetResourceDuo

`func (o *Resource) GetResourceDuo() ResourcesDuo`

GetResourceDuo returns the ResourceDuo field if non-nil, zero value otherwise.

### GetResourceDuoOk

`func (o *Resource) GetResourceDuoOk() (*ResourcesDuo, bool)`

GetResourceDuoOk returns a tuple with the ResourceDuo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceDuo

`func (o *Resource) SetResourceDuo(v ResourcesDuo)`

SetResourceDuo sets ResourceDuo field to given value.

### HasResourceDuo

`func (o *Resource) HasResourceDuo() bool`

HasResourceDuo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



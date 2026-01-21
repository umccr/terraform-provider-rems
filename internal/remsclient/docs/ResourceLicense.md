# ResourceLicense

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int64** |  | 
**Licensetype** | **string** |  | 
**Organization** | [**OrganizationOverview**](OrganizationOverview.md) |  | 
**Enabled** | **bool** |  | 
**Archived** | **bool** |  | 
**Localizations** | [**map[string]ResourcesLicensesLocalizationsKeyword8046**](ResourcesLicensesLocalizationsKeyword8046.md) |  | 

## Methods

### NewResourceLicense

`func NewResourceLicense(id int64, licensetype string, organization OrganizationOverview, enabled bool, archived bool, localizations map[string]ResourcesLicensesLocalizationsKeyword8046, ) *ResourceLicense`

NewResourceLicense instantiates a new ResourceLicense object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResourceLicenseWithDefaults

`func NewResourceLicenseWithDefaults() *ResourceLicense`

NewResourceLicenseWithDefaults instantiates a new ResourceLicense object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ResourceLicense) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ResourceLicense) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ResourceLicense) SetId(v int64)`

SetId sets Id field to given value.


### GetLicensetype

`func (o *ResourceLicense) GetLicensetype() string`

GetLicensetype returns the Licensetype field if non-nil, zero value otherwise.

### GetLicensetypeOk

`func (o *ResourceLicense) GetLicensetypeOk() (*string, bool)`

GetLicensetypeOk returns a tuple with the Licensetype field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicensetype

`func (o *ResourceLicense) SetLicensetype(v string)`

SetLicensetype sets Licensetype field to given value.


### GetOrganization

`func (o *ResourceLicense) GetOrganization() OrganizationOverview`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *ResourceLicense) GetOrganizationOk() (*OrganizationOverview, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *ResourceLicense) SetOrganization(v OrganizationOverview)`

SetOrganization sets Organization field to given value.


### GetEnabled

`func (o *ResourceLicense) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ResourceLicense) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ResourceLicense) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetArchived

`func (o *ResourceLicense) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *ResourceLicense) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *ResourceLicense) SetArchived(v bool)`

SetArchived sets Archived field to given value.


### GetLocalizations

`func (o *ResourceLicense) GetLocalizations() map[string]ResourcesLicensesLocalizationsKeyword8046`

GetLocalizations returns the Localizations field if non-nil, zero value otherwise.

### GetLocalizationsOk

`func (o *ResourceLicense) GetLocalizationsOk() (*map[string]ResourcesLicensesLocalizationsKeyword8046, bool)`

GetLocalizationsOk returns a tuple with the Localizations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalizations

`func (o *ResourceLicense) SetLocalizations(v map[string]ResourcesLicensesLocalizationsKeyword8046)`

SetLocalizations sets Localizations field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# License

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int64** |  | 
**Licensetype** | **string** |  | 
**Organization** | [**OrganizationOverview**](OrganizationOverview.md) |  | 
**Enabled** | **bool** |  | 
**Archived** | **bool** |  | 
**Localizations** | [**map[string]LicensesLocalizationsKeyword8026**](LicensesLocalizationsKeyword8026.md) |  | 

## Methods

### NewLicense

`func NewLicense(id int64, licensetype string, organization OrganizationOverview, enabled bool, archived bool, localizations map[string]LicensesLocalizationsKeyword8026, ) *License`

NewLicense instantiates a new License object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLicenseWithDefaults

`func NewLicenseWithDefaults() *License`

NewLicenseWithDefaults instantiates a new License object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *License) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *License) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *License) SetId(v int64)`

SetId sets Id field to given value.


### GetLicensetype

`func (o *License) GetLicensetype() string`

GetLicensetype returns the Licensetype field if non-nil, zero value otherwise.

### GetLicensetypeOk

`func (o *License) GetLicensetypeOk() (*string, bool)`

GetLicensetypeOk returns a tuple with the Licensetype field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicensetype

`func (o *License) SetLicensetype(v string)`

SetLicensetype sets Licensetype field to given value.


### GetOrganization

`func (o *License) GetOrganization() OrganizationOverview`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *License) GetOrganizationOk() (*OrganizationOverview, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *License) SetOrganization(v OrganizationOverview)`

SetOrganization sets Organization field to given value.


### GetEnabled

`func (o *License) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *License) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *License) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetArchived

`func (o *License) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *License) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *License) SetArchived(v bool)`

SetArchived sets Archived field to given value.


### GetLocalizations

`func (o *License) GetLocalizations() map[string]LicensesLocalizationsKeyword8026`

GetLocalizations returns the Localizations field if non-nil, zero value otherwise.

### GetLocalizationsOk

`func (o *License) GetLocalizationsOk() (*map[string]LicensesLocalizationsKeyword8026, bool)`

GetLocalizationsOk returns a tuple with the Localizations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalizations

`func (o *License) SetLocalizations(v map[string]LicensesLocalizationsKeyword8026)`

SetLocalizations sets Localizations field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



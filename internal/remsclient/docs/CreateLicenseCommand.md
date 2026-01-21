# CreateLicenseCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Licensetype** | **string** |  | 
**Organization** | [**OrganizationId**](OrganizationId.md) |  | 
**Localizations** | [**map[string]LicenseLocalization**](LicenseLocalization.md) | Licence localizations keyed by language | 

## Methods

### NewCreateLicenseCommand

`func NewCreateLicenseCommand(licensetype string, organization OrganizationId, localizations map[string]LicenseLocalization, ) *CreateLicenseCommand`

NewCreateLicenseCommand instantiates a new CreateLicenseCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateLicenseCommandWithDefaults

`func NewCreateLicenseCommandWithDefaults() *CreateLicenseCommand`

NewCreateLicenseCommandWithDefaults instantiates a new CreateLicenseCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLicensetype

`func (o *CreateLicenseCommand) GetLicensetype() string`

GetLicensetype returns the Licensetype field if non-nil, zero value otherwise.

### GetLicensetypeOk

`func (o *CreateLicenseCommand) GetLicensetypeOk() (*string, bool)`

GetLicensetypeOk returns a tuple with the Licensetype field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicensetype

`func (o *CreateLicenseCommand) SetLicensetype(v string)`

SetLicensetype sets Licensetype field to given value.


### GetOrganization

`func (o *CreateLicenseCommand) GetOrganization() OrganizationId`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *CreateLicenseCommand) GetOrganizationOk() (*OrganizationId, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *CreateLicenseCommand) SetOrganization(v OrganizationId)`

SetOrganization sets Organization field to given value.


### GetLocalizations

`func (o *CreateLicenseCommand) GetLocalizations() map[string]LicenseLocalization`

GetLocalizations returns the Localizations field if non-nil, zero value otherwise.

### GetLocalizationsOk

`func (o *CreateLicenseCommand) GetLocalizationsOk() (*map[string]LicenseLocalization, bool)`

GetLocalizationsOk returns a tuple with the Localizations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalizations

`func (o *CreateLicenseCommand) SetLocalizations(v map[string]LicenseLocalization)`

SetLocalizations sets Localizations field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



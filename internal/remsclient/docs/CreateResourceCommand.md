# CreateResourceCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Resid** | **string** |  | 
**Organization** | [**OrganizationId**](OrganizationId.md) |  | 
**Licenses** | **[]int64** |  | 
**ResourceDuo** | Pointer to [**CreateResourceCommandDuo**](CreateResourceCommandDuo.md) |  | [optional] 

## Methods

### NewCreateResourceCommand

`func NewCreateResourceCommand(resid string, organization OrganizationId, licenses []int64, ) *CreateResourceCommand`

NewCreateResourceCommand instantiates a new CreateResourceCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateResourceCommandWithDefaults

`func NewCreateResourceCommandWithDefaults() *CreateResourceCommand`

NewCreateResourceCommandWithDefaults instantiates a new CreateResourceCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResid

`func (o *CreateResourceCommand) GetResid() string`

GetResid returns the Resid field if non-nil, zero value otherwise.

### GetResidOk

`func (o *CreateResourceCommand) GetResidOk() (*string, bool)`

GetResidOk returns a tuple with the Resid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResid

`func (o *CreateResourceCommand) SetResid(v string)`

SetResid sets Resid field to given value.


### GetOrganization

`func (o *CreateResourceCommand) GetOrganization() OrganizationId`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *CreateResourceCommand) GetOrganizationOk() (*OrganizationId, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *CreateResourceCommand) SetOrganization(v OrganizationId)`

SetOrganization sets Organization field to given value.


### GetLicenses

`func (o *CreateResourceCommand) GetLicenses() []int64`

GetLicenses returns the Licenses field if non-nil, zero value otherwise.

### GetLicensesOk

`func (o *CreateResourceCommand) GetLicensesOk() (*[]int64, bool)`

GetLicensesOk returns a tuple with the Licenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenses

`func (o *CreateResourceCommand) SetLicenses(v []int64)`

SetLicenses sets Licenses field to given value.


### GetResourceDuo

`func (o *CreateResourceCommand) GetResourceDuo() CreateResourceCommandDuo`

GetResourceDuo returns the ResourceDuo field if non-nil, zero value otherwise.

### GetResourceDuoOk

`func (o *CreateResourceCommand) GetResourceDuoOk() (*CreateResourceCommandDuo, bool)`

GetResourceDuoOk returns a tuple with the ResourceDuo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceDuo

`func (o *CreateResourceCommand) SetResourceDuo(v CreateResourceCommandDuo)`

SetResourceDuo sets ResourceDuo field to given value.

### HasResourceDuo

`func (o *CreateResourceCommand) HasResourceDuo() bool`

HasResourceDuo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



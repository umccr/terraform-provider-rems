# OrganizationArchivedCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrganizationId** | **string** |  | 
**Archived** | **bool** |  | 

## Methods

### NewOrganizationArchivedCommand

`func NewOrganizationArchivedCommand(organizationId string, archived bool, ) *OrganizationArchivedCommand`

NewOrganizationArchivedCommand instantiates a new OrganizationArchivedCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationArchivedCommandWithDefaults

`func NewOrganizationArchivedCommandWithDefaults() *OrganizationArchivedCommand`

NewOrganizationArchivedCommandWithDefaults instantiates a new OrganizationArchivedCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationId

`func (o *OrganizationArchivedCommand) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OrganizationArchivedCommand) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OrganizationArchivedCommand) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetArchived

`func (o *OrganizationArchivedCommand) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *OrganizationArchivedCommand) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *OrganizationArchivedCommand) SetArchived(v bool)`

SetArchived sets Archived field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# CreateOrganizationCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Archived** | Pointer to **bool** |  | [optional] 
**OrganizationId** | **string** |  | 
**OrganizationShortName** | **map[string]string** | Text values keyed by languages | 
**OrganizationReviewEmails** | Pointer to [**[]CreateOrganizationCommandReviewEmails**](CreateOrganizationCommandReviewEmails.md) |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**OrganizationOwners** | Pointer to [**[]User**](User.md) |  | [optional] 
**OrganizationModifier** | Pointer to [**UserWithAttributes**](UserWithAttributes.md) |  | [optional] 
**OrganizationLastModified** | Pointer to **time.Time** |  | [optional] 
**OrganizationName** | **map[string]string** | Text values keyed by languages | 

## Methods

### NewCreateOrganizationCommand

`func NewCreateOrganizationCommand(organizationId string, organizationShortName map[string]string, organizationName map[string]string, ) *CreateOrganizationCommand`

NewCreateOrganizationCommand instantiates a new CreateOrganizationCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrganizationCommandWithDefaults

`func NewCreateOrganizationCommandWithDefaults() *CreateOrganizationCommand`

NewCreateOrganizationCommandWithDefaults instantiates a new CreateOrganizationCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchived

`func (o *CreateOrganizationCommand) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *CreateOrganizationCommand) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *CreateOrganizationCommand) SetArchived(v bool)`

SetArchived sets Archived field to given value.

### HasArchived

`func (o *CreateOrganizationCommand) HasArchived() bool`

HasArchived returns a boolean if a field has been set.

### GetOrganizationId

`func (o *CreateOrganizationCommand) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *CreateOrganizationCommand) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *CreateOrganizationCommand) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetOrganizationShortName

`func (o *CreateOrganizationCommand) GetOrganizationShortName() map[string]string`

GetOrganizationShortName returns the OrganizationShortName field if non-nil, zero value otherwise.

### GetOrganizationShortNameOk

`func (o *CreateOrganizationCommand) GetOrganizationShortNameOk() (*map[string]string, bool)`

GetOrganizationShortNameOk returns a tuple with the OrganizationShortName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationShortName

`func (o *CreateOrganizationCommand) SetOrganizationShortName(v map[string]string)`

SetOrganizationShortName sets OrganizationShortName field to given value.


### GetOrganizationReviewEmails

`func (o *CreateOrganizationCommand) GetOrganizationReviewEmails() []CreateOrganizationCommandReviewEmails`

GetOrganizationReviewEmails returns the OrganizationReviewEmails field if non-nil, zero value otherwise.

### GetOrganizationReviewEmailsOk

`func (o *CreateOrganizationCommand) GetOrganizationReviewEmailsOk() (*[]CreateOrganizationCommandReviewEmails, bool)`

GetOrganizationReviewEmailsOk returns a tuple with the OrganizationReviewEmails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationReviewEmails

`func (o *CreateOrganizationCommand) SetOrganizationReviewEmails(v []CreateOrganizationCommandReviewEmails)`

SetOrganizationReviewEmails sets OrganizationReviewEmails field to given value.

### HasOrganizationReviewEmails

`func (o *CreateOrganizationCommand) HasOrganizationReviewEmails() bool`

HasOrganizationReviewEmails returns a boolean if a field has been set.

### GetEnabled

`func (o *CreateOrganizationCommand) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateOrganizationCommand) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateOrganizationCommand) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateOrganizationCommand) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetOrganizationOwners

`func (o *CreateOrganizationCommand) GetOrganizationOwners() []User`

GetOrganizationOwners returns the OrganizationOwners field if non-nil, zero value otherwise.

### GetOrganizationOwnersOk

`func (o *CreateOrganizationCommand) GetOrganizationOwnersOk() (*[]User, bool)`

GetOrganizationOwnersOk returns a tuple with the OrganizationOwners field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationOwners

`func (o *CreateOrganizationCommand) SetOrganizationOwners(v []User)`

SetOrganizationOwners sets OrganizationOwners field to given value.

### HasOrganizationOwners

`func (o *CreateOrganizationCommand) HasOrganizationOwners() bool`

HasOrganizationOwners returns a boolean if a field has been set.

### GetOrganizationModifier

`func (o *CreateOrganizationCommand) GetOrganizationModifier() UserWithAttributes`

GetOrganizationModifier returns the OrganizationModifier field if non-nil, zero value otherwise.

### GetOrganizationModifierOk

`func (o *CreateOrganizationCommand) GetOrganizationModifierOk() (*UserWithAttributes, bool)`

GetOrganizationModifierOk returns a tuple with the OrganizationModifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationModifier

`func (o *CreateOrganizationCommand) SetOrganizationModifier(v UserWithAttributes)`

SetOrganizationModifier sets OrganizationModifier field to given value.

### HasOrganizationModifier

`func (o *CreateOrganizationCommand) HasOrganizationModifier() bool`

HasOrganizationModifier returns a boolean if a field has been set.

### GetOrganizationLastModified

`func (o *CreateOrganizationCommand) GetOrganizationLastModified() time.Time`

GetOrganizationLastModified returns the OrganizationLastModified field if non-nil, zero value otherwise.

### GetOrganizationLastModifiedOk

`func (o *CreateOrganizationCommand) GetOrganizationLastModifiedOk() (*time.Time, bool)`

GetOrganizationLastModifiedOk returns a tuple with the OrganizationLastModified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationLastModified

`func (o *CreateOrganizationCommand) SetOrganizationLastModified(v time.Time)`

SetOrganizationLastModified sets OrganizationLastModified field to given value.

### HasOrganizationLastModified

`func (o *CreateOrganizationCommand) HasOrganizationLastModified() bool`

HasOrganizationLastModified returns a boolean if a field has been set.

### GetOrganizationName

`func (o *CreateOrganizationCommand) GetOrganizationName() map[string]string`

GetOrganizationName returns the OrganizationName field if non-nil, zero value otherwise.

### GetOrganizationNameOk

`func (o *CreateOrganizationCommand) GetOrganizationNameOk() (*map[string]string, bool)`

GetOrganizationNameOk returns a tuple with the OrganizationName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationName

`func (o *CreateOrganizationCommand) SetOrganizationName(v map[string]string)`

SetOrganizationName sets OrganizationName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



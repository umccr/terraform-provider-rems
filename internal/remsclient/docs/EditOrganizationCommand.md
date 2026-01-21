# EditOrganizationCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Archived** | Pointer to **bool** |  | [optional] 
**OrganizationId** | **string** |  | 
**OrganizationShortName** | **map[string]string** | Text values keyed by languages | 
**OrganizationReviewEmails** | Pointer to [**[]EditOrganizationCommandReviewEmails**](EditOrganizationCommandReviewEmails.md) |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**OrganizationOwners** | Pointer to [**[]User**](User.md) |  | [optional] 
**OrganizationModifier** | Pointer to [**UserWithAttributes**](UserWithAttributes.md) |  | [optional] 
**OrganizationLastModified** | Pointer to **time.Time** |  | [optional] 
**OrganizationName** | **map[string]string** | Text values keyed by languages | 

## Methods

### NewEditOrganizationCommand

`func NewEditOrganizationCommand(organizationId string, organizationShortName map[string]string, organizationName map[string]string, ) *EditOrganizationCommand`

NewEditOrganizationCommand instantiates a new EditOrganizationCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEditOrganizationCommandWithDefaults

`func NewEditOrganizationCommandWithDefaults() *EditOrganizationCommand`

NewEditOrganizationCommandWithDefaults instantiates a new EditOrganizationCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchived

`func (o *EditOrganizationCommand) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *EditOrganizationCommand) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *EditOrganizationCommand) SetArchived(v bool)`

SetArchived sets Archived field to given value.

### HasArchived

`func (o *EditOrganizationCommand) HasArchived() bool`

HasArchived returns a boolean if a field has been set.

### GetOrganizationId

`func (o *EditOrganizationCommand) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *EditOrganizationCommand) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *EditOrganizationCommand) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetOrganizationShortName

`func (o *EditOrganizationCommand) GetOrganizationShortName() map[string]string`

GetOrganizationShortName returns the OrganizationShortName field if non-nil, zero value otherwise.

### GetOrganizationShortNameOk

`func (o *EditOrganizationCommand) GetOrganizationShortNameOk() (*map[string]string, bool)`

GetOrganizationShortNameOk returns a tuple with the OrganizationShortName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationShortName

`func (o *EditOrganizationCommand) SetOrganizationShortName(v map[string]string)`

SetOrganizationShortName sets OrganizationShortName field to given value.


### GetOrganizationReviewEmails

`func (o *EditOrganizationCommand) GetOrganizationReviewEmails() []EditOrganizationCommandReviewEmails`

GetOrganizationReviewEmails returns the OrganizationReviewEmails field if non-nil, zero value otherwise.

### GetOrganizationReviewEmailsOk

`func (o *EditOrganizationCommand) GetOrganizationReviewEmailsOk() (*[]EditOrganizationCommandReviewEmails, bool)`

GetOrganizationReviewEmailsOk returns a tuple with the OrganizationReviewEmails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationReviewEmails

`func (o *EditOrganizationCommand) SetOrganizationReviewEmails(v []EditOrganizationCommandReviewEmails)`

SetOrganizationReviewEmails sets OrganizationReviewEmails field to given value.

### HasOrganizationReviewEmails

`func (o *EditOrganizationCommand) HasOrganizationReviewEmails() bool`

HasOrganizationReviewEmails returns a boolean if a field has been set.

### GetEnabled

`func (o *EditOrganizationCommand) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *EditOrganizationCommand) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *EditOrganizationCommand) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *EditOrganizationCommand) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetOrganizationOwners

`func (o *EditOrganizationCommand) GetOrganizationOwners() []User`

GetOrganizationOwners returns the OrganizationOwners field if non-nil, zero value otherwise.

### GetOrganizationOwnersOk

`func (o *EditOrganizationCommand) GetOrganizationOwnersOk() (*[]User, bool)`

GetOrganizationOwnersOk returns a tuple with the OrganizationOwners field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationOwners

`func (o *EditOrganizationCommand) SetOrganizationOwners(v []User)`

SetOrganizationOwners sets OrganizationOwners field to given value.

### HasOrganizationOwners

`func (o *EditOrganizationCommand) HasOrganizationOwners() bool`

HasOrganizationOwners returns a boolean if a field has been set.

### GetOrganizationModifier

`func (o *EditOrganizationCommand) GetOrganizationModifier() UserWithAttributes`

GetOrganizationModifier returns the OrganizationModifier field if non-nil, zero value otherwise.

### GetOrganizationModifierOk

`func (o *EditOrganizationCommand) GetOrganizationModifierOk() (*UserWithAttributes, bool)`

GetOrganizationModifierOk returns a tuple with the OrganizationModifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationModifier

`func (o *EditOrganizationCommand) SetOrganizationModifier(v UserWithAttributes)`

SetOrganizationModifier sets OrganizationModifier field to given value.

### HasOrganizationModifier

`func (o *EditOrganizationCommand) HasOrganizationModifier() bool`

HasOrganizationModifier returns a boolean if a field has been set.

### GetOrganizationLastModified

`func (o *EditOrganizationCommand) GetOrganizationLastModified() time.Time`

GetOrganizationLastModified returns the OrganizationLastModified field if non-nil, zero value otherwise.

### GetOrganizationLastModifiedOk

`func (o *EditOrganizationCommand) GetOrganizationLastModifiedOk() (*time.Time, bool)`

GetOrganizationLastModifiedOk returns a tuple with the OrganizationLastModified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationLastModified

`func (o *EditOrganizationCommand) SetOrganizationLastModified(v time.Time)`

SetOrganizationLastModified sets OrganizationLastModified field to given value.

### HasOrganizationLastModified

`func (o *EditOrganizationCommand) HasOrganizationLastModified() bool`

HasOrganizationLastModified returns a boolean if a field has been set.

### GetOrganizationName

`func (o *EditOrganizationCommand) GetOrganizationName() map[string]string`

GetOrganizationName returns the OrganizationName field if non-nil, zero value otherwise.

### GetOrganizationNameOk

`func (o *EditOrganizationCommand) GetOrganizationNameOk() (*map[string]string, bool)`

GetOrganizationNameOk returns a tuple with the OrganizationName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationName

`func (o *EditOrganizationCommand) SetOrganizationName(v map[string]string)`

SetOrganizationName sets OrganizationName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# OrganizationFull

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Archived** | Pointer to **bool** |  | [optional] 
**OrganizationId** | **string** |  | 
**OrganizationShortName** | **map[string]string** | Text values keyed by languages | 
**OrganizationReviewEmails** | Pointer to [**[]Response8030ReviewEmails**](Response8030ReviewEmails.md) |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**OrganizationOwners** | Pointer to [**[]UserWithAttributes**](UserWithAttributes.md) |  | [optional] 
**OrganizationModifier** | Pointer to [**UserWithAttributes**](UserWithAttributes.md) |  | [optional] 
**OrganizationLastModified** | Pointer to **time.Time** |  | [optional] 
**OrganizationName** | **map[string]string** | Text values keyed by languages | 

## Methods

### NewOrganizationFull

`func NewOrganizationFull(organizationId string, organizationShortName map[string]string, organizationName map[string]string, ) *OrganizationFull`

NewOrganizationFull instantiates a new OrganizationFull object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationFullWithDefaults

`func NewOrganizationFullWithDefaults() *OrganizationFull`

NewOrganizationFullWithDefaults instantiates a new OrganizationFull object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchived

`func (o *OrganizationFull) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *OrganizationFull) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *OrganizationFull) SetArchived(v bool)`

SetArchived sets Archived field to given value.

### HasArchived

`func (o *OrganizationFull) HasArchived() bool`

HasArchived returns a boolean if a field has been set.

### GetOrganizationId

`func (o *OrganizationFull) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *OrganizationFull) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *OrganizationFull) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetOrganizationShortName

`func (o *OrganizationFull) GetOrganizationShortName() map[string]string`

GetOrganizationShortName returns the OrganizationShortName field if non-nil, zero value otherwise.

### GetOrganizationShortNameOk

`func (o *OrganizationFull) GetOrganizationShortNameOk() (*map[string]string, bool)`

GetOrganizationShortNameOk returns a tuple with the OrganizationShortName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationShortName

`func (o *OrganizationFull) SetOrganizationShortName(v map[string]string)`

SetOrganizationShortName sets OrganizationShortName field to given value.


### GetOrganizationReviewEmails

`func (o *OrganizationFull) GetOrganizationReviewEmails() []Response8030ReviewEmails`

GetOrganizationReviewEmails returns the OrganizationReviewEmails field if non-nil, zero value otherwise.

### GetOrganizationReviewEmailsOk

`func (o *OrganizationFull) GetOrganizationReviewEmailsOk() (*[]Response8030ReviewEmails, bool)`

GetOrganizationReviewEmailsOk returns a tuple with the OrganizationReviewEmails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationReviewEmails

`func (o *OrganizationFull) SetOrganizationReviewEmails(v []Response8030ReviewEmails)`

SetOrganizationReviewEmails sets OrganizationReviewEmails field to given value.

### HasOrganizationReviewEmails

`func (o *OrganizationFull) HasOrganizationReviewEmails() bool`

HasOrganizationReviewEmails returns a boolean if a field has been set.

### GetEnabled

`func (o *OrganizationFull) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *OrganizationFull) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *OrganizationFull) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *OrganizationFull) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetOrganizationOwners

`func (o *OrganizationFull) GetOrganizationOwners() []UserWithAttributes`

GetOrganizationOwners returns the OrganizationOwners field if non-nil, zero value otherwise.

### GetOrganizationOwnersOk

`func (o *OrganizationFull) GetOrganizationOwnersOk() (*[]UserWithAttributes, bool)`

GetOrganizationOwnersOk returns a tuple with the OrganizationOwners field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationOwners

`func (o *OrganizationFull) SetOrganizationOwners(v []UserWithAttributes)`

SetOrganizationOwners sets OrganizationOwners field to given value.

### HasOrganizationOwners

`func (o *OrganizationFull) HasOrganizationOwners() bool`

HasOrganizationOwners returns a boolean if a field has been set.

### GetOrganizationModifier

`func (o *OrganizationFull) GetOrganizationModifier() UserWithAttributes`

GetOrganizationModifier returns the OrganizationModifier field if non-nil, zero value otherwise.

### GetOrganizationModifierOk

`func (o *OrganizationFull) GetOrganizationModifierOk() (*UserWithAttributes, bool)`

GetOrganizationModifierOk returns a tuple with the OrganizationModifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationModifier

`func (o *OrganizationFull) SetOrganizationModifier(v UserWithAttributes)`

SetOrganizationModifier sets OrganizationModifier field to given value.

### HasOrganizationModifier

`func (o *OrganizationFull) HasOrganizationModifier() bool`

HasOrganizationModifier returns a boolean if a field has been set.

### GetOrganizationLastModified

`func (o *OrganizationFull) GetOrganizationLastModified() time.Time`

GetOrganizationLastModified returns the OrganizationLastModified field if non-nil, zero value otherwise.

### GetOrganizationLastModifiedOk

`func (o *OrganizationFull) GetOrganizationLastModifiedOk() (*time.Time, bool)`

GetOrganizationLastModifiedOk returns a tuple with the OrganizationLastModified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationLastModified

`func (o *OrganizationFull) SetOrganizationLastModified(v time.Time)`

SetOrganizationLastModified sets OrganizationLastModified field to given value.

### HasOrganizationLastModified

`func (o *OrganizationFull) HasOrganizationLastModified() bool`

HasOrganizationLastModified returns a boolean if a field has been set.

### GetOrganizationName

`func (o *OrganizationFull) GetOrganizationName() map[string]string`

GetOrganizationName returns the OrganizationName field if non-nil, zero value otherwise.

### GetOrganizationNameOk

`func (o *OrganizationFull) GetOrganizationNameOk() (*map[string]string, bool)`

GetOrganizationNameOk returns a tuple with the OrganizationName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationName

`func (o *OrganizationFull) SetOrganizationName(v map[string]string)`

SetOrganizationName sets OrganizationName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



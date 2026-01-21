# UserWithAttributes

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Userid** | **string** |  | 
**Name** | **NullableString** |  | 
**Email** | **NullableString** |  | 
**Organizations** | Pointer to [**[]OrganizationId**](OrganizationId.md) |  | [optional] 
**NotificationEmail** | Pointer to **NullableString** |  | [optional] 
**ResearcherStatusBy** | Pointer to **string** |  | [optional] 

## Methods

### NewUserWithAttributes

`func NewUserWithAttributes(userid string, name NullableString, email NullableString, ) *UserWithAttributes`

NewUserWithAttributes instantiates a new UserWithAttributes object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserWithAttributesWithDefaults

`func NewUserWithAttributesWithDefaults() *UserWithAttributes`

NewUserWithAttributesWithDefaults instantiates a new UserWithAttributes object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserid

`func (o *UserWithAttributes) GetUserid() string`

GetUserid returns the Userid field if non-nil, zero value otherwise.

### GetUseridOk

`func (o *UserWithAttributes) GetUseridOk() (*string, bool)`

GetUseridOk returns a tuple with the Userid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserid

`func (o *UserWithAttributes) SetUserid(v string)`

SetUserid sets Userid field to given value.


### GetName

`func (o *UserWithAttributes) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UserWithAttributes) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UserWithAttributes) SetName(v string)`

SetName sets Name field to given value.


### SetNameNil

`func (o *UserWithAttributes) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *UserWithAttributes) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetEmail

`func (o *UserWithAttributes) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *UserWithAttributes) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *UserWithAttributes) SetEmail(v string)`

SetEmail sets Email field to given value.


### SetEmailNil

`func (o *UserWithAttributes) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *UserWithAttributes) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetOrganizations

`func (o *UserWithAttributes) GetOrganizations() []OrganizationId`

GetOrganizations returns the Organizations field if non-nil, zero value otherwise.

### GetOrganizationsOk

`func (o *UserWithAttributes) GetOrganizationsOk() (*[]OrganizationId, bool)`

GetOrganizationsOk returns a tuple with the Organizations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizations

`func (o *UserWithAttributes) SetOrganizations(v []OrganizationId)`

SetOrganizations sets Organizations field to given value.

### HasOrganizations

`func (o *UserWithAttributes) HasOrganizations() bool`

HasOrganizations returns a boolean if a field has been set.

### GetNotificationEmail

`func (o *UserWithAttributes) GetNotificationEmail() string`

GetNotificationEmail returns the NotificationEmail field if non-nil, zero value otherwise.

### GetNotificationEmailOk

`func (o *UserWithAttributes) GetNotificationEmailOk() (*string, bool)`

GetNotificationEmailOk returns a tuple with the NotificationEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationEmail

`func (o *UserWithAttributes) SetNotificationEmail(v string)`

SetNotificationEmail sets NotificationEmail field to given value.

### HasNotificationEmail

`func (o *UserWithAttributes) HasNotificationEmail() bool`

HasNotificationEmail returns a boolean if a field has been set.

### SetNotificationEmailNil

`func (o *UserWithAttributes) SetNotificationEmailNil(b bool)`

 SetNotificationEmailNil sets the value for NotificationEmail to be an explicit nil

### UnsetNotificationEmail
`func (o *UserWithAttributes) UnsetNotificationEmail()`

UnsetNotificationEmail ensures that no value is present for NotificationEmail, not even an explicit nil
### GetResearcherStatusBy

`func (o *UserWithAttributes) GetResearcherStatusBy() string`

GetResearcherStatusBy returns the ResearcherStatusBy field if non-nil, zero value otherwise.

### GetResearcherStatusByOk

`func (o *UserWithAttributes) GetResearcherStatusByOk() (*string, bool)`

GetResearcherStatusByOk returns a tuple with the ResearcherStatusBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResearcherStatusBy

`func (o *UserWithAttributes) SetResearcherStatusBy(v string)`

SetResearcherStatusBy sets ResearcherStatusBy field to given value.

### HasResearcherStatusBy

`func (o *UserWithAttributes) HasResearcherStatusBy() bool`

HasResearcherStatusBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# AvailableActor

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

### NewAvailableActor

`func NewAvailableActor(userid string, name NullableString, email NullableString, ) *AvailableActor`

NewAvailableActor instantiates a new AvailableActor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAvailableActorWithDefaults

`func NewAvailableActorWithDefaults() *AvailableActor`

NewAvailableActorWithDefaults instantiates a new AvailableActor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserid

`func (o *AvailableActor) GetUserid() string`

GetUserid returns the Userid field if non-nil, zero value otherwise.

### GetUseridOk

`func (o *AvailableActor) GetUseridOk() (*string, bool)`

GetUseridOk returns a tuple with the Userid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserid

`func (o *AvailableActor) SetUserid(v string)`

SetUserid sets Userid field to given value.


### GetName

`func (o *AvailableActor) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AvailableActor) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AvailableActor) SetName(v string)`

SetName sets Name field to given value.


### SetNameNil

`func (o *AvailableActor) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *AvailableActor) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetEmail

`func (o *AvailableActor) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *AvailableActor) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *AvailableActor) SetEmail(v string)`

SetEmail sets Email field to given value.


### SetEmailNil

`func (o *AvailableActor) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *AvailableActor) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetOrganizations

`func (o *AvailableActor) GetOrganizations() []OrganizationId`

GetOrganizations returns the Organizations field if non-nil, zero value otherwise.

### GetOrganizationsOk

`func (o *AvailableActor) GetOrganizationsOk() (*[]OrganizationId, bool)`

GetOrganizationsOk returns a tuple with the Organizations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizations

`func (o *AvailableActor) SetOrganizations(v []OrganizationId)`

SetOrganizations sets Organizations field to given value.

### HasOrganizations

`func (o *AvailableActor) HasOrganizations() bool`

HasOrganizations returns a boolean if a field has been set.

### GetNotificationEmail

`func (o *AvailableActor) GetNotificationEmail() string`

GetNotificationEmail returns the NotificationEmail field if non-nil, zero value otherwise.

### GetNotificationEmailOk

`func (o *AvailableActor) GetNotificationEmailOk() (*string, bool)`

GetNotificationEmailOk returns a tuple with the NotificationEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationEmail

`func (o *AvailableActor) SetNotificationEmail(v string)`

SetNotificationEmail sets NotificationEmail field to given value.

### HasNotificationEmail

`func (o *AvailableActor) HasNotificationEmail() bool`

HasNotificationEmail returns a boolean if a field has been set.

### SetNotificationEmailNil

`func (o *AvailableActor) SetNotificationEmailNil(b bool)`

 SetNotificationEmailNil sets the value for NotificationEmail to be an explicit nil

### UnsetNotificationEmail
`func (o *AvailableActor) UnsetNotificationEmail()`

UnsetNotificationEmail ensures that no value is present for NotificationEmail, not even an explicit nil
### GetResearcherStatusBy

`func (o *AvailableActor) GetResearcherStatusBy() string`

GetResearcherStatusBy returns the ResearcherStatusBy field if non-nil, zero value otherwise.

### GetResearcherStatusByOk

`func (o *AvailableActor) GetResearcherStatusByOk() (*string, bool)`

GetResearcherStatusByOk returns a tuple with the ResearcherStatusBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResearcherStatusBy

`func (o *AvailableActor) SetResearcherStatusBy(v string)`

SetResearcherStatusBy sets ResearcherStatusBy field to given value.

### HasResearcherStatusBy

`func (o *AvailableActor) HasResearcherStatusBy() bool`

HasResearcherStatusBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



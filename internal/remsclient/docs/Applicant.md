# Applicant

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

### NewApplicant

`func NewApplicant(userid string, name NullableString, email NullableString, ) *Applicant`

NewApplicant instantiates a new Applicant object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicantWithDefaults

`func NewApplicantWithDefaults() *Applicant`

NewApplicantWithDefaults instantiates a new Applicant object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserid

`func (o *Applicant) GetUserid() string`

GetUserid returns the Userid field if non-nil, zero value otherwise.

### GetUseridOk

`func (o *Applicant) GetUseridOk() (*string, bool)`

GetUseridOk returns a tuple with the Userid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserid

`func (o *Applicant) SetUserid(v string)`

SetUserid sets Userid field to given value.


### GetName

`func (o *Applicant) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Applicant) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Applicant) SetName(v string)`

SetName sets Name field to given value.


### SetNameNil

`func (o *Applicant) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *Applicant) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetEmail

`func (o *Applicant) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *Applicant) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *Applicant) SetEmail(v string)`

SetEmail sets Email field to given value.


### SetEmailNil

`func (o *Applicant) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *Applicant) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetOrganizations

`func (o *Applicant) GetOrganizations() []OrganizationId`

GetOrganizations returns the Organizations field if non-nil, zero value otherwise.

### GetOrganizationsOk

`func (o *Applicant) GetOrganizationsOk() (*[]OrganizationId, bool)`

GetOrganizationsOk returns a tuple with the Organizations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizations

`func (o *Applicant) SetOrganizations(v []OrganizationId)`

SetOrganizations sets Organizations field to given value.

### HasOrganizations

`func (o *Applicant) HasOrganizations() bool`

HasOrganizations returns a boolean if a field has been set.

### GetNotificationEmail

`func (o *Applicant) GetNotificationEmail() string`

GetNotificationEmail returns the NotificationEmail field if non-nil, zero value otherwise.

### GetNotificationEmailOk

`func (o *Applicant) GetNotificationEmailOk() (*string, bool)`

GetNotificationEmailOk returns a tuple with the NotificationEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationEmail

`func (o *Applicant) SetNotificationEmail(v string)`

SetNotificationEmail sets NotificationEmail field to given value.

### HasNotificationEmail

`func (o *Applicant) HasNotificationEmail() bool`

HasNotificationEmail returns a boolean if a field has been set.

### SetNotificationEmailNil

`func (o *Applicant) SetNotificationEmailNil(b bool)`

 SetNotificationEmailNil sets the value for NotificationEmail to be an explicit nil

### UnsetNotificationEmail
`func (o *Applicant) UnsetNotificationEmail()`

UnsetNotificationEmail ensures that no value is present for NotificationEmail, not even an explicit nil
### GetResearcherStatusBy

`func (o *Applicant) GetResearcherStatusBy() string`

GetResearcherStatusBy returns the ResearcherStatusBy field if non-nil, zero value otherwise.

### GetResearcherStatusByOk

`func (o *Applicant) GetResearcherStatusByOk() (*string, bool)`

GetResearcherStatusByOk returns a tuple with the ResearcherStatusBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResearcherStatusBy

`func (o *Applicant) SetResearcherStatusBy(v string)`

SetResearcherStatusBy sets ResearcherStatusBy field to given value.

### HasResearcherStatusBy

`func (o *Applicant) HasResearcherStatusBy() bool`

HasResearcherStatusBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



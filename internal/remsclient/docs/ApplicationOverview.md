# ApplicationOverview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationWorkflow** | [**Response7799Workflow**](Response7799Workflow.md) |  | 
**ApplicationExternalId** | **string** | Assigned external id if it exists, otherwise the generated one | 
**ApplicationFirstSubmitted** | Pointer to **time.Time** |  | [optional] 
**ApplicationBlacklist** | Pointer to [**[]BlacklistEntry**](BlacklistEntry.md) | Which members of this application are blacklisted for which resources | [optional] 
**ApplicationId** | **int64** |  | 
**ApplicationDuo** | Pointer to [**Response7799Duo**](Response7799Duo.md) |  | [optional] 
**ApplicationAssignedExternalId** | Pointer to **string** |  | [optional] 
**ApplicationApplicant** | [**UserWithAttributes**](UserWithAttributes.md) |  | 
**ApplicationCopiedFrom** | Pointer to [**Response7799CopiedFrom**](Response7799CopiedFrom.md) |  | [optional] 
**ApplicationTodo** | **NullableString** |  | 
**ApplicationMembers** | [**[]UserWithAttributes**](UserWithAttributes.md) |  | 
**EntitlementEnd** | Pointer to **NullableTime** |  | [optional] 
**ApplicationResources** | [**[]V2Resource**](V2Resource.md) |  | 
**ApplicationDeadline** | Pointer to **time.Time** |  | [optional] 
**ApplicationAcceptedLicenses** | **map[string][]int64** |  | 
**ApplicationInvitedMembers** | [**[]Response7799InvitedMembers**](Response7799InvitedMembers.md) |  | 
**ApplicationDescription** | **string** |  | 
**ApplicationVotes** | Pointer to **map[string]string** |  | [optional] 
**ApplicationGeneratedExternalId** | Pointer to **string** |  | [optional] 
**ApplicationPermissions** | **[]string** |  | 
**ApplicationLastActivity** | **time.Time** |  | 
**ApplicationProcessingState** | Pointer to [**Response7799ProcessingState**](Response7799ProcessingState.md) |  | [optional] 
**ApplicationRoles** | **[]string** |  | 
**ApplicationAttachments** | [**[]ApplicationAttachment**](ApplicationAttachment.md) |  | 
**ApplicationCreated** | **time.Time** |  | 
**ApplicationState** | **string** |  | 
**ApplicationCopiedTo** | Pointer to [**[]Response7799CopiedTo**](Response7799CopiedTo.md) |  | [optional] 
**ApplicationModified** | **time.Time** |  | 

## Methods

### NewApplicationOverview

`func NewApplicationOverview(applicationWorkflow Response7799Workflow, applicationExternalId string, applicationId int64, applicationApplicant UserWithAttributes, applicationTodo NullableString, applicationMembers []UserWithAttributes, applicationResources []V2Resource, applicationAcceptedLicenses map[string][]int64, applicationInvitedMembers []Response7799InvitedMembers, applicationDescription string, applicationPermissions []string, applicationLastActivity time.Time, applicationRoles []string, applicationAttachments []ApplicationAttachment, applicationCreated time.Time, applicationState string, applicationModified time.Time, ) *ApplicationOverview`

NewApplicationOverview instantiates a new ApplicationOverview object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationOverviewWithDefaults

`func NewApplicationOverviewWithDefaults() *ApplicationOverview`

NewApplicationOverviewWithDefaults instantiates a new ApplicationOverview object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationWorkflow

`func (o *ApplicationOverview) GetApplicationWorkflow() Response7799Workflow`

GetApplicationWorkflow returns the ApplicationWorkflow field if non-nil, zero value otherwise.

### GetApplicationWorkflowOk

`func (o *ApplicationOverview) GetApplicationWorkflowOk() (*Response7799Workflow, bool)`

GetApplicationWorkflowOk returns a tuple with the ApplicationWorkflow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationWorkflow

`func (o *ApplicationOverview) SetApplicationWorkflow(v Response7799Workflow)`

SetApplicationWorkflow sets ApplicationWorkflow field to given value.


### GetApplicationExternalId

`func (o *ApplicationOverview) GetApplicationExternalId() string`

GetApplicationExternalId returns the ApplicationExternalId field if non-nil, zero value otherwise.

### GetApplicationExternalIdOk

`func (o *ApplicationOverview) GetApplicationExternalIdOk() (*string, bool)`

GetApplicationExternalIdOk returns a tuple with the ApplicationExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationExternalId

`func (o *ApplicationOverview) SetApplicationExternalId(v string)`

SetApplicationExternalId sets ApplicationExternalId field to given value.


### GetApplicationFirstSubmitted

`func (o *ApplicationOverview) GetApplicationFirstSubmitted() time.Time`

GetApplicationFirstSubmitted returns the ApplicationFirstSubmitted field if non-nil, zero value otherwise.

### GetApplicationFirstSubmittedOk

`func (o *ApplicationOverview) GetApplicationFirstSubmittedOk() (*time.Time, bool)`

GetApplicationFirstSubmittedOk returns a tuple with the ApplicationFirstSubmitted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationFirstSubmitted

`func (o *ApplicationOverview) SetApplicationFirstSubmitted(v time.Time)`

SetApplicationFirstSubmitted sets ApplicationFirstSubmitted field to given value.

### HasApplicationFirstSubmitted

`func (o *ApplicationOverview) HasApplicationFirstSubmitted() bool`

HasApplicationFirstSubmitted returns a boolean if a field has been set.

### GetApplicationBlacklist

`func (o *ApplicationOverview) GetApplicationBlacklist() []BlacklistEntry`

GetApplicationBlacklist returns the ApplicationBlacklist field if non-nil, zero value otherwise.

### GetApplicationBlacklistOk

`func (o *ApplicationOverview) GetApplicationBlacklistOk() (*[]BlacklistEntry, bool)`

GetApplicationBlacklistOk returns a tuple with the ApplicationBlacklist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationBlacklist

`func (o *ApplicationOverview) SetApplicationBlacklist(v []BlacklistEntry)`

SetApplicationBlacklist sets ApplicationBlacklist field to given value.

### HasApplicationBlacklist

`func (o *ApplicationOverview) HasApplicationBlacklist() bool`

HasApplicationBlacklist returns a boolean if a field has been set.

### GetApplicationId

`func (o *ApplicationOverview) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *ApplicationOverview) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *ApplicationOverview) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetApplicationDuo

`func (o *ApplicationOverview) GetApplicationDuo() Response7799Duo`

GetApplicationDuo returns the ApplicationDuo field if non-nil, zero value otherwise.

### GetApplicationDuoOk

`func (o *ApplicationOverview) GetApplicationDuoOk() (*Response7799Duo, bool)`

GetApplicationDuoOk returns a tuple with the ApplicationDuo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationDuo

`func (o *ApplicationOverview) SetApplicationDuo(v Response7799Duo)`

SetApplicationDuo sets ApplicationDuo field to given value.

### HasApplicationDuo

`func (o *ApplicationOverview) HasApplicationDuo() bool`

HasApplicationDuo returns a boolean if a field has been set.

### GetApplicationAssignedExternalId

`func (o *ApplicationOverview) GetApplicationAssignedExternalId() string`

GetApplicationAssignedExternalId returns the ApplicationAssignedExternalId field if non-nil, zero value otherwise.

### GetApplicationAssignedExternalIdOk

`func (o *ApplicationOverview) GetApplicationAssignedExternalIdOk() (*string, bool)`

GetApplicationAssignedExternalIdOk returns a tuple with the ApplicationAssignedExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationAssignedExternalId

`func (o *ApplicationOverview) SetApplicationAssignedExternalId(v string)`

SetApplicationAssignedExternalId sets ApplicationAssignedExternalId field to given value.

### HasApplicationAssignedExternalId

`func (o *ApplicationOverview) HasApplicationAssignedExternalId() bool`

HasApplicationAssignedExternalId returns a boolean if a field has been set.

### GetApplicationApplicant

`func (o *ApplicationOverview) GetApplicationApplicant() UserWithAttributes`

GetApplicationApplicant returns the ApplicationApplicant field if non-nil, zero value otherwise.

### GetApplicationApplicantOk

`func (o *ApplicationOverview) GetApplicationApplicantOk() (*UserWithAttributes, bool)`

GetApplicationApplicantOk returns a tuple with the ApplicationApplicant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationApplicant

`func (o *ApplicationOverview) SetApplicationApplicant(v UserWithAttributes)`

SetApplicationApplicant sets ApplicationApplicant field to given value.


### GetApplicationCopiedFrom

`func (o *ApplicationOverview) GetApplicationCopiedFrom() Response7799CopiedFrom`

GetApplicationCopiedFrom returns the ApplicationCopiedFrom field if non-nil, zero value otherwise.

### GetApplicationCopiedFromOk

`func (o *ApplicationOverview) GetApplicationCopiedFromOk() (*Response7799CopiedFrom, bool)`

GetApplicationCopiedFromOk returns a tuple with the ApplicationCopiedFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationCopiedFrom

`func (o *ApplicationOverview) SetApplicationCopiedFrom(v Response7799CopiedFrom)`

SetApplicationCopiedFrom sets ApplicationCopiedFrom field to given value.

### HasApplicationCopiedFrom

`func (o *ApplicationOverview) HasApplicationCopiedFrom() bool`

HasApplicationCopiedFrom returns a boolean if a field has been set.

### GetApplicationTodo

`func (o *ApplicationOverview) GetApplicationTodo() string`

GetApplicationTodo returns the ApplicationTodo field if non-nil, zero value otherwise.

### GetApplicationTodoOk

`func (o *ApplicationOverview) GetApplicationTodoOk() (*string, bool)`

GetApplicationTodoOk returns a tuple with the ApplicationTodo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationTodo

`func (o *ApplicationOverview) SetApplicationTodo(v string)`

SetApplicationTodo sets ApplicationTodo field to given value.


### SetApplicationTodoNil

`func (o *ApplicationOverview) SetApplicationTodoNil(b bool)`

 SetApplicationTodoNil sets the value for ApplicationTodo to be an explicit nil

### UnsetApplicationTodo
`func (o *ApplicationOverview) UnsetApplicationTodo()`

UnsetApplicationTodo ensures that no value is present for ApplicationTodo, not even an explicit nil
### GetApplicationMembers

`func (o *ApplicationOverview) GetApplicationMembers() []UserWithAttributes`

GetApplicationMembers returns the ApplicationMembers field if non-nil, zero value otherwise.

### GetApplicationMembersOk

`func (o *ApplicationOverview) GetApplicationMembersOk() (*[]UserWithAttributes, bool)`

GetApplicationMembersOk returns a tuple with the ApplicationMembers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationMembers

`func (o *ApplicationOverview) SetApplicationMembers(v []UserWithAttributes)`

SetApplicationMembers sets ApplicationMembers field to given value.


### GetEntitlementEnd

`func (o *ApplicationOverview) GetEntitlementEnd() time.Time`

GetEntitlementEnd returns the EntitlementEnd field if non-nil, zero value otherwise.

### GetEntitlementEndOk

`func (o *ApplicationOverview) GetEntitlementEndOk() (*time.Time, bool)`

GetEntitlementEndOk returns a tuple with the EntitlementEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntitlementEnd

`func (o *ApplicationOverview) SetEntitlementEnd(v time.Time)`

SetEntitlementEnd sets EntitlementEnd field to given value.

### HasEntitlementEnd

`func (o *ApplicationOverview) HasEntitlementEnd() bool`

HasEntitlementEnd returns a boolean if a field has been set.

### SetEntitlementEndNil

`func (o *ApplicationOverview) SetEntitlementEndNil(b bool)`

 SetEntitlementEndNil sets the value for EntitlementEnd to be an explicit nil

### UnsetEntitlementEnd
`func (o *ApplicationOverview) UnsetEntitlementEnd()`

UnsetEntitlementEnd ensures that no value is present for EntitlementEnd, not even an explicit nil
### GetApplicationResources

`func (o *ApplicationOverview) GetApplicationResources() []V2Resource`

GetApplicationResources returns the ApplicationResources field if non-nil, zero value otherwise.

### GetApplicationResourcesOk

`func (o *ApplicationOverview) GetApplicationResourcesOk() (*[]V2Resource, bool)`

GetApplicationResourcesOk returns a tuple with the ApplicationResources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationResources

`func (o *ApplicationOverview) SetApplicationResources(v []V2Resource)`

SetApplicationResources sets ApplicationResources field to given value.


### GetApplicationDeadline

`func (o *ApplicationOverview) GetApplicationDeadline() time.Time`

GetApplicationDeadline returns the ApplicationDeadline field if non-nil, zero value otherwise.

### GetApplicationDeadlineOk

`func (o *ApplicationOverview) GetApplicationDeadlineOk() (*time.Time, bool)`

GetApplicationDeadlineOk returns a tuple with the ApplicationDeadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationDeadline

`func (o *ApplicationOverview) SetApplicationDeadline(v time.Time)`

SetApplicationDeadline sets ApplicationDeadline field to given value.

### HasApplicationDeadline

`func (o *ApplicationOverview) HasApplicationDeadline() bool`

HasApplicationDeadline returns a boolean if a field has been set.

### GetApplicationAcceptedLicenses

`func (o *ApplicationOverview) GetApplicationAcceptedLicenses() map[string][]int64`

GetApplicationAcceptedLicenses returns the ApplicationAcceptedLicenses field if non-nil, zero value otherwise.

### GetApplicationAcceptedLicensesOk

`func (o *ApplicationOverview) GetApplicationAcceptedLicensesOk() (*map[string][]int64, bool)`

GetApplicationAcceptedLicensesOk returns a tuple with the ApplicationAcceptedLicenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationAcceptedLicenses

`func (o *ApplicationOverview) SetApplicationAcceptedLicenses(v map[string][]int64)`

SetApplicationAcceptedLicenses sets ApplicationAcceptedLicenses field to given value.


### GetApplicationInvitedMembers

`func (o *ApplicationOverview) GetApplicationInvitedMembers() []Response7799InvitedMembers`

GetApplicationInvitedMembers returns the ApplicationInvitedMembers field if non-nil, zero value otherwise.

### GetApplicationInvitedMembersOk

`func (o *ApplicationOverview) GetApplicationInvitedMembersOk() (*[]Response7799InvitedMembers, bool)`

GetApplicationInvitedMembersOk returns a tuple with the ApplicationInvitedMembers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationInvitedMembers

`func (o *ApplicationOverview) SetApplicationInvitedMembers(v []Response7799InvitedMembers)`

SetApplicationInvitedMembers sets ApplicationInvitedMembers field to given value.


### GetApplicationDescription

`func (o *ApplicationOverview) GetApplicationDescription() string`

GetApplicationDescription returns the ApplicationDescription field if non-nil, zero value otherwise.

### GetApplicationDescriptionOk

`func (o *ApplicationOverview) GetApplicationDescriptionOk() (*string, bool)`

GetApplicationDescriptionOk returns a tuple with the ApplicationDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationDescription

`func (o *ApplicationOverview) SetApplicationDescription(v string)`

SetApplicationDescription sets ApplicationDescription field to given value.


### GetApplicationVotes

`func (o *ApplicationOverview) GetApplicationVotes() map[string]string`

GetApplicationVotes returns the ApplicationVotes field if non-nil, zero value otherwise.

### GetApplicationVotesOk

`func (o *ApplicationOverview) GetApplicationVotesOk() (*map[string]string, bool)`

GetApplicationVotesOk returns a tuple with the ApplicationVotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationVotes

`func (o *ApplicationOverview) SetApplicationVotes(v map[string]string)`

SetApplicationVotes sets ApplicationVotes field to given value.

### HasApplicationVotes

`func (o *ApplicationOverview) HasApplicationVotes() bool`

HasApplicationVotes returns a boolean if a field has been set.

### GetApplicationGeneratedExternalId

`func (o *ApplicationOverview) GetApplicationGeneratedExternalId() string`

GetApplicationGeneratedExternalId returns the ApplicationGeneratedExternalId field if non-nil, zero value otherwise.

### GetApplicationGeneratedExternalIdOk

`func (o *ApplicationOverview) GetApplicationGeneratedExternalIdOk() (*string, bool)`

GetApplicationGeneratedExternalIdOk returns a tuple with the ApplicationGeneratedExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationGeneratedExternalId

`func (o *ApplicationOverview) SetApplicationGeneratedExternalId(v string)`

SetApplicationGeneratedExternalId sets ApplicationGeneratedExternalId field to given value.

### HasApplicationGeneratedExternalId

`func (o *ApplicationOverview) HasApplicationGeneratedExternalId() bool`

HasApplicationGeneratedExternalId returns a boolean if a field has been set.

### GetApplicationPermissions

`func (o *ApplicationOverview) GetApplicationPermissions() []string`

GetApplicationPermissions returns the ApplicationPermissions field if non-nil, zero value otherwise.

### GetApplicationPermissionsOk

`func (o *ApplicationOverview) GetApplicationPermissionsOk() (*[]string, bool)`

GetApplicationPermissionsOk returns a tuple with the ApplicationPermissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationPermissions

`func (o *ApplicationOverview) SetApplicationPermissions(v []string)`

SetApplicationPermissions sets ApplicationPermissions field to given value.


### GetApplicationLastActivity

`func (o *ApplicationOverview) GetApplicationLastActivity() time.Time`

GetApplicationLastActivity returns the ApplicationLastActivity field if non-nil, zero value otherwise.

### GetApplicationLastActivityOk

`func (o *ApplicationOverview) GetApplicationLastActivityOk() (*time.Time, bool)`

GetApplicationLastActivityOk returns a tuple with the ApplicationLastActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationLastActivity

`func (o *ApplicationOverview) SetApplicationLastActivity(v time.Time)`

SetApplicationLastActivity sets ApplicationLastActivity field to given value.


### GetApplicationProcessingState

`func (o *ApplicationOverview) GetApplicationProcessingState() Response7799ProcessingState`

GetApplicationProcessingState returns the ApplicationProcessingState field if non-nil, zero value otherwise.

### GetApplicationProcessingStateOk

`func (o *ApplicationOverview) GetApplicationProcessingStateOk() (*Response7799ProcessingState, bool)`

GetApplicationProcessingStateOk returns a tuple with the ApplicationProcessingState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationProcessingState

`func (o *ApplicationOverview) SetApplicationProcessingState(v Response7799ProcessingState)`

SetApplicationProcessingState sets ApplicationProcessingState field to given value.

### HasApplicationProcessingState

`func (o *ApplicationOverview) HasApplicationProcessingState() bool`

HasApplicationProcessingState returns a boolean if a field has been set.

### GetApplicationRoles

`func (o *ApplicationOverview) GetApplicationRoles() []string`

GetApplicationRoles returns the ApplicationRoles field if non-nil, zero value otherwise.

### GetApplicationRolesOk

`func (o *ApplicationOverview) GetApplicationRolesOk() (*[]string, bool)`

GetApplicationRolesOk returns a tuple with the ApplicationRoles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationRoles

`func (o *ApplicationOverview) SetApplicationRoles(v []string)`

SetApplicationRoles sets ApplicationRoles field to given value.


### GetApplicationAttachments

`func (o *ApplicationOverview) GetApplicationAttachments() []ApplicationAttachment`

GetApplicationAttachments returns the ApplicationAttachments field if non-nil, zero value otherwise.

### GetApplicationAttachmentsOk

`func (o *ApplicationOverview) GetApplicationAttachmentsOk() (*[]ApplicationAttachment, bool)`

GetApplicationAttachmentsOk returns a tuple with the ApplicationAttachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationAttachments

`func (o *ApplicationOverview) SetApplicationAttachments(v []ApplicationAttachment)`

SetApplicationAttachments sets ApplicationAttachments field to given value.


### GetApplicationCreated

`func (o *ApplicationOverview) GetApplicationCreated() time.Time`

GetApplicationCreated returns the ApplicationCreated field if non-nil, zero value otherwise.

### GetApplicationCreatedOk

`func (o *ApplicationOverview) GetApplicationCreatedOk() (*time.Time, bool)`

GetApplicationCreatedOk returns a tuple with the ApplicationCreated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationCreated

`func (o *ApplicationOverview) SetApplicationCreated(v time.Time)`

SetApplicationCreated sets ApplicationCreated field to given value.


### GetApplicationState

`func (o *ApplicationOverview) GetApplicationState() string`

GetApplicationState returns the ApplicationState field if non-nil, zero value otherwise.

### GetApplicationStateOk

`func (o *ApplicationOverview) GetApplicationStateOk() (*string, bool)`

GetApplicationStateOk returns a tuple with the ApplicationState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationState

`func (o *ApplicationOverview) SetApplicationState(v string)`

SetApplicationState sets ApplicationState field to given value.


### GetApplicationCopiedTo

`func (o *ApplicationOverview) GetApplicationCopiedTo() []Response7799CopiedTo`

GetApplicationCopiedTo returns the ApplicationCopiedTo field if non-nil, zero value otherwise.

### GetApplicationCopiedToOk

`func (o *ApplicationOverview) GetApplicationCopiedToOk() (*[]Response7799CopiedTo, bool)`

GetApplicationCopiedToOk returns a tuple with the ApplicationCopiedTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationCopiedTo

`func (o *ApplicationOverview) SetApplicationCopiedTo(v []Response7799CopiedTo)`

SetApplicationCopiedTo sets ApplicationCopiedTo field to given value.

### HasApplicationCopiedTo

`func (o *ApplicationOverview) HasApplicationCopiedTo() bool`

HasApplicationCopiedTo returns a boolean if a field has been set.

### GetApplicationModified

`func (o *ApplicationOverview) GetApplicationModified() time.Time`

GetApplicationModified returns the ApplicationModified field if non-nil, zero value otherwise.

### GetApplicationModifiedOk

`func (o *ApplicationOverview) GetApplicationModifiedOk() (*time.Time, bool)`

GetApplicationModifiedOk returns a tuple with the ApplicationModified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationModified

`func (o *ApplicationOverview) SetApplicationModified(v time.Time)`

SetApplicationModified sets ApplicationModified field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



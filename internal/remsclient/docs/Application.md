# Application

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationWorkflow** | [**ApplicationWorkflow**](ApplicationWorkflow.md) |  | 
**ApplicationExternalId** | **string** | Assigned external id if it exists, otherwise the generated one | 
**ApplicationFirstSubmitted** | Pointer to **time.Time** |  | [optional] 
**ApplicationBlacklist** | Pointer to [**[]BlacklistEntry**](BlacklistEntry.md) | Which members of this application are blacklisted for which resources | [optional] 
**ApplicationId** | **int64** |  | 
**ApplicationDuo** | Pointer to [**ApplicationDuo**](ApplicationDuo.md) |  | [optional] 
**ApplicationAssignedExternalId** | Pointer to **string** |  | [optional] 
**ApplicationApplicant** | [**UserWithAttributes**](UserWithAttributes.md) |  | 
**ApplicationCopiedFrom** | Pointer to [**ApplicationCopiedFrom**](ApplicationCopiedFrom.md) |  | [optional] 
**ApplicationTodo** | **NullableString** |  | 
**ApplicationMembers** | [**[]UserWithAttributes**](UserWithAttributes.md) |  | 
**EntitlementEnd** | Pointer to **NullableTime** |  | [optional] 
**ApplicationResources** | [**[]V2Resource**](V2Resource.md) |  | 
**ApplicationDeadline** | Pointer to **time.Time** |  | [optional] 
**ApplicationAcceptedLicenses** | **map[string][]int64** |  | 
**ApplicationForms** | [**[]Form**](Form.md) |  | 
**ApplicationInvitedMembers** | [**[]ApplicationInvitedMembers**](ApplicationInvitedMembers.md) |  | 
**ApplicationDescription** | **string** |  | 
**ApplicationVotes** | Pointer to **map[string]string** |  | [optional] 
**ApplicationGeneratedExternalId** | Pointer to **string** |  | [optional] 
**ApplicationPermissions** | **[]string** |  | 
**ApplicationLastActivity** | **time.Time** |  | 
**ApplicationProcessingState** | Pointer to [**ApplicationProcessingState**](ApplicationProcessingState.md) |  | [optional] 
**ApplicationEvents** | [**[]Event**](Event.md) |  | 
**ApplicationRoles** | **[]string** |  | 
**ApplicationAttachments** | [**[]ApplicationAttachment**](ApplicationAttachment.md) |  | 
**ApplicationLicenses** | [**[]V2License**](V2License.md) |  | 
**ApplicationCreated** | **time.Time** |  | 
**ApplicationState** | **string** |  | 
**ApplicationCopiedTo** | Pointer to [**[]ApplicationCopiedTo**](ApplicationCopiedTo.md) |  | [optional] 
**ApplicationModified** | **time.Time** |  | 

## Methods

### NewApplication

`func NewApplication(applicationWorkflow ApplicationWorkflow, applicationExternalId string, applicationId int64, applicationApplicant UserWithAttributes, applicationTodo NullableString, applicationMembers []UserWithAttributes, applicationResources []V2Resource, applicationAcceptedLicenses map[string][]int64, applicationForms []Form, applicationInvitedMembers []ApplicationInvitedMembers, applicationDescription string, applicationPermissions []string, applicationLastActivity time.Time, applicationEvents []Event, applicationRoles []string, applicationAttachments []ApplicationAttachment, applicationLicenses []V2License, applicationCreated time.Time, applicationState string, applicationModified time.Time, ) *Application`

NewApplication instantiates a new Application object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationWithDefaults

`func NewApplicationWithDefaults() *Application`

NewApplicationWithDefaults instantiates a new Application object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationWorkflow

`func (o *Application) GetApplicationWorkflow() ApplicationWorkflow`

GetApplicationWorkflow returns the ApplicationWorkflow field if non-nil, zero value otherwise.

### GetApplicationWorkflowOk

`func (o *Application) GetApplicationWorkflowOk() (*ApplicationWorkflow, bool)`

GetApplicationWorkflowOk returns a tuple with the ApplicationWorkflow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationWorkflow

`func (o *Application) SetApplicationWorkflow(v ApplicationWorkflow)`

SetApplicationWorkflow sets ApplicationWorkflow field to given value.


### GetApplicationExternalId

`func (o *Application) GetApplicationExternalId() string`

GetApplicationExternalId returns the ApplicationExternalId field if non-nil, zero value otherwise.

### GetApplicationExternalIdOk

`func (o *Application) GetApplicationExternalIdOk() (*string, bool)`

GetApplicationExternalIdOk returns a tuple with the ApplicationExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationExternalId

`func (o *Application) SetApplicationExternalId(v string)`

SetApplicationExternalId sets ApplicationExternalId field to given value.


### GetApplicationFirstSubmitted

`func (o *Application) GetApplicationFirstSubmitted() time.Time`

GetApplicationFirstSubmitted returns the ApplicationFirstSubmitted field if non-nil, zero value otherwise.

### GetApplicationFirstSubmittedOk

`func (o *Application) GetApplicationFirstSubmittedOk() (*time.Time, bool)`

GetApplicationFirstSubmittedOk returns a tuple with the ApplicationFirstSubmitted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationFirstSubmitted

`func (o *Application) SetApplicationFirstSubmitted(v time.Time)`

SetApplicationFirstSubmitted sets ApplicationFirstSubmitted field to given value.

### HasApplicationFirstSubmitted

`func (o *Application) HasApplicationFirstSubmitted() bool`

HasApplicationFirstSubmitted returns a boolean if a field has been set.

### GetApplicationBlacklist

`func (o *Application) GetApplicationBlacklist() []BlacklistEntry`

GetApplicationBlacklist returns the ApplicationBlacklist field if non-nil, zero value otherwise.

### GetApplicationBlacklistOk

`func (o *Application) GetApplicationBlacklistOk() (*[]BlacklistEntry, bool)`

GetApplicationBlacklistOk returns a tuple with the ApplicationBlacklist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationBlacklist

`func (o *Application) SetApplicationBlacklist(v []BlacklistEntry)`

SetApplicationBlacklist sets ApplicationBlacklist field to given value.

### HasApplicationBlacklist

`func (o *Application) HasApplicationBlacklist() bool`

HasApplicationBlacklist returns a boolean if a field has been set.

### GetApplicationId

`func (o *Application) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *Application) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *Application) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetApplicationDuo

`func (o *Application) GetApplicationDuo() ApplicationDuo`

GetApplicationDuo returns the ApplicationDuo field if non-nil, zero value otherwise.

### GetApplicationDuoOk

`func (o *Application) GetApplicationDuoOk() (*ApplicationDuo, bool)`

GetApplicationDuoOk returns a tuple with the ApplicationDuo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationDuo

`func (o *Application) SetApplicationDuo(v ApplicationDuo)`

SetApplicationDuo sets ApplicationDuo field to given value.

### HasApplicationDuo

`func (o *Application) HasApplicationDuo() bool`

HasApplicationDuo returns a boolean if a field has been set.

### GetApplicationAssignedExternalId

`func (o *Application) GetApplicationAssignedExternalId() string`

GetApplicationAssignedExternalId returns the ApplicationAssignedExternalId field if non-nil, zero value otherwise.

### GetApplicationAssignedExternalIdOk

`func (o *Application) GetApplicationAssignedExternalIdOk() (*string, bool)`

GetApplicationAssignedExternalIdOk returns a tuple with the ApplicationAssignedExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationAssignedExternalId

`func (o *Application) SetApplicationAssignedExternalId(v string)`

SetApplicationAssignedExternalId sets ApplicationAssignedExternalId field to given value.

### HasApplicationAssignedExternalId

`func (o *Application) HasApplicationAssignedExternalId() bool`

HasApplicationAssignedExternalId returns a boolean if a field has been set.

### GetApplicationApplicant

`func (o *Application) GetApplicationApplicant() UserWithAttributes`

GetApplicationApplicant returns the ApplicationApplicant field if non-nil, zero value otherwise.

### GetApplicationApplicantOk

`func (o *Application) GetApplicationApplicantOk() (*UserWithAttributes, bool)`

GetApplicationApplicantOk returns a tuple with the ApplicationApplicant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationApplicant

`func (o *Application) SetApplicationApplicant(v UserWithAttributes)`

SetApplicationApplicant sets ApplicationApplicant field to given value.


### GetApplicationCopiedFrom

`func (o *Application) GetApplicationCopiedFrom() ApplicationCopiedFrom`

GetApplicationCopiedFrom returns the ApplicationCopiedFrom field if non-nil, zero value otherwise.

### GetApplicationCopiedFromOk

`func (o *Application) GetApplicationCopiedFromOk() (*ApplicationCopiedFrom, bool)`

GetApplicationCopiedFromOk returns a tuple with the ApplicationCopiedFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationCopiedFrom

`func (o *Application) SetApplicationCopiedFrom(v ApplicationCopiedFrom)`

SetApplicationCopiedFrom sets ApplicationCopiedFrom field to given value.

### HasApplicationCopiedFrom

`func (o *Application) HasApplicationCopiedFrom() bool`

HasApplicationCopiedFrom returns a boolean if a field has been set.

### GetApplicationTodo

`func (o *Application) GetApplicationTodo() string`

GetApplicationTodo returns the ApplicationTodo field if non-nil, zero value otherwise.

### GetApplicationTodoOk

`func (o *Application) GetApplicationTodoOk() (*string, bool)`

GetApplicationTodoOk returns a tuple with the ApplicationTodo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationTodo

`func (o *Application) SetApplicationTodo(v string)`

SetApplicationTodo sets ApplicationTodo field to given value.


### SetApplicationTodoNil

`func (o *Application) SetApplicationTodoNil(b bool)`

 SetApplicationTodoNil sets the value for ApplicationTodo to be an explicit nil

### UnsetApplicationTodo
`func (o *Application) UnsetApplicationTodo()`

UnsetApplicationTodo ensures that no value is present for ApplicationTodo, not even an explicit nil
### GetApplicationMembers

`func (o *Application) GetApplicationMembers() []UserWithAttributes`

GetApplicationMembers returns the ApplicationMembers field if non-nil, zero value otherwise.

### GetApplicationMembersOk

`func (o *Application) GetApplicationMembersOk() (*[]UserWithAttributes, bool)`

GetApplicationMembersOk returns a tuple with the ApplicationMembers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationMembers

`func (o *Application) SetApplicationMembers(v []UserWithAttributes)`

SetApplicationMembers sets ApplicationMembers field to given value.


### GetEntitlementEnd

`func (o *Application) GetEntitlementEnd() time.Time`

GetEntitlementEnd returns the EntitlementEnd field if non-nil, zero value otherwise.

### GetEntitlementEndOk

`func (o *Application) GetEntitlementEndOk() (*time.Time, bool)`

GetEntitlementEndOk returns a tuple with the EntitlementEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntitlementEnd

`func (o *Application) SetEntitlementEnd(v time.Time)`

SetEntitlementEnd sets EntitlementEnd field to given value.

### HasEntitlementEnd

`func (o *Application) HasEntitlementEnd() bool`

HasEntitlementEnd returns a boolean if a field has been set.

### SetEntitlementEndNil

`func (o *Application) SetEntitlementEndNil(b bool)`

 SetEntitlementEndNil sets the value for EntitlementEnd to be an explicit nil

### UnsetEntitlementEnd
`func (o *Application) UnsetEntitlementEnd()`

UnsetEntitlementEnd ensures that no value is present for EntitlementEnd, not even an explicit nil
### GetApplicationResources

`func (o *Application) GetApplicationResources() []V2Resource`

GetApplicationResources returns the ApplicationResources field if non-nil, zero value otherwise.

### GetApplicationResourcesOk

`func (o *Application) GetApplicationResourcesOk() (*[]V2Resource, bool)`

GetApplicationResourcesOk returns a tuple with the ApplicationResources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationResources

`func (o *Application) SetApplicationResources(v []V2Resource)`

SetApplicationResources sets ApplicationResources field to given value.


### GetApplicationDeadline

`func (o *Application) GetApplicationDeadline() time.Time`

GetApplicationDeadline returns the ApplicationDeadline field if non-nil, zero value otherwise.

### GetApplicationDeadlineOk

`func (o *Application) GetApplicationDeadlineOk() (*time.Time, bool)`

GetApplicationDeadlineOk returns a tuple with the ApplicationDeadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationDeadline

`func (o *Application) SetApplicationDeadline(v time.Time)`

SetApplicationDeadline sets ApplicationDeadline field to given value.

### HasApplicationDeadline

`func (o *Application) HasApplicationDeadline() bool`

HasApplicationDeadline returns a boolean if a field has been set.

### GetApplicationAcceptedLicenses

`func (o *Application) GetApplicationAcceptedLicenses() map[string][]int64`

GetApplicationAcceptedLicenses returns the ApplicationAcceptedLicenses field if non-nil, zero value otherwise.

### GetApplicationAcceptedLicensesOk

`func (o *Application) GetApplicationAcceptedLicensesOk() (*map[string][]int64, bool)`

GetApplicationAcceptedLicensesOk returns a tuple with the ApplicationAcceptedLicenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationAcceptedLicenses

`func (o *Application) SetApplicationAcceptedLicenses(v map[string][]int64)`

SetApplicationAcceptedLicenses sets ApplicationAcceptedLicenses field to given value.


### GetApplicationForms

`func (o *Application) GetApplicationForms() []Form`

GetApplicationForms returns the ApplicationForms field if non-nil, zero value otherwise.

### GetApplicationFormsOk

`func (o *Application) GetApplicationFormsOk() (*[]Form, bool)`

GetApplicationFormsOk returns a tuple with the ApplicationForms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationForms

`func (o *Application) SetApplicationForms(v []Form)`

SetApplicationForms sets ApplicationForms field to given value.


### GetApplicationInvitedMembers

`func (o *Application) GetApplicationInvitedMembers() []ApplicationInvitedMembers`

GetApplicationInvitedMembers returns the ApplicationInvitedMembers field if non-nil, zero value otherwise.

### GetApplicationInvitedMembersOk

`func (o *Application) GetApplicationInvitedMembersOk() (*[]ApplicationInvitedMembers, bool)`

GetApplicationInvitedMembersOk returns a tuple with the ApplicationInvitedMembers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationInvitedMembers

`func (o *Application) SetApplicationInvitedMembers(v []ApplicationInvitedMembers)`

SetApplicationInvitedMembers sets ApplicationInvitedMembers field to given value.


### GetApplicationDescription

`func (o *Application) GetApplicationDescription() string`

GetApplicationDescription returns the ApplicationDescription field if non-nil, zero value otherwise.

### GetApplicationDescriptionOk

`func (o *Application) GetApplicationDescriptionOk() (*string, bool)`

GetApplicationDescriptionOk returns a tuple with the ApplicationDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationDescription

`func (o *Application) SetApplicationDescription(v string)`

SetApplicationDescription sets ApplicationDescription field to given value.


### GetApplicationVotes

`func (o *Application) GetApplicationVotes() map[string]string`

GetApplicationVotes returns the ApplicationVotes field if non-nil, zero value otherwise.

### GetApplicationVotesOk

`func (o *Application) GetApplicationVotesOk() (*map[string]string, bool)`

GetApplicationVotesOk returns a tuple with the ApplicationVotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationVotes

`func (o *Application) SetApplicationVotes(v map[string]string)`

SetApplicationVotes sets ApplicationVotes field to given value.

### HasApplicationVotes

`func (o *Application) HasApplicationVotes() bool`

HasApplicationVotes returns a boolean if a field has been set.

### GetApplicationGeneratedExternalId

`func (o *Application) GetApplicationGeneratedExternalId() string`

GetApplicationGeneratedExternalId returns the ApplicationGeneratedExternalId field if non-nil, zero value otherwise.

### GetApplicationGeneratedExternalIdOk

`func (o *Application) GetApplicationGeneratedExternalIdOk() (*string, bool)`

GetApplicationGeneratedExternalIdOk returns a tuple with the ApplicationGeneratedExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationGeneratedExternalId

`func (o *Application) SetApplicationGeneratedExternalId(v string)`

SetApplicationGeneratedExternalId sets ApplicationGeneratedExternalId field to given value.

### HasApplicationGeneratedExternalId

`func (o *Application) HasApplicationGeneratedExternalId() bool`

HasApplicationGeneratedExternalId returns a boolean if a field has been set.

### GetApplicationPermissions

`func (o *Application) GetApplicationPermissions() []string`

GetApplicationPermissions returns the ApplicationPermissions field if non-nil, zero value otherwise.

### GetApplicationPermissionsOk

`func (o *Application) GetApplicationPermissionsOk() (*[]string, bool)`

GetApplicationPermissionsOk returns a tuple with the ApplicationPermissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationPermissions

`func (o *Application) SetApplicationPermissions(v []string)`

SetApplicationPermissions sets ApplicationPermissions field to given value.


### GetApplicationLastActivity

`func (o *Application) GetApplicationLastActivity() time.Time`

GetApplicationLastActivity returns the ApplicationLastActivity field if non-nil, zero value otherwise.

### GetApplicationLastActivityOk

`func (o *Application) GetApplicationLastActivityOk() (*time.Time, bool)`

GetApplicationLastActivityOk returns a tuple with the ApplicationLastActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationLastActivity

`func (o *Application) SetApplicationLastActivity(v time.Time)`

SetApplicationLastActivity sets ApplicationLastActivity field to given value.


### GetApplicationProcessingState

`func (o *Application) GetApplicationProcessingState() ApplicationProcessingState`

GetApplicationProcessingState returns the ApplicationProcessingState field if non-nil, zero value otherwise.

### GetApplicationProcessingStateOk

`func (o *Application) GetApplicationProcessingStateOk() (*ApplicationProcessingState, bool)`

GetApplicationProcessingStateOk returns a tuple with the ApplicationProcessingState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationProcessingState

`func (o *Application) SetApplicationProcessingState(v ApplicationProcessingState)`

SetApplicationProcessingState sets ApplicationProcessingState field to given value.

### HasApplicationProcessingState

`func (o *Application) HasApplicationProcessingState() bool`

HasApplicationProcessingState returns a boolean if a field has been set.

### GetApplicationEvents

`func (o *Application) GetApplicationEvents() []Event`

GetApplicationEvents returns the ApplicationEvents field if non-nil, zero value otherwise.

### GetApplicationEventsOk

`func (o *Application) GetApplicationEventsOk() (*[]Event, bool)`

GetApplicationEventsOk returns a tuple with the ApplicationEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationEvents

`func (o *Application) SetApplicationEvents(v []Event)`

SetApplicationEvents sets ApplicationEvents field to given value.


### GetApplicationRoles

`func (o *Application) GetApplicationRoles() []string`

GetApplicationRoles returns the ApplicationRoles field if non-nil, zero value otherwise.

### GetApplicationRolesOk

`func (o *Application) GetApplicationRolesOk() (*[]string, bool)`

GetApplicationRolesOk returns a tuple with the ApplicationRoles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationRoles

`func (o *Application) SetApplicationRoles(v []string)`

SetApplicationRoles sets ApplicationRoles field to given value.


### GetApplicationAttachments

`func (o *Application) GetApplicationAttachments() []ApplicationAttachment`

GetApplicationAttachments returns the ApplicationAttachments field if non-nil, zero value otherwise.

### GetApplicationAttachmentsOk

`func (o *Application) GetApplicationAttachmentsOk() (*[]ApplicationAttachment, bool)`

GetApplicationAttachmentsOk returns a tuple with the ApplicationAttachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationAttachments

`func (o *Application) SetApplicationAttachments(v []ApplicationAttachment)`

SetApplicationAttachments sets ApplicationAttachments field to given value.


### GetApplicationLicenses

`func (o *Application) GetApplicationLicenses() []V2License`

GetApplicationLicenses returns the ApplicationLicenses field if non-nil, zero value otherwise.

### GetApplicationLicensesOk

`func (o *Application) GetApplicationLicensesOk() (*[]V2License, bool)`

GetApplicationLicensesOk returns a tuple with the ApplicationLicenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationLicenses

`func (o *Application) SetApplicationLicenses(v []V2License)`

SetApplicationLicenses sets ApplicationLicenses field to given value.


### GetApplicationCreated

`func (o *Application) GetApplicationCreated() time.Time`

GetApplicationCreated returns the ApplicationCreated field if non-nil, zero value otherwise.

### GetApplicationCreatedOk

`func (o *Application) GetApplicationCreatedOk() (*time.Time, bool)`

GetApplicationCreatedOk returns a tuple with the ApplicationCreated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationCreated

`func (o *Application) SetApplicationCreated(v time.Time)`

SetApplicationCreated sets ApplicationCreated field to given value.


### GetApplicationState

`func (o *Application) GetApplicationState() string`

GetApplicationState returns the ApplicationState field if non-nil, zero value otherwise.

### GetApplicationStateOk

`func (o *Application) GetApplicationStateOk() (*string, bool)`

GetApplicationStateOk returns a tuple with the ApplicationState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationState

`func (o *Application) SetApplicationState(v string)`

SetApplicationState sets ApplicationState field to given value.


### GetApplicationCopiedTo

`func (o *Application) GetApplicationCopiedTo() []ApplicationCopiedTo`

GetApplicationCopiedTo returns the ApplicationCopiedTo field if non-nil, zero value otherwise.

### GetApplicationCopiedToOk

`func (o *Application) GetApplicationCopiedToOk() (*[]ApplicationCopiedTo, bool)`

GetApplicationCopiedToOk returns a tuple with the ApplicationCopiedTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationCopiedTo

`func (o *Application) SetApplicationCopiedTo(v []ApplicationCopiedTo)`

SetApplicationCopiedTo sets ApplicationCopiedTo field to given value.

### HasApplicationCopiedTo

`func (o *Application) HasApplicationCopiedTo() bool`

HasApplicationCopiedTo returns a boolean if a field has been set.

### GetApplicationModified

`func (o *Application) GetApplicationModified() time.Time`

GetApplicationModified returns the ApplicationModified field if non-nil, zero value otherwise.

### GetApplicationModifiedOk

`func (o *Application) GetApplicationModifiedOk() (*time.Time, bool)`

GetApplicationModifiedOk returns a tuple with the ApplicationModified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationModified

`func (o *Application) SetApplicationModified(v time.Time)`

SetApplicationModified sets ApplicationModified field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



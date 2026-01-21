# ApplicationRaw

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationUserRoles** | **map[string][]string** |  | 
**ApplicationWorkflow** | [**ApplicationRawWorkflow**](ApplicationRawWorkflow.md) |  | 
**ApplicationExternalId** | **string** | Assigned external id if it exists, otherwise the generated one | 
**ApplicationFirstSubmitted** | Pointer to **time.Time** |  | [optional] 
**ApplicationBlacklist** | Pointer to [**[]BlacklistEntry**](BlacklistEntry.md) | Which members of this application are blacklisted for which resources | [optional] 
**ApplicationId** | **int64** |  | 
**ApplicationDuo** | Pointer to [**ApplicationRawDuo**](ApplicationRawDuo.md) |  | [optional] 
**ApplicationAssignedExternalId** | Pointer to **string** |  | [optional] 
**ApplicationApplicant** | [**UserWithAttributes**](UserWithAttributes.md) |  | 
**ApplicationCopiedFrom** | Pointer to [**ApplicationRawCopiedFrom**](ApplicationRawCopiedFrom.md) |  | [optional] 
**ApplicationTodo** | **NullableString** |  | 
**ApplicationMembers** | [**[]UserWithAttributes**](UserWithAttributes.md) |  | 
**EntitlementEnd** | Pointer to **NullableTime** |  | [optional] 
**ApplicationResources** | [**[]V2Resource**](V2Resource.md) |  | 
**ApplicationDeadline** | Pointer to **time.Time** |  | [optional] 
**ApplicationAcceptedLicenses** | **map[string][]int64** |  | 
**ApplicationForms** | [**[]Form**](Form.md) |  | 
**ApplicationInvitedMembers** | [**[]ApplicationRawInvitedMembers**](ApplicationRawInvitedMembers.md) |  | 
**ApplicationDescription** | **string** |  | 
**ApplicationVotes** | Pointer to **map[string]string** |  | [optional] 
**ApplicationGeneratedExternalId** | Pointer to **string** |  | [optional] 
**ApplicationLastActivity** | **time.Time** |  | 
**ApplicationProcessingState** | Pointer to [**ApplicationRawProcessingState**](ApplicationRawProcessingState.md) |  | [optional] 
**ApplicationEvents** | [**[]Event**](Event.md) |  | 
**ApplicationAttachments** | [**[]ApplicationAttachment**](ApplicationAttachment.md) |  | 
**ApplicationLicenses** | [**[]V2License**](V2License.md) |  | 
**ApplicationCreated** | **time.Time** |  | 
**ApplicationRolePermissions** | **map[string][]string** |  | 
**ApplicationState** | **string** |  | 
**ApplicationCopiedTo** | Pointer to [**[]ApplicationRawCopiedTo**](ApplicationRawCopiedTo.md) |  | [optional] 
**ApplicationModified** | **time.Time** |  | 

## Methods

### NewApplicationRaw

`func NewApplicationRaw(applicationUserRoles map[string][]string, applicationWorkflow ApplicationRawWorkflow, applicationExternalId string, applicationId int64, applicationApplicant UserWithAttributes, applicationTodo NullableString, applicationMembers []UserWithAttributes, applicationResources []V2Resource, applicationAcceptedLicenses map[string][]int64, applicationForms []Form, applicationInvitedMembers []ApplicationRawInvitedMembers, applicationDescription string, applicationLastActivity time.Time, applicationEvents []Event, applicationAttachments []ApplicationAttachment, applicationLicenses []V2License, applicationCreated time.Time, applicationRolePermissions map[string][]string, applicationState string, applicationModified time.Time, ) *ApplicationRaw`

NewApplicationRaw instantiates a new ApplicationRaw object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationRawWithDefaults

`func NewApplicationRawWithDefaults() *ApplicationRaw`

NewApplicationRawWithDefaults instantiates a new ApplicationRaw object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationUserRoles

`func (o *ApplicationRaw) GetApplicationUserRoles() map[string][]string`

GetApplicationUserRoles returns the ApplicationUserRoles field if non-nil, zero value otherwise.

### GetApplicationUserRolesOk

`func (o *ApplicationRaw) GetApplicationUserRolesOk() (*map[string][]string, bool)`

GetApplicationUserRolesOk returns a tuple with the ApplicationUserRoles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationUserRoles

`func (o *ApplicationRaw) SetApplicationUserRoles(v map[string][]string)`

SetApplicationUserRoles sets ApplicationUserRoles field to given value.


### GetApplicationWorkflow

`func (o *ApplicationRaw) GetApplicationWorkflow() ApplicationRawWorkflow`

GetApplicationWorkflow returns the ApplicationWorkflow field if non-nil, zero value otherwise.

### GetApplicationWorkflowOk

`func (o *ApplicationRaw) GetApplicationWorkflowOk() (*ApplicationRawWorkflow, bool)`

GetApplicationWorkflowOk returns a tuple with the ApplicationWorkflow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationWorkflow

`func (o *ApplicationRaw) SetApplicationWorkflow(v ApplicationRawWorkflow)`

SetApplicationWorkflow sets ApplicationWorkflow field to given value.


### GetApplicationExternalId

`func (o *ApplicationRaw) GetApplicationExternalId() string`

GetApplicationExternalId returns the ApplicationExternalId field if non-nil, zero value otherwise.

### GetApplicationExternalIdOk

`func (o *ApplicationRaw) GetApplicationExternalIdOk() (*string, bool)`

GetApplicationExternalIdOk returns a tuple with the ApplicationExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationExternalId

`func (o *ApplicationRaw) SetApplicationExternalId(v string)`

SetApplicationExternalId sets ApplicationExternalId field to given value.


### GetApplicationFirstSubmitted

`func (o *ApplicationRaw) GetApplicationFirstSubmitted() time.Time`

GetApplicationFirstSubmitted returns the ApplicationFirstSubmitted field if non-nil, zero value otherwise.

### GetApplicationFirstSubmittedOk

`func (o *ApplicationRaw) GetApplicationFirstSubmittedOk() (*time.Time, bool)`

GetApplicationFirstSubmittedOk returns a tuple with the ApplicationFirstSubmitted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationFirstSubmitted

`func (o *ApplicationRaw) SetApplicationFirstSubmitted(v time.Time)`

SetApplicationFirstSubmitted sets ApplicationFirstSubmitted field to given value.

### HasApplicationFirstSubmitted

`func (o *ApplicationRaw) HasApplicationFirstSubmitted() bool`

HasApplicationFirstSubmitted returns a boolean if a field has been set.

### GetApplicationBlacklist

`func (o *ApplicationRaw) GetApplicationBlacklist() []BlacklistEntry`

GetApplicationBlacklist returns the ApplicationBlacklist field if non-nil, zero value otherwise.

### GetApplicationBlacklistOk

`func (o *ApplicationRaw) GetApplicationBlacklistOk() (*[]BlacklistEntry, bool)`

GetApplicationBlacklistOk returns a tuple with the ApplicationBlacklist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationBlacklist

`func (o *ApplicationRaw) SetApplicationBlacklist(v []BlacklistEntry)`

SetApplicationBlacklist sets ApplicationBlacklist field to given value.

### HasApplicationBlacklist

`func (o *ApplicationRaw) HasApplicationBlacklist() bool`

HasApplicationBlacklist returns a boolean if a field has been set.

### GetApplicationId

`func (o *ApplicationRaw) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *ApplicationRaw) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *ApplicationRaw) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetApplicationDuo

`func (o *ApplicationRaw) GetApplicationDuo() ApplicationRawDuo`

GetApplicationDuo returns the ApplicationDuo field if non-nil, zero value otherwise.

### GetApplicationDuoOk

`func (o *ApplicationRaw) GetApplicationDuoOk() (*ApplicationRawDuo, bool)`

GetApplicationDuoOk returns a tuple with the ApplicationDuo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationDuo

`func (o *ApplicationRaw) SetApplicationDuo(v ApplicationRawDuo)`

SetApplicationDuo sets ApplicationDuo field to given value.

### HasApplicationDuo

`func (o *ApplicationRaw) HasApplicationDuo() bool`

HasApplicationDuo returns a boolean if a field has been set.

### GetApplicationAssignedExternalId

`func (o *ApplicationRaw) GetApplicationAssignedExternalId() string`

GetApplicationAssignedExternalId returns the ApplicationAssignedExternalId field if non-nil, zero value otherwise.

### GetApplicationAssignedExternalIdOk

`func (o *ApplicationRaw) GetApplicationAssignedExternalIdOk() (*string, bool)`

GetApplicationAssignedExternalIdOk returns a tuple with the ApplicationAssignedExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationAssignedExternalId

`func (o *ApplicationRaw) SetApplicationAssignedExternalId(v string)`

SetApplicationAssignedExternalId sets ApplicationAssignedExternalId field to given value.

### HasApplicationAssignedExternalId

`func (o *ApplicationRaw) HasApplicationAssignedExternalId() bool`

HasApplicationAssignedExternalId returns a boolean if a field has been set.

### GetApplicationApplicant

`func (o *ApplicationRaw) GetApplicationApplicant() UserWithAttributes`

GetApplicationApplicant returns the ApplicationApplicant field if non-nil, zero value otherwise.

### GetApplicationApplicantOk

`func (o *ApplicationRaw) GetApplicationApplicantOk() (*UserWithAttributes, bool)`

GetApplicationApplicantOk returns a tuple with the ApplicationApplicant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationApplicant

`func (o *ApplicationRaw) SetApplicationApplicant(v UserWithAttributes)`

SetApplicationApplicant sets ApplicationApplicant field to given value.


### GetApplicationCopiedFrom

`func (o *ApplicationRaw) GetApplicationCopiedFrom() ApplicationRawCopiedFrom`

GetApplicationCopiedFrom returns the ApplicationCopiedFrom field if non-nil, zero value otherwise.

### GetApplicationCopiedFromOk

`func (o *ApplicationRaw) GetApplicationCopiedFromOk() (*ApplicationRawCopiedFrom, bool)`

GetApplicationCopiedFromOk returns a tuple with the ApplicationCopiedFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationCopiedFrom

`func (o *ApplicationRaw) SetApplicationCopiedFrom(v ApplicationRawCopiedFrom)`

SetApplicationCopiedFrom sets ApplicationCopiedFrom field to given value.

### HasApplicationCopiedFrom

`func (o *ApplicationRaw) HasApplicationCopiedFrom() bool`

HasApplicationCopiedFrom returns a boolean if a field has been set.

### GetApplicationTodo

`func (o *ApplicationRaw) GetApplicationTodo() string`

GetApplicationTodo returns the ApplicationTodo field if non-nil, zero value otherwise.

### GetApplicationTodoOk

`func (o *ApplicationRaw) GetApplicationTodoOk() (*string, bool)`

GetApplicationTodoOk returns a tuple with the ApplicationTodo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationTodo

`func (o *ApplicationRaw) SetApplicationTodo(v string)`

SetApplicationTodo sets ApplicationTodo field to given value.


### SetApplicationTodoNil

`func (o *ApplicationRaw) SetApplicationTodoNil(b bool)`

 SetApplicationTodoNil sets the value for ApplicationTodo to be an explicit nil

### UnsetApplicationTodo
`func (o *ApplicationRaw) UnsetApplicationTodo()`

UnsetApplicationTodo ensures that no value is present for ApplicationTodo, not even an explicit nil
### GetApplicationMembers

`func (o *ApplicationRaw) GetApplicationMembers() []UserWithAttributes`

GetApplicationMembers returns the ApplicationMembers field if non-nil, zero value otherwise.

### GetApplicationMembersOk

`func (o *ApplicationRaw) GetApplicationMembersOk() (*[]UserWithAttributes, bool)`

GetApplicationMembersOk returns a tuple with the ApplicationMembers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationMembers

`func (o *ApplicationRaw) SetApplicationMembers(v []UserWithAttributes)`

SetApplicationMembers sets ApplicationMembers field to given value.


### GetEntitlementEnd

`func (o *ApplicationRaw) GetEntitlementEnd() time.Time`

GetEntitlementEnd returns the EntitlementEnd field if non-nil, zero value otherwise.

### GetEntitlementEndOk

`func (o *ApplicationRaw) GetEntitlementEndOk() (*time.Time, bool)`

GetEntitlementEndOk returns a tuple with the EntitlementEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntitlementEnd

`func (o *ApplicationRaw) SetEntitlementEnd(v time.Time)`

SetEntitlementEnd sets EntitlementEnd field to given value.

### HasEntitlementEnd

`func (o *ApplicationRaw) HasEntitlementEnd() bool`

HasEntitlementEnd returns a boolean if a field has been set.

### SetEntitlementEndNil

`func (o *ApplicationRaw) SetEntitlementEndNil(b bool)`

 SetEntitlementEndNil sets the value for EntitlementEnd to be an explicit nil

### UnsetEntitlementEnd
`func (o *ApplicationRaw) UnsetEntitlementEnd()`

UnsetEntitlementEnd ensures that no value is present for EntitlementEnd, not even an explicit nil
### GetApplicationResources

`func (o *ApplicationRaw) GetApplicationResources() []V2Resource`

GetApplicationResources returns the ApplicationResources field if non-nil, zero value otherwise.

### GetApplicationResourcesOk

`func (o *ApplicationRaw) GetApplicationResourcesOk() (*[]V2Resource, bool)`

GetApplicationResourcesOk returns a tuple with the ApplicationResources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationResources

`func (o *ApplicationRaw) SetApplicationResources(v []V2Resource)`

SetApplicationResources sets ApplicationResources field to given value.


### GetApplicationDeadline

`func (o *ApplicationRaw) GetApplicationDeadline() time.Time`

GetApplicationDeadline returns the ApplicationDeadline field if non-nil, zero value otherwise.

### GetApplicationDeadlineOk

`func (o *ApplicationRaw) GetApplicationDeadlineOk() (*time.Time, bool)`

GetApplicationDeadlineOk returns a tuple with the ApplicationDeadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationDeadline

`func (o *ApplicationRaw) SetApplicationDeadline(v time.Time)`

SetApplicationDeadline sets ApplicationDeadline field to given value.

### HasApplicationDeadline

`func (o *ApplicationRaw) HasApplicationDeadline() bool`

HasApplicationDeadline returns a boolean if a field has been set.

### GetApplicationAcceptedLicenses

`func (o *ApplicationRaw) GetApplicationAcceptedLicenses() map[string][]int64`

GetApplicationAcceptedLicenses returns the ApplicationAcceptedLicenses field if non-nil, zero value otherwise.

### GetApplicationAcceptedLicensesOk

`func (o *ApplicationRaw) GetApplicationAcceptedLicensesOk() (*map[string][]int64, bool)`

GetApplicationAcceptedLicensesOk returns a tuple with the ApplicationAcceptedLicenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationAcceptedLicenses

`func (o *ApplicationRaw) SetApplicationAcceptedLicenses(v map[string][]int64)`

SetApplicationAcceptedLicenses sets ApplicationAcceptedLicenses field to given value.


### GetApplicationForms

`func (o *ApplicationRaw) GetApplicationForms() []Form`

GetApplicationForms returns the ApplicationForms field if non-nil, zero value otherwise.

### GetApplicationFormsOk

`func (o *ApplicationRaw) GetApplicationFormsOk() (*[]Form, bool)`

GetApplicationFormsOk returns a tuple with the ApplicationForms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationForms

`func (o *ApplicationRaw) SetApplicationForms(v []Form)`

SetApplicationForms sets ApplicationForms field to given value.


### GetApplicationInvitedMembers

`func (o *ApplicationRaw) GetApplicationInvitedMembers() []ApplicationRawInvitedMembers`

GetApplicationInvitedMembers returns the ApplicationInvitedMembers field if non-nil, zero value otherwise.

### GetApplicationInvitedMembersOk

`func (o *ApplicationRaw) GetApplicationInvitedMembersOk() (*[]ApplicationRawInvitedMembers, bool)`

GetApplicationInvitedMembersOk returns a tuple with the ApplicationInvitedMembers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationInvitedMembers

`func (o *ApplicationRaw) SetApplicationInvitedMembers(v []ApplicationRawInvitedMembers)`

SetApplicationInvitedMembers sets ApplicationInvitedMembers field to given value.


### GetApplicationDescription

`func (o *ApplicationRaw) GetApplicationDescription() string`

GetApplicationDescription returns the ApplicationDescription field if non-nil, zero value otherwise.

### GetApplicationDescriptionOk

`func (o *ApplicationRaw) GetApplicationDescriptionOk() (*string, bool)`

GetApplicationDescriptionOk returns a tuple with the ApplicationDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationDescription

`func (o *ApplicationRaw) SetApplicationDescription(v string)`

SetApplicationDescription sets ApplicationDescription field to given value.


### GetApplicationVotes

`func (o *ApplicationRaw) GetApplicationVotes() map[string]string`

GetApplicationVotes returns the ApplicationVotes field if non-nil, zero value otherwise.

### GetApplicationVotesOk

`func (o *ApplicationRaw) GetApplicationVotesOk() (*map[string]string, bool)`

GetApplicationVotesOk returns a tuple with the ApplicationVotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationVotes

`func (o *ApplicationRaw) SetApplicationVotes(v map[string]string)`

SetApplicationVotes sets ApplicationVotes field to given value.

### HasApplicationVotes

`func (o *ApplicationRaw) HasApplicationVotes() bool`

HasApplicationVotes returns a boolean if a field has been set.

### GetApplicationGeneratedExternalId

`func (o *ApplicationRaw) GetApplicationGeneratedExternalId() string`

GetApplicationGeneratedExternalId returns the ApplicationGeneratedExternalId field if non-nil, zero value otherwise.

### GetApplicationGeneratedExternalIdOk

`func (o *ApplicationRaw) GetApplicationGeneratedExternalIdOk() (*string, bool)`

GetApplicationGeneratedExternalIdOk returns a tuple with the ApplicationGeneratedExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationGeneratedExternalId

`func (o *ApplicationRaw) SetApplicationGeneratedExternalId(v string)`

SetApplicationGeneratedExternalId sets ApplicationGeneratedExternalId field to given value.

### HasApplicationGeneratedExternalId

`func (o *ApplicationRaw) HasApplicationGeneratedExternalId() bool`

HasApplicationGeneratedExternalId returns a boolean if a field has been set.

### GetApplicationLastActivity

`func (o *ApplicationRaw) GetApplicationLastActivity() time.Time`

GetApplicationLastActivity returns the ApplicationLastActivity field if non-nil, zero value otherwise.

### GetApplicationLastActivityOk

`func (o *ApplicationRaw) GetApplicationLastActivityOk() (*time.Time, bool)`

GetApplicationLastActivityOk returns a tuple with the ApplicationLastActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationLastActivity

`func (o *ApplicationRaw) SetApplicationLastActivity(v time.Time)`

SetApplicationLastActivity sets ApplicationLastActivity field to given value.


### GetApplicationProcessingState

`func (o *ApplicationRaw) GetApplicationProcessingState() ApplicationRawProcessingState`

GetApplicationProcessingState returns the ApplicationProcessingState field if non-nil, zero value otherwise.

### GetApplicationProcessingStateOk

`func (o *ApplicationRaw) GetApplicationProcessingStateOk() (*ApplicationRawProcessingState, bool)`

GetApplicationProcessingStateOk returns a tuple with the ApplicationProcessingState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationProcessingState

`func (o *ApplicationRaw) SetApplicationProcessingState(v ApplicationRawProcessingState)`

SetApplicationProcessingState sets ApplicationProcessingState field to given value.

### HasApplicationProcessingState

`func (o *ApplicationRaw) HasApplicationProcessingState() bool`

HasApplicationProcessingState returns a boolean if a field has been set.

### GetApplicationEvents

`func (o *ApplicationRaw) GetApplicationEvents() []Event`

GetApplicationEvents returns the ApplicationEvents field if non-nil, zero value otherwise.

### GetApplicationEventsOk

`func (o *ApplicationRaw) GetApplicationEventsOk() (*[]Event, bool)`

GetApplicationEventsOk returns a tuple with the ApplicationEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationEvents

`func (o *ApplicationRaw) SetApplicationEvents(v []Event)`

SetApplicationEvents sets ApplicationEvents field to given value.


### GetApplicationAttachments

`func (o *ApplicationRaw) GetApplicationAttachments() []ApplicationAttachment`

GetApplicationAttachments returns the ApplicationAttachments field if non-nil, zero value otherwise.

### GetApplicationAttachmentsOk

`func (o *ApplicationRaw) GetApplicationAttachmentsOk() (*[]ApplicationAttachment, bool)`

GetApplicationAttachmentsOk returns a tuple with the ApplicationAttachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationAttachments

`func (o *ApplicationRaw) SetApplicationAttachments(v []ApplicationAttachment)`

SetApplicationAttachments sets ApplicationAttachments field to given value.


### GetApplicationLicenses

`func (o *ApplicationRaw) GetApplicationLicenses() []V2License`

GetApplicationLicenses returns the ApplicationLicenses field if non-nil, zero value otherwise.

### GetApplicationLicensesOk

`func (o *ApplicationRaw) GetApplicationLicensesOk() (*[]V2License, bool)`

GetApplicationLicensesOk returns a tuple with the ApplicationLicenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationLicenses

`func (o *ApplicationRaw) SetApplicationLicenses(v []V2License)`

SetApplicationLicenses sets ApplicationLicenses field to given value.


### GetApplicationCreated

`func (o *ApplicationRaw) GetApplicationCreated() time.Time`

GetApplicationCreated returns the ApplicationCreated field if non-nil, zero value otherwise.

### GetApplicationCreatedOk

`func (o *ApplicationRaw) GetApplicationCreatedOk() (*time.Time, bool)`

GetApplicationCreatedOk returns a tuple with the ApplicationCreated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationCreated

`func (o *ApplicationRaw) SetApplicationCreated(v time.Time)`

SetApplicationCreated sets ApplicationCreated field to given value.


### GetApplicationRolePermissions

`func (o *ApplicationRaw) GetApplicationRolePermissions() map[string][]string`

GetApplicationRolePermissions returns the ApplicationRolePermissions field if non-nil, zero value otherwise.

### GetApplicationRolePermissionsOk

`func (o *ApplicationRaw) GetApplicationRolePermissionsOk() (*map[string][]string, bool)`

GetApplicationRolePermissionsOk returns a tuple with the ApplicationRolePermissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationRolePermissions

`func (o *ApplicationRaw) SetApplicationRolePermissions(v map[string][]string)`

SetApplicationRolePermissions sets ApplicationRolePermissions field to given value.


### GetApplicationState

`func (o *ApplicationRaw) GetApplicationState() string`

GetApplicationState returns the ApplicationState field if non-nil, zero value otherwise.

### GetApplicationStateOk

`func (o *ApplicationRaw) GetApplicationStateOk() (*string, bool)`

GetApplicationStateOk returns a tuple with the ApplicationState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationState

`func (o *ApplicationRaw) SetApplicationState(v string)`

SetApplicationState sets ApplicationState field to given value.


### GetApplicationCopiedTo

`func (o *ApplicationRaw) GetApplicationCopiedTo() []ApplicationRawCopiedTo`

GetApplicationCopiedTo returns the ApplicationCopiedTo field if non-nil, zero value otherwise.

### GetApplicationCopiedToOk

`func (o *ApplicationRaw) GetApplicationCopiedToOk() (*[]ApplicationRawCopiedTo, bool)`

GetApplicationCopiedToOk returns a tuple with the ApplicationCopiedTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationCopiedTo

`func (o *ApplicationRaw) SetApplicationCopiedTo(v []ApplicationRawCopiedTo)`

SetApplicationCopiedTo sets ApplicationCopiedTo field to given value.

### HasApplicationCopiedTo

`func (o *ApplicationRaw) HasApplicationCopiedTo() bool`

HasApplicationCopiedTo returns a boolean if a field has been set.

### GetApplicationModified

`func (o *ApplicationRaw) GetApplicationModified() time.Time`

GetApplicationModified returns the ApplicationModified field if non-nil, zero value otherwise.

### GetApplicationModifiedOk

`func (o *ApplicationRaw) GetApplicationModifiedOk() (*time.Time, bool)`

GetApplicationModifiedOk returns a tuple with the ApplicationModified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationModified

`func (o *ApplicationRaw) SetApplicationModified(v time.Time)`

SetApplicationModified sets ApplicationModified field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# InvitationResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InvitationWorkflow** | Pointer to [**Response8021Workflow**](Response8021Workflow.md) |  | [optional] 
**InvitationCreated** | **time.Time** |  | 
**InvitationSent** | Pointer to **time.Time** |  | [optional] 
**InvitationAccepted** | Pointer to **time.Time** |  | [optional] 
**InvitationInvitedBy** | [**UserWithAttributes**](UserWithAttributes.md) |  | 
**InvitationName** | **string** |  | 
**InvitationEmail** | **string** |  | 
**InvitationId** | Pointer to **int64** |  | [optional] 
**InvitationInvitedUser** | Pointer to [**UserWithAttributes**](UserWithAttributes.md) |  | [optional] 

## Methods

### NewInvitationResponse

`func NewInvitationResponse(invitationCreated time.Time, invitationInvitedBy UserWithAttributes, invitationName string, invitationEmail string, ) *InvitationResponse`

NewInvitationResponse instantiates a new InvitationResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvitationResponseWithDefaults

`func NewInvitationResponseWithDefaults() *InvitationResponse`

NewInvitationResponseWithDefaults instantiates a new InvitationResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInvitationWorkflow

`func (o *InvitationResponse) GetInvitationWorkflow() Response8021Workflow`

GetInvitationWorkflow returns the InvitationWorkflow field if non-nil, zero value otherwise.

### GetInvitationWorkflowOk

`func (o *InvitationResponse) GetInvitationWorkflowOk() (*Response8021Workflow, bool)`

GetInvitationWorkflowOk returns a tuple with the InvitationWorkflow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitationWorkflow

`func (o *InvitationResponse) SetInvitationWorkflow(v Response8021Workflow)`

SetInvitationWorkflow sets InvitationWorkflow field to given value.

### HasInvitationWorkflow

`func (o *InvitationResponse) HasInvitationWorkflow() bool`

HasInvitationWorkflow returns a boolean if a field has been set.

### GetInvitationCreated

`func (o *InvitationResponse) GetInvitationCreated() time.Time`

GetInvitationCreated returns the InvitationCreated field if non-nil, zero value otherwise.

### GetInvitationCreatedOk

`func (o *InvitationResponse) GetInvitationCreatedOk() (*time.Time, bool)`

GetInvitationCreatedOk returns a tuple with the InvitationCreated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitationCreated

`func (o *InvitationResponse) SetInvitationCreated(v time.Time)`

SetInvitationCreated sets InvitationCreated field to given value.


### GetInvitationSent

`func (o *InvitationResponse) GetInvitationSent() time.Time`

GetInvitationSent returns the InvitationSent field if non-nil, zero value otherwise.

### GetInvitationSentOk

`func (o *InvitationResponse) GetInvitationSentOk() (*time.Time, bool)`

GetInvitationSentOk returns a tuple with the InvitationSent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitationSent

`func (o *InvitationResponse) SetInvitationSent(v time.Time)`

SetInvitationSent sets InvitationSent field to given value.

### HasInvitationSent

`func (o *InvitationResponse) HasInvitationSent() bool`

HasInvitationSent returns a boolean if a field has been set.

### GetInvitationAccepted

`func (o *InvitationResponse) GetInvitationAccepted() time.Time`

GetInvitationAccepted returns the InvitationAccepted field if non-nil, zero value otherwise.

### GetInvitationAcceptedOk

`func (o *InvitationResponse) GetInvitationAcceptedOk() (*time.Time, bool)`

GetInvitationAcceptedOk returns a tuple with the InvitationAccepted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitationAccepted

`func (o *InvitationResponse) SetInvitationAccepted(v time.Time)`

SetInvitationAccepted sets InvitationAccepted field to given value.

### HasInvitationAccepted

`func (o *InvitationResponse) HasInvitationAccepted() bool`

HasInvitationAccepted returns a boolean if a field has been set.

### GetInvitationInvitedBy

`func (o *InvitationResponse) GetInvitationInvitedBy() UserWithAttributes`

GetInvitationInvitedBy returns the InvitationInvitedBy field if non-nil, zero value otherwise.

### GetInvitationInvitedByOk

`func (o *InvitationResponse) GetInvitationInvitedByOk() (*UserWithAttributes, bool)`

GetInvitationInvitedByOk returns a tuple with the InvitationInvitedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitationInvitedBy

`func (o *InvitationResponse) SetInvitationInvitedBy(v UserWithAttributes)`

SetInvitationInvitedBy sets InvitationInvitedBy field to given value.


### GetInvitationName

`func (o *InvitationResponse) GetInvitationName() string`

GetInvitationName returns the InvitationName field if non-nil, zero value otherwise.

### GetInvitationNameOk

`func (o *InvitationResponse) GetInvitationNameOk() (*string, bool)`

GetInvitationNameOk returns a tuple with the InvitationName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitationName

`func (o *InvitationResponse) SetInvitationName(v string)`

SetInvitationName sets InvitationName field to given value.


### GetInvitationEmail

`func (o *InvitationResponse) GetInvitationEmail() string`

GetInvitationEmail returns the InvitationEmail field if non-nil, zero value otherwise.

### GetInvitationEmailOk

`func (o *InvitationResponse) GetInvitationEmailOk() (*string, bool)`

GetInvitationEmailOk returns a tuple with the InvitationEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitationEmail

`func (o *InvitationResponse) SetInvitationEmail(v string)`

SetInvitationEmail sets InvitationEmail field to given value.


### GetInvitationId

`func (o *InvitationResponse) GetInvitationId() int64`

GetInvitationId returns the InvitationId field if non-nil, zero value otherwise.

### GetInvitationIdOk

`func (o *InvitationResponse) GetInvitationIdOk() (*int64, bool)`

GetInvitationIdOk returns a tuple with the InvitationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitationId

`func (o *InvitationResponse) SetInvitationId(v int64)`

SetInvitationId sets InvitationId field to given value.

### HasInvitationId

`func (o *InvitationResponse) HasInvitationId() bool`

HasInvitationId returns a boolean if a field has been set.

### GetInvitationInvitedUser

`func (o *InvitationResponse) GetInvitationInvitedUser() UserWithAttributes`

GetInvitationInvitedUser returns the InvitationInvitedUser field if non-nil, zero value otherwise.

### GetInvitationInvitedUserOk

`func (o *InvitationResponse) GetInvitationInvitedUserOk() (*UserWithAttributes, bool)`

GetInvitationInvitedUserOk returns a tuple with the InvitationInvitedUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitationInvitedUser

`func (o *InvitationResponse) SetInvitationInvitedUser(v UserWithAttributes)`

SetInvitationInvitedUser sets InvitationInvitedUser field to given value.

### HasInvitationInvitedUser

`func (o *InvitationResponse) HasInvitationInvitedUser() bool`

HasInvitationInvitedUser returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



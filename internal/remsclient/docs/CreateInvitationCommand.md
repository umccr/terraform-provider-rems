# CreateInvitationCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Email** | **string** |  | 
**WorkflowId** | Pointer to **int64** |  | [optional] 

## Methods

### NewCreateInvitationCommand

`func NewCreateInvitationCommand(name string, email string, ) *CreateInvitationCommand`

NewCreateInvitationCommand instantiates a new CreateInvitationCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateInvitationCommandWithDefaults

`func NewCreateInvitationCommandWithDefaults() *CreateInvitationCommand`

NewCreateInvitationCommandWithDefaults instantiates a new CreateInvitationCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateInvitationCommand) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateInvitationCommand) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateInvitationCommand) SetName(v string)`

SetName sets Name field to given value.


### GetEmail

`func (o *CreateInvitationCommand) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CreateInvitationCommand) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CreateInvitationCommand) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetWorkflowId

`func (o *CreateInvitationCommand) GetWorkflowId() int64`

GetWorkflowId returns the WorkflowId field if non-nil, zero value otherwise.

### GetWorkflowIdOk

`func (o *CreateInvitationCommand) GetWorkflowIdOk() (*int64, bool)`

GetWorkflowIdOk returns a tuple with the WorkflowId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowId

`func (o *CreateInvitationCommand) SetWorkflowId(v int64)`

SetWorkflowId sets WorkflowId field to given value.

### HasWorkflowId

`func (o *CreateInvitationCommand) HasWorkflowId() bool`

HasWorkflowId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



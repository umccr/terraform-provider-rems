# EditWorkflowCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int64** |  | 
**Organization** | Pointer to [**OrganizationId**](OrganizationId.md) |  | [optional] 
**Title** | Pointer to **string** |  | [optional] 
**Handlers** | Pointer to **[]string** |  | [optional] 
**DisableCommands** | Pointer to [**[]DisableCommandRule**](DisableCommandRule.md) |  | [optional] 
**Voting** | Pointer to [**WorkflowVoting**](WorkflowVoting.md) |  | [optional] 
**AnonymizeHandling** | Pointer to **NullableBool** |  | [optional] 
**ProcessingStates** | Pointer to [**[]ProcessingState**](ProcessingState.md) |  | [optional] 

## Methods

### NewEditWorkflowCommand

`func NewEditWorkflowCommand(id int64, ) *EditWorkflowCommand`

NewEditWorkflowCommand instantiates a new EditWorkflowCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEditWorkflowCommandWithDefaults

`func NewEditWorkflowCommandWithDefaults() *EditWorkflowCommand`

NewEditWorkflowCommandWithDefaults instantiates a new EditWorkflowCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EditWorkflowCommand) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EditWorkflowCommand) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EditWorkflowCommand) SetId(v int64)`

SetId sets Id field to given value.


### GetOrganization

`func (o *EditWorkflowCommand) GetOrganization() OrganizationId`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *EditWorkflowCommand) GetOrganizationOk() (*OrganizationId, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *EditWorkflowCommand) SetOrganization(v OrganizationId)`

SetOrganization sets Organization field to given value.

### HasOrganization

`func (o *EditWorkflowCommand) HasOrganization() bool`

HasOrganization returns a boolean if a field has been set.

### GetTitle

`func (o *EditWorkflowCommand) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *EditWorkflowCommand) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *EditWorkflowCommand) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *EditWorkflowCommand) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetHandlers

`func (o *EditWorkflowCommand) GetHandlers() []string`

GetHandlers returns the Handlers field if non-nil, zero value otherwise.

### GetHandlersOk

`func (o *EditWorkflowCommand) GetHandlersOk() (*[]string, bool)`

GetHandlersOk returns a tuple with the Handlers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHandlers

`func (o *EditWorkflowCommand) SetHandlers(v []string)`

SetHandlers sets Handlers field to given value.

### HasHandlers

`func (o *EditWorkflowCommand) HasHandlers() bool`

HasHandlers returns a boolean if a field has been set.

### GetDisableCommands

`func (o *EditWorkflowCommand) GetDisableCommands() []DisableCommandRule`

GetDisableCommands returns the DisableCommands field if non-nil, zero value otherwise.

### GetDisableCommandsOk

`func (o *EditWorkflowCommand) GetDisableCommandsOk() (*[]DisableCommandRule, bool)`

GetDisableCommandsOk returns a tuple with the DisableCommands field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisableCommands

`func (o *EditWorkflowCommand) SetDisableCommands(v []DisableCommandRule)`

SetDisableCommands sets DisableCommands field to given value.

### HasDisableCommands

`func (o *EditWorkflowCommand) HasDisableCommands() bool`

HasDisableCommands returns a boolean if a field has been set.

### GetVoting

`func (o *EditWorkflowCommand) GetVoting() WorkflowVoting`

GetVoting returns the Voting field if non-nil, zero value otherwise.

### GetVotingOk

`func (o *EditWorkflowCommand) GetVotingOk() (*WorkflowVoting, bool)`

GetVotingOk returns a tuple with the Voting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoting

`func (o *EditWorkflowCommand) SetVoting(v WorkflowVoting)`

SetVoting sets Voting field to given value.

### HasVoting

`func (o *EditWorkflowCommand) HasVoting() bool`

HasVoting returns a boolean if a field has been set.

### GetAnonymizeHandling

`func (o *EditWorkflowCommand) GetAnonymizeHandling() bool`

GetAnonymizeHandling returns the AnonymizeHandling field if non-nil, zero value otherwise.

### GetAnonymizeHandlingOk

`func (o *EditWorkflowCommand) GetAnonymizeHandlingOk() (*bool, bool)`

GetAnonymizeHandlingOk returns a tuple with the AnonymizeHandling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnonymizeHandling

`func (o *EditWorkflowCommand) SetAnonymizeHandling(v bool)`

SetAnonymizeHandling sets AnonymizeHandling field to given value.

### HasAnonymizeHandling

`func (o *EditWorkflowCommand) HasAnonymizeHandling() bool`

HasAnonymizeHandling returns a boolean if a field has been set.

### SetAnonymizeHandlingNil

`func (o *EditWorkflowCommand) SetAnonymizeHandlingNil(b bool)`

 SetAnonymizeHandlingNil sets the value for AnonymizeHandling to be an explicit nil

### UnsetAnonymizeHandling
`func (o *EditWorkflowCommand) UnsetAnonymizeHandling()`

UnsetAnonymizeHandling ensures that no value is present for AnonymizeHandling, not even an explicit nil
### GetProcessingStates

`func (o *EditWorkflowCommand) GetProcessingStates() []ProcessingState`

GetProcessingStates returns the ProcessingStates field if non-nil, zero value otherwise.

### GetProcessingStatesOk

`func (o *EditWorkflowCommand) GetProcessingStatesOk() (*[]ProcessingState, bool)`

GetProcessingStatesOk returns a tuple with the ProcessingStates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingStates

`func (o *EditWorkflowCommand) SetProcessingStates(v []ProcessingState)`

SetProcessingStates sets ProcessingStates field to given value.

### HasProcessingStates

`func (o *EditWorkflowCommand) HasProcessingStates() bool`

HasProcessingStates returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ApplicationWorkflow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WorkflowId** | **int64** |  | 
**WorkflowType** | **string** |  | 
**WorkflowDynamicHandlers** | Pointer to [**[]Handler**](Handler.md) |  | [optional] 
**WorkflowVoting** | Pointer to [**WorkflowVoting**](WorkflowVoting.md) |  | [optional] 
**WorkflowAnonymizeHandling** | Pointer to **bool** |  | [optional] 
**WorkflowProcessingStates** | Pointer to [**[]ProcessingState**](ProcessingState.md) |  | [optional] 

## Methods

### NewApplicationWorkflow

`func NewApplicationWorkflow(workflowId int64, workflowType string, ) *ApplicationWorkflow`

NewApplicationWorkflow instantiates a new ApplicationWorkflow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationWorkflowWithDefaults

`func NewApplicationWorkflowWithDefaults() *ApplicationWorkflow`

NewApplicationWorkflowWithDefaults instantiates a new ApplicationWorkflow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkflowId

`func (o *ApplicationWorkflow) GetWorkflowId() int64`

GetWorkflowId returns the WorkflowId field if non-nil, zero value otherwise.

### GetWorkflowIdOk

`func (o *ApplicationWorkflow) GetWorkflowIdOk() (*int64, bool)`

GetWorkflowIdOk returns a tuple with the WorkflowId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowId

`func (o *ApplicationWorkflow) SetWorkflowId(v int64)`

SetWorkflowId sets WorkflowId field to given value.


### GetWorkflowType

`func (o *ApplicationWorkflow) GetWorkflowType() string`

GetWorkflowType returns the WorkflowType field if non-nil, zero value otherwise.

### GetWorkflowTypeOk

`func (o *ApplicationWorkflow) GetWorkflowTypeOk() (*string, bool)`

GetWorkflowTypeOk returns a tuple with the WorkflowType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowType

`func (o *ApplicationWorkflow) SetWorkflowType(v string)`

SetWorkflowType sets WorkflowType field to given value.


### GetWorkflowDynamicHandlers

`func (o *ApplicationWorkflow) GetWorkflowDynamicHandlers() []Handler`

GetWorkflowDynamicHandlers returns the WorkflowDynamicHandlers field if non-nil, zero value otherwise.

### GetWorkflowDynamicHandlersOk

`func (o *ApplicationWorkflow) GetWorkflowDynamicHandlersOk() (*[]Handler, bool)`

GetWorkflowDynamicHandlersOk returns a tuple with the WorkflowDynamicHandlers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowDynamicHandlers

`func (o *ApplicationWorkflow) SetWorkflowDynamicHandlers(v []Handler)`

SetWorkflowDynamicHandlers sets WorkflowDynamicHandlers field to given value.

### HasWorkflowDynamicHandlers

`func (o *ApplicationWorkflow) HasWorkflowDynamicHandlers() bool`

HasWorkflowDynamicHandlers returns a boolean if a field has been set.

### GetWorkflowVoting

`func (o *ApplicationWorkflow) GetWorkflowVoting() WorkflowVoting`

GetWorkflowVoting returns the WorkflowVoting field if non-nil, zero value otherwise.

### GetWorkflowVotingOk

`func (o *ApplicationWorkflow) GetWorkflowVotingOk() (*WorkflowVoting, bool)`

GetWorkflowVotingOk returns a tuple with the WorkflowVoting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowVoting

`func (o *ApplicationWorkflow) SetWorkflowVoting(v WorkflowVoting)`

SetWorkflowVoting sets WorkflowVoting field to given value.

### HasWorkflowVoting

`func (o *ApplicationWorkflow) HasWorkflowVoting() bool`

HasWorkflowVoting returns a boolean if a field has been set.

### GetWorkflowAnonymizeHandling

`func (o *ApplicationWorkflow) GetWorkflowAnonymizeHandling() bool`

GetWorkflowAnonymizeHandling returns the WorkflowAnonymizeHandling field if non-nil, zero value otherwise.

### GetWorkflowAnonymizeHandlingOk

`func (o *ApplicationWorkflow) GetWorkflowAnonymizeHandlingOk() (*bool, bool)`

GetWorkflowAnonymizeHandlingOk returns a tuple with the WorkflowAnonymizeHandling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowAnonymizeHandling

`func (o *ApplicationWorkflow) SetWorkflowAnonymizeHandling(v bool)`

SetWorkflowAnonymizeHandling sets WorkflowAnonymizeHandling field to given value.

### HasWorkflowAnonymizeHandling

`func (o *ApplicationWorkflow) HasWorkflowAnonymizeHandling() bool`

HasWorkflowAnonymizeHandling returns a boolean if a field has been set.

### GetWorkflowProcessingStates

`func (o *ApplicationWorkflow) GetWorkflowProcessingStates() []ProcessingState`

GetWorkflowProcessingStates returns the WorkflowProcessingStates field if non-nil, zero value otherwise.

### GetWorkflowProcessingStatesOk

`func (o *ApplicationWorkflow) GetWorkflowProcessingStatesOk() (*[]ProcessingState, bool)`

GetWorkflowProcessingStatesOk returns a tuple with the WorkflowProcessingStates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowProcessingStates

`func (o *ApplicationWorkflow) SetWorkflowProcessingStates(v []ProcessingState)`

SetWorkflowProcessingStates sets WorkflowProcessingStates field to given value.

### HasWorkflowProcessingStates

`func (o *ApplicationWorkflow) HasWorkflowProcessingStates() bool`

HasWorkflowProcessingStates returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



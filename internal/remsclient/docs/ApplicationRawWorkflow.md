# ApplicationRawWorkflow

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

### NewApplicationRawWorkflow

`func NewApplicationRawWorkflow(workflowId int64, workflowType string, ) *ApplicationRawWorkflow`

NewApplicationRawWorkflow instantiates a new ApplicationRawWorkflow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationRawWorkflowWithDefaults

`func NewApplicationRawWorkflowWithDefaults() *ApplicationRawWorkflow`

NewApplicationRawWorkflowWithDefaults instantiates a new ApplicationRawWorkflow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkflowId

`func (o *ApplicationRawWorkflow) GetWorkflowId() int64`

GetWorkflowId returns the WorkflowId field if non-nil, zero value otherwise.

### GetWorkflowIdOk

`func (o *ApplicationRawWorkflow) GetWorkflowIdOk() (*int64, bool)`

GetWorkflowIdOk returns a tuple with the WorkflowId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowId

`func (o *ApplicationRawWorkflow) SetWorkflowId(v int64)`

SetWorkflowId sets WorkflowId field to given value.


### GetWorkflowType

`func (o *ApplicationRawWorkflow) GetWorkflowType() string`

GetWorkflowType returns the WorkflowType field if non-nil, zero value otherwise.

### GetWorkflowTypeOk

`func (o *ApplicationRawWorkflow) GetWorkflowTypeOk() (*string, bool)`

GetWorkflowTypeOk returns a tuple with the WorkflowType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowType

`func (o *ApplicationRawWorkflow) SetWorkflowType(v string)`

SetWorkflowType sets WorkflowType field to given value.


### GetWorkflowDynamicHandlers

`func (o *ApplicationRawWorkflow) GetWorkflowDynamicHandlers() []Handler`

GetWorkflowDynamicHandlers returns the WorkflowDynamicHandlers field if non-nil, zero value otherwise.

### GetWorkflowDynamicHandlersOk

`func (o *ApplicationRawWorkflow) GetWorkflowDynamicHandlersOk() (*[]Handler, bool)`

GetWorkflowDynamicHandlersOk returns a tuple with the WorkflowDynamicHandlers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowDynamicHandlers

`func (o *ApplicationRawWorkflow) SetWorkflowDynamicHandlers(v []Handler)`

SetWorkflowDynamicHandlers sets WorkflowDynamicHandlers field to given value.

### HasWorkflowDynamicHandlers

`func (o *ApplicationRawWorkflow) HasWorkflowDynamicHandlers() bool`

HasWorkflowDynamicHandlers returns a boolean if a field has been set.

### GetWorkflowVoting

`func (o *ApplicationRawWorkflow) GetWorkflowVoting() WorkflowVoting`

GetWorkflowVoting returns the WorkflowVoting field if non-nil, zero value otherwise.

### GetWorkflowVotingOk

`func (o *ApplicationRawWorkflow) GetWorkflowVotingOk() (*WorkflowVoting, bool)`

GetWorkflowVotingOk returns a tuple with the WorkflowVoting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowVoting

`func (o *ApplicationRawWorkflow) SetWorkflowVoting(v WorkflowVoting)`

SetWorkflowVoting sets WorkflowVoting field to given value.

### HasWorkflowVoting

`func (o *ApplicationRawWorkflow) HasWorkflowVoting() bool`

HasWorkflowVoting returns a boolean if a field has been set.

### GetWorkflowAnonymizeHandling

`func (o *ApplicationRawWorkflow) GetWorkflowAnonymizeHandling() bool`

GetWorkflowAnonymizeHandling returns the WorkflowAnonymizeHandling field if non-nil, zero value otherwise.

### GetWorkflowAnonymizeHandlingOk

`func (o *ApplicationRawWorkflow) GetWorkflowAnonymizeHandlingOk() (*bool, bool)`

GetWorkflowAnonymizeHandlingOk returns a tuple with the WorkflowAnonymizeHandling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowAnonymizeHandling

`func (o *ApplicationRawWorkflow) SetWorkflowAnonymizeHandling(v bool)`

SetWorkflowAnonymizeHandling sets WorkflowAnonymizeHandling field to given value.

### HasWorkflowAnonymizeHandling

`func (o *ApplicationRawWorkflow) HasWorkflowAnonymizeHandling() bool`

HasWorkflowAnonymizeHandling returns a boolean if a field has been set.

### GetWorkflowProcessingStates

`func (o *ApplicationRawWorkflow) GetWorkflowProcessingStates() []ProcessingState`

GetWorkflowProcessingStates returns the WorkflowProcessingStates field if non-nil, zero value otherwise.

### GetWorkflowProcessingStatesOk

`func (o *ApplicationRawWorkflow) GetWorkflowProcessingStatesOk() (*[]ProcessingState, bool)`

GetWorkflowProcessingStatesOk returns a tuple with the WorkflowProcessingStates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowProcessingStates

`func (o *ApplicationRawWorkflow) SetWorkflowProcessingStates(v []ProcessingState)`

SetWorkflowProcessingStates sets WorkflowProcessingStates field to given value.

### HasWorkflowProcessingStates

`func (o *ApplicationRawWorkflow) HasWorkflowProcessingStates() bool`

HasWorkflowProcessingStates returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



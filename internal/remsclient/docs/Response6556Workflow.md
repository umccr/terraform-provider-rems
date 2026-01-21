# Response6556Workflow

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

### NewResponse6556Workflow

`func NewResponse6556Workflow(workflowId int64, workflowType string, ) *Response6556Workflow`

NewResponse6556Workflow instantiates a new Response6556Workflow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponse6556WorkflowWithDefaults

`func NewResponse6556WorkflowWithDefaults() *Response6556Workflow`

NewResponse6556WorkflowWithDefaults instantiates a new Response6556Workflow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkflowId

`func (o *Response6556Workflow) GetWorkflowId() int64`

GetWorkflowId returns the WorkflowId field if non-nil, zero value otherwise.

### GetWorkflowIdOk

`func (o *Response6556Workflow) GetWorkflowIdOk() (*int64, bool)`

GetWorkflowIdOk returns a tuple with the WorkflowId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowId

`func (o *Response6556Workflow) SetWorkflowId(v int64)`

SetWorkflowId sets WorkflowId field to given value.


### GetWorkflowType

`func (o *Response6556Workflow) GetWorkflowType() string`

GetWorkflowType returns the WorkflowType field if non-nil, zero value otherwise.

### GetWorkflowTypeOk

`func (o *Response6556Workflow) GetWorkflowTypeOk() (*string, bool)`

GetWorkflowTypeOk returns a tuple with the WorkflowType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowType

`func (o *Response6556Workflow) SetWorkflowType(v string)`

SetWorkflowType sets WorkflowType field to given value.


### GetWorkflowDynamicHandlers

`func (o *Response6556Workflow) GetWorkflowDynamicHandlers() []Handler`

GetWorkflowDynamicHandlers returns the WorkflowDynamicHandlers field if non-nil, zero value otherwise.

### GetWorkflowDynamicHandlersOk

`func (o *Response6556Workflow) GetWorkflowDynamicHandlersOk() (*[]Handler, bool)`

GetWorkflowDynamicHandlersOk returns a tuple with the WorkflowDynamicHandlers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowDynamicHandlers

`func (o *Response6556Workflow) SetWorkflowDynamicHandlers(v []Handler)`

SetWorkflowDynamicHandlers sets WorkflowDynamicHandlers field to given value.

### HasWorkflowDynamicHandlers

`func (o *Response6556Workflow) HasWorkflowDynamicHandlers() bool`

HasWorkflowDynamicHandlers returns a boolean if a field has been set.

### GetWorkflowVoting

`func (o *Response6556Workflow) GetWorkflowVoting() WorkflowVoting`

GetWorkflowVoting returns the WorkflowVoting field if non-nil, zero value otherwise.

### GetWorkflowVotingOk

`func (o *Response6556Workflow) GetWorkflowVotingOk() (*WorkflowVoting, bool)`

GetWorkflowVotingOk returns a tuple with the WorkflowVoting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowVoting

`func (o *Response6556Workflow) SetWorkflowVoting(v WorkflowVoting)`

SetWorkflowVoting sets WorkflowVoting field to given value.

### HasWorkflowVoting

`func (o *Response6556Workflow) HasWorkflowVoting() bool`

HasWorkflowVoting returns a boolean if a field has been set.

### GetWorkflowAnonymizeHandling

`func (o *Response6556Workflow) GetWorkflowAnonymizeHandling() bool`

GetWorkflowAnonymizeHandling returns the WorkflowAnonymizeHandling field if non-nil, zero value otherwise.

### GetWorkflowAnonymizeHandlingOk

`func (o *Response6556Workflow) GetWorkflowAnonymizeHandlingOk() (*bool, bool)`

GetWorkflowAnonymizeHandlingOk returns a tuple with the WorkflowAnonymizeHandling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowAnonymizeHandling

`func (o *Response6556Workflow) SetWorkflowAnonymizeHandling(v bool)`

SetWorkflowAnonymizeHandling sets WorkflowAnonymizeHandling field to given value.

### HasWorkflowAnonymizeHandling

`func (o *Response6556Workflow) HasWorkflowAnonymizeHandling() bool`

HasWorkflowAnonymizeHandling returns a boolean if a field has been set.

### GetWorkflowProcessingStates

`func (o *Response6556Workflow) GetWorkflowProcessingStates() []ProcessingState`

GetWorkflowProcessingStates returns the WorkflowProcessingStates field if non-nil, zero value otherwise.

### GetWorkflowProcessingStatesOk

`func (o *Response6556Workflow) GetWorkflowProcessingStatesOk() (*[]ProcessingState, bool)`

GetWorkflowProcessingStatesOk returns a tuple with the WorkflowProcessingStates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowProcessingStates

`func (o *Response6556Workflow) SetWorkflowProcessingStates(v []ProcessingState)`

SetWorkflowProcessingStates sets WorkflowProcessingStates field to given value.

### HasWorkflowProcessingStates

`func (o *Response6556Workflow) HasWorkflowProcessingStates() bool`

HasWorkflowProcessingStates returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# Response6598Workflow

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

### NewResponse6598Workflow

`func NewResponse6598Workflow(workflowId int64, workflowType string, ) *Response6598Workflow`

NewResponse6598Workflow instantiates a new Response6598Workflow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponse6598WorkflowWithDefaults

`func NewResponse6598WorkflowWithDefaults() *Response6598Workflow`

NewResponse6598WorkflowWithDefaults instantiates a new Response6598Workflow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkflowId

`func (o *Response6598Workflow) GetWorkflowId() int64`

GetWorkflowId returns the WorkflowId field if non-nil, zero value otherwise.

### GetWorkflowIdOk

`func (o *Response6598Workflow) GetWorkflowIdOk() (*int64, bool)`

GetWorkflowIdOk returns a tuple with the WorkflowId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowId

`func (o *Response6598Workflow) SetWorkflowId(v int64)`

SetWorkflowId sets WorkflowId field to given value.


### GetWorkflowType

`func (o *Response6598Workflow) GetWorkflowType() string`

GetWorkflowType returns the WorkflowType field if non-nil, zero value otherwise.

### GetWorkflowTypeOk

`func (o *Response6598Workflow) GetWorkflowTypeOk() (*string, bool)`

GetWorkflowTypeOk returns a tuple with the WorkflowType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowType

`func (o *Response6598Workflow) SetWorkflowType(v string)`

SetWorkflowType sets WorkflowType field to given value.


### GetWorkflowDynamicHandlers

`func (o *Response6598Workflow) GetWorkflowDynamicHandlers() []Handler`

GetWorkflowDynamicHandlers returns the WorkflowDynamicHandlers field if non-nil, zero value otherwise.

### GetWorkflowDynamicHandlersOk

`func (o *Response6598Workflow) GetWorkflowDynamicHandlersOk() (*[]Handler, bool)`

GetWorkflowDynamicHandlersOk returns a tuple with the WorkflowDynamicHandlers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowDynamicHandlers

`func (o *Response6598Workflow) SetWorkflowDynamicHandlers(v []Handler)`

SetWorkflowDynamicHandlers sets WorkflowDynamicHandlers field to given value.

### HasWorkflowDynamicHandlers

`func (o *Response6598Workflow) HasWorkflowDynamicHandlers() bool`

HasWorkflowDynamicHandlers returns a boolean if a field has been set.

### GetWorkflowVoting

`func (o *Response6598Workflow) GetWorkflowVoting() WorkflowVoting`

GetWorkflowVoting returns the WorkflowVoting field if non-nil, zero value otherwise.

### GetWorkflowVotingOk

`func (o *Response6598Workflow) GetWorkflowVotingOk() (*WorkflowVoting, bool)`

GetWorkflowVotingOk returns a tuple with the WorkflowVoting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowVoting

`func (o *Response6598Workflow) SetWorkflowVoting(v WorkflowVoting)`

SetWorkflowVoting sets WorkflowVoting field to given value.

### HasWorkflowVoting

`func (o *Response6598Workflow) HasWorkflowVoting() bool`

HasWorkflowVoting returns a boolean if a field has been set.

### GetWorkflowAnonymizeHandling

`func (o *Response6598Workflow) GetWorkflowAnonymizeHandling() bool`

GetWorkflowAnonymizeHandling returns the WorkflowAnonymizeHandling field if non-nil, zero value otherwise.

### GetWorkflowAnonymizeHandlingOk

`func (o *Response6598Workflow) GetWorkflowAnonymizeHandlingOk() (*bool, bool)`

GetWorkflowAnonymizeHandlingOk returns a tuple with the WorkflowAnonymizeHandling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowAnonymizeHandling

`func (o *Response6598Workflow) SetWorkflowAnonymizeHandling(v bool)`

SetWorkflowAnonymizeHandling sets WorkflowAnonymizeHandling field to given value.

### HasWorkflowAnonymizeHandling

`func (o *Response6598Workflow) HasWorkflowAnonymizeHandling() bool`

HasWorkflowAnonymizeHandling returns a boolean if a field has been set.

### GetWorkflowProcessingStates

`func (o *Response6598Workflow) GetWorkflowProcessingStates() []ProcessingState`

GetWorkflowProcessingStates returns the WorkflowProcessingStates field if non-nil, zero value otherwise.

### GetWorkflowProcessingStatesOk

`func (o *Response6598Workflow) GetWorkflowProcessingStatesOk() (*[]ProcessingState, bool)`

GetWorkflowProcessingStatesOk returns a tuple with the WorkflowProcessingStates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowProcessingStates

`func (o *Response6598Workflow) SetWorkflowProcessingStates(v []ProcessingState)`

SetWorkflowProcessingStates sets WorkflowProcessingStates field to given value.

### HasWorkflowProcessingStates

`func (o *Response6598Workflow) HasWorkflowProcessingStates() bool`

HasWorkflowProcessingStates returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



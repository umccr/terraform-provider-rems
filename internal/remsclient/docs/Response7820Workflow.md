# Response7820Workflow

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

### NewResponse7820Workflow

`func NewResponse7820Workflow(workflowId int64, workflowType string, ) *Response7820Workflow`

NewResponse7820Workflow instantiates a new Response7820Workflow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponse7820WorkflowWithDefaults

`func NewResponse7820WorkflowWithDefaults() *Response7820Workflow`

NewResponse7820WorkflowWithDefaults instantiates a new Response7820Workflow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkflowId

`func (o *Response7820Workflow) GetWorkflowId() int64`

GetWorkflowId returns the WorkflowId field if non-nil, zero value otherwise.

### GetWorkflowIdOk

`func (o *Response7820Workflow) GetWorkflowIdOk() (*int64, bool)`

GetWorkflowIdOk returns a tuple with the WorkflowId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowId

`func (o *Response7820Workflow) SetWorkflowId(v int64)`

SetWorkflowId sets WorkflowId field to given value.


### GetWorkflowType

`func (o *Response7820Workflow) GetWorkflowType() string`

GetWorkflowType returns the WorkflowType field if non-nil, zero value otherwise.

### GetWorkflowTypeOk

`func (o *Response7820Workflow) GetWorkflowTypeOk() (*string, bool)`

GetWorkflowTypeOk returns a tuple with the WorkflowType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowType

`func (o *Response7820Workflow) SetWorkflowType(v string)`

SetWorkflowType sets WorkflowType field to given value.


### GetWorkflowDynamicHandlers

`func (o *Response7820Workflow) GetWorkflowDynamicHandlers() []Handler`

GetWorkflowDynamicHandlers returns the WorkflowDynamicHandlers field if non-nil, zero value otherwise.

### GetWorkflowDynamicHandlersOk

`func (o *Response7820Workflow) GetWorkflowDynamicHandlersOk() (*[]Handler, bool)`

GetWorkflowDynamicHandlersOk returns a tuple with the WorkflowDynamicHandlers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowDynamicHandlers

`func (o *Response7820Workflow) SetWorkflowDynamicHandlers(v []Handler)`

SetWorkflowDynamicHandlers sets WorkflowDynamicHandlers field to given value.

### HasWorkflowDynamicHandlers

`func (o *Response7820Workflow) HasWorkflowDynamicHandlers() bool`

HasWorkflowDynamicHandlers returns a boolean if a field has been set.

### GetWorkflowVoting

`func (o *Response7820Workflow) GetWorkflowVoting() WorkflowVoting`

GetWorkflowVoting returns the WorkflowVoting field if non-nil, zero value otherwise.

### GetWorkflowVotingOk

`func (o *Response7820Workflow) GetWorkflowVotingOk() (*WorkflowVoting, bool)`

GetWorkflowVotingOk returns a tuple with the WorkflowVoting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowVoting

`func (o *Response7820Workflow) SetWorkflowVoting(v WorkflowVoting)`

SetWorkflowVoting sets WorkflowVoting field to given value.

### HasWorkflowVoting

`func (o *Response7820Workflow) HasWorkflowVoting() bool`

HasWorkflowVoting returns a boolean if a field has been set.

### GetWorkflowAnonymizeHandling

`func (o *Response7820Workflow) GetWorkflowAnonymizeHandling() bool`

GetWorkflowAnonymizeHandling returns the WorkflowAnonymizeHandling field if non-nil, zero value otherwise.

### GetWorkflowAnonymizeHandlingOk

`func (o *Response7820Workflow) GetWorkflowAnonymizeHandlingOk() (*bool, bool)`

GetWorkflowAnonymizeHandlingOk returns a tuple with the WorkflowAnonymizeHandling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowAnonymizeHandling

`func (o *Response7820Workflow) SetWorkflowAnonymizeHandling(v bool)`

SetWorkflowAnonymizeHandling sets WorkflowAnonymizeHandling field to given value.

### HasWorkflowAnonymizeHandling

`func (o *Response7820Workflow) HasWorkflowAnonymizeHandling() bool`

HasWorkflowAnonymizeHandling returns a boolean if a field has been set.

### GetWorkflowProcessingStates

`func (o *Response7820Workflow) GetWorkflowProcessingStates() []ProcessingState`

GetWorkflowProcessingStates returns the WorkflowProcessingStates field if non-nil, zero value otherwise.

### GetWorkflowProcessingStatesOk

`func (o *Response7820Workflow) GetWorkflowProcessingStatesOk() (*[]ProcessingState, bool)`

GetWorkflowProcessingStatesOk returns a tuple with the WorkflowProcessingStates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowProcessingStates

`func (o *Response7820Workflow) SetWorkflowProcessingStates(v []ProcessingState)`

SetWorkflowProcessingStates sets WorkflowProcessingStates field to given value.

### HasWorkflowProcessingStates

`func (o *Response7820Workflow) HasWorkflowProcessingStates() bool`

HasWorkflowProcessingStates returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



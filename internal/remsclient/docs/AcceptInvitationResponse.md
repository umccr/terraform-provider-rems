# AcceptInvitationResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Errors** | Pointer to **[]map[string]interface{}** |  | [optional] 
**InvitationWorkflow** | Pointer to [**AcceptInvitationResponseWorkflow**](AcceptInvitationResponseWorkflow.md) |  | [optional] 

## Methods

### NewAcceptInvitationResponse

`func NewAcceptInvitationResponse(success bool, ) *AcceptInvitationResponse`

NewAcceptInvitationResponse instantiates a new AcceptInvitationResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAcceptInvitationResponseWithDefaults

`func NewAcceptInvitationResponseWithDefaults() *AcceptInvitationResponse`

NewAcceptInvitationResponseWithDefaults instantiates a new AcceptInvitationResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *AcceptInvitationResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AcceptInvitationResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AcceptInvitationResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetErrors

`func (o *AcceptInvitationResponse) GetErrors() []map[string]interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *AcceptInvitationResponse) GetErrorsOk() (*[]map[string]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *AcceptInvitationResponse) SetErrors(v []map[string]interface{})`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *AcceptInvitationResponse) HasErrors() bool`

HasErrors returns a boolean if a field has been set.

### GetInvitationWorkflow

`func (o *AcceptInvitationResponse) GetInvitationWorkflow() AcceptInvitationResponseWorkflow`

GetInvitationWorkflow returns the InvitationWorkflow field if non-nil, zero value otherwise.

### GetInvitationWorkflowOk

`func (o *AcceptInvitationResponse) GetInvitationWorkflowOk() (*AcceptInvitationResponseWorkflow, bool)`

GetInvitationWorkflowOk returns a tuple with the InvitationWorkflow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitationWorkflow

`func (o *AcceptInvitationResponse) SetInvitationWorkflow(v AcceptInvitationResponseWorkflow)`

SetInvitationWorkflow sets InvitationWorkflow field to given value.

### HasInvitationWorkflow

`func (o *AcceptInvitationResponse) HasInvitationWorkflow() bool`

HasInvitationWorkflow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



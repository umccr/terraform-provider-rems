# CreateInvitationResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**InvitationId** | Pointer to **int64** |  | [optional] 
**Errors** | Pointer to **[]map[string]interface{}** |  | [optional] 

## Methods

### NewCreateInvitationResponse

`func NewCreateInvitationResponse(success bool, ) *CreateInvitationResponse`

NewCreateInvitationResponse instantiates a new CreateInvitationResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateInvitationResponseWithDefaults

`func NewCreateInvitationResponseWithDefaults() *CreateInvitationResponse`

NewCreateInvitationResponseWithDefaults instantiates a new CreateInvitationResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *CreateInvitationResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *CreateInvitationResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *CreateInvitationResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetInvitationId

`func (o *CreateInvitationResponse) GetInvitationId() int64`

GetInvitationId returns the InvitationId field if non-nil, zero value otherwise.

### GetInvitationIdOk

`func (o *CreateInvitationResponse) GetInvitationIdOk() (*int64, bool)`

GetInvitationIdOk returns a tuple with the InvitationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitationId

`func (o *CreateInvitationResponse) SetInvitationId(v int64)`

SetInvitationId sets InvitationId field to given value.

### HasInvitationId

`func (o *CreateInvitationResponse) HasInvitationId() bool`

HasInvitationId returns a boolean if a field has been set.

### GetErrors

`func (o *CreateInvitationResponse) GetErrors() []map[string]interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *CreateInvitationResponse) GetErrorsOk() (*[]map[string]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *CreateInvitationResponse) SetErrors(v []map[string]interface{})`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *CreateInvitationResponse) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



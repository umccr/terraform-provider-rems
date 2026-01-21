# AcceptInvitationResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Errors** | Pointer to **[]map[string]interface{}** |  | [optional] 
**Warnings** | Pointer to **[]map[string]interface{}** |  | [optional] 
**ApplicationId** | Pointer to **int64** |  | [optional] 

## Methods

### NewAcceptInvitationResult

`func NewAcceptInvitationResult(success bool, ) *AcceptInvitationResult`

NewAcceptInvitationResult instantiates a new AcceptInvitationResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAcceptInvitationResultWithDefaults

`func NewAcceptInvitationResultWithDefaults() *AcceptInvitationResult`

NewAcceptInvitationResultWithDefaults instantiates a new AcceptInvitationResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *AcceptInvitationResult) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AcceptInvitationResult) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AcceptInvitationResult) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetErrors

`func (o *AcceptInvitationResult) GetErrors() []map[string]interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *AcceptInvitationResult) GetErrorsOk() (*[]map[string]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *AcceptInvitationResult) SetErrors(v []map[string]interface{})`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *AcceptInvitationResult) HasErrors() bool`

HasErrors returns a boolean if a field has been set.

### GetWarnings

`func (o *AcceptInvitationResult) GetWarnings() []map[string]interface{}`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *AcceptInvitationResult) GetWarningsOk() (*[]map[string]interface{}, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *AcceptInvitationResult) SetWarnings(v []map[string]interface{})`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *AcceptInvitationResult) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.

### GetApplicationId

`func (o *AcceptInvitationResult) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *AcceptInvitationResult) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *AcceptInvitationResult) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.

### HasApplicationId

`func (o *AcceptInvitationResult) HasApplicationId() bool`

HasApplicationId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



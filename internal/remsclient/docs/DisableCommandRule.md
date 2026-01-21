# DisableCommandRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Command** | **string** |  | 
**WhenState** | Pointer to **[]string** |  | [optional] 
**WhenRole** | Pointer to **[]string** |  | [optional] 

## Methods

### NewDisableCommandRule

`func NewDisableCommandRule(command string, ) *DisableCommandRule`

NewDisableCommandRule instantiates a new DisableCommandRule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDisableCommandRuleWithDefaults

`func NewDisableCommandRuleWithDefaults() *DisableCommandRule`

NewDisableCommandRuleWithDefaults instantiates a new DisableCommandRule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCommand

`func (o *DisableCommandRule) GetCommand() string`

GetCommand returns the Command field if non-nil, zero value otherwise.

### GetCommandOk

`func (o *DisableCommandRule) GetCommandOk() (*string, bool)`

GetCommandOk returns a tuple with the Command field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommand

`func (o *DisableCommandRule) SetCommand(v string)`

SetCommand sets Command field to given value.


### GetWhenState

`func (o *DisableCommandRule) GetWhenState() []string`

GetWhenState returns the WhenState field if non-nil, zero value otherwise.

### GetWhenStateOk

`func (o *DisableCommandRule) GetWhenStateOk() (*[]string, bool)`

GetWhenStateOk returns a tuple with the WhenState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWhenState

`func (o *DisableCommandRule) SetWhenState(v []string)`

SetWhenState sets WhenState field to given value.

### HasWhenState

`func (o *DisableCommandRule) HasWhenState() bool`

HasWhenState returns a boolean if a field has been set.

### GetWhenRole

`func (o *DisableCommandRule) GetWhenRole() []string`

GetWhenRole returns the WhenRole field if non-nil, zero value otherwise.

### GetWhenRoleOk

`func (o *DisableCommandRule) GetWhenRoleOk() (*[]string, bool)`

GetWhenRoleOk returns a tuple with the WhenRole field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWhenRole

`func (o *DisableCommandRule) SetWhenRole(v []string)`

SetWhenRole sets WhenRole field to given value.

### HasWhenRole

`func (o *DisableCommandRule) HasWhenRole() bool`

HasWhenRole returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



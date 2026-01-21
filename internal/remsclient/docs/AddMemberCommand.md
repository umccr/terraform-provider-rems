# AddMemberCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**Member** | [**User**](User.md) |  | 

## Methods

### NewAddMemberCommand

`func NewAddMemberCommand(applicationId int64, member User, ) *AddMemberCommand`

NewAddMemberCommand instantiates a new AddMemberCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddMemberCommandWithDefaults

`func NewAddMemberCommandWithDefaults() *AddMemberCommand`

NewAddMemberCommandWithDefaults instantiates a new AddMemberCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *AddMemberCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *AddMemberCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *AddMemberCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetMember

`func (o *AddMemberCommand) GetMember() User`

GetMember returns the Member field if non-nil, zero value otherwise.

### GetMemberOk

`func (o *AddMemberCommand) GetMemberOk() (*User, bool)`

GetMemberOk returns a tuple with the Member field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMember

`func (o *AddMemberCommand) SetMember(v User)`

SetMember sets Member field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



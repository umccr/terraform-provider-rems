# InviteMemberCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**Member** | [**InviteMemberCommandMember**](InviteMemberCommandMember.md) |  | 

## Methods

### NewInviteMemberCommand

`func NewInviteMemberCommand(applicationId int64, member InviteMemberCommandMember, ) *InviteMemberCommand`

NewInviteMemberCommand instantiates a new InviteMemberCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInviteMemberCommandWithDefaults

`func NewInviteMemberCommandWithDefaults() *InviteMemberCommand`

NewInviteMemberCommandWithDefaults instantiates a new InviteMemberCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *InviteMemberCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *InviteMemberCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *InviteMemberCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetMember

`func (o *InviteMemberCommand) GetMember() InviteMemberCommandMember`

GetMember returns the Member field if non-nil, zero value otherwise.

### GetMemberOk

`func (o *InviteMemberCommand) GetMemberOk() (*InviteMemberCommandMember, bool)`

GetMemberOk returns a tuple with the Member field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMember

`func (o *InviteMemberCommand) SetMember(v InviteMemberCommandMember)`

SetMember sets Member field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



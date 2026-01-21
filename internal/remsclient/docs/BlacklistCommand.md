# BlacklistCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BlacklistResource** | [**BlacklistCommandResource**](BlacklistCommandResource.md) |  | 
**BlacklistUser** | [**User**](User.md) |  | 
**Comment** | **string** |  | 

## Methods

### NewBlacklistCommand

`func NewBlacklistCommand(blacklistResource BlacklistCommandResource, blacklistUser User, comment string, ) *BlacklistCommand`

NewBlacklistCommand instantiates a new BlacklistCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBlacklistCommandWithDefaults

`func NewBlacklistCommandWithDefaults() *BlacklistCommand`

NewBlacklistCommandWithDefaults instantiates a new BlacklistCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBlacklistResource

`func (o *BlacklistCommand) GetBlacklistResource() BlacklistCommandResource`

GetBlacklistResource returns the BlacklistResource field if non-nil, zero value otherwise.

### GetBlacklistResourceOk

`func (o *BlacklistCommand) GetBlacklistResourceOk() (*BlacklistCommandResource, bool)`

GetBlacklistResourceOk returns a tuple with the BlacklistResource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlacklistResource

`func (o *BlacklistCommand) SetBlacklistResource(v BlacklistCommandResource)`

SetBlacklistResource sets BlacklistResource field to given value.


### GetBlacklistUser

`func (o *BlacklistCommand) GetBlacklistUser() User`

GetBlacklistUser returns the BlacklistUser field if non-nil, zero value otherwise.

### GetBlacklistUserOk

`func (o *BlacklistCommand) GetBlacklistUserOk() (*User, bool)`

GetBlacklistUserOk returns a tuple with the BlacklistUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlacklistUser

`func (o *BlacklistCommand) SetBlacklistUser(v User)`

SetBlacklistUser sets BlacklistUser field to given value.


### GetComment

`func (o *BlacklistCommand) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *BlacklistCommand) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *BlacklistCommand) SetComment(v string)`

SetComment sets Comment field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



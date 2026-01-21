# UninviteMemberCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**Comment** | Pointer to **string** |  | [optional] 
**Attachments** | Pointer to [**[]CommandAttachment**](CommandAttachment.md) |  | [optional] 
**Member** | [**UninviteMemberCommandMember**](UninviteMemberCommandMember.md) |  | 

## Methods

### NewUninviteMemberCommand

`func NewUninviteMemberCommand(applicationId int64, member UninviteMemberCommandMember, ) *UninviteMemberCommand`

NewUninviteMemberCommand instantiates a new UninviteMemberCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUninviteMemberCommandWithDefaults

`func NewUninviteMemberCommandWithDefaults() *UninviteMemberCommand`

NewUninviteMemberCommandWithDefaults instantiates a new UninviteMemberCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *UninviteMemberCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *UninviteMemberCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *UninviteMemberCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetComment

`func (o *UninviteMemberCommand) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *UninviteMemberCommand) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *UninviteMemberCommand) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *UninviteMemberCommand) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetAttachments

`func (o *UninviteMemberCommand) GetAttachments() []CommandAttachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *UninviteMemberCommand) GetAttachmentsOk() (*[]CommandAttachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *UninviteMemberCommand) SetAttachments(v []CommandAttachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *UninviteMemberCommand) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetMember

`func (o *UninviteMemberCommand) GetMember() UninviteMemberCommandMember`

GetMember returns the Member field if non-nil, zero value otherwise.

### GetMemberOk

`func (o *UninviteMemberCommand) GetMemberOk() (*UninviteMemberCommandMember, bool)`

GetMemberOk returns a tuple with the Member field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMember

`func (o *UninviteMemberCommand) SetMember(v UninviteMemberCommandMember)`

SetMember sets Member field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



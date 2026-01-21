# ChangeApplicantCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**Comment** | Pointer to **string** |  | [optional] 
**Attachments** | Pointer to [**[]CommandAttachment**](CommandAttachment.md) |  | [optional] 
**Member** | [**User**](User.md) |  | 

## Methods

### NewChangeApplicantCommand

`func NewChangeApplicantCommand(applicationId int64, member User, ) *ChangeApplicantCommand`

NewChangeApplicantCommand instantiates a new ChangeApplicantCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChangeApplicantCommandWithDefaults

`func NewChangeApplicantCommandWithDefaults() *ChangeApplicantCommand`

NewChangeApplicantCommandWithDefaults instantiates a new ChangeApplicantCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *ChangeApplicantCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *ChangeApplicantCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *ChangeApplicantCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetComment

`func (o *ChangeApplicantCommand) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *ChangeApplicantCommand) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *ChangeApplicantCommand) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *ChangeApplicantCommand) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetAttachments

`func (o *ChangeApplicantCommand) GetAttachments() []CommandAttachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *ChangeApplicantCommand) GetAttachmentsOk() (*[]CommandAttachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *ChangeApplicantCommand) SetAttachments(v []CommandAttachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *ChangeApplicantCommand) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetMember

`func (o *ChangeApplicantCommand) GetMember() User`

GetMember returns the Member field if non-nil, zero value otherwise.

### GetMemberOk

`func (o *ChangeApplicantCommand) GetMemberOk() (*User, bool)`

GetMemberOk returns a tuple with the Member field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMember

`func (o *ChangeApplicantCommand) SetMember(v User)`

SetMember sets Member field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# InviteReviewerCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**Comment** | Pointer to **string** |  | [optional] 
**Attachments** | Pointer to [**[]CommandAttachment**](CommandAttachment.md) |  | [optional] 
**Reviewer** | [**InviteReviewerCommandReviewer**](InviteReviewerCommandReviewer.md) |  | 

## Methods

### NewInviteReviewerCommand

`func NewInviteReviewerCommand(applicationId int64, reviewer InviteReviewerCommandReviewer, ) *InviteReviewerCommand`

NewInviteReviewerCommand instantiates a new InviteReviewerCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInviteReviewerCommandWithDefaults

`func NewInviteReviewerCommandWithDefaults() *InviteReviewerCommand`

NewInviteReviewerCommandWithDefaults instantiates a new InviteReviewerCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *InviteReviewerCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *InviteReviewerCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *InviteReviewerCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetComment

`func (o *InviteReviewerCommand) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *InviteReviewerCommand) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *InviteReviewerCommand) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *InviteReviewerCommand) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetAttachments

`func (o *InviteReviewerCommand) GetAttachments() []CommandAttachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *InviteReviewerCommand) GetAttachmentsOk() (*[]CommandAttachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *InviteReviewerCommand) SetAttachments(v []CommandAttachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *InviteReviewerCommand) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetReviewer

`func (o *InviteReviewerCommand) GetReviewer() InviteReviewerCommandReviewer`

GetReviewer returns the Reviewer field if non-nil, zero value otherwise.

### GetReviewerOk

`func (o *InviteReviewerCommand) GetReviewerOk() (*InviteReviewerCommandReviewer, bool)`

GetReviewerOk returns a tuple with the Reviewer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewer

`func (o *InviteReviewerCommand) SetReviewer(v InviteReviewerCommandReviewer)`

SetReviewer sets Reviewer field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



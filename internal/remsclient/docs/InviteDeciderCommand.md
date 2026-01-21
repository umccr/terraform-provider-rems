# InviteDeciderCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**Comment** | Pointer to **string** |  | [optional] 
**Attachments** | Pointer to [**[]CommandAttachment**](CommandAttachment.md) |  | [optional] 
**Decider** | [**InviteDeciderCommandDecider**](InviteDeciderCommandDecider.md) |  | 

## Methods

### NewInviteDeciderCommand

`func NewInviteDeciderCommand(applicationId int64, decider InviteDeciderCommandDecider, ) *InviteDeciderCommand`

NewInviteDeciderCommand instantiates a new InviteDeciderCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInviteDeciderCommandWithDefaults

`func NewInviteDeciderCommandWithDefaults() *InviteDeciderCommand`

NewInviteDeciderCommandWithDefaults instantiates a new InviteDeciderCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *InviteDeciderCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *InviteDeciderCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *InviteDeciderCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetComment

`func (o *InviteDeciderCommand) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *InviteDeciderCommand) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *InviteDeciderCommand) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *InviteDeciderCommand) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetAttachments

`func (o *InviteDeciderCommand) GetAttachments() []CommandAttachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *InviteDeciderCommand) GetAttachmentsOk() (*[]CommandAttachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *InviteDeciderCommand) SetAttachments(v []CommandAttachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *InviteDeciderCommand) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetDecider

`func (o *InviteDeciderCommand) GetDecider() InviteDeciderCommandDecider`

GetDecider returns the Decider field if non-nil, zero value otherwise.

### GetDeciderOk

`func (o *InviteDeciderCommand) GetDeciderOk() (*InviteDeciderCommandDecider, bool)`

GetDeciderOk returns a tuple with the Decider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecider

`func (o *InviteDeciderCommand) SetDecider(v InviteDeciderCommandDecider)`

SetDecider sets Decider field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



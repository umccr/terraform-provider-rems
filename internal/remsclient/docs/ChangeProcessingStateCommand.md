# ChangeProcessingStateCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**Comment** | Pointer to **string** |  | [optional] 
**Attachments** | Pointer to [**[]CommandAttachment**](CommandAttachment.md) |  | [optional] 
**ProcessingState** | **string** |  | 
**Public** | **bool** |  | 

## Methods

### NewChangeProcessingStateCommand

`func NewChangeProcessingStateCommand(applicationId int64, processingState string, public bool, ) *ChangeProcessingStateCommand`

NewChangeProcessingStateCommand instantiates a new ChangeProcessingStateCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChangeProcessingStateCommandWithDefaults

`func NewChangeProcessingStateCommandWithDefaults() *ChangeProcessingStateCommand`

NewChangeProcessingStateCommandWithDefaults instantiates a new ChangeProcessingStateCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *ChangeProcessingStateCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *ChangeProcessingStateCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *ChangeProcessingStateCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetComment

`func (o *ChangeProcessingStateCommand) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *ChangeProcessingStateCommand) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *ChangeProcessingStateCommand) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *ChangeProcessingStateCommand) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetAttachments

`func (o *ChangeProcessingStateCommand) GetAttachments() []CommandAttachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *ChangeProcessingStateCommand) GetAttachmentsOk() (*[]CommandAttachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *ChangeProcessingStateCommand) SetAttachments(v []CommandAttachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *ChangeProcessingStateCommand) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetProcessingState

`func (o *ChangeProcessingStateCommand) GetProcessingState() string`

GetProcessingState returns the ProcessingState field if non-nil, zero value otherwise.

### GetProcessingStateOk

`func (o *ChangeProcessingStateCommand) GetProcessingStateOk() (*string, bool)`

GetProcessingStateOk returns a tuple with the ProcessingState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingState

`func (o *ChangeProcessingStateCommand) SetProcessingState(v string)`

SetProcessingState sets ProcessingState field to given value.


### GetPublic

`func (o *ChangeProcessingStateCommand) GetPublic() bool`

GetPublic returns the Public field if non-nil, zero value otherwise.

### GetPublicOk

`func (o *ChangeProcessingStateCommand) GetPublicOk() (*bool, bool)`

GetPublicOk returns a tuple with the Public field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublic

`func (o *ChangeProcessingStateCommand) SetPublic(v bool)`

SetPublic sets Public field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ReviewCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**Comment** | Pointer to **string** |  | [optional] 
**Attachments** | Pointer to [**[]CommandAttachment**](CommandAttachment.md) |  | [optional] 

## Methods

### NewReviewCommand

`func NewReviewCommand(applicationId int64, ) *ReviewCommand`

NewReviewCommand instantiates a new ReviewCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReviewCommandWithDefaults

`func NewReviewCommandWithDefaults() *ReviewCommand`

NewReviewCommandWithDefaults instantiates a new ReviewCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *ReviewCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *ReviewCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *ReviewCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetComment

`func (o *ReviewCommand) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *ReviewCommand) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *ReviewCommand) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *ReviewCommand) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetAttachments

`func (o *ReviewCommand) GetAttachments() []CommandAttachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *ReviewCommand) GetAttachmentsOk() (*[]CommandAttachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *ReviewCommand) SetAttachments(v []CommandAttachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *ReviewCommand) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



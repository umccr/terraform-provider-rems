# RemarkCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**Comment** | Pointer to **string** |  | [optional] 
**Attachments** | Pointer to [**[]CommandAttachment**](CommandAttachment.md) |  | [optional] 
**Public** | **bool** |  | 

## Methods

### NewRemarkCommand

`func NewRemarkCommand(applicationId int64, public bool, ) *RemarkCommand`

NewRemarkCommand instantiates a new RemarkCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRemarkCommandWithDefaults

`func NewRemarkCommandWithDefaults() *RemarkCommand`

NewRemarkCommandWithDefaults instantiates a new RemarkCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *RemarkCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *RemarkCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *RemarkCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetComment

`func (o *RemarkCommand) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *RemarkCommand) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *RemarkCommand) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *RemarkCommand) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetAttachments

`func (o *RemarkCommand) GetAttachments() []CommandAttachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *RemarkCommand) GetAttachmentsOk() (*[]CommandAttachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *RemarkCommand) SetAttachments(v []CommandAttachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *RemarkCommand) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetPublic

`func (o *RemarkCommand) GetPublic() bool`

GetPublic returns the Public field if non-nil, zero value otherwise.

### GetPublicOk

`func (o *RemarkCommand) GetPublicOk() (*bool, bool)`

GetPublicOk returns a tuple with the Public field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublic

`func (o *RemarkCommand) SetPublic(v bool)`

SetPublic sets Public field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



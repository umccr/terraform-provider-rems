# RedactAttachmentsCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**Comment** | Pointer to **string** |  | [optional] 
**Attachments** | Pointer to [**[]CommandAttachment**](CommandAttachment.md) |  | [optional] 
**RedactedAttachments** | [**[]CommandAttachment**](CommandAttachment.md) |  | 
**Public** | **bool** |  | 

## Methods

### NewRedactAttachmentsCommand

`func NewRedactAttachmentsCommand(applicationId int64, redactedAttachments []CommandAttachment, public bool, ) *RedactAttachmentsCommand`

NewRedactAttachmentsCommand instantiates a new RedactAttachmentsCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRedactAttachmentsCommandWithDefaults

`func NewRedactAttachmentsCommandWithDefaults() *RedactAttachmentsCommand`

NewRedactAttachmentsCommandWithDefaults instantiates a new RedactAttachmentsCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *RedactAttachmentsCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *RedactAttachmentsCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *RedactAttachmentsCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetComment

`func (o *RedactAttachmentsCommand) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *RedactAttachmentsCommand) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *RedactAttachmentsCommand) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *RedactAttachmentsCommand) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetAttachments

`func (o *RedactAttachmentsCommand) GetAttachments() []CommandAttachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *RedactAttachmentsCommand) GetAttachmentsOk() (*[]CommandAttachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *RedactAttachmentsCommand) SetAttachments(v []CommandAttachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *RedactAttachmentsCommand) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetRedactedAttachments

`func (o *RedactAttachmentsCommand) GetRedactedAttachments() []CommandAttachment`

GetRedactedAttachments returns the RedactedAttachments field if non-nil, zero value otherwise.

### GetRedactedAttachmentsOk

`func (o *RedactAttachmentsCommand) GetRedactedAttachmentsOk() (*[]CommandAttachment, bool)`

GetRedactedAttachmentsOk returns a tuple with the RedactedAttachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedactedAttachments

`func (o *RedactAttachmentsCommand) SetRedactedAttachments(v []CommandAttachment)`

SetRedactedAttachments sets RedactedAttachments field to given value.


### GetPublic

`func (o *RedactAttachmentsCommand) GetPublic() bool`

GetPublic returns the Public field if non-nil, zero value otherwise.

### GetPublicOk

`func (o *RedactAttachmentsCommand) GetPublicOk() (*bool, bool)`

GetPublicOk returns a tuple with the Public field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublic

`func (o *RedactAttachmentsCommand) SetPublic(v bool)`

SetPublic sets Public field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



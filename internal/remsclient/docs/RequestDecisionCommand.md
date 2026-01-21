# RequestDecisionCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**Comment** | Pointer to **string** |  | [optional] 
**Attachments** | Pointer to [**[]CommandAttachment**](CommandAttachment.md) |  | [optional] 
**Deciders** | **[]string** |  | 

## Methods

### NewRequestDecisionCommand

`func NewRequestDecisionCommand(applicationId int64, deciders []string, ) *RequestDecisionCommand`

NewRequestDecisionCommand instantiates a new RequestDecisionCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRequestDecisionCommandWithDefaults

`func NewRequestDecisionCommandWithDefaults() *RequestDecisionCommand`

NewRequestDecisionCommandWithDefaults instantiates a new RequestDecisionCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *RequestDecisionCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *RequestDecisionCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *RequestDecisionCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetComment

`func (o *RequestDecisionCommand) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *RequestDecisionCommand) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *RequestDecisionCommand) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *RequestDecisionCommand) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetAttachments

`func (o *RequestDecisionCommand) GetAttachments() []CommandAttachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *RequestDecisionCommand) GetAttachmentsOk() (*[]CommandAttachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *RequestDecisionCommand) SetAttachments(v []CommandAttachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *RequestDecisionCommand) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetDeciders

`func (o *RequestDecisionCommand) GetDeciders() []string`

GetDeciders returns the Deciders field if non-nil, zero value otherwise.

### GetDecidersOk

`func (o *RequestDecisionCommand) GetDecidersOk() (*[]string, bool)`

GetDecidersOk returns a tuple with the Deciders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeciders

`func (o *RequestDecisionCommand) SetDeciders(v []string)`

SetDeciders sets Deciders field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



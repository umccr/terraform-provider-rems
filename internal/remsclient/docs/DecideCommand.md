# DecideCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**Comment** | Pointer to **string** |  | [optional] 
**Attachments** | Pointer to [**[]CommandAttachment**](CommandAttachment.md) |  | [optional] 
**Decision** | **string** |  | 

## Methods

### NewDecideCommand

`func NewDecideCommand(applicationId int64, decision string, ) *DecideCommand`

NewDecideCommand instantiates a new DecideCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDecideCommandWithDefaults

`func NewDecideCommandWithDefaults() *DecideCommand`

NewDecideCommandWithDefaults instantiates a new DecideCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *DecideCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *DecideCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *DecideCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetComment

`func (o *DecideCommand) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *DecideCommand) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *DecideCommand) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *DecideCommand) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetAttachments

`func (o *DecideCommand) GetAttachments() []CommandAttachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *DecideCommand) GetAttachmentsOk() (*[]CommandAttachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *DecideCommand) SetAttachments(v []CommandAttachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *DecideCommand) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetDecision

`func (o *DecideCommand) GetDecision() string`

GetDecision returns the Decision field if non-nil, zero value otherwise.

### GetDecisionOk

`func (o *DecideCommand) GetDecisionOk() (*string, bool)`

GetDecisionOk returns a tuple with the Decision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecision

`func (o *DecideCommand) SetDecision(v string)`

SetDecision sets Decision field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



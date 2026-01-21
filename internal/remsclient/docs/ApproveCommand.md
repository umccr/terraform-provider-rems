# ApproveCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**Comment** | Pointer to **string** |  | [optional] 
**Attachments** | Pointer to [**[]CommandAttachment**](CommandAttachment.md) |  | [optional] 
**EntitlementEnd** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewApproveCommand

`func NewApproveCommand(applicationId int64, ) *ApproveCommand`

NewApproveCommand instantiates a new ApproveCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApproveCommandWithDefaults

`func NewApproveCommandWithDefaults() *ApproveCommand`

NewApproveCommandWithDefaults instantiates a new ApproveCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *ApproveCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *ApproveCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *ApproveCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetComment

`func (o *ApproveCommand) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *ApproveCommand) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *ApproveCommand) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *ApproveCommand) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetAttachments

`func (o *ApproveCommand) GetAttachments() []CommandAttachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *ApproveCommand) GetAttachmentsOk() (*[]CommandAttachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *ApproveCommand) SetAttachments(v []CommandAttachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *ApproveCommand) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetEntitlementEnd

`func (o *ApproveCommand) GetEntitlementEnd() time.Time`

GetEntitlementEnd returns the EntitlementEnd field if non-nil, zero value otherwise.

### GetEntitlementEndOk

`func (o *ApproveCommand) GetEntitlementEndOk() (*time.Time, bool)`

GetEntitlementEndOk returns a tuple with the EntitlementEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntitlementEnd

`func (o *ApproveCommand) SetEntitlementEnd(v time.Time)`

SetEntitlementEnd sets EntitlementEnd field to given value.

### HasEntitlementEnd

`func (o *ApproveCommand) HasEntitlementEnd() bool`

HasEntitlementEnd returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ChangeResourcesCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**Comment** | Pointer to **string** |  | [optional] 
**Attachments** | Pointer to [**[]CommandAttachment**](CommandAttachment.md) |  | [optional] 
**CatalogueItemIds** | **[]int64** |  | 

## Methods

### NewChangeResourcesCommand

`func NewChangeResourcesCommand(applicationId int64, catalogueItemIds []int64, ) *ChangeResourcesCommand`

NewChangeResourcesCommand instantiates a new ChangeResourcesCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChangeResourcesCommandWithDefaults

`func NewChangeResourcesCommandWithDefaults() *ChangeResourcesCommand`

NewChangeResourcesCommandWithDefaults instantiates a new ChangeResourcesCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *ChangeResourcesCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *ChangeResourcesCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *ChangeResourcesCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetComment

`func (o *ChangeResourcesCommand) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *ChangeResourcesCommand) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *ChangeResourcesCommand) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *ChangeResourcesCommand) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetAttachments

`func (o *ChangeResourcesCommand) GetAttachments() []CommandAttachment`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *ChangeResourcesCommand) GetAttachmentsOk() (*[]CommandAttachment, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *ChangeResourcesCommand) SetAttachments(v []CommandAttachment)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *ChangeResourcesCommand) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetCatalogueItemIds

`func (o *ChangeResourcesCommand) GetCatalogueItemIds() []int64`

GetCatalogueItemIds returns the CatalogueItemIds field if non-nil, zero value otherwise.

### GetCatalogueItemIdsOk

`func (o *ChangeResourcesCommand) GetCatalogueItemIdsOk() (*[]int64, bool)`

GetCatalogueItemIdsOk returns a tuple with the CatalogueItemIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalogueItemIds

`func (o *ChangeResourcesCommand) SetCatalogueItemIds(v []int64)`

SetCatalogueItemIds sets CatalogueItemIds field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



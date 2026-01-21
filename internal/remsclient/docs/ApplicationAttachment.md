# ApplicationAttachment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AttachmentId** | **int64** |  | 
**AttachmentFilename** | **map[string]interface{}** |  | 
**AttachmentType** | **string** |  | 
**AttachmentEvent** | Pointer to [**Response7799AttachmentsEvent**](Response7799AttachmentsEvent.md) |  | [optional] 
**AttachmentUser** | Pointer to [**UserWithAttributes**](UserWithAttributes.md) |  | [optional] 
**AttachmentRedacted** | Pointer to **bool** |  | [optional] 
**AttachmentCanRedact** | Pointer to **bool** |  | [optional] 

## Methods

### NewApplicationAttachment

`func NewApplicationAttachment(attachmentId int64, attachmentFilename map[string]interface{}, attachmentType string, ) *ApplicationAttachment`

NewApplicationAttachment instantiates a new ApplicationAttachment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationAttachmentWithDefaults

`func NewApplicationAttachmentWithDefaults() *ApplicationAttachment`

NewApplicationAttachmentWithDefaults instantiates a new ApplicationAttachment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttachmentId

`func (o *ApplicationAttachment) GetAttachmentId() int64`

GetAttachmentId returns the AttachmentId field if non-nil, zero value otherwise.

### GetAttachmentIdOk

`func (o *ApplicationAttachment) GetAttachmentIdOk() (*int64, bool)`

GetAttachmentIdOk returns a tuple with the AttachmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentId

`func (o *ApplicationAttachment) SetAttachmentId(v int64)`

SetAttachmentId sets AttachmentId field to given value.


### GetAttachmentFilename

`func (o *ApplicationAttachment) GetAttachmentFilename() map[string]interface{}`

GetAttachmentFilename returns the AttachmentFilename field if non-nil, zero value otherwise.

### GetAttachmentFilenameOk

`func (o *ApplicationAttachment) GetAttachmentFilenameOk() (*map[string]interface{}, bool)`

GetAttachmentFilenameOk returns a tuple with the AttachmentFilename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentFilename

`func (o *ApplicationAttachment) SetAttachmentFilename(v map[string]interface{})`

SetAttachmentFilename sets AttachmentFilename field to given value.


### GetAttachmentType

`func (o *ApplicationAttachment) GetAttachmentType() string`

GetAttachmentType returns the AttachmentType field if non-nil, zero value otherwise.

### GetAttachmentTypeOk

`func (o *ApplicationAttachment) GetAttachmentTypeOk() (*string, bool)`

GetAttachmentTypeOk returns a tuple with the AttachmentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentType

`func (o *ApplicationAttachment) SetAttachmentType(v string)`

SetAttachmentType sets AttachmentType field to given value.


### GetAttachmentEvent

`func (o *ApplicationAttachment) GetAttachmentEvent() Response7799AttachmentsEvent`

GetAttachmentEvent returns the AttachmentEvent field if non-nil, zero value otherwise.

### GetAttachmentEventOk

`func (o *ApplicationAttachment) GetAttachmentEventOk() (*Response7799AttachmentsEvent, bool)`

GetAttachmentEventOk returns a tuple with the AttachmentEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentEvent

`func (o *ApplicationAttachment) SetAttachmentEvent(v Response7799AttachmentsEvent)`

SetAttachmentEvent sets AttachmentEvent field to given value.

### HasAttachmentEvent

`func (o *ApplicationAttachment) HasAttachmentEvent() bool`

HasAttachmentEvent returns a boolean if a field has been set.

### GetAttachmentUser

`func (o *ApplicationAttachment) GetAttachmentUser() UserWithAttributes`

GetAttachmentUser returns the AttachmentUser field if non-nil, zero value otherwise.

### GetAttachmentUserOk

`func (o *ApplicationAttachment) GetAttachmentUserOk() (*UserWithAttributes, bool)`

GetAttachmentUserOk returns a tuple with the AttachmentUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentUser

`func (o *ApplicationAttachment) SetAttachmentUser(v UserWithAttributes)`

SetAttachmentUser sets AttachmentUser field to given value.

### HasAttachmentUser

`func (o *ApplicationAttachment) HasAttachmentUser() bool`

HasAttachmentUser returns a boolean if a field has been set.

### GetAttachmentRedacted

`func (o *ApplicationAttachment) GetAttachmentRedacted() bool`

GetAttachmentRedacted returns the AttachmentRedacted field if non-nil, zero value otherwise.

### GetAttachmentRedactedOk

`func (o *ApplicationAttachment) GetAttachmentRedactedOk() (*bool, bool)`

GetAttachmentRedactedOk returns a tuple with the AttachmentRedacted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentRedacted

`func (o *ApplicationAttachment) SetAttachmentRedacted(v bool)`

SetAttachmentRedacted sets AttachmentRedacted field to given value.

### HasAttachmentRedacted

`func (o *ApplicationAttachment) HasAttachmentRedacted() bool`

HasAttachmentRedacted returns a boolean if a field has been set.

### GetAttachmentCanRedact

`func (o *ApplicationAttachment) GetAttachmentCanRedact() bool`

GetAttachmentCanRedact returns the AttachmentCanRedact field if non-nil, zero value otherwise.

### GetAttachmentCanRedactOk

`func (o *ApplicationAttachment) GetAttachmentCanRedactOk() (*bool, bool)`

GetAttachmentCanRedactOk returns a tuple with the AttachmentCanRedact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentCanRedact

`func (o *ApplicationAttachment) SetAttachmentCanRedact(v bool)`

SetAttachmentCanRedact sets AttachmentCanRedact field to given value.

### HasAttachmentCanRedact

`func (o *ApplicationAttachment) HasAttachmentCanRedact() bool`

HasAttachmentCanRedact returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



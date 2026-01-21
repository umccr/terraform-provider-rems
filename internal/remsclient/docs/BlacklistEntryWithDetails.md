# BlacklistEntryWithDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BlacklistUser** | [**UserWithAttributes**](UserWithAttributes.md) |  | 
**BlacklistResource** | [**Response7960Resource**](Response7960Resource.md) |  | 
**BlacklistComment** | **string** |  | 
**BlacklistAddedBy** | [**UserWithAttributes**](UserWithAttributes.md) |  | 
**BlacklistAddedAt** | **time.Time** |  | 

## Methods

### NewBlacklistEntryWithDetails

`func NewBlacklistEntryWithDetails(blacklistUser UserWithAttributes, blacklistResource Response7960Resource, blacklistComment string, blacklistAddedBy UserWithAttributes, blacklistAddedAt time.Time, ) *BlacklistEntryWithDetails`

NewBlacklistEntryWithDetails instantiates a new BlacklistEntryWithDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBlacklistEntryWithDetailsWithDefaults

`func NewBlacklistEntryWithDetailsWithDefaults() *BlacklistEntryWithDetails`

NewBlacklistEntryWithDetailsWithDefaults instantiates a new BlacklistEntryWithDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBlacklistUser

`func (o *BlacklistEntryWithDetails) GetBlacklistUser() UserWithAttributes`

GetBlacklistUser returns the BlacklistUser field if non-nil, zero value otherwise.

### GetBlacklistUserOk

`func (o *BlacklistEntryWithDetails) GetBlacklistUserOk() (*UserWithAttributes, bool)`

GetBlacklistUserOk returns a tuple with the BlacklistUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlacklistUser

`func (o *BlacklistEntryWithDetails) SetBlacklistUser(v UserWithAttributes)`

SetBlacklistUser sets BlacklistUser field to given value.


### GetBlacklistResource

`func (o *BlacklistEntryWithDetails) GetBlacklistResource() Response7960Resource`

GetBlacklistResource returns the BlacklistResource field if non-nil, zero value otherwise.

### GetBlacklistResourceOk

`func (o *BlacklistEntryWithDetails) GetBlacklistResourceOk() (*Response7960Resource, bool)`

GetBlacklistResourceOk returns a tuple with the BlacklistResource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlacklistResource

`func (o *BlacklistEntryWithDetails) SetBlacklistResource(v Response7960Resource)`

SetBlacklistResource sets BlacklistResource field to given value.


### GetBlacklistComment

`func (o *BlacklistEntryWithDetails) GetBlacklistComment() string`

GetBlacklistComment returns the BlacklistComment field if non-nil, zero value otherwise.

### GetBlacklistCommentOk

`func (o *BlacklistEntryWithDetails) GetBlacklistCommentOk() (*string, bool)`

GetBlacklistCommentOk returns a tuple with the BlacklistComment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlacklistComment

`func (o *BlacklistEntryWithDetails) SetBlacklistComment(v string)`

SetBlacklistComment sets BlacklistComment field to given value.


### GetBlacklistAddedBy

`func (o *BlacklistEntryWithDetails) GetBlacklistAddedBy() UserWithAttributes`

GetBlacklistAddedBy returns the BlacklistAddedBy field if non-nil, zero value otherwise.

### GetBlacklistAddedByOk

`func (o *BlacklistEntryWithDetails) GetBlacklistAddedByOk() (*UserWithAttributes, bool)`

GetBlacklistAddedByOk returns a tuple with the BlacklistAddedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlacklistAddedBy

`func (o *BlacklistEntryWithDetails) SetBlacklistAddedBy(v UserWithAttributes)`

SetBlacklistAddedBy sets BlacklistAddedBy field to given value.


### GetBlacklistAddedAt

`func (o *BlacklistEntryWithDetails) GetBlacklistAddedAt() time.Time`

GetBlacklistAddedAt returns the BlacklistAddedAt field if non-nil, zero value otherwise.

### GetBlacklistAddedAtOk

`func (o *BlacklistEntryWithDetails) GetBlacklistAddedAtOk() (*time.Time, bool)`

GetBlacklistAddedAtOk returns a tuple with the BlacklistAddedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlacklistAddedAt

`func (o *BlacklistEntryWithDetails) SetBlacklistAddedAt(v time.Time)`

SetBlacklistAddedAt sets BlacklistAddedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



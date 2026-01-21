# BlacklistEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BlacklistUser** | [**UserWithAttributes**](UserWithAttributes.md) |  | 
**BlacklistResource** | [**Response7799BlacklistResource**](Response7799BlacklistResource.md) |  | 

## Methods

### NewBlacklistEntry

`func NewBlacklistEntry(blacklistUser UserWithAttributes, blacklistResource Response7799BlacklistResource, ) *BlacklistEntry`

NewBlacklistEntry instantiates a new BlacklistEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBlacklistEntryWithDefaults

`func NewBlacklistEntryWithDefaults() *BlacklistEntry`

NewBlacklistEntryWithDefaults instantiates a new BlacklistEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBlacklistUser

`func (o *BlacklistEntry) GetBlacklistUser() UserWithAttributes`

GetBlacklistUser returns the BlacklistUser field if non-nil, zero value otherwise.

### GetBlacklistUserOk

`func (o *BlacklistEntry) GetBlacklistUserOk() (*UserWithAttributes, bool)`

GetBlacklistUserOk returns a tuple with the BlacklistUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlacklistUser

`func (o *BlacklistEntry) SetBlacklistUser(v UserWithAttributes)`

SetBlacklistUser sets BlacklistUser field to given value.


### GetBlacklistResource

`func (o *BlacklistEntry) GetBlacklistResource() Response7799BlacklistResource`

GetBlacklistResource returns the BlacklistResource field if non-nil, zero value otherwise.

### GetBlacklistResourceOk

`func (o *BlacklistEntry) GetBlacklistResourceOk() (*Response7799BlacklistResource, bool)`

GetBlacklistResourceOk returns a tuple with the BlacklistResource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlacklistResource

`func (o *BlacklistEntry) SetBlacklistResource(v Response7799BlacklistResource)`

SetBlacklistResource sets BlacklistResource field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



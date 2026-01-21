# DuoCode

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Restrictions** | Pointer to [**[]ValidateRequestDuoCodesRestrictions**](ValidateRequestDuoCodesRestrictions.md) |  | [optional] 
**MoreInfo** | Pointer to **map[string]string** | Text values keyed by languages | [optional] 

## Methods

### NewDuoCode

`func NewDuoCode(id string, ) *DuoCode`

NewDuoCode instantiates a new DuoCode object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDuoCodeWithDefaults

`func NewDuoCodeWithDefaults() *DuoCode`

NewDuoCodeWithDefaults instantiates a new DuoCode object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DuoCode) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DuoCode) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DuoCode) SetId(v string)`

SetId sets Id field to given value.


### GetRestrictions

`func (o *DuoCode) GetRestrictions() []ValidateRequestDuoCodesRestrictions`

GetRestrictions returns the Restrictions field if non-nil, zero value otherwise.

### GetRestrictionsOk

`func (o *DuoCode) GetRestrictionsOk() (*[]ValidateRequestDuoCodesRestrictions, bool)`

GetRestrictionsOk returns a tuple with the Restrictions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestrictions

`func (o *DuoCode) SetRestrictions(v []ValidateRequestDuoCodesRestrictions)`

SetRestrictions sets Restrictions field to given value.

### HasRestrictions

`func (o *DuoCode) HasRestrictions() bool`

HasRestrictions returns a boolean if a field has been set.

### GetMoreInfo

`func (o *DuoCode) GetMoreInfo() map[string]string`

GetMoreInfo returns the MoreInfo field if non-nil, zero value otherwise.

### GetMoreInfoOk

`func (o *DuoCode) GetMoreInfoOk() (*map[string]string, bool)`

GetMoreInfoOk returns a tuple with the MoreInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMoreInfo

`func (o *DuoCode) SetMoreInfo(v map[string]string)`

SetMoreInfo sets MoreInfo field to given value.

### HasMoreInfo

`func (o *DuoCode) HasMoreInfo() bool`

HasMoreInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



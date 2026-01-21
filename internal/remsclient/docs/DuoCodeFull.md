# DuoCodeFull

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Restrictions** | Pointer to [**[]Response7799ResourcesDuoCodesRestrictions**](Response7799ResourcesDuoCodesRestrictions.md) |  | [optional] 
**MoreInfo** | Pointer to **map[string]string** | Text values keyed by languages | [optional] 
**Shorthand** | Pointer to **NullableString** |  | [optional] 
**Label** | **map[string]string** | Text values keyed by languages | 
**Description** | **map[string]string** | Text values keyed by languages | 

## Methods

### NewDuoCodeFull

`func NewDuoCodeFull(id string, label map[string]string, description map[string]string, ) *DuoCodeFull`

NewDuoCodeFull instantiates a new DuoCodeFull object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDuoCodeFullWithDefaults

`func NewDuoCodeFullWithDefaults() *DuoCodeFull`

NewDuoCodeFullWithDefaults instantiates a new DuoCodeFull object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DuoCodeFull) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DuoCodeFull) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DuoCodeFull) SetId(v string)`

SetId sets Id field to given value.


### GetRestrictions

`func (o *DuoCodeFull) GetRestrictions() []Response7799ResourcesDuoCodesRestrictions`

GetRestrictions returns the Restrictions field if non-nil, zero value otherwise.

### GetRestrictionsOk

`func (o *DuoCodeFull) GetRestrictionsOk() (*[]Response7799ResourcesDuoCodesRestrictions, bool)`

GetRestrictionsOk returns a tuple with the Restrictions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRestrictions

`func (o *DuoCodeFull) SetRestrictions(v []Response7799ResourcesDuoCodesRestrictions)`

SetRestrictions sets Restrictions field to given value.

### HasRestrictions

`func (o *DuoCodeFull) HasRestrictions() bool`

HasRestrictions returns a boolean if a field has been set.

### GetMoreInfo

`func (o *DuoCodeFull) GetMoreInfo() map[string]string`

GetMoreInfo returns the MoreInfo field if non-nil, zero value otherwise.

### GetMoreInfoOk

`func (o *DuoCodeFull) GetMoreInfoOk() (*map[string]string, bool)`

GetMoreInfoOk returns a tuple with the MoreInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMoreInfo

`func (o *DuoCodeFull) SetMoreInfo(v map[string]string)`

SetMoreInfo sets MoreInfo field to given value.

### HasMoreInfo

`func (o *DuoCodeFull) HasMoreInfo() bool`

HasMoreInfo returns a boolean if a field has been set.

### GetShorthand

`func (o *DuoCodeFull) GetShorthand() string`

GetShorthand returns the Shorthand field if non-nil, zero value otherwise.

### GetShorthandOk

`func (o *DuoCodeFull) GetShorthandOk() (*string, bool)`

GetShorthandOk returns a tuple with the Shorthand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShorthand

`func (o *DuoCodeFull) SetShorthand(v string)`

SetShorthand sets Shorthand field to given value.

### HasShorthand

`func (o *DuoCodeFull) HasShorthand() bool`

HasShorthand returns a boolean if a field has been set.

### SetShorthandNil

`func (o *DuoCodeFull) SetShorthandNil(b bool)`

 SetShorthandNil sets the value for Shorthand to be an explicit nil

### UnsetShorthand
`func (o *DuoCodeFull) UnsetShorthand()`

UnsetShorthand ensures that no value is present for Shorthand, not even an explicit nil
### GetLabel

`func (o *DuoCodeFull) GetLabel() map[string]string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *DuoCodeFull) GetLabelOk() (*map[string]string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *DuoCodeFull) SetLabel(v map[string]string)`

SetLabel sets Label field to given value.


### GetDescription

`func (o *DuoCodeFull) GetDescription() map[string]string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *DuoCodeFull) GetDescriptionOk() (*map[string]string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *DuoCodeFull) SetDescription(v map[string]string)`

SetDescription sets Description field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



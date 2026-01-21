# CreateCategoryCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CategoryTitle** | **map[string]string** | Text values keyed by languages | 
**CategoryDescription** | Pointer to **map[string]string** | Text values keyed by languages | [optional] 
**CategoryDisplayOrder** | Pointer to **int64** |  | [optional] 
**CategoryChildren** | Pointer to [**[]CategoryId**](CategoryId.md) |  | [optional] 

## Methods

### NewCreateCategoryCommand

`func NewCreateCategoryCommand(categoryTitle map[string]string, ) *CreateCategoryCommand`

NewCreateCategoryCommand instantiates a new CreateCategoryCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCategoryCommandWithDefaults

`func NewCreateCategoryCommandWithDefaults() *CreateCategoryCommand`

NewCreateCategoryCommandWithDefaults instantiates a new CreateCategoryCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCategoryTitle

`func (o *CreateCategoryCommand) GetCategoryTitle() map[string]string`

GetCategoryTitle returns the CategoryTitle field if non-nil, zero value otherwise.

### GetCategoryTitleOk

`func (o *CreateCategoryCommand) GetCategoryTitleOk() (*map[string]string, bool)`

GetCategoryTitleOk returns a tuple with the CategoryTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryTitle

`func (o *CreateCategoryCommand) SetCategoryTitle(v map[string]string)`

SetCategoryTitle sets CategoryTitle field to given value.


### GetCategoryDescription

`func (o *CreateCategoryCommand) GetCategoryDescription() map[string]string`

GetCategoryDescription returns the CategoryDescription field if non-nil, zero value otherwise.

### GetCategoryDescriptionOk

`func (o *CreateCategoryCommand) GetCategoryDescriptionOk() (*map[string]string, bool)`

GetCategoryDescriptionOk returns a tuple with the CategoryDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryDescription

`func (o *CreateCategoryCommand) SetCategoryDescription(v map[string]string)`

SetCategoryDescription sets CategoryDescription field to given value.

### HasCategoryDescription

`func (o *CreateCategoryCommand) HasCategoryDescription() bool`

HasCategoryDescription returns a boolean if a field has been set.

### GetCategoryDisplayOrder

`func (o *CreateCategoryCommand) GetCategoryDisplayOrder() int64`

GetCategoryDisplayOrder returns the CategoryDisplayOrder field if non-nil, zero value otherwise.

### GetCategoryDisplayOrderOk

`func (o *CreateCategoryCommand) GetCategoryDisplayOrderOk() (*int64, bool)`

GetCategoryDisplayOrderOk returns a tuple with the CategoryDisplayOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryDisplayOrder

`func (o *CreateCategoryCommand) SetCategoryDisplayOrder(v int64)`

SetCategoryDisplayOrder sets CategoryDisplayOrder field to given value.

### HasCategoryDisplayOrder

`func (o *CreateCategoryCommand) HasCategoryDisplayOrder() bool`

HasCategoryDisplayOrder returns a boolean if a field has been set.

### GetCategoryChildren

`func (o *CreateCategoryCommand) GetCategoryChildren() []CategoryId`

GetCategoryChildren returns the CategoryChildren field if non-nil, zero value otherwise.

### GetCategoryChildrenOk

`func (o *CreateCategoryCommand) GetCategoryChildrenOk() (*[]CategoryId, bool)`

GetCategoryChildrenOk returns a tuple with the CategoryChildren field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryChildren

`func (o *CreateCategoryCommand) SetCategoryChildren(v []CategoryId)`

SetCategoryChildren sets CategoryChildren field to given value.

### HasCategoryChildren

`func (o *CreateCategoryCommand) HasCategoryChildren() bool`

HasCategoryChildren returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



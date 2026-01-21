# Category

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CategoryId** | **int64** |  | 
**CategoryTitle** | **map[string]string** | Text values keyed by languages | 
**CategoryDescription** | Pointer to **map[string]string** | Text values keyed by languages | [optional] 
**CategoryDisplayOrder** | Pointer to **int64** |  | [optional] 
**CategoryChildren** | Pointer to [**[]CategoryId**](CategoryId.md) |  | [optional] 

## Methods

### NewCategory

`func NewCategory(categoryId int64, categoryTitle map[string]string, ) *Category`

NewCategory instantiates a new Category object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCategoryWithDefaults

`func NewCategoryWithDefaults() *Category`

NewCategoryWithDefaults instantiates a new Category object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCategoryId

`func (o *Category) GetCategoryId() int64`

GetCategoryId returns the CategoryId field if non-nil, zero value otherwise.

### GetCategoryIdOk

`func (o *Category) GetCategoryIdOk() (*int64, bool)`

GetCategoryIdOk returns a tuple with the CategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryId

`func (o *Category) SetCategoryId(v int64)`

SetCategoryId sets CategoryId field to given value.


### GetCategoryTitle

`func (o *Category) GetCategoryTitle() map[string]string`

GetCategoryTitle returns the CategoryTitle field if non-nil, zero value otherwise.

### GetCategoryTitleOk

`func (o *Category) GetCategoryTitleOk() (*map[string]string, bool)`

GetCategoryTitleOk returns a tuple with the CategoryTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryTitle

`func (o *Category) SetCategoryTitle(v map[string]string)`

SetCategoryTitle sets CategoryTitle field to given value.


### GetCategoryDescription

`func (o *Category) GetCategoryDescription() map[string]string`

GetCategoryDescription returns the CategoryDescription field if non-nil, zero value otherwise.

### GetCategoryDescriptionOk

`func (o *Category) GetCategoryDescriptionOk() (*map[string]string, bool)`

GetCategoryDescriptionOk returns a tuple with the CategoryDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryDescription

`func (o *Category) SetCategoryDescription(v map[string]string)`

SetCategoryDescription sets CategoryDescription field to given value.

### HasCategoryDescription

`func (o *Category) HasCategoryDescription() bool`

HasCategoryDescription returns a boolean if a field has been set.

### GetCategoryDisplayOrder

`func (o *Category) GetCategoryDisplayOrder() int64`

GetCategoryDisplayOrder returns the CategoryDisplayOrder field if non-nil, zero value otherwise.

### GetCategoryDisplayOrderOk

`func (o *Category) GetCategoryDisplayOrderOk() (*int64, bool)`

GetCategoryDisplayOrderOk returns a tuple with the CategoryDisplayOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryDisplayOrder

`func (o *Category) SetCategoryDisplayOrder(v int64)`

SetCategoryDisplayOrder sets CategoryDisplayOrder field to given value.

### HasCategoryDisplayOrder

`func (o *Category) HasCategoryDisplayOrder() bool`

HasCategoryDisplayOrder returns a boolean if a field has been set.

### GetCategoryChildren

`func (o *Category) GetCategoryChildren() []CategoryId`

GetCategoryChildren returns the CategoryChildren field if non-nil, zero value otherwise.

### GetCategoryChildrenOk

`func (o *Category) GetCategoryChildrenOk() (*[]CategoryId, bool)`

GetCategoryChildrenOk returns a tuple with the CategoryChildren field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryChildren

`func (o *Category) SetCategoryChildren(v []CategoryId)`

SetCategoryChildren sets CategoryChildren field to given value.

### HasCategoryChildren

`func (o *Category) HasCategoryChildren() bool`

HasCategoryChildren returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



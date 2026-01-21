# CategoryTree

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CategoryId** | **int64** |  | 
**CategoryTitle** | **map[string]string** | Text values keyed by languages | 
**CategoryDescription** | Pointer to **map[string]string** | Text values keyed by languages | [optional] 
**CategoryDisplayOrder** | Pointer to **int64** |  | [optional] 
**CategoryChildren** | Pointer to [**[]CategoryTree**](CategoryTree.md) |  | [optional] 
**CategoryItems** | Pointer to [**[]CatalogueItem**](CatalogueItem.md) |  | [optional] 

## Methods

### NewCategoryTree

`func NewCategoryTree(categoryId int64, categoryTitle map[string]string, ) *CategoryTree`

NewCategoryTree instantiates a new CategoryTree object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCategoryTreeWithDefaults

`func NewCategoryTreeWithDefaults() *CategoryTree`

NewCategoryTreeWithDefaults instantiates a new CategoryTree object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCategoryId

`func (o *CategoryTree) GetCategoryId() int64`

GetCategoryId returns the CategoryId field if non-nil, zero value otherwise.

### GetCategoryIdOk

`func (o *CategoryTree) GetCategoryIdOk() (*int64, bool)`

GetCategoryIdOk returns a tuple with the CategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryId

`func (o *CategoryTree) SetCategoryId(v int64)`

SetCategoryId sets CategoryId field to given value.


### GetCategoryTitle

`func (o *CategoryTree) GetCategoryTitle() map[string]string`

GetCategoryTitle returns the CategoryTitle field if non-nil, zero value otherwise.

### GetCategoryTitleOk

`func (o *CategoryTree) GetCategoryTitleOk() (*map[string]string, bool)`

GetCategoryTitleOk returns a tuple with the CategoryTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryTitle

`func (o *CategoryTree) SetCategoryTitle(v map[string]string)`

SetCategoryTitle sets CategoryTitle field to given value.


### GetCategoryDescription

`func (o *CategoryTree) GetCategoryDescription() map[string]string`

GetCategoryDescription returns the CategoryDescription field if non-nil, zero value otherwise.

### GetCategoryDescriptionOk

`func (o *CategoryTree) GetCategoryDescriptionOk() (*map[string]string, bool)`

GetCategoryDescriptionOk returns a tuple with the CategoryDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryDescription

`func (o *CategoryTree) SetCategoryDescription(v map[string]string)`

SetCategoryDescription sets CategoryDescription field to given value.

### HasCategoryDescription

`func (o *CategoryTree) HasCategoryDescription() bool`

HasCategoryDescription returns a boolean if a field has been set.

### GetCategoryDisplayOrder

`func (o *CategoryTree) GetCategoryDisplayOrder() int64`

GetCategoryDisplayOrder returns the CategoryDisplayOrder field if non-nil, zero value otherwise.

### GetCategoryDisplayOrderOk

`func (o *CategoryTree) GetCategoryDisplayOrderOk() (*int64, bool)`

GetCategoryDisplayOrderOk returns a tuple with the CategoryDisplayOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryDisplayOrder

`func (o *CategoryTree) SetCategoryDisplayOrder(v int64)`

SetCategoryDisplayOrder sets CategoryDisplayOrder field to given value.

### HasCategoryDisplayOrder

`func (o *CategoryTree) HasCategoryDisplayOrder() bool`

HasCategoryDisplayOrder returns a boolean if a field has been set.

### GetCategoryChildren

`func (o *CategoryTree) GetCategoryChildren() []CategoryTree`

GetCategoryChildren returns the CategoryChildren field if non-nil, zero value otherwise.

### GetCategoryChildrenOk

`func (o *CategoryTree) GetCategoryChildrenOk() (*[]CategoryTree, bool)`

GetCategoryChildrenOk returns a tuple with the CategoryChildren field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryChildren

`func (o *CategoryTree) SetCategoryChildren(v []CategoryTree)`

SetCategoryChildren sets CategoryChildren field to given value.

### HasCategoryChildren

`func (o *CategoryTree) HasCategoryChildren() bool`

HasCategoryChildren returns a boolean if a field has been set.

### GetCategoryItems

`func (o *CategoryTree) GetCategoryItems() []CatalogueItem`

GetCategoryItems returns the CategoryItems field if non-nil, zero value otherwise.

### GetCategoryItemsOk

`func (o *CategoryTree) GetCategoryItemsOk() (*[]CatalogueItem, bool)`

GetCategoryItemsOk returns a tuple with the CategoryItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryItems

`func (o *CategoryTree) SetCategoryItems(v []CatalogueItem)`

SetCategoryItems sets CategoryItems field to given value.

### HasCategoryItems

`func (o *CategoryTree) HasCategoryItems() bool`

HasCategoryItems returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



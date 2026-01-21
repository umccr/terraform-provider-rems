# UpdateCatalogueItemResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**CatalogueItemId** | Pointer to **int64** |  | [optional] 
**Errors** | Pointer to **[]map[string]interface{}** |  | [optional] 

## Methods

### NewUpdateCatalogueItemResponse

`func NewUpdateCatalogueItemResponse(success bool, ) *UpdateCatalogueItemResponse`

NewUpdateCatalogueItemResponse instantiates a new UpdateCatalogueItemResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateCatalogueItemResponseWithDefaults

`func NewUpdateCatalogueItemResponseWithDefaults() *UpdateCatalogueItemResponse`

NewUpdateCatalogueItemResponseWithDefaults instantiates a new UpdateCatalogueItemResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *UpdateCatalogueItemResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *UpdateCatalogueItemResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *UpdateCatalogueItemResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetCatalogueItemId

`func (o *UpdateCatalogueItemResponse) GetCatalogueItemId() int64`

GetCatalogueItemId returns the CatalogueItemId field if non-nil, zero value otherwise.

### GetCatalogueItemIdOk

`func (o *UpdateCatalogueItemResponse) GetCatalogueItemIdOk() (*int64, bool)`

GetCatalogueItemIdOk returns a tuple with the CatalogueItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCatalogueItemId

`func (o *UpdateCatalogueItemResponse) SetCatalogueItemId(v int64)`

SetCatalogueItemId sets CatalogueItemId field to given value.

### HasCatalogueItemId

`func (o *UpdateCatalogueItemResponse) HasCatalogueItemId() bool`

HasCatalogueItemId returns a boolean if a field has been set.

### GetErrors

`func (o *UpdateCatalogueItemResponse) GetErrors() []map[string]interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *UpdateCatalogueItemResponse) GetErrorsOk() (*[]map[string]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *UpdateCatalogueItemResponse) SetErrors(v []map[string]interface{})`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *UpdateCatalogueItemResponse) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



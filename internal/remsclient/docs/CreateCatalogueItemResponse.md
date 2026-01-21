# CreateCatalogueItemResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Id** | Pointer to **int64** |  | [optional] 
**Errors** | Pointer to **[]map[string]interface{}** |  | [optional] 

## Methods

### NewCreateCatalogueItemResponse

`func NewCreateCatalogueItemResponse(success bool, ) *CreateCatalogueItemResponse`

NewCreateCatalogueItemResponse instantiates a new CreateCatalogueItemResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCatalogueItemResponseWithDefaults

`func NewCreateCatalogueItemResponseWithDefaults() *CreateCatalogueItemResponse`

NewCreateCatalogueItemResponseWithDefaults instantiates a new CreateCatalogueItemResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *CreateCatalogueItemResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *CreateCatalogueItemResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *CreateCatalogueItemResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetId

`func (o *CreateCatalogueItemResponse) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateCatalogueItemResponse) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateCatalogueItemResponse) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *CreateCatalogueItemResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetErrors

`func (o *CreateCatalogueItemResponse) GetErrors() []map[string]interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *CreateCatalogueItemResponse) GetErrorsOk() (*[]map[string]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *CreateCatalogueItemResponse) SetErrors(v []map[string]interface{})`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *CreateCatalogueItemResponse) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



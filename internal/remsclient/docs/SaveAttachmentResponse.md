# SaveAttachmentResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Errors** | Pointer to **[]map[string]interface{}** |  | [optional] 
**Warnings** | Pointer to **[]map[string]interface{}** |  | [optional] 
**Id** | Pointer to **int64** |  | [optional] 

## Methods

### NewSaveAttachmentResponse

`func NewSaveAttachmentResponse(success bool, ) *SaveAttachmentResponse`

NewSaveAttachmentResponse instantiates a new SaveAttachmentResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSaveAttachmentResponseWithDefaults

`func NewSaveAttachmentResponseWithDefaults() *SaveAttachmentResponse`

NewSaveAttachmentResponseWithDefaults instantiates a new SaveAttachmentResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *SaveAttachmentResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *SaveAttachmentResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *SaveAttachmentResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetErrors

`func (o *SaveAttachmentResponse) GetErrors() []map[string]interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *SaveAttachmentResponse) GetErrorsOk() (*[]map[string]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *SaveAttachmentResponse) SetErrors(v []map[string]interface{})`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *SaveAttachmentResponse) HasErrors() bool`

HasErrors returns a boolean if a field has been set.

### GetWarnings

`func (o *SaveAttachmentResponse) GetWarnings() []map[string]interface{}`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *SaveAttachmentResponse) GetWarningsOk() (*[]map[string]interface{}, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *SaveAttachmentResponse) SetWarnings(v []map[string]interface{})`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *SaveAttachmentResponse) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.

### GetId

`func (o *SaveAttachmentResponse) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SaveAttachmentResponse) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SaveAttachmentResponse) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *SaveAttachmentResponse) HasId() bool`

HasId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# EditOrganizationResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**OrganizationId** | **string** |  | 
**Errors** | Pointer to **[]map[string]interface{}** |  | [optional] 

## Methods

### NewEditOrganizationResponse

`func NewEditOrganizationResponse(success bool, organizationId string, ) *EditOrganizationResponse`

NewEditOrganizationResponse instantiates a new EditOrganizationResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEditOrganizationResponseWithDefaults

`func NewEditOrganizationResponseWithDefaults() *EditOrganizationResponse`

NewEditOrganizationResponseWithDefaults instantiates a new EditOrganizationResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *EditOrganizationResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *EditOrganizationResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *EditOrganizationResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetOrganizationId

`func (o *EditOrganizationResponse) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *EditOrganizationResponse) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *EditOrganizationResponse) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetErrors

`func (o *EditOrganizationResponse) GetErrors() []map[string]interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *EditOrganizationResponse) GetErrorsOk() (*[]map[string]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *EditOrganizationResponse) SetErrors(v []map[string]interface{})`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *EditOrganizationResponse) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ValidateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**FieldValues** | [**[]ValidateRequestFieldValues**](ValidateRequestFieldValues.md) |  | 
**DuoCodes** | Pointer to [**[]DuoCode**](DuoCode.md) |  | [optional] 

## Methods

### NewValidateRequest

`func NewValidateRequest(applicationId int64, fieldValues []ValidateRequestFieldValues, ) *ValidateRequest`

NewValidateRequest instantiates a new ValidateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValidateRequestWithDefaults

`func NewValidateRequestWithDefaults() *ValidateRequest`

NewValidateRequestWithDefaults instantiates a new ValidateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *ValidateRequest) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *ValidateRequest) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *ValidateRequest) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetFieldValues

`func (o *ValidateRequest) GetFieldValues() []ValidateRequestFieldValues`

GetFieldValues returns the FieldValues field if non-nil, zero value otherwise.

### GetFieldValuesOk

`func (o *ValidateRequest) GetFieldValuesOk() (*[]ValidateRequestFieldValues, bool)`

GetFieldValuesOk returns a tuple with the FieldValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldValues

`func (o *ValidateRequest) SetFieldValues(v []ValidateRequestFieldValues)`

SetFieldValues sets FieldValues field to given value.


### GetDuoCodes

`func (o *ValidateRequest) GetDuoCodes() []DuoCode`

GetDuoCodes returns the DuoCodes field if non-nil, zero value otherwise.

### GetDuoCodesOk

`func (o *ValidateRequest) GetDuoCodesOk() (*[]DuoCode, bool)`

GetDuoCodesOk returns a tuple with the DuoCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuoCodes

`func (o *ValidateRequest) SetDuoCodes(v []DuoCode)`

SetDuoCodes sets DuoCodes field to given value.

### HasDuoCodes

`func (o *ValidateRequest) HasDuoCodes() bool`

HasDuoCodes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



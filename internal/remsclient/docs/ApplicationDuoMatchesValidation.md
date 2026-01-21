# ApplicationDuoMatchesValidation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Validity** | **string** |  | 
**Errors** | Pointer to [**[]ApplicationDuoMatchesValidationErrors**](ApplicationDuoMatchesValidationErrors.md) |  | [optional] 

## Methods

### NewApplicationDuoMatchesValidation

`func NewApplicationDuoMatchesValidation(validity string, ) *ApplicationDuoMatchesValidation`

NewApplicationDuoMatchesValidation instantiates a new ApplicationDuoMatchesValidation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationDuoMatchesValidationWithDefaults

`func NewApplicationDuoMatchesValidationWithDefaults() *ApplicationDuoMatchesValidation`

NewApplicationDuoMatchesValidationWithDefaults instantiates a new ApplicationDuoMatchesValidation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValidity

`func (o *ApplicationDuoMatchesValidation) GetValidity() string`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *ApplicationDuoMatchesValidation) GetValidityOk() (*string, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *ApplicationDuoMatchesValidation) SetValidity(v string)`

SetValidity sets Validity field to given value.


### GetErrors

`func (o *ApplicationDuoMatchesValidation) GetErrors() []ApplicationDuoMatchesValidationErrors`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *ApplicationDuoMatchesValidation) GetErrorsOk() (*[]ApplicationDuoMatchesValidationErrors, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *ApplicationDuoMatchesValidation) SetErrors(v []ApplicationDuoMatchesValidationErrors)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *ApplicationDuoMatchesValidation) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



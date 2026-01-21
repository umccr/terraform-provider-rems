# DuoCodeMatch

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DuoId** | **string** |  | 
**DuoShorthand** | **string** |  | 
**DuoLabel** | **map[string]map[string]interface{}** |  | 
**ResourceId** | **int64** |  | 
**DuoValidation** | [**Response7799DuoMatchesValidation**](Response7799DuoMatchesValidation.md) |  | 

## Methods

### NewDuoCodeMatch

`func NewDuoCodeMatch(duoId string, duoShorthand string, duoLabel map[string]map[string]interface{}, resourceId int64, duoValidation Response7799DuoMatchesValidation, ) *DuoCodeMatch`

NewDuoCodeMatch instantiates a new DuoCodeMatch object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDuoCodeMatchWithDefaults

`func NewDuoCodeMatchWithDefaults() *DuoCodeMatch`

NewDuoCodeMatchWithDefaults instantiates a new DuoCodeMatch object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDuoId

`func (o *DuoCodeMatch) GetDuoId() string`

GetDuoId returns the DuoId field if non-nil, zero value otherwise.

### GetDuoIdOk

`func (o *DuoCodeMatch) GetDuoIdOk() (*string, bool)`

GetDuoIdOk returns a tuple with the DuoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuoId

`func (o *DuoCodeMatch) SetDuoId(v string)`

SetDuoId sets DuoId field to given value.


### GetDuoShorthand

`func (o *DuoCodeMatch) GetDuoShorthand() string`

GetDuoShorthand returns the DuoShorthand field if non-nil, zero value otherwise.

### GetDuoShorthandOk

`func (o *DuoCodeMatch) GetDuoShorthandOk() (*string, bool)`

GetDuoShorthandOk returns a tuple with the DuoShorthand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuoShorthand

`func (o *DuoCodeMatch) SetDuoShorthand(v string)`

SetDuoShorthand sets DuoShorthand field to given value.


### GetDuoLabel

`func (o *DuoCodeMatch) GetDuoLabel() map[string]map[string]interface{}`

GetDuoLabel returns the DuoLabel field if non-nil, zero value otherwise.

### GetDuoLabelOk

`func (o *DuoCodeMatch) GetDuoLabelOk() (*map[string]map[string]interface{}, bool)`

GetDuoLabelOk returns a tuple with the DuoLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuoLabel

`func (o *DuoCodeMatch) SetDuoLabel(v map[string]map[string]interface{})`

SetDuoLabel sets DuoLabel field to given value.


### GetResourceId

`func (o *DuoCodeMatch) GetResourceId() int64`

GetResourceId returns the ResourceId field if non-nil, zero value otherwise.

### GetResourceIdOk

`func (o *DuoCodeMatch) GetResourceIdOk() (*int64, bool)`

GetResourceIdOk returns a tuple with the ResourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceId

`func (o *DuoCodeMatch) SetResourceId(v int64)`

SetResourceId sets ResourceId field to given value.


### GetDuoValidation

`func (o *DuoCodeMatch) GetDuoValidation() Response7799DuoMatchesValidation`

GetDuoValidation returns the DuoValidation field if non-nil, zero value otherwise.

### GetDuoValidationOk

`func (o *DuoCodeMatch) GetDuoValidationOk() (*Response7799DuoMatchesValidation, bool)`

GetDuoValidationOk returns a tuple with the DuoValidation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuoValidation

`func (o *DuoCodeMatch) SetDuoValidation(v Response7799DuoMatchesValidation)`

SetDuoValidation sets DuoValidation field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



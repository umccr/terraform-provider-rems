# CreateFormCommandFieldsVisibility

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**VisibilityType** | **string** |  | 
**VisibilityField** | Pointer to [**CreateFormCommandFieldsVisibilityField**](CreateFormCommandFieldsVisibilityField.md) |  | [optional] 
**VisibilityValues** | Pointer to **[]string** |  | [optional] 

## Methods

### NewCreateFormCommandFieldsVisibility

`func NewCreateFormCommandFieldsVisibility(visibilityType string, ) *CreateFormCommandFieldsVisibility`

NewCreateFormCommandFieldsVisibility instantiates a new CreateFormCommandFieldsVisibility object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateFormCommandFieldsVisibilityWithDefaults

`func NewCreateFormCommandFieldsVisibilityWithDefaults() *CreateFormCommandFieldsVisibility`

NewCreateFormCommandFieldsVisibilityWithDefaults instantiates a new CreateFormCommandFieldsVisibility object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVisibilityType

`func (o *CreateFormCommandFieldsVisibility) GetVisibilityType() string`

GetVisibilityType returns the VisibilityType field if non-nil, zero value otherwise.

### GetVisibilityTypeOk

`func (o *CreateFormCommandFieldsVisibility) GetVisibilityTypeOk() (*string, bool)`

GetVisibilityTypeOk returns a tuple with the VisibilityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibilityType

`func (o *CreateFormCommandFieldsVisibility) SetVisibilityType(v string)`

SetVisibilityType sets VisibilityType field to given value.


### GetVisibilityField

`func (o *CreateFormCommandFieldsVisibility) GetVisibilityField() CreateFormCommandFieldsVisibilityField`

GetVisibilityField returns the VisibilityField field if non-nil, zero value otherwise.

### GetVisibilityFieldOk

`func (o *CreateFormCommandFieldsVisibility) GetVisibilityFieldOk() (*CreateFormCommandFieldsVisibilityField, bool)`

GetVisibilityFieldOk returns a tuple with the VisibilityField field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibilityField

`func (o *CreateFormCommandFieldsVisibility) SetVisibilityField(v CreateFormCommandFieldsVisibilityField)`

SetVisibilityField sets VisibilityField field to given value.

### HasVisibilityField

`func (o *CreateFormCommandFieldsVisibility) HasVisibilityField() bool`

HasVisibilityField returns a boolean if a field has been set.

### GetVisibilityValues

`func (o *CreateFormCommandFieldsVisibility) GetVisibilityValues() []string`

GetVisibilityValues returns the VisibilityValues field if non-nil, zero value otherwise.

### GetVisibilityValuesOk

`func (o *CreateFormCommandFieldsVisibility) GetVisibilityValuesOk() (*[]string, bool)`

GetVisibilityValuesOk returns a tuple with the VisibilityValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibilityValues

`func (o *CreateFormCommandFieldsVisibility) SetVisibilityValues(v []string)`

SetVisibilityValues sets VisibilityValues field to given value.

### HasVisibilityValues

`func (o *CreateFormCommandFieldsVisibility) HasVisibilityValues() bool`

HasVisibilityValues returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



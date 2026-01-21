# ApplicationFormsFieldsVisibility

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**VisibilityType** | **string** |  | 
**VisibilityField** | Pointer to [**ApplicationFormsFieldsVisibilityField**](ApplicationFormsFieldsVisibilityField.md) |  | [optional] 
**VisibilityValues** | Pointer to **[]string** |  | [optional] 

## Methods

### NewApplicationFormsFieldsVisibility

`func NewApplicationFormsFieldsVisibility(visibilityType string, ) *ApplicationFormsFieldsVisibility`

NewApplicationFormsFieldsVisibility instantiates a new ApplicationFormsFieldsVisibility object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationFormsFieldsVisibilityWithDefaults

`func NewApplicationFormsFieldsVisibilityWithDefaults() *ApplicationFormsFieldsVisibility`

NewApplicationFormsFieldsVisibilityWithDefaults instantiates a new ApplicationFormsFieldsVisibility object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVisibilityType

`func (o *ApplicationFormsFieldsVisibility) GetVisibilityType() string`

GetVisibilityType returns the VisibilityType field if non-nil, zero value otherwise.

### GetVisibilityTypeOk

`func (o *ApplicationFormsFieldsVisibility) GetVisibilityTypeOk() (*string, bool)`

GetVisibilityTypeOk returns a tuple with the VisibilityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibilityType

`func (o *ApplicationFormsFieldsVisibility) SetVisibilityType(v string)`

SetVisibilityType sets VisibilityType field to given value.


### GetVisibilityField

`func (o *ApplicationFormsFieldsVisibility) GetVisibilityField() ApplicationFormsFieldsVisibilityField`

GetVisibilityField returns the VisibilityField field if non-nil, zero value otherwise.

### GetVisibilityFieldOk

`func (o *ApplicationFormsFieldsVisibility) GetVisibilityFieldOk() (*ApplicationFormsFieldsVisibilityField, bool)`

GetVisibilityFieldOk returns a tuple with the VisibilityField field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibilityField

`func (o *ApplicationFormsFieldsVisibility) SetVisibilityField(v ApplicationFormsFieldsVisibilityField)`

SetVisibilityField sets VisibilityField field to given value.

### HasVisibilityField

`func (o *ApplicationFormsFieldsVisibility) HasVisibilityField() bool`

HasVisibilityField returns a boolean if a field has been set.

### GetVisibilityValues

`func (o *ApplicationFormsFieldsVisibility) GetVisibilityValues() []string`

GetVisibilityValues returns the VisibilityValues field if non-nil, zero value otherwise.

### GetVisibilityValuesOk

`func (o *ApplicationFormsFieldsVisibility) GetVisibilityValuesOk() (*[]string, bool)`

GetVisibilityValuesOk returns a tuple with the VisibilityValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibilityValues

`func (o *ApplicationFormsFieldsVisibility) SetVisibilityValues(v []string)`

SetVisibilityValues sets VisibilityValues field to given value.

### HasVisibilityValues

`func (o *ApplicationFormsFieldsVisibility) HasVisibilityValues() bool`

HasVisibilityValues returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



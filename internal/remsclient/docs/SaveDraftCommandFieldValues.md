# SaveDraftCommandFieldValues

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Form** | **int64** |  | 
**Field** | **string** |  | 
**Value** | **map[string]interface{}** | A string for most fields, or [[{\&quot;column\&quot;: string, \&quot;value\&quot;: string}]] for table fields | 

## Methods

### NewSaveDraftCommandFieldValues

`func NewSaveDraftCommandFieldValues(form int64, field string, value map[string]interface{}, ) *SaveDraftCommandFieldValues`

NewSaveDraftCommandFieldValues instantiates a new SaveDraftCommandFieldValues object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSaveDraftCommandFieldValuesWithDefaults

`func NewSaveDraftCommandFieldValuesWithDefaults() *SaveDraftCommandFieldValues`

NewSaveDraftCommandFieldValuesWithDefaults instantiates a new SaveDraftCommandFieldValues object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetForm

`func (o *SaveDraftCommandFieldValues) GetForm() int64`

GetForm returns the Form field if non-nil, zero value otherwise.

### GetFormOk

`func (o *SaveDraftCommandFieldValues) GetFormOk() (*int64, bool)`

GetFormOk returns a tuple with the Form field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForm

`func (o *SaveDraftCommandFieldValues) SetForm(v int64)`

SetForm sets Form field to given value.


### GetField

`func (o *SaveDraftCommandFieldValues) GetField() string`

GetField returns the Field field if non-nil, zero value otherwise.

### GetFieldOk

`func (o *SaveDraftCommandFieldValues) GetFieldOk() (*string, bool)`

GetFieldOk returns a tuple with the Field field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetField

`func (o *SaveDraftCommandFieldValues) SetField(v string)`

SetField sets Field field to given value.


### GetValue

`func (o *SaveDraftCommandFieldValues) GetValue() map[string]interface{}`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *SaveDraftCommandFieldValues) GetValueOk() (*map[string]interface{}, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *SaveDraftCommandFieldValues) SetValue(v map[string]interface{})`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# ChangeFormCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Form** | **NullableInt64** | new form id | 

## Methods

### NewChangeFormCommand

`func NewChangeFormCommand(form NullableInt64, ) *ChangeFormCommand`

NewChangeFormCommand instantiates a new ChangeFormCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChangeFormCommandWithDefaults

`func NewChangeFormCommandWithDefaults() *ChangeFormCommand`

NewChangeFormCommandWithDefaults instantiates a new ChangeFormCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetForm

`func (o *ChangeFormCommand) GetForm() int64`

GetForm returns the Form field if non-nil, zero value otherwise.

### GetFormOk

`func (o *ChangeFormCommand) GetFormOk() (*int64, bool)`

GetFormOk returns a tuple with the Form field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForm

`func (o *ChangeFormCommand) SetForm(v int64)`

SetForm sets Form field to given value.


### SetFormNil

`func (o *ChangeFormCommand) SetFormNil(b bool)`

 SetFormNil sets the value for Form to be an explicit nil

### UnsetForm
`func (o *ChangeFormCommand) UnsetForm()`

UnsetForm ensures that no value is present for Form, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



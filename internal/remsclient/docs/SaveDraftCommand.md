# SaveDraftCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**FieldValues** | [**[]SaveDraftCommandFieldValues**](SaveDraftCommandFieldValues.md) |  | 
**DuoCodes** | Pointer to [**[]DuoCode**](DuoCode.md) |  | [optional] 

## Methods

### NewSaveDraftCommand

`func NewSaveDraftCommand(applicationId int64, fieldValues []SaveDraftCommandFieldValues, ) *SaveDraftCommand`

NewSaveDraftCommand instantiates a new SaveDraftCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSaveDraftCommandWithDefaults

`func NewSaveDraftCommandWithDefaults() *SaveDraftCommand`

NewSaveDraftCommandWithDefaults instantiates a new SaveDraftCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *SaveDraftCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *SaveDraftCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *SaveDraftCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetFieldValues

`func (o *SaveDraftCommand) GetFieldValues() []SaveDraftCommandFieldValues`

GetFieldValues returns the FieldValues field if non-nil, zero value otherwise.

### GetFieldValuesOk

`func (o *SaveDraftCommand) GetFieldValuesOk() (*[]SaveDraftCommandFieldValues, bool)`

GetFieldValuesOk returns a tuple with the FieldValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFieldValues

`func (o *SaveDraftCommand) SetFieldValues(v []SaveDraftCommandFieldValues)`

SetFieldValues sets FieldValues field to given value.


### GetDuoCodes

`func (o *SaveDraftCommand) GetDuoCodes() []DuoCode`

GetDuoCodes returns the DuoCodes field if non-nil, zero value otherwise.

### GetDuoCodesOk

`func (o *SaveDraftCommand) GetDuoCodesOk() (*[]DuoCode, bool)`

GetDuoCodesOk returns a tuple with the DuoCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuoCodes

`func (o *SaveDraftCommand) SetDuoCodes(v []DuoCode)`

SetDuoCodes sets DuoCodes field to given value.

### HasDuoCodes

`func (o *SaveDraftCommand) HasDuoCodes() bool`

HasDuoCodes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



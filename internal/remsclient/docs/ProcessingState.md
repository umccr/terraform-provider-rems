# ProcessingState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProcessingStateValue** | **string** |  | 
**ProcessingStateTitle** | Pointer to **map[string]string** | Text values keyed by languages | [optional] 

## Methods

### NewProcessingState

`func NewProcessingState(processingStateValue string, ) *ProcessingState`

NewProcessingState instantiates a new ProcessingState object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProcessingStateWithDefaults

`func NewProcessingStateWithDefaults() *ProcessingState`

NewProcessingStateWithDefaults instantiates a new ProcessingState object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProcessingStateValue

`func (o *ProcessingState) GetProcessingStateValue() string`

GetProcessingStateValue returns the ProcessingStateValue field if non-nil, zero value otherwise.

### GetProcessingStateValueOk

`func (o *ProcessingState) GetProcessingStateValueOk() (*string, bool)`

GetProcessingStateValueOk returns a tuple with the ProcessingStateValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingStateValue

`func (o *ProcessingState) SetProcessingStateValue(v string)`

SetProcessingStateValue sets ProcessingStateValue field to given value.


### GetProcessingStateTitle

`func (o *ProcessingState) GetProcessingStateTitle() map[string]string`

GetProcessingStateTitle returns the ProcessingStateTitle field if non-nil, zero value otherwise.

### GetProcessingStateTitleOk

`func (o *ProcessingState) GetProcessingStateTitleOk() (*map[string]string, bool)`

GetProcessingStateTitleOk returns a tuple with the ProcessingStateTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingStateTitle

`func (o *ProcessingState) SetProcessingStateTitle(v map[string]string)`

SetProcessingStateTitle sets ProcessingStateTitle field to given value.

### HasProcessingStateTitle

`func (o *ProcessingState) HasProcessingStateTitle() bool`

HasProcessingStateTitle returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



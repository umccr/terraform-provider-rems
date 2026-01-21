# ApplicationDuo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DuoCodes** | Pointer to [**[]DuoCodeFull**](DuoCodeFull.md) |  | [optional] 
**DuoMatches** | Pointer to [**[]DuoCodeMatch**](DuoCodeMatch.md) |  | [optional] 

## Methods

### NewApplicationDuo

`func NewApplicationDuo() *ApplicationDuo`

NewApplicationDuo instantiates a new ApplicationDuo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationDuoWithDefaults

`func NewApplicationDuoWithDefaults() *ApplicationDuo`

NewApplicationDuoWithDefaults instantiates a new ApplicationDuo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDuoCodes

`func (o *ApplicationDuo) GetDuoCodes() []DuoCodeFull`

GetDuoCodes returns the DuoCodes field if non-nil, zero value otherwise.

### GetDuoCodesOk

`func (o *ApplicationDuo) GetDuoCodesOk() (*[]DuoCodeFull, bool)`

GetDuoCodesOk returns a tuple with the DuoCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuoCodes

`func (o *ApplicationDuo) SetDuoCodes(v []DuoCodeFull)`

SetDuoCodes sets DuoCodes field to given value.

### HasDuoCodes

`func (o *ApplicationDuo) HasDuoCodes() bool`

HasDuoCodes returns a boolean if a field has been set.

### GetDuoMatches

`func (o *ApplicationDuo) GetDuoMatches() []DuoCodeMatch`

GetDuoMatches returns the DuoMatches field if non-nil, zero value otherwise.

### GetDuoMatchesOk

`func (o *ApplicationDuo) GetDuoMatchesOk() (*[]DuoCodeMatch, bool)`

GetDuoMatchesOk returns a tuple with the DuoMatches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuoMatches

`func (o *ApplicationDuo) SetDuoMatches(v []DuoCodeMatch)`

SetDuoMatches sets DuoMatches field to given value.

### HasDuoMatches

`func (o *ApplicationDuo) HasDuoMatches() bool`

HasDuoMatches returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



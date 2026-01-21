# Response6598Duo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DuoCodes** | Pointer to [**[]DuoCodeFull**](DuoCodeFull.md) |  | [optional] 
**DuoMatches** | Pointer to [**[]DuoCodeMatch**](DuoCodeMatch.md) |  | [optional] 

## Methods

### NewResponse6598Duo

`func NewResponse6598Duo() *Response6598Duo`

NewResponse6598Duo instantiates a new Response6598Duo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponse6598DuoWithDefaults

`func NewResponse6598DuoWithDefaults() *Response6598Duo`

NewResponse6598DuoWithDefaults instantiates a new Response6598Duo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDuoCodes

`func (o *Response6598Duo) GetDuoCodes() []DuoCodeFull`

GetDuoCodes returns the DuoCodes field if non-nil, zero value otherwise.

### GetDuoCodesOk

`func (o *Response6598Duo) GetDuoCodesOk() (*[]DuoCodeFull, bool)`

GetDuoCodesOk returns a tuple with the DuoCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuoCodes

`func (o *Response6598Duo) SetDuoCodes(v []DuoCodeFull)`

SetDuoCodes sets DuoCodes field to given value.

### HasDuoCodes

`func (o *Response6598Duo) HasDuoCodes() bool`

HasDuoCodes returns a boolean if a field has been set.

### GetDuoMatches

`func (o *Response6598Duo) GetDuoMatches() []DuoCodeMatch`

GetDuoMatches returns the DuoMatches field if non-nil, zero value otherwise.

### GetDuoMatchesOk

`func (o *Response6598Duo) GetDuoMatchesOk() (*[]DuoCodeMatch, bool)`

GetDuoMatchesOk returns a tuple with the DuoMatches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuoMatches

`func (o *Response6598Duo) SetDuoMatches(v []DuoCodeMatch)`

SetDuoMatches sets DuoMatches field to given value.

### HasDuoMatches

`func (o *Response6598Duo) HasDuoMatches() bool`

HasDuoMatches returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



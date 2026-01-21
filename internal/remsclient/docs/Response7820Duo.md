# Response7820Duo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DuoCodes** | Pointer to [**[]DuoCodeFull**](DuoCodeFull.md) |  | [optional] 
**DuoMatches** | Pointer to [**[]DuoCodeMatch**](DuoCodeMatch.md) |  | [optional] 

## Methods

### NewResponse7820Duo

`func NewResponse7820Duo() *Response7820Duo`

NewResponse7820Duo instantiates a new Response7820Duo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponse7820DuoWithDefaults

`func NewResponse7820DuoWithDefaults() *Response7820Duo`

NewResponse7820DuoWithDefaults instantiates a new Response7820Duo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDuoCodes

`func (o *Response7820Duo) GetDuoCodes() []DuoCodeFull`

GetDuoCodes returns the DuoCodes field if non-nil, zero value otherwise.

### GetDuoCodesOk

`func (o *Response7820Duo) GetDuoCodesOk() (*[]DuoCodeFull, bool)`

GetDuoCodesOk returns a tuple with the DuoCodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuoCodes

`func (o *Response7820Duo) SetDuoCodes(v []DuoCodeFull)`

SetDuoCodes sets DuoCodes field to given value.

### HasDuoCodes

`func (o *Response7820Duo) HasDuoCodes() bool`

HasDuoCodes returns a boolean if a field has been set.

### GetDuoMatches

`func (o *Response7820Duo) GetDuoMatches() []DuoCodeMatch`

GetDuoMatches returns the DuoMatches field if non-nil, zero value otherwise.

### GetDuoMatchesOk

`func (o *Response7820Duo) GetDuoMatchesOk() (*[]DuoCodeMatch, bool)`

GetDuoMatchesOk returns a tuple with the DuoMatches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuoMatches

`func (o *Response7820Duo) SetDuoMatches(v []DuoCodeMatch)`

SetDuoMatches sets DuoMatches field to given value.

### HasDuoMatches

`func (o *Response7820Duo) HasDuoMatches() bool`

HasDuoMatches returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



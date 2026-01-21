# AuditLogEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Time** | **time.Time** |  | 
**Path** | **string** |  | 
**Method** | **string** |  | 
**Apikey** | **NullableString** |  | 
**Userid** | **NullableString** |  | 
**Status** | **string** |  | 

## Methods

### NewAuditLogEntry

`func NewAuditLogEntry(time time.Time, path string, method string, apikey NullableString, userid NullableString, status string, ) *AuditLogEntry`

NewAuditLogEntry instantiates a new AuditLogEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuditLogEntryWithDefaults

`func NewAuditLogEntryWithDefaults() *AuditLogEntry`

NewAuditLogEntryWithDefaults instantiates a new AuditLogEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTime

`func (o *AuditLogEntry) GetTime() time.Time`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *AuditLogEntry) GetTimeOk() (*time.Time, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *AuditLogEntry) SetTime(v time.Time)`

SetTime sets Time field to given value.


### GetPath

`func (o *AuditLogEntry) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *AuditLogEntry) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *AuditLogEntry) SetPath(v string)`

SetPath sets Path field to given value.


### GetMethod

`func (o *AuditLogEntry) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *AuditLogEntry) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *AuditLogEntry) SetMethod(v string)`

SetMethod sets Method field to given value.


### GetApikey

`func (o *AuditLogEntry) GetApikey() string`

GetApikey returns the Apikey field if non-nil, zero value otherwise.

### GetApikeyOk

`func (o *AuditLogEntry) GetApikeyOk() (*string, bool)`

GetApikeyOk returns a tuple with the Apikey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApikey

`func (o *AuditLogEntry) SetApikey(v string)`

SetApikey sets Apikey field to given value.


### SetApikeyNil

`func (o *AuditLogEntry) SetApikeyNil(b bool)`

 SetApikeyNil sets the value for Apikey to be an explicit nil

### UnsetApikey
`func (o *AuditLogEntry) UnsetApikey()`

UnsetApikey ensures that no value is present for Apikey, not even an explicit nil
### GetUserid

`func (o *AuditLogEntry) GetUserid() string`

GetUserid returns the Userid field if non-nil, zero value otherwise.

### GetUseridOk

`func (o *AuditLogEntry) GetUseridOk() (*string, bool)`

GetUseridOk returns a tuple with the Userid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserid

`func (o *AuditLogEntry) SetUserid(v string)`

SetUserid sets Userid field to given value.


### SetUseridNil

`func (o *AuditLogEntry) SetUseridNil(b bool)`

 SetUseridNil sets the value for Userid to be an explicit nil

### UnsetUserid
`func (o *AuditLogEntry) UnsetUserid()`

UnsetUserid ensures that no value is present for Userid, not even an explicit nil
### GetStatus

`func (o *AuditLogEntry) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AuditLogEntry) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AuditLogEntry) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



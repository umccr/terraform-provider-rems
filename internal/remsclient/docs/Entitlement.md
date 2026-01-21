# Entitlement

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Resource** | **string** |  | 
**User** | [**UserWithAttributes**](UserWithAttributes.md) |  | 
**ApplicationId** | **int64** |  | 
**Start** | **time.Time** |  | 
**End** | **NullableTime** |  | 
**Mail** | **NullableString** | DEPRECATED, will disappear | 

## Methods

### NewEntitlement

`func NewEntitlement(resource string, user UserWithAttributes, applicationId int64, start time.Time, end NullableTime, mail NullableString, ) *Entitlement`

NewEntitlement instantiates a new Entitlement object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEntitlementWithDefaults

`func NewEntitlementWithDefaults() *Entitlement`

NewEntitlementWithDefaults instantiates a new Entitlement object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResource

`func (o *Entitlement) GetResource() string`

GetResource returns the Resource field if non-nil, zero value otherwise.

### GetResourceOk

`func (o *Entitlement) GetResourceOk() (*string, bool)`

GetResourceOk returns a tuple with the Resource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResource

`func (o *Entitlement) SetResource(v string)`

SetResource sets Resource field to given value.


### GetUser

`func (o *Entitlement) GetUser() UserWithAttributes`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *Entitlement) GetUserOk() (*UserWithAttributes, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *Entitlement) SetUser(v UserWithAttributes)`

SetUser sets User field to given value.


### GetApplicationId

`func (o *Entitlement) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *Entitlement) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *Entitlement) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetStart

`func (o *Entitlement) GetStart() time.Time`

GetStart returns the Start field if non-nil, zero value otherwise.

### GetStartOk

`func (o *Entitlement) GetStartOk() (*time.Time, bool)`

GetStartOk returns a tuple with the Start field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStart

`func (o *Entitlement) SetStart(v time.Time)`

SetStart sets Start field to given value.


### GetEnd

`func (o *Entitlement) GetEnd() time.Time`

GetEnd returns the End field if non-nil, zero value otherwise.

### GetEndOk

`func (o *Entitlement) GetEndOk() (*time.Time, bool)`

GetEndOk returns a tuple with the End field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnd

`func (o *Entitlement) SetEnd(v time.Time)`

SetEnd sets End field to given value.


### SetEndNil

`func (o *Entitlement) SetEndNil(b bool)`

 SetEndNil sets the value for End to be an explicit nil

### UnsetEnd
`func (o *Entitlement) UnsetEnd()`

UnsetEnd ensures that no value is present for End, not even an explicit nil
### GetMail

`func (o *Entitlement) GetMail() string`

GetMail returns the Mail field if non-nil, zero value otherwise.

### GetMailOk

`func (o *Entitlement) GetMailOk() (*string, bool)`

GetMailOk returns a tuple with the Mail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMail

`func (o *Entitlement) SetMail(v string)`

SetMail sets Mail field to given value.


### SetMailNil

`func (o *Entitlement) SetMailNil(b bool)`

 SetMailNil sets the value for Mail to be an explicit nil

### UnsetMail
`func (o *Entitlement) UnsetMail()`

UnsetMail ensures that no value is present for Mail, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# Health

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Healthy** | **bool** |  | 
**Version** | [**HealthVersion**](HealthVersion.md) |  | 
**LatestEvent** | **NullableTime** |  | 

## Methods

### NewHealth

`func NewHealth(healthy bool, version HealthVersion, latestEvent NullableTime, ) *Health`

NewHealth instantiates a new Health object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHealthWithDefaults

`func NewHealthWithDefaults() *Health`

NewHealthWithDefaults instantiates a new Health object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHealthy

`func (o *Health) GetHealthy() bool`

GetHealthy returns the Healthy field if non-nil, zero value otherwise.

### GetHealthyOk

`func (o *Health) GetHealthyOk() (*bool, bool)`

GetHealthyOk returns a tuple with the Healthy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealthy

`func (o *Health) SetHealthy(v bool)`

SetHealthy sets Healthy field to given value.


### GetVersion

`func (o *Health) GetVersion() HealthVersion`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *Health) GetVersionOk() (*HealthVersion, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *Health) SetVersion(v HealthVersion)`

SetVersion sets Version field to given value.


### GetLatestEvent

`func (o *Health) GetLatestEvent() time.Time`

GetLatestEvent returns the LatestEvent field if non-nil, zero value otherwise.

### GetLatestEventOk

`func (o *Health) GetLatestEventOk() (*time.Time, bool)`

GetLatestEventOk returns a tuple with the LatestEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestEvent

`func (o *Health) SetLatestEvent(v time.Time)`

SetLatestEvent sets LatestEvent field to given value.


### SetLatestEventNil

`func (o *Health) SetLatestEventNil(b bool)`

 SetLatestEventNil sets the value for LatestEvent to be an explicit nil

### UnsetLatestEvent
`func (o *Health) UnsetLatestEvent()`

UnsetLatestEvent ensures that no value is present for LatestEvent, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



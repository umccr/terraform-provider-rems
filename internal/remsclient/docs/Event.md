# Event

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EventId** | Pointer to **int64** |  | [optional] 
**EventType** | **string** |  | 
**EventTime** | **time.Time** |  | 
**EventActor** | **string** |  | 
**ApplicationId** | **int64** |  | 
**EventActorAttributes** | [**UserWithAttributes**](UserWithAttributes.md) |  | 

## Methods

### NewEvent

`func NewEvent(eventType string, eventTime time.Time, eventActor string, applicationId int64, eventActorAttributes UserWithAttributes, ) *Event`

NewEvent instantiates a new Event object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEventWithDefaults

`func NewEventWithDefaults() *Event`

NewEventWithDefaults instantiates a new Event object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEventId

`func (o *Event) GetEventId() int64`

GetEventId returns the EventId field if non-nil, zero value otherwise.

### GetEventIdOk

`func (o *Event) GetEventIdOk() (*int64, bool)`

GetEventIdOk returns a tuple with the EventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventId

`func (o *Event) SetEventId(v int64)`

SetEventId sets EventId field to given value.

### HasEventId

`func (o *Event) HasEventId() bool`

HasEventId returns a boolean if a field has been set.

### GetEventType

`func (o *Event) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *Event) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *Event) SetEventType(v string)`

SetEventType sets EventType field to given value.


### GetEventTime

`func (o *Event) GetEventTime() time.Time`

GetEventTime returns the EventTime field if non-nil, zero value otherwise.

### GetEventTimeOk

`func (o *Event) GetEventTimeOk() (*time.Time, bool)`

GetEventTimeOk returns a tuple with the EventTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventTime

`func (o *Event) SetEventTime(v time.Time)`

SetEventTime sets EventTime field to given value.


### GetEventActor

`func (o *Event) GetEventActor() string`

GetEventActor returns the EventActor field if non-nil, zero value otherwise.

### GetEventActorOk

`func (o *Event) GetEventActorOk() (*string, bool)`

GetEventActorOk returns a tuple with the EventActor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventActor

`func (o *Event) SetEventActor(v string)`

SetEventActor sets EventActor field to given value.


### GetApplicationId

`func (o *Event) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *Event) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *Event) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetEventActorAttributes

`func (o *Event) GetEventActorAttributes() UserWithAttributes`

GetEventActorAttributes returns the EventActorAttributes field if non-nil, zero value otherwise.

### GetEventActorAttributesOk

`func (o *Event) GetEventActorAttributesOk() (*UserWithAttributes, bool)`

GetEventActorAttributesOk returns a tuple with the EventActorAttributes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventActorAttributes

`func (o *Event) SetEventActorAttributes(v UserWithAttributes)`

SetEventActorAttributes sets EventActorAttributes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



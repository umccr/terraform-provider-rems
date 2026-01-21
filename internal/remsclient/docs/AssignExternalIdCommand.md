# AssignExternalIdCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**ExternalId** | **string** |  | 

## Methods

### NewAssignExternalIdCommand

`func NewAssignExternalIdCommand(applicationId int64, externalId string, ) *AssignExternalIdCommand`

NewAssignExternalIdCommand instantiates a new AssignExternalIdCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssignExternalIdCommandWithDefaults

`func NewAssignExternalIdCommandWithDefaults() *AssignExternalIdCommand`

NewAssignExternalIdCommandWithDefaults instantiates a new AssignExternalIdCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *AssignExternalIdCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *AssignExternalIdCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *AssignExternalIdCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetExternalId

`func (o *AssignExternalIdCommand) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *AssignExternalIdCommand) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *AssignExternalIdCommand) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



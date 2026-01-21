# AcceptLicensesCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApplicationId** | **int64** |  | 
**AcceptedLicenses** | **[]int64** |  | 

## Methods

### NewAcceptLicensesCommand

`func NewAcceptLicensesCommand(applicationId int64, acceptedLicenses []int64, ) *AcceptLicensesCommand`

NewAcceptLicensesCommand instantiates a new AcceptLicensesCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAcceptLicensesCommandWithDefaults

`func NewAcceptLicensesCommandWithDefaults() *AcceptLicensesCommand`

NewAcceptLicensesCommandWithDefaults instantiates a new AcceptLicensesCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApplicationId

`func (o *AcceptLicensesCommand) GetApplicationId() int64`

GetApplicationId returns the ApplicationId field if non-nil, zero value otherwise.

### GetApplicationIdOk

`func (o *AcceptLicensesCommand) GetApplicationIdOk() (*int64, bool)`

GetApplicationIdOk returns a tuple with the ApplicationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationId

`func (o *AcceptLicensesCommand) SetApplicationId(v int64)`

SetApplicationId sets ApplicationId field to given value.


### GetAcceptedLicenses

`func (o *AcceptLicensesCommand) GetAcceptedLicenses() []int64`

GetAcceptedLicenses returns the AcceptedLicenses field if non-nil, zero value otherwise.

### GetAcceptedLicensesOk

`func (o *AcceptLicensesCommand) GetAcceptedLicensesOk() (*[]int64, bool)`

GetAcceptedLicensesOk returns a tuple with the AcceptedLicenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptedLicenses

`func (o *AcceptLicensesCommand) SetAcceptedLicenses(v []int64)`

SetAcceptedLicenses sets AcceptedLicenses field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



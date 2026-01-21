# Workflow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int64** |  | 
**Organization** | [**OrganizationOverview**](OrganizationOverview.md) |  | 
**Title** | **string** |  | 
**Workflow** | **map[string]interface{}** |  | 
**Enabled** | **bool** |  | 
**Archived** | **bool** |  | 

## Methods

### NewWorkflow

`func NewWorkflow(id int64, organization OrganizationOverview, title string, workflow map[string]interface{}, enabled bool, archived bool, ) *Workflow`

NewWorkflow instantiates a new Workflow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowWithDefaults

`func NewWorkflowWithDefaults() *Workflow`

NewWorkflowWithDefaults instantiates a new Workflow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Workflow) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Workflow) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Workflow) SetId(v int64)`

SetId sets Id field to given value.


### GetOrganization

`func (o *Workflow) GetOrganization() OrganizationOverview`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *Workflow) GetOrganizationOk() (*OrganizationOverview, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *Workflow) SetOrganization(v OrganizationOverview)`

SetOrganization sets Organization field to given value.


### GetTitle

`func (o *Workflow) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Workflow) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Workflow) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetWorkflow

`func (o *Workflow) GetWorkflow() map[string]interface{}`

GetWorkflow returns the Workflow field if non-nil, zero value otherwise.

### GetWorkflowOk

`func (o *Workflow) GetWorkflowOk() (*map[string]interface{}, bool)`

GetWorkflowOk returns a tuple with the Workflow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflow

`func (o *Workflow) SetWorkflow(v map[string]interface{})`

SetWorkflow sets Workflow field to given value.


### GetEnabled

`func (o *Workflow) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *Workflow) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *Workflow) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetArchived

`func (o *Workflow) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *Workflow) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *Workflow) SetArchived(v bool)`

SetArchived sets Archived field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



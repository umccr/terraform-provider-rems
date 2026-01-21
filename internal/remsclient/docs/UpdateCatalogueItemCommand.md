# UpdateCatalogueItemCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Form** | Pointer to **NullableInt64** | new form id | [optional] 
**Workflow** | Pointer to **NullableInt64** | new workflow id | [optional] 

## Methods

### NewUpdateCatalogueItemCommand

`func NewUpdateCatalogueItemCommand() *UpdateCatalogueItemCommand`

NewUpdateCatalogueItemCommand instantiates a new UpdateCatalogueItemCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateCatalogueItemCommandWithDefaults

`func NewUpdateCatalogueItemCommandWithDefaults() *UpdateCatalogueItemCommand`

NewUpdateCatalogueItemCommandWithDefaults instantiates a new UpdateCatalogueItemCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetForm

`func (o *UpdateCatalogueItemCommand) GetForm() int64`

GetForm returns the Form field if non-nil, zero value otherwise.

### GetFormOk

`func (o *UpdateCatalogueItemCommand) GetFormOk() (*int64, bool)`

GetFormOk returns a tuple with the Form field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForm

`func (o *UpdateCatalogueItemCommand) SetForm(v int64)`

SetForm sets Form field to given value.

### HasForm

`func (o *UpdateCatalogueItemCommand) HasForm() bool`

HasForm returns a boolean if a field has been set.

### SetFormNil

`func (o *UpdateCatalogueItemCommand) SetFormNil(b bool)`

 SetFormNil sets the value for Form to be an explicit nil

### UnsetForm
`func (o *UpdateCatalogueItemCommand) UnsetForm()`

UnsetForm ensures that no value is present for Form, not even an explicit nil
### GetWorkflow

`func (o *UpdateCatalogueItemCommand) GetWorkflow() int64`

GetWorkflow returns the Workflow field if non-nil, zero value otherwise.

### GetWorkflowOk

`func (o *UpdateCatalogueItemCommand) GetWorkflowOk() (*int64, bool)`

GetWorkflowOk returns a tuple with the Workflow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflow

`func (o *UpdateCatalogueItemCommand) SetWorkflow(v int64)`

SetWorkflow sets Workflow field to given value.

### HasWorkflow

`func (o *UpdateCatalogueItemCommand) HasWorkflow() bool`

HasWorkflow returns a boolean if a field has been set.

### SetWorkflowNil

`func (o *UpdateCatalogueItemCommand) SetWorkflowNil(b bool)`

 SetWorkflowNil sets the value for Workflow to be an explicit nil

### UnsetWorkflow
`func (o *UpdateCatalogueItemCommand) UnsetWorkflow()`

UnsetWorkflow ensures that no value is present for Workflow, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



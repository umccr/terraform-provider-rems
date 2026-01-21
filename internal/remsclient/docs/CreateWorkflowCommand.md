# CreateWorkflowCommand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AnonymizeHandling** | Pointer to **NullableBool** |  | [optional] 
**DisableCommands** | Pointer to [**[]DisableCommandRule**](DisableCommandRule.md) |  | [optional] 
**Licenses** | Pointer to [**[]LicenseId**](LicenseId.md) |  | [optional] 
**Type** | **string** |  | 
**Organization** | [**OrganizationId**](OrganizationId.md) |  | 
**Handlers** | Pointer to **[]string** |  | [optional] 
**Title** | **string** |  | 
**ProcessingStates** | Pointer to [**[]ProcessingState**](ProcessingState.md) |  | [optional] 
**Voting** | Pointer to [**WorkflowVoting**](WorkflowVoting.md) |  | [optional] 
**Forms** | Pointer to [**[]CreateWorkflowCommandForms**](CreateWorkflowCommandForms.md) |  | [optional] 

## Methods

### NewCreateWorkflowCommand

`func NewCreateWorkflowCommand(type_ string, organization OrganizationId, title string, ) *CreateWorkflowCommand`

NewCreateWorkflowCommand instantiates a new CreateWorkflowCommand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateWorkflowCommandWithDefaults

`func NewCreateWorkflowCommandWithDefaults() *CreateWorkflowCommand`

NewCreateWorkflowCommandWithDefaults instantiates a new CreateWorkflowCommand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnonymizeHandling

`func (o *CreateWorkflowCommand) GetAnonymizeHandling() bool`

GetAnonymizeHandling returns the AnonymizeHandling field if non-nil, zero value otherwise.

### GetAnonymizeHandlingOk

`func (o *CreateWorkflowCommand) GetAnonymizeHandlingOk() (*bool, bool)`

GetAnonymizeHandlingOk returns a tuple with the AnonymizeHandling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnonymizeHandling

`func (o *CreateWorkflowCommand) SetAnonymizeHandling(v bool)`

SetAnonymizeHandling sets AnonymizeHandling field to given value.

### HasAnonymizeHandling

`func (o *CreateWorkflowCommand) HasAnonymizeHandling() bool`

HasAnonymizeHandling returns a boolean if a field has been set.

### SetAnonymizeHandlingNil

`func (o *CreateWorkflowCommand) SetAnonymizeHandlingNil(b bool)`

 SetAnonymizeHandlingNil sets the value for AnonymizeHandling to be an explicit nil

### UnsetAnonymizeHandling
`func (o *CreateWorkflowCommand) UnsetAnonymizeHandling()`

UnsetAnonymizeHandling ensures that no value is present for AnonymizeHandling, not even an explicit nil
### GetDisableCommands

`func (o *CreateWorkflowCommand) GetDisableCommands() []DisableCommandRule`

GetDisableCommands returns the DisableCommands field if non-nil, zero value otherwise.

### GetDisableCommandsOk

`func (o *CreateWorkflowCommand) GetDisableCommandsOk() (*[]DisableCommandRule, bool)`

GetDisableCommandsOk returns a tuple with the DisableCommands field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisableCommands

`func (o *CreateWorkflowCommand) SetDisableCommands(v []DisableCommandRule)`

SetDisableCommands sets DisableCommands field to given value.

### HasDisableCommands

`func (o *CreateWorkflowCommand) HasDisableCommands() bool`

HasDisableCommands returns a boolean if a field has been set.

### GetLicenses

`func (o *CreateWorkflowCommand) GetLicenses() []LicenseId`

GetLicenses returns the Licenses field if non-nil, zero value otherwise.

### GetLicensesOk

`func (o *CreateWorkflowCommand) GetLicensesOk() (*[]LicenseId, bool)`

GetLicensesOk returns a tuple with the Licenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenses

`func (o *CreateWorkflowCommand) SetLicenses(v []LicenseId)`

SetLicenses sets Licenses field to given value.

### HasLicenses

`func (o *CreateWorkflowCommand) HasLicenses() bool`

HasLicenses returns a boolean if a field has been set.

### GetType

`func (o *CreateWorkflowCommand) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateWorkflowCommand) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateWorkflowCommand) SetType(v string)`

SetType sets Type field to given value.


### GetOrganization

`func (o *CreateWorkflowCommand) GetOrganization() OrganizationId`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *CreateWorkflowCommand) GetOrganizationOk() (*OrganizationId, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *CreateWorkflowCommand) SetOrganization(v OrganizationId)`

SetOrganization sets Organization field to given value.


### GetHandlers

`func (o *CreateWorkflowCommand) GetHandlers() []string`

GetHandlers returns the Handlers field if non-nil, zero value otherwise.

### GetHandlersOk

`func (o *CreateWorkflowCommand) GetHandlersOk() (*[]string, bool)`

GetHandlersOk returns a tuple with the Handlers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHandlers

`func (o *CreateWorkflowCommand) SetHandlers(v []string)`

SetHandlers sets Handlers field to given value.

### HasHandlers

`func (o *CreateWorkflowCommand) HasHandlers() bool`

HasHandlers returns a boolean if a field has been set.

### GetTitle

`func (o *CreateWorkflowCommand) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CreateWorkflowCommand) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CreateWorkflowCommand) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetProcessingStates

`func (o *CreateWorkflowCommand) GetProcessingStates() []ProcessingState`

GetProcessingStates returns the ProcessingStates field if non-nil, zero value otherwise.

### GetProcessingStatesOk

`func (o *CreateWorkflowCommand) GetProcessingStatesOk() (*[]ProcessingState, bool)`

GetProcessingStatesOk returns a tuple with the ProcessingStates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingStates

`func (o *CreateWorkflowCommand) SetProcessingStates(v []ProcessingState)`

SetProcessingStates sets ProcessingStates field to given value.

### HasProcessingStates

`func (o *CreateWorkflowCommand) HasProcessingStates() bool`

HasProcessingStates returns a boolean if a field has been set.

### GetVoting

`func (o *CreateWorkflowCommand) GetVoting() WorkflowVoting`

GetVoting returns the Voting field if non-nil, zero value otherwise.

### GetVotingOk

`func (o *CreateWorkflowCommand) GetVotingOk() (*WorkflowVoting, bool)`

GetVotingOk returns a tuple with the Voting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoting

`func (o *CreateWorkflowCommand) SetVoting(v WorkflowVoting)`

SetVoting sets Voting field to given value.

### HasVoting

`func (o *CreateWorkflowCommand) HasVoting() bool`

HasVoting returns a boolean if a field has been set.

### GetForms

`func (o *CreateWorkflowCommand) GetForms() []CreateWorkflowCommandForms`

GetForms returns the Forms field if non-nil, zero value otherwise.

### GetFormsOk

`func (o *CreateWorkflowCommand) GetFormsOk() (*[]CreateWorkflowCommandForms, bool)`

GetFormsOk returns a tuple with the Forms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForms

`func (o *CreateWorkflowCommand) SetForms(v []CreateWorkflowCommandForms)`

SetForms sets Forms field to given value.

### HasForms

`func (o *CreateWorkflowCommand) HasForms() bool`

HasForms returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# CreateOrganizationCommandReviewEmails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **map[string]string** | Text values keyed by languages | 
**Email** | **string** |  | 

## Methods

### NewCreateOrganizationCommandReviewEmails

`func NewCreateOrganizationCommandReviewEmails(name map[string]string, email string, ) *CreateOrganizationCommandReviewEmails`

NewCreateOrganizationCommandReviewEmails instantiates a new CreateOrganizationCommandReviewEmails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrganizationCommandReviewEmailsWithDefaults

`func NewCreateOrganizationCommandReviewEmailsWithDefaults() *CreateOrganizationCommandReviewEmails`

NewCreateOrganizationCommandReviewEmailsWithDefaults instantiates a new CreateOrganizationCommandReviewEmails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateOrganizationCommandReviewEmails) GetName() map[string]string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateOrganizationCommandReviewEmails) GetNameOk() (*map[string]string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateOrganizationCommandReviewEmails) SetName(v map[string]string)`

SetName sets Name field to given value.


### GetEmail

`func (o *CreateOrganizationCommandReviewEmails) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CreateOrganizationCommandReviewEmails) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CreateOrganizationCommandReviewEmails) SetEmail(v string)`

SetEmail sets Email field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



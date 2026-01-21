# \ApplicationsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiApplicationsAcceptInvitationPost**](ApplicationsAPI.md#ApiApplicationsAcceptInvitationPost) | **Post** /api/applications/accept-invitation | Accept an invitation by token (roles: logged-in)
[**ApiApplicationsAcceptLicensesPost**](ApplicationsAPI.md#ApiApplicationsAcceptLicensesPost) | **Post** /api/applications/accept-licenses | Submit a &#x60;accept-licenses&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsAddAttachmentPost**](ApplicationsAPI.md#ApiApplicationsAddAttachmentPost) | **Post** /api/applications/add-attachment | Add an attachment file related to an application (roles: logged-in)
[**ApiApplicationsAddLicensesPost**](ApplicationsAPI.md#ApiApplicationsAddLicensesPost) | **Post** /api/applications/add-licenses | Submit a &#x60;add-licenses&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsAddMemberPost**](ApplicationsAPI.md#ApiApplicationsAddMemberPost) | **Post** /api/applications/add-member | Submit a &#x60;add-member&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsApplicationIdAttachmentsGet**](ApplicationsAPI.md#ApiApplicationsApplicationIdAttachmentsGet) | **Get** /api/applications/{application-id}/attachments | Get attachments for an application as a zip file (roles: logged-in)
[**ApiApplicationsApplicationIdGet**](ApplicationsAPI.md#ApiApplicationsApplicationIdGet) | **Get** /api/applications/{application-id} | Get application by &#x60;application-id&#x60;. Application is customized for the requesting user (e.g. event visibility, permissions, etc). (roles: logged-in)
[**ApiApplicationsApplicationIdLicenseAttachmentLicenseIdLanguageGet**](ApplicationsAPI.md#ApiApplicationsApplicationIdLicenseAttachmentLicenseIdLanguageGet) | **Get** /api/applications/{application-id}/license-attachment/{license-id}/{language} | Get file associated with licence of type attachment associated with application. (roles: logged-in)
[**ApiApplicationsApplicationIdPdfGet**](ApplicationsAPI.md#ApiApplicationsApplicationIdPdfGet) | **Get** /api/applications/{application-id}/pdf | Get a pdf version of an application (roles: logged-in)
[**ApiApplicationsApplicationIdRawGet**](ApplicationsAPI.md#ApiApplicationsApplicationIdRawGet) | **Get** /api/applications/{application-id}/raw | Get application by &#x60;application-id&#x60;. Unlike the /api/applications/:application-id endpoint, the data here isn&#39;t customized for the requesting user (see schema for details). Suitable for integrations and exporting applications. (roles: owner, reporter)
[**ApiApplicationsApprovePost**](ApplicationsAPI.md#ApiApplicationsApprovePost) | **Post** /api/applications/approve | Submit a &#x60;approve&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsAssignExternalIdPost**](ApplicationsAPI.md#ApiApplicationsAssignExternalIdPost) | **Post** /api/applications/assign-external-id | Submit a &#x60;assign-external-id&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsAttachmentAttachmentIdGet**](ApplicationsAPI.md#ApiApplicationsAttachmentAttachmentIdGet) | **Get** /api/applications/attachment/{attachment-id} | Get an attachment (roles: logged-in)
[**ApiApplicationsChangeApplicantPost**](ApplicationsAPI.md#ApiApplicationsChangeApplicantPost) | **Post** /api/applications/change-applicant | Submit a &#x60;change-applicant&#x60; command for an application. Promote member of application to applicant. Previous applicant becomes a member. (roles: logged-in)
[**ApiApplicationsChangeProcessingStatePost**](ApplicationsAPI.md#ApiApplicationsChangeProcessingStatePost) | **Post** /api/applications/change-processing-state | Submit a &#x60;change-processing-state&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsChangeResourcesPost**](ApplicationsAPI.md#ApiApplicationsChangeResourcesPost) | **Post** /api/applications/change-resources | Submit a &#x60;change-resources&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsClosePost**](ApplicationsAPI.md#ApiApplicationsClosePost) | **Post** /api/applications/close | Submit a &#x60;close&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsCommandsGet**](ApplicationsAPI.md#ApiApplicationsCommandsGet) | **Get** /api/applications/commands | List of application commands (roles: handler, organization-owner, owner, reporter)
[**ApiApplicationsCopyAsNewPost**](ApplicationsAPI.md#ApiApplicationsCopyAsNewPost) | **Post** /api/applications/copy-as-new | Create a new application as a copy of an existing application. (roles: logged-in)
[**ApiApplicationsCreatePost**](ApplicationsAPI.md#ApiApplicationsCreatePost) | **Post** /api/applications/create | Create a new application (roles: logged-in)
[**ApiApplicationsDecidePost**](ApplicationsAPI.md#ApiApplicationsDecidePost) | **Post** /api/applications/decide | Submit a &#x60;decide&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsDecidersGet**](ApplicationsAPI.md#ApiApplicationsDecidersGet) | **Get** /api/applications/deciders | Available deciders (roles: handler)
[**ApiApplicationsDeletePost**](ApplicationsAPI.md#ApiApplicationsDeletePost) | **Post** /api/applications/delete | Submit a &#x60;delete&#x60; command for an application. Only drafts can be deleted. Only applicants can delete drafts. (roles: logged-in)
[**ApiApplicationsExportGet**](ApplicationsAPI.md#ApiApplicationsExportGet) | **Get** /api/applications/export | Export all submitted applications of a given form as CSV (roles: owner, reporter)
[**ApiApplicationsGet**](ApplicationsAPI.md#ApiApplicationsGet) | **Get** /api/applications | Get all applications which the current user can see (roles: logged-in)
[**ApiApplicationsHandledCountGet**](ApplicationsAPI.md#ApiApplicationsHandledCountGet) | **Get** /api/applications/handled/count | Get count of all applications that the current user no more needs to act on. (roles: logged-in)
[**ApiApplicationsHandledGet**](ApplicationsAPI.md#ApiApplicationsHandledGet) | **Get** /api/applications/handled | Get all applications that the current user no more needs to act on. (roles: logged-in)
[**ApiApplicationsInviteDeciderPost**](ApplicationsAPI.md#ApiApplicationsInviteDeciderPost) | **Post** /api/applications/invite-decider | Submit a &#x60;invite-decider&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsInviteMemberPost**](ApplicationsAPI.md#ApiApplicationsInviteMemberPost) | **Post** /api/applications/invite-member | Submit a &#x60;invite-member&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsInviteReviewerPost**](ApplicationsAPI.md#ApiApplicationsInviteReviewerPost) | **Post** /api/applications/invite-reviewer | Submit a &#x60;invite-reviewer&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsMembersGet**](ApplicationsAPI.md#ApiApplicationsMembersGet) | **Get** /api/applications/members | Existing REMS users available for application membership (roles: handler)
[**ApiApplicationsRedactAttachmentsPost**](ApplicationsAPI.md#ApiApplicationsRedactAttachmentsPost) | **Post** /api/applications/redact-attachments | Submit a &#x60;redact-attachments&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsRejectPost**](ApplicationsAPI.md#ApiApplicationsRejectPost) | **Post** /api/applications/reject | Submit a &#x60;reject&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsRemarkPost**](ApplicationsAPI.md#ApiApplicationsRemarkPost) | **Post** /api/applications/remark | Submit a &#x60;remark&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsRemoveMemberPost**](ApplicationsAPI.md#ApiApplicationsRemoveMemberPost) | **Post** /api/applications/remove-member | Submit a &#x60;remove-member&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsRequestDecisionPost**](ApplicationsAPI.md#ApiApplicationsRequestDecisionPost) | **Post** /api/applications/request-decision | Submit a &#x60;request-decision&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsRequestReviewPost**](ApplicationsAPI.md#ApiApplicationsRequestReviewPost) | **Post** /api/applications/request-review | Submit a &#x60;request-review&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsReturnPost**](ApplicationsAPI.md#ApiApplicationsReturnPost) | **Post** /api/applications/return | Submit a &#x60;return&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsReviewPost**](ApplicationsAPI.md#ApiApplicationsReviewPost) | **Post** /api/applications/review | Submit a &#x60;review&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsReviewersGet**](ApplicationsAPI.md#ApiApplicationsReviewersGet) | **Get** /api/applications/reviewers | Available reviewers (roles: handler)
[**ApiApplicationsRevokePost**](ApplicationsAPI.md#ApiApplicationsRevokePost) | **Post** /api/applications/revoke | Submit a &#x60;revoke&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsSaveDraftPost**](ApplicationsAPI.md#ApiApplicationsSaveDraftPost) | **Post** /api/applications/save-draft | Submit a &#x60;save-draft&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsSubmitPost**](ApplicationsAPI.md#ApiApplicationsSubmitPost) | **Post** /api/applications/submit | Submit a &#x60;submit&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsTodoGet**](ApplicationsAPI.md#ApiApplicationsTodoGet) | **Get** /api/applications/todo | Get all applications that the current user needs to act on. (roles: logged-in)
[**ApiApplicationsUninviteMemberPost**](ApplicationsAPI.md#ApiApplicationsUninviteMemberPost) | **Post** /api/applications/uninvite-member | Submit a &#x60;uninvite-member&#x60; command for an application.  (roles: logged-in)
[**ApiApplicationsValidatePost**](ApplicationsAPI.md#ApiApplicationsValidatePost) | **Post** /api/applications/validate | Validate the form, like in save, but nothing is saved. NB: At the moment, both errors and validations are identical, but this may not always be so. (roles: logged-in)
[**ApiApplicationsVotePost**](ApplicationsAPI.md#ApiApplicationsVotePost) | **Post** /api/applications/vote | Submit a &#x60;vote&#x60; command for an application.  (roles: logged-in)
[**ApiMyApplicationsGet**](ApplicationsAPI.md#ApiMyApplicationsGet) | **Get** /api/my-applications | Get the current user&#39;s own applications (roles: logged-in)



## ApiApplicationsAcceptInvitationPost

> AcceptInvitationResult ApiApplicationsAcceptInvitationPost(ctx).InvitationToken(invitationToken).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Accept an invitation by token (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	invitationToken := "invitationToken_example" // string | invitation token
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsAcceptInvitationPost(context.Background()).InvitationToken(invitationToken).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsAcceptInvitationPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsAcceptInvitationPost`: AcceptInvitationResult
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsAcceptInvitationPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsAcceptInvitationPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **invitationToken** | **string** | invitation token | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**AcceptInvitationResult**](AcceptInvitationResult.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsAcceptLicensesPost

> SuccessResponse ApiApplicationsAcceptLicensesPost(ctx).AcceptLicensesCommand(acceptLicensesCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `accept-licenses` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	acceptLicensesCommand := *openapiclient.NewAcceptLicensesCommand(int64(123), []int64{int64(123)}) // AcceptLicensesCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsAcceptLicensesPost(context.Background()).AcceptLicensesCommand(acceptLicensesCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsAcceptLicensesPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsAcceptLicensesPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsAcceptLicensesPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsAcceptLicensesPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptLicensesCommand** | [**AcceptLicensesCommand**](AcceptLicensesCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsAddAttachmentPost

> SaveAttachmentResponse ApiApplicationsAddAttachmentPost(ctx).ApplicationId(applicationId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).UNKNOWN_PARAMETER_NAME(UNKNOWN_PARAMETER_NAME).Execute()

Add an attachment file related to an application (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	applicationId := int64(789) // int64 | application id
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)
	UNKNOWN_PARAMETER_NAME := TODO //  |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsAddAttachmentPost(context.Background()).ApplicationId(applicationId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).UNKNOWN_PARAMETER_NAME(UNKNOWN_PARAMETER_NAME).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsAddAttachmentPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsAddAttachmentPost`: SaveAttachmentResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsAddAttachmentPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsAddAttachmentPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **applicationId** | **int64** | application id | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **UNKNOWN_PARAMETER_NAME** | [****](.md) |  | 

### Return type

[**SaveAttachmentResponse**](SaveAttachmentResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsAddLicensesPost

> SuccessResponse ApiApplicationsAddLicensesPost(ctx).AddLicensesCommand(addLicensesCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `add-licenses` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	addLicensesCommand := *openapiclient.NewAddLicensesCommand(int64(123), []int64{int64(123)}) // AddLicensesCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsAddLicensesPost(context.Background()).AddLicensesCommand(addLicensesCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsAddLicensesPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsAddLicensesPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsAddLicensesPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsAddLicensesPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **addLicensesCommand** | [**AddLicensesCommand**](AddLicensesCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsAddMemberPost

> SuccessResponse ApiApplicationsAddMemberPost(ctx).AddMemberCommand(addMemberCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `add-member` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	addMemberCommand := *openapiclient.NewAddMemberCommand(int64(123), *openapiclient.NewUser("Userid_example")) // AddMemberCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsAddMemberPost(context.Background()).AddMemberCommand(addMemberCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsAddMemberPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsAddMemberPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsAddMemberPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsAddMemberPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **addMemberCommand** | [**AddMemberCommand**](AddMemberCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsApplicationIdAttachmentsGet

> ApiApplicationsApplicationIdAttachmentsGet(ctx, applicationId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).All(all).Execute()

Get attachments for an application as a zip file (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	applicationId := int64(789) // int64 | application id
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)
	all := true // bool | Defaults to true. If set to false, the zip will only contain latest application attachments: no previous versions of attachments, and no event attachments. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ApplicationsAPI.ApiApplicationsApplicationIdAttachmentsGet(context.Background(), applicationId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).All(all).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsApplicationIdAttachmentsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**applicationId** | **int64** | application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsApplicationIdAttachmentsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **all** | **bool** | Defaults to true. If set to false, the zip will only contain latest application attachments: no previous versions of attachments, and no event attachments. | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsApplicationIdGet

> Application ApiApplicationsApplicationIdGet(ctx, applicationId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Get application by `application-id`. Application is customized for the requesting user (e.g. event visibility, permissions, etc). (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	applicationId := int64(789) // int64 | application id
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsApplicationIdGet(context.Background(), applicationId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsApplicationIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsApplicationIdGet`: Application
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsApplicationIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**applicationId** | **int64** | application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsApplicationIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**Application**](Application.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsApplicationIdLicenseAttachmentLicenseIdLanguageGet

> ApiApplicationsApplicationIdLicenseAttachmentLicenseIdLanguageGet(ctx, applicationId, licenseId, language).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Get file associated with licence of type attachment associated with application. (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	applicationId := int64(789) // int64 | application id
	licenseId := int64(789) // int64 | license id
	language := "language_example" // string | language code
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ApplicationsAPI.ApiApplicationsApplicationIdLicenseAttachmentLicenseIdLanguageGet(context.Background(), applicationId, licenseId, language).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsApplicationIdLicenseAttachmentLicenseIdLanguageGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**applicationId** | **int64** | application id | 
**licenseId** | **int64** | license id | 
**language** | **string** | language code | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsApplicationIdLicenseAttachmentLicenseIdLanguageGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsApplicationIdPdfGet

> ApiApplicationsApplicationIdPdfGet(ctx, applicationId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Get a pdf version of an application (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	applicationId := int64(789) // int64 | application id
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ApplicationsAPI.ApiApplicationsApplicationIdPdfGet(context.Background(), applicationId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsApplicationIdPdfGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**applicationId** | **int64** | application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsApplicationIdPdfGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsApplicationIdRawGet

> ApplicationRaw ApiApplicationsApplicationIdRawGet(ctx, applicationId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Get application by `application-id`. Unlike the /api/applications/:application-id endpoint, the data here isn't customized for the requesting user (see schema for details). Suitable for integrations and exporting applications. (roles: owner, reporter)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	applicationId := int64(789) // int64 | application id
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsApplicationIdRawGet(context.Background(), applicationId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsApplicationIdRawGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsApplicationIdRawGet`: ApplicationRaw
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsApplicationIdRawGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**applicationId** | **int64** | application id | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsApplicationIdRawGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**ApplicationRaw**](ApplicationRaw.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsApprovePost

> SuccessResponse ApiApplicationsApprovePost(ctx).ApproveCommand(approveCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `approve` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	approveCommand := *openapiclient.NewApproveCommand(int64(123)) // ApproveCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsApprovePost(context.Background()).ApproveCommand(approveCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsApprovePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsApprovePost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsApprovePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsApprovePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **approveCommand** | [**ApproveCommand**](ApproveCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsAssignExternalIdPost

> SuccessResponse ApiApplicationsAssignExternalIdPost(ctx).AssignExternalIdCommand(assignExternalIdCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `assign-external-id` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	assignExternalIdCommand := *openapiclient.NewAssignExternalIdCommand(int64(123), "ExternalId_example") // AssignExternalIdCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsAssignExternalIdPost(context.Background()).AssignExternalIdCommand(assignExternalIdCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsAssignExternalIdPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsAssignExternalIdPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsAssignExternalIdPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsAssignExternalIdPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assignExternalIdCommand** | [**AssignExternalIdCommand**](AssignExternalIdCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsAttachmentAttachmentIdGet

> ApiApplicationsAttachmentAttachmentIdGet(ctx, attachmentId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Get an attachment (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	attachmentId := int64(789) // int64 | attachment id
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ApplicationsAPI.ApiApplicationsAttachmentAttachmentIdGet(context.Background(), attachmentId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsAttachmentAttachmentIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**attachmentId** | **int64** | attachment id | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsAttachmentAttachmentIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsChangeApplicantPost

> SuccessResponse ApiApplicationsChangeApplicantPost(ctx).ChangeApplicantCommand(changeApplicantCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `change-applicant` command for an application. Promote member of application to applicant. Previous applicant becomes a member. (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	changeApplicantCommand := *openapiclient.NewChangeApplicantCommand(int64(123), *openapiclient.NewUser("Userid_example")) // ChangeApplicantCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsChangeApplicantPost(context.Background()).ChangeApplicantCommand(changeApplicantCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsChangeApplicantPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsChangeApplicantPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsChangeApplicantPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsChangeApplicantPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **changeApplicantCommand** | [**ChangeApplicantCommand**](ChangeApplicantCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsChangeProcessingStatePost

> SuccessResponse ApiApplicationsChangeProcessingStatePost(ctx).ChangeProcessingStateCommand(changeProcessingStateCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `change-processing-state` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	changeProcessingStateCommand := *openapiclient.NewChangeProcessingStateCommand(int64(123), "ProcessingState_example", false) // ChangeProcessingStateCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsChangeProcessingStatePost(context.Background()).ChangeProcessingStateCommand(changeProcessingStateCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsChangeProcessingStatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsChangeProcessingStatePost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsChangeProcessingStatePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsChangeProcessingStatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **changeProcessingStateCommand** | [**ChangeProcessingStateCommand**](ChangeProcessingStateCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsChangeResourcesPost

> SuccessResponse ApiApplicationsChangeResourcesPost(ctx).ChangeResourcesCommand(changeResourcesCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `change-resources` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	changeResourcesCommand := *openapiclient.NewChangeResourcesCommand(int64(123), []int64{int64(123)}) // ChangeResourcesCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsChangeResourcesPost(context.Background()).ChangeResourcesCommand(changeResourcesCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsChangeResourcesPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsChangeResourcesPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsChangeResourcesPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsChangeResourcesPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **changeResourcesCommand** | [**ChangeResourcesCommand**](ChangeResourcesCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsClosePost

> SuccessResponse ApiApplicationsClosePost(ctx).CloseCommand(closeCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `close` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	closeCommand := *openapiclient.NewCloseCommand(int64(123)) // CloseCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsClosePost(context.Background()).CloseCommand(closeCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsClosePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsClosePost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsClosePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsClosePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **closeCommand** | [**CloseCommand**](CloseCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsCommandsGet

> []string ApiApplicationsCommandsGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

List of application commands (roles: handler, organization-owner, owner, reporter)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsCommandsGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsCommandsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsCommandsGet`: []string
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsCommandsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsCommandsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

**[]string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsCopyAsNewPost

> CopyAsNewResponse ApiApplicationsCopyAsNewPost(ctx).CopyAsNewCommand(copyAsNewCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Create a new application as a copy of an existing application. (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	copyAsNewCommand := *openapiclient.NewCopyAsNewCommand(int64(123)) // CopyAsNewCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsCopyAsNewPost(context.Background()).CopyAsNewCommand(copyAsNewCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsCopyAsNewPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsCopyAsNewPost`: CopyAsNewResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsCopyAsNewPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsCopyAsNewPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **copyAsNewCommand** | [**CopyAsNewCommand**](CopyAsNewCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**CopyAsNewResponse**](CopyAsNewResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsCreatePost

> CreateApplicationResponse ApiApplicationsCreatePost(ctx).CreateApplicationCommand(createApplicationCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Create a new application (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	createApplicationCommand := *openapiclient.NewCreateApplicationCommand([]int64{int64(123)}) // CreateApplicationCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsCreatePost(context.Background()).CreateApplicationCommand(createApplicationCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsCreatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsCreatePost`: CreateApplicationResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsCreatePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsCreatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createApplicationCommand** | [**CreateApplicationCommand**](CreateApplicationCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**CreateApplicationResponse**](CreateApplicationResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsDecidePost

> SuccessResponse ApiApplicationsDecidePost(ctx).DecideCommand(decideCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `decide` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	decideCommand := *openapiclient.NewDecideCommand(int64(123), "Decision_example") // DecideCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsDecidePost(context.Background()).DecideCommand(decideCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsDecidePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsDecidePost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsDecidePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsDecidePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **decideCommand** | [**DecideCommand**](DecideCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsDecidersGet

> []Decider ApiApplicationsDecidersGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Available deciders (roles: handler)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsDecidersGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsDecidersGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsDecidersGet`: []Decider
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsDecidersGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsDecidersGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**[]Decider**](Decider.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsDeletePost

> SuccessResponse ApiApplicationsDeletePost(ctx).DeleteCommand(deleteCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `delete` command for an application. Only drafts can be deleted. Only applicants can delete drafts. (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	deleteCommand := *openapiclient.NewDeleteCommand(int64(123)) // DeleteCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsDeletePost(context.Background()).DeleteCommand(deleteCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsDeletePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsDeletePost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsDeletePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsDeletePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **deleteCommand** | [**DeleteCommand**](DeleteCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsExportGet

> ApiApplicationsExportGet(ctx).FormId(formId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Export all submitted applications of a given form as CSV (roles: owner, reporter)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	formId := int64(789) // int64 | form id
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ApplicationsAPI.ApiApplicationsExportGet(context.Background()).FormId(formId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsExportGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsExportGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **formId** | **int64** | form id | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsGet

> []ApplicationOverview ApiApplicationsGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Query(query).Execute()

Get all applications which the current user can see (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)
	query := "query_example" // string | search query [documentation](https://github.com/CSCfi/rems/blob/master/docs/search.md) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Query(query).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsGet`: []ApplicationOverview
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **query** | **string** | search query [documentation](https://github.com/CSCfi/rems/blob/master/docs/search.md) | 

### Return type

[**[]ApplicationOverview**](ApplicationOverview.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsHandledCountGet

> int64 ApiApplicationsHandledCountGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Get count of all applications that the current user no more needs to act on. (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsHandledCountGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsHandledCountGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsHandledCountGet`: int64
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsHandledCountGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsHandledCountGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

**int64**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsHandledGet

> []ApplicationOverview ApiApplicationsHandledGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Query(query).OnlyActiveHandlers(onlyActiveHandlers).Limit(limit).Execute()

Get all applications that the current user no more needs to act on. (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)
	query := "query_example" // string | search query [documentation](https://github.com/CSCfi/rems/blob/master/docs/search.md) (optional)
	onlyActiveHandlers := true // bool | return only workflow handlers that are active making a smaller result (optional)
	limit := int64(789) // int64 | how many results to return (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsHandledGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Query(query).OnlyActiveHandlers(onlyActiveHandlers).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsHandledGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsHandledGet`: []ApplicationOverview
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsHandledGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsHandledGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **query** | **string** | search query [documentation](https://github.com/CSCfi/rems/blob/master/docs/search.md) | 
 **onlyActiveHandlers** | **bool** | return only workflow handlers that are active making a smaller result | 
 **limit** | **int64** | how many results to return | 

### Return type

[**[]ApplicationOverview**](ApplicationOverview.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsInviteDeciderPost

> SuccessResponse ApiApplicationsInviteDeciderPost(ctx).InviteDeciderCommand(inviteDeciderCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `invite-decider` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	inviteDeciderCommand := *openapiclient.NewInviteDeciderCommand(int64(123), *openapiclient.NewInviteDeciderCommandDecider("Name_example", "Email_example")) // InviteDeciderCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsInviteDeciderPost(context.Background()).InviteDeciderCommand(inviteDeciderCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsInviteDeciderPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsInviteDeciderPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsInviteDeciderPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsInviteDeciderPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inviteDeciderCommand** | [**InviteDeciderCommand**](InviteDeciderCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsInviteMemberPost

> SuccessResponse ApiApplicationsInviteMemberPost(ctx).InviteMemberCommand(inviteMemberCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `invite-member` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	inviteMemberCommand := *openapiclient.NewInviteMemberCommand(int64(123), *openapiclient.NewInviteMemberCommandMember("Name_example", "Email_example")) // InviteMemberCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsInviteMemberPost(context.Background()).InviteMemberCommand(inviteMemberCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsInviteMemberPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsInviteMemberPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsInviteMemberPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsInviteMemberPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inviteMemberCommand** | [**InviteMemberCommand**](InviteMemberCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsInviteReviewerPost

> SuccessResponse ApiApplicationsInviteReviewerPost(ctx).InviteReviewerCommand(inviteReviewerCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `invite-reviewer` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	inviteReviewerCommand := *openapiclient.NewInviteReviewerCommand(int64(123), *openapiclient.NewInviteReviewerCommandReviewer("Name_example", "Email_example")) // InviteReviewerCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsInviteReviewerPost(context.Background()).InviteReviewerCommand(inviteReviewerCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsInviteReviewerPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsInviteReviewerPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsInviteReviewerPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsInviteReviewerPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inviteReviewerCommand** | [**InviteReviewerCommand**](InviteReviewerCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsMembersGet

> []Applicant ApiApplicationsMembersGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Existing REMS users available for application membership (roles: handler)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsMembersGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsMembersGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsMembersGet`: []Applicant
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsMembersGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsMembersGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**[]Applicant**](Applicant.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsRedactAttachmentsPost

> SuccessResponse ApiApplicationsRedactAttachmentsPost(ctx).RedactAttachmentsCommand(redactAttachmentsCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `redact-attachments` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	redactAttachmentsCommand := *openapiclient.NewRedactAttachmentsCommand(int64(123), []openapiclient.CommandAttachment{*openapiclient.NewCommandAttachment(int64(123))}, false) // RedactAttachmentsCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsRedactAttachmentsPost(context.Background()).RedactAttachmentsCommand(redactAttachmentsCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsRedactAttachmentsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsRedactAttachmentsPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsRedactAttachmentsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsRedactAttachmentsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **redactAttachmentsCommand** | [**RedactAttachmentsCommand**](RedactAttachmentsCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsRejectPost

> SuccessResponse ApiApplicationsRejectPost(ctx).RejectCommand(rejectCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `reject` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	rejectCommand := *openapiclient.NewRejectCommand(int64(123)) // RejectCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsRejectPost(context.Background()).RejectCommand(rejectCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsRejectPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsRejectPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsRejectPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsRejectPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **rejectCommand** | [**RejectCommand**](RejectCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsRemarkPost

> SuccessResponse ApiApplicationsRemarkPost(ctx).RemarkCommand(remarkCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `remark` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	remarkCommand := *openapiclient.NewRemarkCommand(int64(123), false) // RemarkCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsRemarkPost(context.Background()).RemarkCommand(remarkCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsRemarkPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsRemarkPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsRemarkPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsRemarkPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **remarkCommand** | [**RemarkCommand**](RemarkCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsRemoveMemberPost

> SuccessResponse ApiApplicationsRemoveMemberPost(ctx).RemoveMemberCommand(removeMemberCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `remove-member` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	removeMemberCommand := *openapiclient.NewRemoveMemberCommand(int64(123), *openapiclient.NewUser("Userid_example")) // RemoveMemberCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsRemoveMemberPost(context.Background()).RemoveMemberCommand(removeMemberCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsRemoveMemberPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsRemoveMemberPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsRemoveMemberPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsRemoveMemberPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **removeMemberCommand** | [**RemoveMemberCommand**](RemoveMemberCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsRequestDecisionPost

> SuccessResponse ApiApplicationsRequestDecisionPost(ctx).RequestDecisionCommand(requestDecisionCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `request-decision` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	requestDecisionCommand := *openapiclient.NewRequestDecisionCommand(int64(123), []string{"Deciders_example"}) // RequestDecisionCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsRequestDecisionPost(context.Background()).RequestDecisionCommand(requestDecisionCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsRequestDecisionPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsRequestDecisionPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsRequestDecisionPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsRequestDecisionPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestDecisionCommand** | [**RequestDecisionCommand**](RequestDecisionCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsRequestReviewPost

> SuccessResponse ApiApplicationsRequestReviewPost(ctx).RequestReviewCommand(requestReviewCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `request-review` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	requestReviewCommand := *openapiclient.NewRequestReviewCommand(int64(123), []string{"Reviewers_example"}) // RequestReviewCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsRequestReviewPost(context.Background()).RequestReviewCommand(requestReviewCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsRequestReviewPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsRequestReviewPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsRequestReviewPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsRequestReviewPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestReviewCommand** | [**RequestReviewCommand**](RequestReviewCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsReturnPost

> SuccessResponse ApiApplicationsReturnPost(ctx).ReturnCommand(returnCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `return` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	returnCommand := *openapiclient.NewReturnCommand(int64(123)) // ReturnCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsReturnPost(context.Background()).ReturnCommand(returnCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsReturnPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsReturnPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsReturnPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsReturnPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **returnCommand** | [**ReturnCommand**](ReturnCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsReviewPost

> SuccessResponse ApiApplicationsReviewPost(ctx).ReviewCommand(reviewCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `review` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	reviewCommand := *openapiclient.NewReviewCommand(int64(123)) // ReviewCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsReviewPost(context.Background()).ReviewCommand(reviewCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsReviewPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsReviewPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsReviewPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsReviewPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **reviewCommand** | [**ReviewCommand**](ReviewCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsReviewersGet

> []Reviewer ApiApplicationsReviewersGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Available reviewers (roles: handler)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsReviewersGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsReviewersGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsReviewersGet`: []Reviewer
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsReviewersGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsReviewersGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**[]Reviewer**](Reviewer.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsRevokePost

> SuccessResponse ApiApplicationsRevokePost(ctx).RevokeCommand(revokeCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `revoke` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	revokeCommand := *openapiclient.NewRevokeCommand(int64(123)) // RevokeCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsRevokePost(context.Background()).RevokeCommand(revokeCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsRevokePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsRevokePost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsRevokePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsRevokePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **revokeCommand** | [**RevokeCommand**](RevokeCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsSaveDraftPost

> SuccessResponse ApiApplicationsSaveDraftPost(ctx).SaveDraftCommand(saveDraftCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `save-draft` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	saveDraftCommand := *openapiclient.NewSaveDraftCommand(int64(123), []openapiclient.SaveDraftCommandFieldValues{*openapiclient.NewSaveDraftCommandFieldValues(int64(123), "Field_example", map[string]interface{}(value))}) // SaveDraftCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsSaveDraftPost(context.Background()).SaveDraftCommand(saveDraftCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsSaveDraftPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsSaveDraftPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsSaveDraftPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsSaveDraftPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **saveDraftCommand** | [**SaveDraftCommand**](SaveDraftCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsSubmitPost

> SuccessResponse ApiApplicationsSubmitPost(ctx).SubmitCommand(submitCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `submit` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	submitCommand := *openapiclient.NewSubmitCommand(int64(123)) // SubmitCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsSubmitPost(context.Background()).SubmitCommand(submitCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsSubmitPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsSubmitPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsSubmitPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsSubmitPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **submitCommand** | [**SubmitCommand**](SubmitCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsTodoGet

> []ApplicationOverview ApiApplicationsTodoGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Query(query).Execute()

Get all applications that the current user needs to act on. (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)
	query := "query_example" // string | search query [documentation](https://github.com/CSCfi/rems/blob/master/docs/search.md) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsTodoGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Query(query).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsTodoGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsTodoGet`: []ApplicationOverview
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsTodoGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsTodoGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **query** | **string** | search query [documentation](https://github.com/CSCfi/rems/blob/master/docs/search.md) | 

### Return type

[**[]ApplicationOverview**](ApplicationOverview.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsUninviteMemberPost

> SuccessResponse ApiApplicationsUninviteMemberPost(ctx).UninviteMemberCommand(uninviteMemberCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `uninvite-member` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	uninviteMemberCommand := *openapiclient.NewUninviteMemberCommand(int64(123), *openapiclient.NewUninviteMemberCommandMember("Name_example", "Email_example")) // UninviteMemberCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsUninviteMemberPost(context.Background()).UninviteMemberCommand(uninviteMemberCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsUninviteMemberPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsUninviteMemberPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsUninviteMemberPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsUninviteMemberPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **uninviteMemberCommand** | [**UninviteMemberCommand**](UninviteMemberCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsValidatePost

> SuccessResponse ApiApplicationsValidatePost(ctx).ValidateRequest(validateRequest).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Validate the form, like in save, but nothing is saved. NB: At the moment, both errors and validations are identical, but this may not always be so. (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	validateRequest := *openapiclient.NewValidateRequest(int64(123), []openapiclient.ValidateRequestFieldValues{*openapiclient.NewValidateRequestFieldValues(int64(123), "Field_example", map[string]interface{}(value))}) // ValidateRequest | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsValidatePost(context.Background()).ValidateRequest(validateRequest).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsValidatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsValidatePost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsValidatePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsValidatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **validateRequest** | [**ValidateRequest**](ValidateRequest.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiApplicationsVotePost

> SuccessResponse ApiApplicationsVotePost(ctx).VoteCommand(voteCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Submit a `vote` command for an application.  (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	voteCommand := *openapiclient.NewVoteCommand(int64(123), "Vote_example") // VoteCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiApplicationsVotePost(context.Background()).VoteCommand(voteCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiApplicationsVotePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiApplicationsVotePost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiApplicationsVotePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiApplicationsVotePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **voteCommand** | [**VoteCommand**](VoteCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiMyApplicationsGet

> []ApplicationOverview ApiMyApplicationsGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Query(query).Execute()

Get the current user's own applications (roles: logged-in)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)
	query := "query_example" // string | search query [documentation](https://github.com/CSCfi/rems/blob/master/docs/search.md) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApplicationsAPI.ApiMyApplicationsGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Query(query).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApplicationsAPI.ApiMyApplicationsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiMyApplicationsGet`: []ApplicationOverview
	fmt.Fprintf(os.Stdout, "Response from `ApplicationsAPI.ApiMyApplicationsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiMyApplicationsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **query** | **string** | search query [documentation](https://github.com/CSCfi/rems/blob/master/docs/search.md) | 

### Return type

[**[]ApplicationOverview**](ApplicationOverview.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


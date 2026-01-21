# \InvitationsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiInvitationsAcceptInvitationPost**](InvitationsAPI.md#ApiInvitationsAcceptInvitationPost) | **Post** /api/invitations/accept-invitation | Accept an invitation. The invitation token will be spent. (roles: logged-in)
[**ApiInvitationsCreatePost**](InvitationsAPI.md#ApiInvitationsCreatePost) | **Post** /api/invitations/create | Create an invitation. The invitation will be sent asynchronously to the recipient. (roles: organization-owner, owner)
[**ApiInvitationsGet**](InvitationsAPI.md#ApiInvitationsGet) | **Get** /api/invitations | Get invitations (roles: handler, organization-owner, owner, reporter)



## ApiInvitationsAcceptInvitationPost

> AcceptInvitationResponse ApiInvitationsAcceptInvitationPost(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Token(token).Execute()

Accept an invitation. The invitation token will be spent. (roles: logged-in)

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
	token := "token_example" // string | secret token of the invitation (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InvitationsAPI.ApiInvitationsAcceptInvitationPost(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Token(token).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InvitationsAPI.ApiInvitationsAcceptInvitationPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiInvitationsAcceptInvitationPost`: AcceptInvitationResponse
	fmt.Fprintf(os.Stdout, "Response from `InvitationsAPI.ApiInvitationsAcceptInvitationPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiInvitationsAcceptInvitationPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **token** | **string** | secret token of the invitation | 

### Return type

[**AcceptInvitationResponse**](AcceptInvitationResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiInvitationsCreatePost

> CreateInvitationResponse ApiInvitationsCreatePost(ctx).CreateInvitationCommand(createInvitationCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Create an invitation. The invitation will be sent asynchronously to the recipient. (roles: organization-owner, owner)

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
	createInvitationCommand := *openapiclient.NewCreateInvitationCommand("Name_example", "Email_example") // CreateInvitationCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InvitationsAPI.ApiInvitationsCreatePost(context.Background()).CreateInvitationCommand(createInvitationCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InvitationsAPI.ApiInvitationsCreatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiInvitationsCreatePost`: CreateInvitationResponse
	fmt.Fprintf(os.Stdout, "Response from `InvitationsAPI.ApiInvitationsCreatePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiInvitationsCreatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createInvitationCommand** | [**CreateInvitationCommand**](CreateInvitationCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**CreateInvitationResponse**](CreateInvitationResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiInvitationsGet

> []InvitationResponse ApiInvitationsGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Sent(sent).Accepted(accepted).Execute()

Get invitations (roles: handler, organization-owner, owner, reporter)

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
	sent := true // bool | whether to include sent invitations (optional)
	accepted := true // bool | whether to include accepted invitations (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InvitationsAPI.ApiInvitationsGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Sent(sent).Accepted(accepted).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InvitationsAPI.ApiInvitationsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiInvitationsGet`: []InvitationResponse
	fmt.Fprintf(os.Stdout, "Response from `InvitationsAPI.ApiInvitationsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiInvitationsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **sent** | **bool** | whether to include sent invitations | 
 **accepted** | **bool** | whether to include accepted invitations | 

### Return type

[**[]InvitationResponse**](InvitationResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


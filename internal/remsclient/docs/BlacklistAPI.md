# \BlacklistAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiBlacklistAddPost**](BlacklistAPI.md#ApiBlacklistAddPost) | **Post** /api/blacklist/add | Add a blacklist entry (roles: handler, owner)
[**ApiBlacklistGet**](BlacklistAPI.md#ApiBlacklistGet) | **Get** /api/blacklist | Get blacklist entries (roles: handler, organization-owner, owner, reporter)
[**ApiBlacklistRemovePost**](BlacklistAPI.md#ApiBlacklistRemovePost) | **Post** /api/blacklist/remove | Remove a blacklist entry (roles: handler, owner)
[**ApiBlacklistUsersGet**](BlacklistAPI.md#ApiBlacklistUsersGet) | **Get** /api/blacklist/users | Existing REMS users available for adding to the blacklist (roles: handler, owner)



## ApiBlacklistAddPost

> SuccessResponse ApiBlacklistAddPost(ctx).BlacklistCommand(blacklistCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Add a blacklist entry (roles: handler, owner)

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
	blacklistCommand := *openapiclient.NewBlacklistCommand(*openapiclient.NewBlacklistCommandResource("ResourceExtId_example"), *openapiclient.NewUser("Userid_example"), "Comment_example") // BlacklistCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BlacklistAPI.ApiBlacklistAddPost(context.Background()).BlacklistCommand(blacklistCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BlacklistAPI.ApiBlacklistAddPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiBlacklistAddPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `BlacklistAPI.ApiBlacklistAddPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiBlacklistAddPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **blacklistCommand** | [**BlacklistCommand**](BlacklistCommand.md) |  | 
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


## ApiBlacklistGet

> []BlacklistEntryWithDetails ApiBlacklistGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).User(user).Resource(resource).Execute()

Get blacklist entries (roles: handler, organization-owner, owner, reporter)

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
	user := "user_example" // string |  (optional)
	resource := "resource_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BlacklistAPI.ApiBlacklistGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).User(user).Resource(resource).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BlacklistAPI.ApiBlacklistGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiBlacklistGet`: []BlacklistEntryWithDetails
	fmt.Fprintf(os.Stdout, "Response from `BlacklistAPI.ApiBlacklistGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiBlacklistGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **user** | **string** |  | 
 **resource** | **string** |  | 

### Return type

[**[]BlacklistEntryWithDetails**](BlacklistEntryWithDetails.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiBlacklistRemovePost

> SuccessResponse ApiBlacklistRemovePost(ctx).BlacklistCommand(blacklistCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Remove a blacklist entry (roles: handler, owner)

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
	blacklistCommand := *openapiclient.NewBlacklistCommand(*openapiclient.NewBlacklistCommandResource("ResourceExtId_example"), *openapiclient.NewUser("Userid_example"), "Comment_example") // BlacklistCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BlacklistAPI.ApiBlacklistRemovePost(context.Background()).BlacklistCommand(blacklistCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BlacklistAPI.ApiBlacklistRemovePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiBlacklistRemovePost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `BlacklistAPI.ApiBlacklistRemovePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiBlacklistRemovePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **blacklistCommand** | [**BlacklistCommand**](BlacklistCommand.md) |  | 
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


## ApiBlacklistUsersGet

> []UserWithAttributes ApiBlacklistUsersGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Existing REMS users available for adding to the blacklist (roles: handler, owner)

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
	resp, r, err := apiClient.BlacklistAPI.ApiBlacklistUsersGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BlacklistAPI.ApiBlacklistUsersGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiBlacklistUsersGet`: []UserWithAttributes
	fmt.Fprintf(os.Stdout, "Response from `BlacklistAPI.ApiBlacklistUsersGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiBlacklistUsersGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**[]UserWithAttributes**](UserWithAttributes.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


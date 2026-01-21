# \OrganizationsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiOrganizationsArchivedPut**](OrganizationsAPI.md#ApiOrganizationsArchivedPut) | **Put** /api/organizations/archived | Archive or unarchive the organization (roles: owner)
[**ApiOrganizationsAvailableOwnersGet**](OrganizationsAPI.md#ApiOrganizationsAvailableOwnersGet) | **Get** /api/organizations/available-owners | List of available owners (roles: organization-owner, owner)
[**ApiOrganizationsCreatePost**](OrganizationsAPI.md#ApiOrganizationsCreatePost) | **Post** /api/organizations/create | Create organization (roles: owner)
[**ApiOrganizationsEditPut**](OrganizationsAPI.md#ApiOrganizationsEditPut) | **Put** /api/organizations/edit | Edit organization. Organization owners cannot change the owners. (roles: organization-owner, owner)
[**ApiOrganizationsEnabledPut**](OrganizationsAPI.md#ApiOrganizationsEnabledPut) | **Put** /api/organizations/enabled | Enable or disable the organization (roles: owner)
[**ApiOrganizationsGet**](OrganizationsAPI.md#ApiOrganizationsGet) | **Get** /api/organizations | Get organizations. Returns more information for owners and handlers. (roles: logged-in)
[**ApiOrganizationsOrganizationIdGet**](OrganizationsAPI.md#ApiOrganizationsOrganizationIdGet) | **Get** /api/organizations/{organization-id} | Get an organization. Returns more information for owners and handlers. (roles: logged-in)



## ApiOrganizationsArchivedPut

> SuccessResponse ApiOrganizationsArchivedPut(ctx).OrganizationArchivedCommand(organizationArchivedCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Archive or unarchive the organization (roles: owner)

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
	organizationArchivedCommand := *openapiclient.NewOrganizationArchivedCommand("OrganizationId_example", false) // OrganizationArchivedCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganizationsAPI.ApiOrganizationsArchivedPut(context.Background()).OrganizationArchivedCommand(organizationArchivedCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganizationsAPI.ApiOrganizationsArchivedPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiOrganizationsArchivedPut`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `OrganizationsAPI.ApiOrganizationsArchivedPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiOrganizationsArchivedPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **organizationArchivedCommand** | [**OrganizationArchivedCommand**](OrganizationArchivedCommand.md) |  | 
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


## ApiOrganizationsAvailableOwnersGet

> []AvailableOwner ApiOrganizationsAvailableOwnersGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

List of available owners (roles: organization-owner, owner)

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
	resp, r, err := apiClient.OrganizationsAPI.ApiOrganizationsAvailableOwnersGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganizationsAPI.ApiOrganizationsAvailableOwnersGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiOrganizationsAvailableOwnersGet`: []AvailableOwner
	fmt.Fprintf(os.Stdout, "Response from `OrganizationsAPI.ApiOrganizationsAvailableOwnersGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiOrganizationsAvailableOwnersGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**[]AvailableOwner**](AvailableOwner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiOrganizationsCreatePost

> CreateOrganizationResponse ApiOrganizationsCreatePost(ctx).CreateOrganizationCommand(createOrganizationCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Create organization (roles: owner)

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
	createOrganizationCommand := *openapiclient.NewCreateOrganizationCommand("OrganizationId_example", map[string]string{"key": "Inner_example"}, map[string]string{"key": "Inner_example"}) // CreateOrganizationCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganizationsAPI.ApiOrganizationsCreatePost(context.Background()).CreateOrganizationCommand(createOrganizationCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganizationsAPI.ApiOrganizationsCreatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiOrganizationsCreatePost`: CreateOrganizationResponse
	fmt.Fprintf(os.Stdout, "Response from `OrganizationsAPI.ApiOrganizationsCreatePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiOrganizationsCreatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createOrganizationCommand** | [**CreateOrganizationCommand**](CreateOrganizationCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**CreateOrganizationResponse**](CreateOrganizationResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiOrganizationsEditPut

> EditOrganizationResponse ApiOrganizationsEditPut(ctx).EditOrganizationCommand(editOrganizationCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Edit organization. Organization owners cannot change the owners. (roles: organization-owner, owner)

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
	editOrganizationCommand := *openapiclient.NewEditOrganizationCommand("OrganizationId_example", map[string]string{"key": "Inner_example"}, map[string]string{"key": "Inner_example"}) // EditOrganizationCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganizationsAPI.ApiOrganizationsEditPut(context.Background()).EditOrganizationCommand(editOrganizationCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganizationsAPI.ApiOrganizationsEditPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiOrganizationsEditPut`: EditOrganizationResponse
	fmt.Fprintf(os.Stdout, "Response from `OrganizationsAPI.ApiOrganizationsEditPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiOrganizationsEditPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **editOrganizationCommand** | [**EditOrganizationCommand**](EditOrganizationCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**EditOrganizationResponse**](EditOrganizationResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiOrganizationsEnabledPut

> SuccessResponse ApiOrganizationsEnabledPut(ctx).OrganizationEnabledCommand(organizationEnabledCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Enable or disable the organization (roles: owner)

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
	organizationEnabledCommand := *openapiclient.NewOrganizationEnabledCommand("OrganizationId_example", false) // OrganizationEnabledCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganizationsAPI.ApiOrganizationsEnabledPut(context.Background()).OrganizationEnabledCommand(organizationEnabledCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganizationsAPI.ApiOrganizationsEnabledPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiOrganizationsEnabledPut`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `OrganizationsAPI.ApiOrganizationsEnabledPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiOrganizationsEnabledPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **organizationEnabledCommand** | [**OrganizationEnabledCommand**](OrganizationEnabledCommand.md) |  | 
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


## ApiOrganizationsGet

> []OrganizationFull ApiOrganizationsGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Owner(owner).Disabled(disabled).Archived(archived).Execute()

Get organizations. Returns more information for owners and handlers. (roles: logged-in)

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
	owner := "owner_example" // string | return only organizations that are owned by owner (optional)
	disabled := true // bool | whether to include disabled organizations (optional)
	archived := true // bool | whether to include archived organizations (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganizationsAPI.ApiOrganizationsGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Owner(owner).Disabled(disabled).Archived(archived).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganizationsAPI.ApiOrganizationsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiOrganizationsGet`: []OrganizationFull
	fmt.Fprintf(os.Stdout, "Response from `OrganizationsAPI.ApiOrganizationsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiOrganizationsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **owner** | **string** | return only organizations that are owned by owner | 
 **disabled** | **bool** | whether to include disabled organizations | 
 **archived** | **bool** | whether to include archived organizations | 

### Return type

[**[]OrganizationFull**](OrganizationFull.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiOrganizationsOrganizationIdGet

> OrganizationFull ApiOrganizationsOrganizationIdGet(ctx, organizationId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Get an organization. Returns more information for owners and handlers. (roles: logged-in)

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
	organizationId := "organizationId_example" // string | organization id
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OrganizationsAPI.ApiOrganizationsOrganizationIdGet(context.Background(), organizationId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OrganizationsAPI.ApiOrganizationsOrganizationIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiOrganizationsOrganizationIdGet`: OrganizationFull
	fmt.Fprintf(os.Stdout, "Response from `OrganizationsAPI.ApiOrganizationsOrganizationIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**organizationId** | **string** | organization id | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiOrganizationsOrganizationIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**OrganizationFull**](OrganizationFull.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


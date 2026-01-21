# \ResourcesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiResourcesArchivedPut**](ResourcesAPI.md#ApiResourcesArchivedPut) | **Put** /api/resources/archived | Archive or unarchive resource (roles: organization-owner, owner)
[**ApiResourcesCreatePost**](ResourcesAPI.md#ApiResourcesCreatePost) | **Post** /api/resources/create | Create resource (roles: organization-owner, owner)
[**ApiResourcesDuoCodesGet**](ResourcesAPI.md#ApiResourcesDuoCodesGet) | **Get** /api/resources/duo-codes | Get DUO codes (roles: logged-in)
[**ApiResourcesEnabledPut**](ResourcesAPI.md#ApiResourcesEnabledPut) | **Put** /api/resources/enabled | Enable or disable resource (roles: organization-owner, owner)
[**ApiResourcesGet**](ResourcesAPI.md#ApiResourcesGet) | **Get** /api/resources | Get resources (roles: handler, organization-owner, owner, reporter)
[**ApiResourcesMondoCodesGet**](ResourcesAPI.md#ApiResourcesMondoCodesGet) | **Get** /api/resources/mondo-codes | Get Mondo codes (roles: logged-in)
[**ApiResourcesResourceIdGet**](ResourcesAPI.md#ApiResourcesResourceIdGet) | **Get** /api/resources/{resource-id} | Get resource by id (roles: handler, organization-owner, owner, reporter)
[**ApiResourcesSearchMondoCodesGet**](ResourcesAPI.md#ApiResourcesSearchMondoCodesGet) | **Get** /api/resources/search-mondo-codes | Search Mondo codes, maximum 100 results (roles: logged-in)



## ApiResourcesArchivedPut

> SuccessResponse ApiResourcesArchivedPut(ctx).ArchivedCommand(archivedCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Archive or unarchive resource (roles: organization-owner, owner)

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
	archivedCommand := *openapiclient.NewArchivedCommand(int64(123), false) // ArchivedCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResourcesAPI.ApiResourcesArchivedPut(context.Background()).ArchivedCommand(archivedCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResourcesAPI.ApiResourcesArchivedPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiResourcesArchivedPut`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ResourcesAPI.ApiResourcesArchivedPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiResourcesArchivedPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **archivedCommand** | [**ArchivedCommand**](ArchivedCommand.md) |  | 
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


## ApiResourcesCreatePost

> CreateResourceResponse ApiResourcesCreatePost(ctx).CreateResourceCommand(createResourceCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Create resource (roles: organization-owner, owner)

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
	createResourceCommand := *openapiclient.NewCreateResourceCommand("Resid_example", *openapiclient.NewOrganizationId("OrganizationId_example"), []int64{int64(123)}) // CreateResourceCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResourcesAPI.ApiResourcesCreatePost(context.Background()).CreateResourceCommand(createResourceCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResourcesAPI.ApiResourcesCreatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiResourcesCreatePost`: CreateResourceResponse
	fmt.Fprintf(os.Stdout, "Response from `ResourcesAPI.ApiResourcesCreatePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiResourcesCreatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createResourceCommand** | [**CreateResourceCommand**](CreateResourceCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**CreateResourceResponse**](CreateResourceResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiResourcesDuoCodesGet

> []DuoCodeFull ApiResourcesDuoCodesGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Get DUO codes (roles: logged-in)

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
	resp, r, err := apiClient.ResourcesAPI.ApiResourcesDuoCodesGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResourcesAPI.ApiResourcesDuoCodesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiResourcesDuoCodesGet`: []DuoCodeFull
	fmt.Fprintf(os.Stdout, "Response from `ResourcesAPI.ApiResourcesDuoCodesGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiResourcesDuoCodesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**[]DuoCodeFull**](DuoCodeFull.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiResourcesEnabledPut

> SuccessResponse ApiResourcesEnabledPut(ctx).EnabledCommand(enabledCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Enable or disable resource (roles: organization-owner, owner)

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
	enabledCommand := *openapiclient.NewEnabledCommand(int64(123), false) // EnabledCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResourcesAPI.ApiResourcesEnabledPut(context.Background()).EnabledCommand(enabledCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResourcesAPI.ApiResourcesEnabledPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiResourcesEnabledPut`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ResourcesAPI.ApiResourcesEnabledPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiResourcesEnabledPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **enabledCommand** | [**EnabledCommand**](EnabledCommand.md) |  | 
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


## ApiResourcesGet

> []Resource ApiResourcesGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Disabled(disabled).Archived(archived).Resid(resid).Execute()

Get resources (roles: handler, organization-owner, owner, reporter)

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
	disabled := true // bool | whether to include disabled resources (optional)
	archived := true // bool | whether to include archived resources (optional)
	resid := "resid_example" // string | optionally filter by resid (external resource identifier) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResourcesAPI.ApiResourcesGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Disabled(disabled).Archived(archived).Resid(resid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResourcesAPI.ApiResourcesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiResourcesGet`: []Resource
	fmt.Fprintf(os.Stdout, "Response from `ResourcesAPI.ApiResourcesGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiResourcesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **disabled** | **bool** | whether to include disabled resources | 
 **archived** | **bool** | whether to include archived resources | 
 **resid** | **string** | optionally filter by resid (external resource identifier) | 

### Return type

[**[]Resource**](Resource.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiResourcesMondoCodesGet

> []MondoCodeFull ApiResourcesMondoCodesGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Get Mondo codes (roles: logged-in)

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
	resp, r, err := apiClient.ResourcesAPI.ApiResourcesMondoCodesGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResourcesAPI.ApiResourcesMondoCodesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiResourcesMondoCodesGet`: []MondoCodeFull
	fmt.Fprintf(os.Stdout, "Response from `ResourcesAPI.ApiResourcesMondoCodesGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiResourcesMondoCodesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**[]MondoCodeFull**](MondoCodeFull.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiResourcesResourceIdGet

> Resource ApiResourcesResourceIdGet(ctx, resourceId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Get resource by id (roles: handler, organization-owner, owner, reporter)

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
	resourceId := int64(789) // int64 | resource id
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResourcesAPI.ApiResourcesResourceIdGet(context.Background(), resourceId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResourcesAPI.ApiResourcesResourceIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiResourcesResourceIdGet`: Resource
	fmt.Fprintf(os.Stdout, "Response from `ResourcesAPI.ApiResourcesResourceIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**resourceId** | **int64** | resource id | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiResourcesResourceIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**Resource**](Resource.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiResourcesSearchMondoCodesGet

> []MondoCodeFull ApiResourcesSearchMondoCodesGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).SearchText(searchText).Execute()

Search Mondo codes, maximum 100 results (roles: logged-in)

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
	searchText := "searchText_example" // string | text to be contained in id or label of the code (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResourcesAPI.ApiResourcesSearchMondoCodesGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).SearchText(searchText).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResourcesAPI.ApiResourcesSearchMondoCodesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiResourcesSearchMondoCodesGet`: []MondoCodeFull
	fmt.Fprintf(os.Stdout, "Response from `ResourcesAPI.ApiResourcesSearchMondoCodesGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiResourcesSearchMondoCodesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **searchText** | **string** | text to be contained in id or label of the code | 

### Return type

[**[]MondoCodeFull**](MondoCodeFull.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


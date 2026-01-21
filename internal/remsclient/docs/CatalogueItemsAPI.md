# \CatalogueItemsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiCatalogueItemsArchivedPut**](CatalogueItemsAPI.md#ApiCatalogueItemsArchivedPut) | **Put** /api/catalogue-items/archived | Archive or unarchive catalogue item (roles: organization-owner, owner)
[**ApiCatalogueItemsCreatePost**](CatalogueItemsAPI.md#ApiCatalogueItemsCreatePost) | **Post** /api/catalogue-items/create | Create a new catalogue item (roles: organization-owner, owner)
[**ApiCatalogueItemsEditPut**](CatalogueItemsAPI.md#ApiCatalogueItemsEditPut) | **Put** /api/catalogue-items/edit | Edit a catalogue item (roles: organization-owner, owner)
[**ApiCatalogueItemsEnabledPut**](CatalogueItemsAPI.md#ApiCatalogueItemsEnabledPut) | **Put** /api/catalogue-items/enabled | Enable or disable catalogue item (roles: organization-owner, owner)
[**ApiCatalogueItemsGet**](CatalogueItemsAPI.md#ApiCatalogueItemsGet) | **Get** /api/catalogue-items | Get catalogue items (roles: logged-in)
[**ApiCatalogueItemsItemIdChangeFormPost**](CatalogueItemsAPI.md#ApiCatalogueItemsItemIdChangeFormPost) | **Post** /api/catalogue-items/{item-id}/change-form | Change catalogue item form. Creates a copy and ends the old. DEPRECATED, will disappear, use /update instead (roles: organization-owner, owner)
[**ApiCatalogueItemsItemIdGet**](CatalogueItemsAPI.md#ApiCatalogueItemsItemIdGet) | **Get** /api/catalogue-items/{item-id} | Get a single catalogue item
[**ApiCatalogueItemsItemIdUpdatePost**](CatalogueItemsAPI.md#ApiCatalogueItemsItemIdUpdatePost) | **Post** /api/catalogue-items/{item-id}/update | Update a catalogue item allowing to change form and workflow. Creates a copy and ends the old. (roles: organization-owner, owner)



## ApiCatalogueItemsArchivedPut

> SuccessResponse ApiCatalogueItemsArchivedPut(ctx).ArchivedCommand(archivedCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Archive or unarchive catalogue item (roles: organization-owner, owner)

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
	resp, r, err := apiClient.CatalogueItemsAPI.ApiCatalogueItemsArchivedPut(context.Background()).ArchivedCommand(archivedCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CatalogueItemsAPI.ApiCatalogueItemsArchivedPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiCatalogueItemsArchivedPut`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `CatalogueItemsAPI.ApiCatalogueItemsArchivedPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiCatalogueItemsArchivedPutRequest struct via the builder pattern


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


## ApiCatalogueItemsCreatePost

> CreateCatalogueItemResponse ApiCatalogueItemsCreatePost(ctx).CreateCatalogueItemCommand(createCatalogueItemCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Create a new catalogue item (roles: organization-owner, owner)

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
	createCatalogueItemCommand := *openapiclient.NewCreateCatalogueItemCommand(int64(123), int64(123), *openapiclient.NewOrganizationId("OrganizationId_example"), map[string]CatalogueItemLocalization{"key": *openapiclient.NewCatalogueItemLocalization("Title_example")}) // CreateCatalogueItemCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CatalogueItemsAPI.ApiCatalogueItemsCreatePost(context.Background()).CreateCatalogueItemCommand(createCatalogueItemCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CatalogueItemsAPI.ApiCatalogueItemsCreatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiCatalogueItemsCreatePost`: CreateCatalogueItemResponse
	fmt.Fprintf(os.Stdout, "Response from `CatalogueItemsAPI.ApiCatalogueItemsCreatePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiCatalogueItemsCreatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCatalogueItemCommand** | [**CreateCatalogueItemCommand**](CreateCatalogueItemCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**CreateCatalogueItemResponse**](CreateCatalogueItemResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiCatalogueItemsEditPut

> SuccessResponse ApiCatalogueItemsEditPut(ctx).EditCatalogueItemCommand(editCatalogueItemCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Edit a catalogue item (roles: organization-owner, owner)

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
	editCatalogueItemCommand := *openapiclient.NewEditCatalogueItemCommand(int64(123), map[string]CatalogueItemLocalization{"key": *openapiclient.NewCatalogueItemLocalization("Title_example")}) // EditCatalogueItemCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CatalogueItemsAPI.ApiCatalogueItemsEditPut(context.Background()).EditCatalogueItemCommand(editCatalogueItemCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CatalogueItemsAPI.ApiCatalogueItemsEditPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiCatalogueItemsEditPut`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `CatalogueItemsAPI.ApiCatalogueItemsEditPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiCatalogueItemsEditPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **editCatalogueItemCommand** | [**EditCatalogueItemCommand**](EditCatalogueItemCommand.md) |  | 
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


## ApiCatalogueItemsEnabledPut

> SuccessResponse ApiCatalogueItemsEnabledPut(ctx).EnabledCommand(enabledCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Enable or disable catalogue item (roles: organization-owner, owner)

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
	resp, r, err := apiClient.CatalogueItemsAPI.ApiCatalogueItemsEnabledPut(context.Background()).EnabledCommand(enabledCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CatalogueItemsAPI.ApiCatalogueItemsEnabledPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiCatalogueItemsEnabledPut`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `CatalogueItemsAPI.ApiCatalogueItemsEnabledPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiCatalogueItemsEnabledPutRequest struct via the builder pattern


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


## ApiCatalogueItemsGet

> []CatalogueItem ApiCatalogueItemsGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Resource(resource).Expand(expand).Archived(archived).Disabled(disabled).Expired(expired).Execute()

Get catalogue items (roles: logged-in)

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
	resource := "resource_example" // string | resource id (optional) (optional)
	expand := "expand_example" // string | expanded additional attributes (optional), can be \"names\" (optional)
	archived := true // bool | whether to include archived items (optional)
	disabled := true // bool | whether to include disabled items (optional)
	expired := true // bool | whether to include expired items (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CatalogueItemsAPI.ApiCatalogueItemsGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Resource(resource).Expand(expand).Archived(archived).Disabled(disabled).Expired(expired).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CatalogueItemsAPI.ApiCatalogueItemsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiCatalogueItemsGet`: []CatalogueItem
	fmt.Fprintf(os.Stdout, "Response from `CatalogueItemsAPI.ApiCatalogueItemsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiCatalogueItemsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **resource** | **string** | resource id (optional) | 
 **expand** | **string** | expanded additional attributes (optional), can be \&quot;names\&quot; | 
 **archived** | **bool** | whether to include archived items | 
 **disabled** | **bool** | whether to include disabled items | 
 **expired** | **bool** | whether to include expired items | 

### Return type

[**[]CatalogueItem**](CatalogueItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiCatalogueItemsItemIdChangeFormPost

> ChangeFormResponse ApiCatalogueItemsItemIdChangeFormPost(ctx, itemId).ChangeFormCommand(changeFormCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Change catalogue item form. Creates a copy and ends the old. DEPRECATED, will disappear, use /update instead (roles: organization-owner, owner)

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
	itemId := int64(789) // int64 | catalogue item
	changeFormCommand := *openapiclient.NewChangeFormCommand(NullableInt64(123)) // ChangeFormCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CatalogueItemsAPI.ApiCatalogueItemsItemIdChangeFormPost(context.Background(), itemId).ChangeFormCommand(changeFormCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CatalogueItemsAPI.ApiCatalogueItemsItemIdChangeFormPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiCatalogueItemsItemIdChangeFormPost`: ChangeFormResponse
	fmt.Fprintf(os.Stdout, "Response from `CatalogueItemsAPI.ApiCatalogueItemsItemIdChangeFormPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**itemId** | **int64** | catalogue item | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiCatalogueItemsItemIdChangeFormPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **changeFormCommand** | [**ChangeFormCommand**](ChangeFormCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**ChangeFormResponse**](ChangeFormResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiCatalogueItemsItemIdGet

> CatalogueItem ApiCatalogueItemsItemIdGet(ctx, itemId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Get a single catalogue item

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
	itemId := int64(789) // int64 | catalogue item
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CatalogueItemsAPI.ApiCatalogueItemsItemIdGet(context.Background(), itemId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CatalogueItemsAPI.ApiCatalogueItemsItemIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiCatalogueItemsItemIdGet`: CatalogueItem
	fmt.Fprintf(os.Stdout, "Response from `CatalogueItemsAPI.ApiCatalogueItemsItemIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**itemId** | **int64** | catalogue item | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiCatalogueItemsItemIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**CatalogueItem**](CatalogueItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiCatalogueItemsItemIdUpdatePost

> UpdateCatalogueItemResponse ApiCatalogueItemsItemIdUpdatePost(ctx, itemId).UpdateCatalogueItemCommand(updateCatalogueItemCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Update a catalogue item allowing to change form and workflow. Creates a copy and ends the old. (roles: organization-owner, owner)

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
	itemId := int64(789) // int64 | catalogue item
	updateCatalogueItemCommand := *openapiclient.NewUpdateCatalogueItemCommand() // UpdateCatalogueItemCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CatalogueItemsAPI.ApiCatalogueItemsItemIdUpdatePost(context.Background(), itemId).UpdateCatalogueItemCommand(updateCatalogueItemCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CatalogueItemsAPI.ApiCatalogueItemsItemIdUpdatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiCatalogueItemsItemIdUpdatePost`: UpdateCatalogueItemResponse
	fmt.Fprintf(os.Stdout, "Response from `CatalogueItemsAPI.ApiCatalogueItemsItemIdUpdatePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**itemId** | **int64** | catalogue item | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiCatalogueItemsItemIdUpdatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateCatalogueItemCommand** | [**UpdateCatalogueItemCommand**](UpdateCatalogueItemCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**UpdateCatalogueItemResponse**](UpdateCatalogueItemResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


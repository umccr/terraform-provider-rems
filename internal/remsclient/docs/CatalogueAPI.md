# \CatalogueAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiCatalogueGet**](CatalogueAPI.md#ApiCatalogueGet) | **Get** /api/catalogue | Get the catalogue of items for the UI (does not include archived items)
[**ApiCatalogueTreeGet**](CatalogueAPI.md#ApiCatalogueTreeGet) | **Get** /api/catalogue/tree | Get the catalogue of items in a tree for the UI (does not include archived items)



## ApiCatalogueGet

> []CatalogueItem ApiCatalogueGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).JoinOrganization(joinOrganization).Execute()

Get the catalogue of items for the UI (does not include archived items)

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
	joinOrganization := true // bool | Should organizations be returned for each item? (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CatalogueAPI.ApiCatalogueGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).JoinOrganization(joinOrganization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CatalogueAPI.ApiCatalogueGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiCatalogueGet`: []CatalogueItem
	fmt.Fprintf(os.Stdout, "Response from `CatalogueAPI.ApiCatalogueGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiCatalogueGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **joinOrganization** | **bool** | Should organizations be returned for each item? | 

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


## ApiCatalogueTreeGet

> GetCatalogueTreeResponse ApiCatalogueTreeGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).JoinOrganization(joinOrganization).Execute()

Get the catalogue of items in a tree for the UI (does not include archived items)

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
	joinOrganization := true // bool | Should organizations be returned for each item? (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CatalogueAPI.ApiCatalogueTreeGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).JoinOrganization(joinOrganization).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CatalogueAPI.ApiCatalogueTreeGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiCatalogueTreeGet`: GetCatalogueTreeResponse
	fmt.Fprintf(os.Stdout, "Response from `CatalogueAPI.ApiCatalogueTreeGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiCatalogueTreeGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **joinOrganization** | **bool** | Should organizations be returned for each item? | 

### Return type

[**GetCatalogueTreeResponse**](GetCatalogueTreeResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


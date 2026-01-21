# \EntitlementsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiEntitlementsExportCsvGet**](EntitlementsAPI.md#ApiEntitlementsExportCsvGet) | **Get** /api/entitlements/export-csv | Return entitlements as CSV string. With proper privileges gets all entitlements, otherwise returns user&#39;s own entitlements. (roles: handler, reporter)
[**ApiEntitlementsGet**](EntitlementsAPI.md#ApiEntitlementsGet) | **Get** /api/entitlements | With proper privileges gets all entitlements, otherwise returns user&#39;s own entitlements. (roles: logged-in)



## ApiEntitlementsExportCsvGet

> string ApiEntitlementsExportCsvGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).User(user).Resource(resource).Expired(expired).Separator(separator).Execute()

Return entitlements as CSV string. With proper privileges gets all entitlements, otherwise returns user's own entitlements. (roles: handler, reporter)

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
	user := "user_example" // string | return entitlements for this user (optional), ignored if the user doesn't have appropriate privileges (optional)
	resource := "resource_example" // string | return entitlements for this resource (optional) (optional)
	expired := true // bool | whether to include expired entitlements (optional)
	separator := "separator_example" // string | which separator to use in returned csv (optional) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EntitlementsAPI.ApiEntitlementsExportCsvGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).User(user).Resource(resource).Expired(expired).Separator(separator).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EntitlementsAPI.ApiEntitlementsExportCsvGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiEntitlementsExportCsvGet`: string
	fmt.Fprintf(os.Stdout, "Response from `EntitlementsAPI.ApiEntitlementsExportCsvGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiEntitlementsExportCsvGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **user** | **string** | return entitlements for this user (optional), ignored if the user doesn&#39;t have appropriate privileges | 
 **resource** | **string** | return entitlements for this resource (optional) | 
 **expired** | **bool** | whether to include expired entitlements | 
 **separator** | **string** | which separator to use in returned csv (optional) | 

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/csv

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiEntitlementsGet

> []Entitlement ApiEntitlementsGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).User(user).Resource(resource).Expired(expired).Execute()

With proper privileges gets all entitlements, otherwise returns user's own entitlements. (roles: logged-in)

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
	user := "user_example" // string | return entitlements for this user (optional), ignored if the user doesn't have appropriate privileges (optional)
	resource := "resource_example" // string | return entitlements for this resource (optional) (optional)
	expired := true // bool | whether to include expired entitlements (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EntitlementsAPI.ApiEntitlementsGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).User(user).Resource(resource).Expired(expired).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EntitlementsAPI.ApiEntitlementsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiEntitlementsGet`: []Entitlement
	fmt.Fprintf(os.Stdout, "Response from `EntitlementsAPI.ApiEntitlementsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiEntitlementsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **user** | **string** | return entitlements for this user (optional), ignored if the user doesn&#39;t have appropriate privileges | 
 **resource** | **string** | return entitlements for this resource (optional) | 
 **expired** | **bool** | whether to include expired entitlements | 

### Return type

[**[]Entitlement**](Entitlement.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


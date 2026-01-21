# \HealthAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiHealthGet**](HealthAPI.md#ApiHealthGet) | **Get** /api/health | Health check



## ApiHealthGet

> Health ApiHealthGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Health check

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
	resp, r, err := apiClient.HealthAPI.ApiHealthGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HealthAPI.ApiHealthGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiHealthGet`: Health
	fmt.Fprintf(os.Stdout, "Response from `HealthAPI.ApiHealthGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiHealthGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**Health**](Health.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


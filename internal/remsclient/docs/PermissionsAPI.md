# \PermissionsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiJwkGet**](PermissionsAPI.md#ApiJwkGet) | **Get** /api/jwk | Get JSON Web Key Set (JWKS) (RFC 7517) containing the keys used for signing GA4GH Visas.
[**ApiPermissionsUserGet**](PermissionsAPI.md#ApiPermissionsUserGet) | **Get** /api/permissions/{user} | Returns user&#39;s permissions in ga4gh visa format. Handlers, owners and reporters can query anybody&#39;s permissions. Other users can query their own permissions. See also https://github.com/CSCfi/rems/blob/master/docs/ga4gh-visas.md (roles: logged-in)



## ApiJwkGet

> GetJWKSResponse ApiJwkGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Get JSON Web Key Set (JWKS) (RFC 7517) containing the keys used for signing GA4GH Visas.

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
	resp, r, err := apiClient.PermissionsAPI.ApiJwkGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PermissionsAPI.ApiJwkGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiJwkGet`: GetJWKSResponse
	fmt.Fprintf(os.Stdout, "Response from `PermissionsAPI.ApiJwkGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiJwkGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**GetJWKSResponse**](GetJWKSResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiPermissionsUserGet

> GetPermissionsResponse ApiPermissionsUserGet(ctx, user).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Expired(expired).Execute()

Returns user's permissions in ga4gh visa format. Handlers, owners and reporters can query anybody's permissions. Other users can query their own permissions. See also https://github.com/CSCfi/rems/blob/master/docs/ga4gh-visas.md (roles: logged-in)

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
	user := "user_example" // string | return permissions for this user, required
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)
	expired := true // bool | whether to include expired permissions (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PermissionsAPI.ApiPermissionsUserGet(context.Background(), user).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Expired(expired).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PermissionsAPI.ApiPermissionsUserGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiPermissionsUserGet`: GetPermissionsResponse
	fmt.Fprintf(os.Stdout, "Response from `PermissionsAPI.ApiPermissionsUserGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**user** | **string** | return permissions for this user, required | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiPermissionsUserGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **expired** | **bool** | whether to include expired permissions | 

### Return type

[**GetPermissionsResponse**](GetPermissionsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


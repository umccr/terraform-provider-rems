# \AuditLogAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiAuditLogGet**](AuditLogAPI.md#ApiAuditLogGet) | **Get** /api/audit-log | Get audit log entries (roles: reporter)



## ApiAuditLogGet

> []AuditLogEntry ApiAuditLogGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Userid(userid).ApplicationId(applicationId).After(after).Before(before).Execute()

Get audit log entries (roles: reporter)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)
	userid := "userid_example" // string | Only show entries for this user (optional)
	applicationId := "applicationId_example" // string | Only show requests for `/api/application/<application>*` endpoints (optional)
	after := time.Now() // time.Time | Only show entries after this time (optional)
	before := time.Now() // time.Time | Only show entries before this time (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuditLogAPI.ApiAuditLogGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Userid(userid).ApplicationId(applicationId).After(after).Before(before).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuditLogAPI.ApiAuditLogGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiAuditLogGet`: []AuditLogEntry
	fmt.Fprintf(os.Stdout, "Response from `AuditLogAPI.ApiAuditLogGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiAuditLogGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **userid** | **string** | Only show entries for this user | 
 **applicationId** | **string** | Only show requests for &#x60;/api/application/&lt;application&gt;*&#x60; endpoints | 
 **after** | **time.Time** | Only show entries after this time | 
 **before** | **time.Time** | Only show entries before this time | 

### Return type

[**[]AuditLogEntry**](AuditLogEntry.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


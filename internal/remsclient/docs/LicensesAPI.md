# \LicensesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiLicensesAddAttachmentPost**](LicensesAPI.md#ApiLicensesAddAttachmentPost) | **Post** /api/licenses/add_attachment | Add an attachment file that will be used in a license (roles: organization-owner, owner)
[**ApiLicensesArchivedPut**](LicensesAPI.md#ApiLicensesArchivedPut) | **Put** /api/licenses/archived | Archive or unarchive license (roles: organization-owner, owner)
[**ApiLicensesAttachmentsAttachmentIdGet**](LicensesAPI.md#ApiLicensesAttachmentsAttachmentIdGet) | **Get** /api/licenses/attachments/{attachment-id} | Get a license&#39;s attachment (roles: organization-owner, owner)
[**ApiLicensesCreatePost**](LicensesAPI.md#ApiLicensesCreatePost) | **Post** /api/licenses/create | Create license (roles: organization-owner, owner)
[**ApiLicensesEnabledPut**](LicensesAPI.md#ApiLicensesEnabledPut) | **Put** /api/licenses/enabled | Enable or disable license (roles: organization-owner, owner)
[**ApiLicensesGet**](LicensesAPI.md#ApiLicensesGet) | **Get** /api/licenses | Get licenses (roles: handler, organization-owner, owner, reporter)
[**ApiLicensesLicenseIdGet**](LicensesAPI.md#ApiLicensesLicenseIdGet) | **Get** /api/licenses/{license-id} | Get license (roles: handler, organization-owner, owner, reporter)
[**ApiLicensesRemoveAttachmentPost**](LicensesAPI.md#ApiLicensesRemoveAttachmentPost) | **Post** /api/licenses/remove_attachment | Remove an attachment that could have been used in a license. (roles: organization-owner, owner)



## ApiLicensesAddAttachmentPost

> AddLicenseAttachmentResponse ApiLicensesAddAttachmentPost(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).UNKNOWN_PARAMETER_NAME(UNKNOWN_PARAMETER_NAME).Execute()

Add an attachment file that will be used in a license (roles: organization-owner, owner)

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
	UNKNOWN_PARAMETER_NAME := TODO //  |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicensesAPI.ApiLicensesAddAttachmentPost(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).UNKNOWN_PARAMETER_NAME(UNKNOWN_PARAMETER_NAME).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicensesAPI.ApiLicensesAddAttachmentPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiLicensesAddAttachmentPost`: AddLicenseAttachmentResponse
	fmt.Fprintf(os.Stdout, "Response from `LicensesAPI.ApiLicensesAddAttachmentPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiLicensesAddAttachmentPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **UNKNOWN_PARAMETER_NAME** | [****](.md) |  | 

### Return type

[**AddLicenseAttachmentResponse**](AddLicenseAttachmentResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiLicensesArchivedPut

> SuccessResponse ApiLicensesArchivedPut(ctx).ArchivedCommand(archivedCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Archive or unarchive license (roles: organization-owner, owner)

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
	resp, r, err := apiClient.LicensesAPI.ApiLicensesArchivedPut(context.Background()).ArchivedCommand(archivedCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicensesAPI.ApiLicensesArchivedPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiLicensesArchivedPut`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `LicensesAPI.ApiLicensesArchivedPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiLicensesArchivedPutRequest struct via the builder pattern


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


## ApiLicensesAttachmentsAttachmentIdGet

> ApiLicensesAttachmentsAttachmentIdGet(ctx, attachmentId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Get a license's attachment (roles: organization-owner, owner)

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
	attachmentId := int64(789) // int64 | attachment id
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.LicensesAPI.ApiLicensesAttachmentsAttachmentIdGet(context.Background(), attachmentId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicensesAPI.ApiLicensesAttachmentsAttachmentIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**attachmentId** | **int64** | attachment id | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiLicensesAttachmentsAttachmentIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiLicensesCreatePost

> CreateLicenseResponse ApiLicensesCreatePost(ctx).CreateLicenseCommand(createLicenseCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Create license (roles: organization-owner, owner)

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
	createLicenseCommand := *openapiclient.NewCreateLicenseCommand("Licensetype_example", *openapiclient.NewOrganizationId("OrganizationId_example"), map[string]LicenseLocalization{"key": *openapiclient.NewLicenseLocalization("Title_example", "Textcontent_example")}) // CreateLicenseCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicensesAPI.ApiLicensesCreatePost(context.Background()).CreateLicenseCommand(createLicenseCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicensesAPI.ApiLicensesCreatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiLicensesCreatePost`: CreateLicenseResponse
	fmt.Fprintf(os.Stdout, "Response from `LicensesAPI.ApiLicensesCreatePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiLicensesCreatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createLicenseCommand** | [**CreateLicenseCommand**](CreateLicenseCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**CreateLicenseResponse**](CreateLicenseResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiLicensesEnabledPut

> SuccessResponse ApiLicensesEnabledPut(ctx).EnabledCommand(enabledCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Enable or disable license (roles: organization-owner, owner)

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
	resp, r, err := apiClient.LicensesAPI.ApiLicensesEnabledPut(context.Background()).EnabledCommand(enabledCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicensesAPI.ApiLicensesEnabledPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiLicensesEnabledPut`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `LicensesAPI.ApiLicensesEnabledPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiLicensesEnabledPutRequest struct via the builder pattern


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


## ApiLicensesGet

> []License ApiLicensesGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Disabled(disabled).Archived(archived).Execute()

Get licenses (roles: handler, organization-owner, owner, reporter)

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
	disabled := true // bool | whether to include disabled licenses (optional)
	archived := true // bool | whether to include archived licenses (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicensesAPI.ApiLicensesGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Disabled(disabled).Archived(archived).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicensesAPI.ApiLicensesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiLicensesGet`: []License
	fmt.Fprintf(os.Stdout, "Response from `LicensesAPI.ApiLicensesGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiLicensesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **disabled** | **bool** | whether to include disabled licenses | 
 **archived** | **bool** | whether to include archived licenses | 

### Return type

[**[]License**](License.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiLicensesLicenseIdGet

> License ApiLicensesLicenseIdGet(ctx, licenseId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Get license (roles: handler, organization-owner, owner, reporter)

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
	licenseId := int64(789) // int64 | license id
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicensesAPI.ApiLicensesLicenseIdGet(context.Background(), licenseId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicensesAPI.ApiLicensesLicenseIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiLicensesLicenseIdGet`: License
	fmt.Fprintf(os.Stdout, "Response from `LicensesAPI.ApiLicensesLicenseIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**licenseId** | **int64** | license id | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiLicensesLicenseIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**License**](License.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiLicensesRemoveAttachmentPost

> SuccessResponse ApiLicensesRemoveAttachmentPost(ctx).AttachmentId(attachmentId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Remove an attachment that could have been used in a license. (roles: organization-owner, owner)

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
	attachmentId := int64(789) // int64 | attachment id
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LicensesAPI.ApiLicensesRemoveAttachmentPost(context.Background()).AttachmentId(attachmentId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LicensesAPI.ApiLicensesRemoveAttachmentPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiLicensesRemoveAttachmentPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `LicensesAPI.ApiLicensesRemoveAttachmentPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiLicensesRemoveAttachmentPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **attachmentId** | **int64** | attachment id | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


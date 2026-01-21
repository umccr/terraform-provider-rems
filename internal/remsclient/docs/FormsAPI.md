# \FormsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiFormsArchivedPut**](FormsAPI.md#ApiFormsArchivedPut) | **Put** /api/forms/archived | Archive or unarchive form (roles: organization-owner, owner)
[**ApiFormsCreatePost**](FormsAPI.md#ApiFormsCreatePost) | **Post** /api/forms/create | Create form (roles: organization-owner, owner)
[**ApiFormsEditPut**](FormsAPI.md#ApiFormsEditPut) | **Put** /api/forms/edit | Edit form (roles: organization-owner, owner)
[**ApiFormsEnabledPut**](FormsAPI.md#ApiFormsEnabledPut) | **Put** /api/forms/enabled | Enable or disable form (roles: organization-owner, owner)
[**ApiFormsFormIdEditableGet**](FormsAPI.md#ApiFormsFormIdEditableGet) | **Get** /api/forms/{form-id}/editable | Check if the form is editable (roles: organization-owner, owner)
[**ApiFormsFormIdGet**](FormsAPI.md#ApiFormsFormIdGet) | **Get** /api/forms/{form-id} | Get form by id (roles: handler, organization-owner, owner, reporter)
[**ApiFormsGet**](FormsAPI.md#ApiFormsGet) | **Get** /api/forms | Get forms (roles: handler, organization-owner, owner, reporter)



## ApiFormsArchivedPut

> SuccessResponse ApiFormsArchivedPut(ctx).ArchivedCommand(archivedCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Archive or unarchive form (roles: organization-owner, owner)

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
	resp, r, err := apiClient.FormsAPI.ApiFormsArchivedPut(context.Background()).ArchivedCommand(archivedCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FormsAPI.ApiFormsArchivedPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiFormsArchivedPut`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `FormsAPI.ApiFormsArchivedPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiFormsArchivedPutRequest struct via the builder pattern


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


## ApiFormsCreatePost

> CreateFormResponse ApiFormsCreatePost(ctx).CreateFormCommand(createFormCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Create form (roles: organization-owner, owner)

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
	createFormCommand := *openapiclient.NewCreateFormCommand(*openapiclient.NewOrganizationId("OrganizationId_example"), []openapiclient.NewFieldTemplate{*openapiclient.NewNewFieldTemplate(map[string]string{"key": "Inner_example"}, "FieldType_example", false)}) // CreateFormCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FormsAPI.ApiFormsCreatePost(context.Background()).CreateFormCommand(createFormCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FormsAPI.ApiFormsCreatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiFormsCreatePost`: CreateFormResponse
	fmt.Fprintf(os.Stdout, "Response from `FormsAPI.ApiFormsCreatePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiFormsCreatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createFormCommand** | [**CreateFormCommand**](CreateFormCommand.md) |  | 
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**CreateFormResponse**](CreateFormResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, application/transit+msgpack, application/transit+json, application/edn
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiFormsEditPut

> SuccessResponse ApiFormsEditPut(ctx).EditFormCommand(editFormCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Edit form (roles: organization-owner, owner)

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
	editFormCommand := *openapiclient.NewEditFormCommand(*openapiclient.NewOrganizationId("OrganizationId_example"), []openapiclient.NewFieldTemplate{*openapiclient.NewNewFieldTemplate(map[string]string{"key": "Inner_example"}, "FieldType_example", false)}, int64(123)) // EditFormCommand | 
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FormsAPI.ApiFormsEditPut(context.Background()).EditFormCommand(editFormCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FormsAPI.ApiFormsEditPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiFormsEditPut`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `FormsAPI.ApiFormsEditPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiFormsEditPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **editFormCommand** | [**EditFormCommand**](EditFormCommand.md) |  | 
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


## ApiFormsEnabledPut

> SuccessResponse ApiFormsEnabledPut(ctx).EnabledCommand(enabledCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Enable or disable form (roles: organization-owner, owner)

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
	resp, r, err := apiClient.FormsAPI.ApiFormsEnabledPut(context.Background()).EnabledCommand(enabledCommand).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FormsAPI.ApiFormsEnabledPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiFormsEnabledPut`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `FormsAPI.ApiFormsEnabledPut`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiFormsEnabledPutRequest struct via the builder pattern


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


## ApiFormsFormIdEditableGet

> SuccessResponse ApiFormsFormIdEditableGet(ctx, formId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Check if the form is editable (roles: organization-owner, owner)

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
	formId := int64(789) // int64 | form-id
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FormsAPI.ApiFormsFormIdEditableGet(context.Background(), formId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FormsAPI.ApiFormsFormIdEditableGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiFormsFormIdEditableGet`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `FormsAPI.ApiFormsFormIdEditableGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**formId** | **int64** | form-id | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiFormsFormIdEditableGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

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


## ApiFormsFormIdGet

> FormTemplate ApiFormsFormIdGet(ctx, formId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()

Get form by id (roles: handler, organization-owner, owner, reporter)

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
	formId := int64(789) // int64 | form-id
	xRemsApiKey := "xRemsApiKey_example" // string | REMS API-Key (optional for UI, required for API) (optional)
	xRemsUserId := "xRemsUserId_example" // string | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FormsAPI.ApiFormsFormIdGet(context.Background(), formId).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FormsAPI.ApiFormsFormIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiFormsFormIdGet`: FormTemplate
	fmt.Fprintf(os.Stdout, "Response from `FormsAPI.ApiFormsFormIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**formId** | **int64** | form-id | 

### Other Parameters

Other parameters are passed through a pointer to a apiApiFormsFormIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 

### Return type

[**FormTemplate**](FormTemplate.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiFormsGet

> []FormTemplateOverview ApiFormsGet(ctx).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Disabled(disabled).Archived(archived).Execute()

Get forms (roles: handler, organization-owner, owner, reporter)

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
	disabled := true // bool | whether to include disabled forms (optional)
	archived := true // bool | whether to include archived forms (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FormsAPI.ApiFormsGet(context.Background()).XRemsApiKey(xRemsApiKey).XRemsUserId(xRemsUserId).Disabled(disabled).Archived(archived).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FormsAPI.ApiFormsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiFormsGet`: []FormTemplateOverview
	fmt.Fprintf(os.Stdout, "Response from `FormsAPI.ApiFormsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiFormsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xRemsApiKey** | **string** | REMS API-Key (optional for UI, required for API) | 
 **xRemsUserId** | **string** | user (optional for UI, required for API). This can be a REMS internal or an external user identity attribute (specified in config.edn). | 
 **disabled** | **bool** | whether to include disabled forms | 
 **archived** | **bool** | whether to include archived forms | 

### Return type

[**[]FormTemplateOverview**](FormTemplateOverview.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/transit+msgpack, application/transit+json, application/edn

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


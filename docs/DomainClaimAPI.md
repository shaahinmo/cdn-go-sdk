# \DomainClaimAPI

All URIs are relative to *https://napi.arvancloud.ir/cdn/4.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DomainsClaimsCheck**](DomainClaimAPI.md#DomainsClaimsCheck) | **Post** /domains/claims/{claim_id}/check | Verify pending domain claim
[**DomainsClaimsList**](DomainClaimAPI.md#DomainsClaimsList) | **Get** /domains/claims | Get list of domain claims
[**DomainsClaimsShow**](DomainClaimAPI.md#DomainsClaimsShow) | **Get** /domains/claims/{claimId} | Get details of a specific domain claim
[**DomainsClaimsStore**](DomainClaimAPI.md#DomainsClaimsStore) | **Post** /domains/claims | Create a new domain claim



## DomainsClaimsCheck

> DomainsClaimsCheck200Response DomainsClaimsCheck(ctx, claimId).Execute()

Verify pending domain claim



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
	claimId := "claimId_example" // string | The ID of the domain claim to verify.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainClaimAPI.DomainsClaimsCheck(context.Background(), claimId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainClaimAPI.DomainsClaimsCheck``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsClaimsCheck`: DomainsClaimsCheck200Response
	fmt.Fprintf(os.Stdout, "Response from `DomainClaimAPI.DomainsClaimsCheck`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**claimId** | **string** | The ID of the domain claim to verify. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDomainsClaimsCheckRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DomainsClaimsCheck200Response**](DomainsClaimsCheck200Response.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DomainsClaimsList

> []DomainClaim DomainsClaimsList(ctx).PerPage(perPage).Page(page).Execute()

Get list of domain claims



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
	perPage := int32(56) // int32 | Set how many items returned per page (optional)
	page := int32(56) // int32 | Set the desired page number (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainClaimAPI.DomainsClaimsList(context.Background()).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainClaimAPI.DomainsClaimsList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsClaimsList`: []DomainClaim
	fmt.Fprintf(os.Stdout, "Response from `DomainClaimAPI.DomainsClaimsList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDomainsClaimsListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **perPage** | **int32** | Set how many items returned per page | 
 **page** | **int32** | Set the desired page number | [default to 1]

### Return type

[**[]DomainClaim**](DomainClaim.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DomainsClaimsShow

> DomainClaim DomainsClaimsShow(ctx, claimId).Execute()

Get details of a specific domain claim



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
	claimId := "claimId_example" // string | The ID of the domain claim to verify.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainClaimAPI.DomainsClaimsShow(context.Background(), claimId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainClaimAPI.DomainsClaimsShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsClaimsShow`: DomainClaim
	fmt.Fprintf(os.Stdout, "Response from `DomainClaimAPI.DomainsClaimsShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**claimId** | **string** | The ID of the domain claim to verify. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDomainsClaimsShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DomainClaim**](DomainClaim.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DomainsClaimsStore

> DomainClaim DomainsClaimsStore(ctx).DomainClaimRequest(domainClaimRequest).Execute()

Create a new domain claim



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
	domainClaimRequest := *openapiclient.NewDomainClaimRequest() // DomainClaimRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DomainClaimAPI.DomainsClaimsStore(context.Background()).DomainClaimRequest(domainClaimRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DomainClaimAPI.DomainsClaimsStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainsClaimsStore`: DomainClaim
	fmt.Fprintf(os.Stdout, "Response from `DomainClaimAPI.DomainsClaimsStore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDomainsClaimsStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **domainClaimRequest** | [**DomainClaimRequest**](DomainClaimRequest.md) |  | 

### Return type

[**DomainClaim**](DomainClaim.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


# \SSLTLSAPI

All URIs are relative to *https://napi.arvancloud.ir/cdn/4.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AccountCertificateInstall**](SSLTLSAPI.md#AccountCertificateInstall) | **Post** /certificates/orders/{certificateOrder}/install | Install a certum certificate on edge servers
[**AccountCertificateIssue**](SSLTLSAPI.md#AccountCertificateIssue) | **Post** /certificates/issue | Issue a new certum certificate
[**AccountCertificateOrderIndex**](SSLTLSAPI.md#AccountCertificateOrderIndex) | **Get** /certificates/orders | Get the list of certum certificate orders
[**AccountCertificateProductIndex**](SSLTLSAPI.md#AccountCertificateProductIndex) | **Get** /certificate-products | Get the list of certum certificate products
[**AccountCertificateReissue**](SSLTLSAPI.md#AccountCertificateReissue) | **Post** /certificates/orders/{certificateOrder}/reissue | Reissue a certum certificate
[**AccountCertificateRevoke**](SSLTLSAPI.md#AccountCertificateRevoke) | **Post** /certificates/orders/{certificateOrder}/revoke | Revoke a certum certificate
[**AccountCertificateShow**](SSLTLSAPI.md#AccountCertificateShow) | **Get** /certificates/orders/{certificateOrder} | Get details of a certum certificate order
[**SslCertDestroy**](SSLTLSAPI.md#SslCertDestroy) | **Delete** /domains/{domain}/ssl/certificates/{certificateId} | Delete an unused customer certificate
[**SslCertGet**](SSLTLSAPI.md#SslCertGet) | **Get** /domains/{domain}/ssl/certificates/{certificateId} | Get details of an issued certificate
[**SslCertIndex**](SSLTLSAPI.md#SslCertIndex) | **Get** /domains/{domain}/ssl/certificates | Get All certificates
[**SslCertIssue**](SSLTLSAPI.md#SslCertIssue) | **Post** /domains/{domain}/ssl/issue | Request for SSL Certificate Issuance
[**SslCertOrderIndex**](SSLTLSAPI.md#SslCertOrderIndex) | **Get** /domains/{domain}/ssl/orders | Get All Managed certificate orders history
[**SslCertOrderRetry**](SSLTLSAPI.md#SslCertOrderRetry) | **Post** /domains/{domain}/ssl/orders/action/retry | Retry a previously &#x60;killed&#x60; order
[**SslCertRevoke**](SSLTLSAPI.md#SslCertRevoke) | **Post** /domains/{domain}/ssl/certificates/{certificateId}/revoke | Revoke a server certificate
[**SslCertStore**](SSLTLSAPI.md#SslCertStore) | **Post** /domains/{domain}/ssl/certificates | Upload Certificate
[**SslIndex**](SSLTLSAPI.md#SslIndex) | **Get** /domains/{domain}/ssl | Get SSL settings
[**SslUpdate**](SSLTLSAPI.md#SslUpdate) | **Patch** /domains/{domain}/ssl | Update domain&#39;s SSL settings



## AccountCertificateInstall

> AccountCertificateInstall200Response AccountCertificateInstall(ctx, certificateOrder).Execute()

Install a certum certificate on edge servers

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
	certificateOrder := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the certificate order

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SSLTLSAPI.AccountCertificateInstall(context.Background(), certificateOrder).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.AccountCertificateInstall``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountCertificateInstall`: AccountCertificateInstall200Response
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.AccountCertificateInstall`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**certificateOrder** | **string** | The ID of the certificate order | 

### Other Parameters

Other parameters are passed through a pointer to a apiAccountCertificateInstallRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AccountCertificateInstall200Response**](AccountCertificateInstall200Response.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccountCertificateIssue

> AccountCertificateOrder AccountCertificateIssue(ctx).CertificateOrderIssueRequest(certificateOrderIssueRequest).Execute()

Issue a new certum certificate

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
	certificateOrderIssueRequest := *openapiclient.NewCertificateOrderIssueRequest([]openapiclient.CertificateOrderIssueRequestDomainsInner{*openapiclient.NewCertificateOrderIssueRequestDomainsInner()}, "ProductId_example") // CertificateOrderIssueRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SSLTLSAPI.AccountCertificateIssue(context.Background()).CertificateOrderIssueRequest(certificateOrderIssueRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.AccountCertificateIssue``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountCertificateIssue`: AccountCertificateOrder
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.AccountCertificateIssue`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAccountCertificateIssueRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **certificateOrderIssueRequest** | [**CertificateOrderIssueRequest**](CertificateOrderIssueRequest.md) |  | 

### Return type

[**AccountCertificateOrder**](AccountCertificateOrder.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccountCertificateOrderIndex

> AccountCertificateOrderIndex200Response AccountCertificateOrderIndex(ctx).PerPage(perPage).Page(page).Execute()

Get the list of certum certificate orders

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
	resp, r, err := apiClient.SSLTLSAPI.AccountCertificateOrderIndex(context.Background()).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.AccountCertificateOrderIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountCertificateOrderIndex`: AccountCertificateOrderIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.AccountCertificateOrderIndex`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAccountCertificateOrderIndexRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **perPage** | **int32** | Set how many items returned per page | 
 **page** | **int32** | Set the desired page number | [default to 1]

### Return type

[**AccountCertificateOrderIndex200Response**](AccountCertificateOrderIndex200Response.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccountCertificateProductIndex

> AccountCertificateProductIndex200Response AccountCertificateProductIndex(ctx).Execute()

Get the list of certum certificate products

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SSLTLSAPI.AccountCertificateProductIndex(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.AccountCertificateProductIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountCertificateProductIndex`: AccountCertificateProductIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.AccountCertificateProductIndex`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiAccountCertificateProductIndexRequest struct via the builder pattern


### Return type

[**AccountCertificateProductIndex200Response**](AccountCertificateProductIndex200Response.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccountCertificateReissue

> AccountCertificateOrder AccountCertificateReissue(ctx, certificateOrder).Execute()

Reissue a certum certificate

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
	certificateOrder := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the certificate order

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SSLTLSAPI.AccountCertificateReissue(context.Background(), certificateOrder).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.AccountCertificateReissue``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountCertificateReissue`: AccountCertificateOrder
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.AccountCertificateReissue`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**certificateOrder** | **string** | The ID of the certificate order | 

### Other Parameters

Other parameters are passed through a pointer to a apiAccountCertificateReissueRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AccountCertificateOrder**](AccountCertificateOrder.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccountCertificateRevoke

> AccountCertificateOrder AccountCertificateRevoke(ctx, certificateOrder).Execute()

Revoke a certum certificate

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
	certificateOrder := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the certificate order

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SSLTLSAPI.AccountCertificateRevoke(context.Background(), certificateOrder).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.AccountCertificateRevoke``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountCertificateRevoke`: AccountCertificateOrder
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.AccountCertificateRevoke`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**certificateOrder** | **string** | The ID of the certificate order | 

### Other Parameters

Other parameters are passed through a pointer to a apiAccountCertificateRevokeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AccountCertificateOrder**](AccountCertificateOrder.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AccountCertificateShow

> AccountCertificateOrder AccountCertificateShow(ctx, certificateOrder).KeepPrivateKey(keepPrivateKey).Execute()

Get details of a certum certificate order

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
	certificateOrder := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the certificate order
	keepPrivateKey := true // bool | whether the private key should be retained on ArvanCloud servers. If set to false, the private key will be permanently removed, and it will no longer be accessible or viewable. Ensure you store the key securely for future use (optional) (default to true)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SSLTLSAPI.AccountCertificateShow(context.Background(), certificateOrder).KeepPrivateKey(keepPrivateKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.AccountCertificateShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AccountCertificateShow`: AccountCertificateOrder
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.AccountCertificateShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**certificateOrder** | **string** | The ID of the certificate order | 

### Other Parameters

Other parameters are passed through a pointer to a apiAccountCertificateShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **keepPrivateKey** | **bool** | whether the private key should be retained on ArvanCloud servers. If set to false, the private key will be permanently removed, and it will no longer be accessible or viewable. Ensure you store the key securely for future use | [default to true]

### Return type

[**AccountCertificateOrder**](AccountCertificateOrder.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SslCertDestroy

> MessageResponse SslCertDestroy(ctx, domain, certificateId).Execute()

Delete an unused customer certificate

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
	domain := "example.com" // string | Domain name
	certificateId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of an ssl certificate

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SSLTLSAPI.SslCertDestroy(context.Background(), domain, certificateId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.SslCertDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SslCertDestroy`: MessageResponse
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.SslCertDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Domain name | 
**certificateId** | **string** | ID of an ssl certificate | 

### Other Parameters

Other parameters are passed through a pointer to a apiSslCertDestroyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**MessageResponse**](MessageResponse.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SslCertGet

> SslCertGet200Response SslCertGet(ctx, domain, certificateId).ShowPrivateKey(showPrivateKey).Execute()

Get details of an issued certificate

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
	domain := "example.com" // string | Domain name
	certificateId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of an ssl certificate
	showPrivateKey := true // bool | Indicates whether the private key should be included in the response. If set to true, the private key will be permanently removed, and it will no longer be accessible or viewable. Ensure you store the key securely for future use (optional) (default to false)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SSLTLSAPI.SslCertGet(context.Background(), domain, certificateId).ShowPrivateKey(showPrivateKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.SslCertGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SslCertGet`: SslCertGet200Response
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.SslCertGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Domain name | 
**certificateId** | **string** | ID of an ssl certificate | 

### Other Parameters

Other parameters are passed through a pointer to a apiSslCertGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **showPrivateKey** | **bool** | Indicates whether the private key should be included in the response. If set to true, the private key will be permanently removed, and it will no longer be accessible or viewable. Ensure you store the key securely for future use | [default to false]

### Return type

[**SslCertGet200Response**](SslCertGet200Response.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SslCertIndex

> SslCertIndex200Response SslCertIndex(ctx, domain).Types(types).Execute()

Get All certificates

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
	domain := "example.com" // string | Domain name
	types := []openapiclient.CertificateType{openapiclient.CertificateType("user")} // []CertificateType | Filter certificates by types (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SSLTLSAPI.SslCertIndex(context.Background(), domain).Types(types).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.SslCertIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SslCertIndex`: SslCertIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.SslCertIndex`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Domain name | 

### Other Parameters

Other parameters are passed through a pointer to a apiSslCertIndexRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **types** | [**[]CertificateType**](CertificateType.md) | Filter certificates by types | 

### Return type

[**SslCertIndex200Response**](SslCertIndex200Response.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SslCertIssue

> SslCertIssue200Response SslCertIssue(ctx, domain).Execute()

Request for SSL Certificate Issuance

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
	domain := "example.com" // string | Domain name

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SSLTLSAPI.SslCertIssue(context.Background(), domain).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.SslCertIssue``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SslCertIssue`: SslCertIssue200Response
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.SslCertIssue`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Domain name | 

### Other Parameters

Other parameters are passed through a pointer to a apiSslCertIssueRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SslCertIssue200Response**](SslCertIssue200Response.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SslCertOrderIndex

> SslCertOrderIndex200Response SslCertOrderIndex(ctx, domain).Type_(type_).Execute()

Get All Managed certificate orders history

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
	domain := "example.com" // string | Domain name
	type_ := "type__example" // string |  (optional) (default to "edge")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SSLTLSAPI.SslCertOrderIndex(context.Background(), domain).Type_(type_).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.SslCertOrderIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SslCertOrderIndex`: SslCertOrderIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.SslCertOrderIndex`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Domain name | 

### Other Parameters

Other parameters are passed through a pointer to a apiSslCertOrderIndexRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **type_** | **string** |  | [default to &quot;edge&quot;]

### Return type

[**SslCertOrderIndex200Response**](SslCertOrderIndex200Response.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SslCertOrderRetry

> MessageResponse SslCertOrderRetry(ctx, domain).Execute()

Retry a previously `killed` order

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
	domain := "example.com" // string | Domain name

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SSLTLSAPI.SslCertOrderRetry(context.Background(), domain).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.SslCertOrderRetry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SslCertOrderRetry`: MessageResponse
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.SslCertOrderRetry`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Domain name | 

### Other Parameters

Other parameters are passed through a pointer to a apiSslCertOrderRetryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**MessageResponse**](MessageResponse.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SslCertRevoke

> MessageResponse SslCertRevoke(ctx, domain, certificateId).Execute()

Revoke a server certificate



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
	domain := "example.com" // string | Domain name
	certificateId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of an ssl certificate

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SSLTLSAPI.SslCertRevoke(context.Background(), domain, certificateId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.SslCertRevoke``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SslCertRevoke`: MessageResponse
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.SslCertRevoke`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Domain name | 
**certificateId** | **string** | ID of an ssl certificate | 

### Other Parameters

Other parameters are passed through a pointer to a apiSslCertRevokeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**MessageResponse**](MessageResponse.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SslCertStore

> MessageResponse SslCertStore(ctx, domain).Certificate(certificate).PrivateKey(privateKey).Execute()

Upload Certificate

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
	domain := "example.com" // string | Domain name
	certificate := os.NewFile(1234, "some_file") // *os.File |  (optional)
	privateKey := os.NewFile(1234, "some_file") // *os.File |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SSLTLSAPI.SslCertStore(context.Background(), domain).Certificate(certificate).PrivateKey(privateKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.SslCertStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SslCertStore`: MessageResponse
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.SslCertStore`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Domain name | 

### Other Parameters

Other parameters are passed through a pointer to a apiSslCertStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **certificate** | ***os.File** |  | 
 **privateKey** | ***os.File** |  | 

### Return type

[**MessageResponse**](MessageResponse.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SslIndex

> SslResponse SslIndex(ctx, domain).Execute()

Get SSL settings

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
	domain := "example.com" // string | Domain name

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SSLTLSAPI.SslIndex(context.Background(), domain).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.SslIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SslIndex`: SslResponse
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.SslIndex`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Domain name | 

### Other Parameters

Other parameters are passed through a pointer to a apiSslIndexRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SslResponse**](SslResponse.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SslUpdate

> SslResponse SslUpdate(ctx, domain).SslUpdate(sslUpdate).Execute()

Update domain's SSL settings

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
	domain := "example.com" // string | Domain name
	sslUpdate := *openapiclient.NewSslUpdate() // SslUpdate |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SSLTLSAPI.SslUpdate(context.Background(), domain).SslUpdate(sslUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SSLTLSAPI.SslUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SslUpdate`: SslResponse
	fmt.Fprintf(os.Stdout, "Response from `SSLTLSAPI.SslUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Domain name | 

### Other Parameters

Other parameters are passed through a pointer to a apiSslUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **sslUpdate** | [**SslUpdate**](SslUpdate.md) |  | 

### Return type

[**SslResponse**](SslResponse.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


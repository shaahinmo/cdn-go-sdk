# \MetricExportersAPI

All URIs are relative to *https://napi.arvancloud.ir/cdn/4.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**MetricExportersDestroy**](MetricExportersAPI.md#MetricExportersDestroy) | **Delete** /domains/{domain}/metric-exporters/{metricExporterId} | Delete a metric exporter
[**MetricExportersIndex**](MetricExportersAPI.md#MetricExportersIndex) | **Get** /metric-exporters | Show list of account&#39;s metric exporters
[**MetricExportersShow**](MetricExportersAPI.md#MetricExportersShow) | **Get** /domains/{domain}/metric-exporters/{metricExporterId} | Show a metric exporter&#39;s details based on given id
[**MetricExportersStore**](MetricExportersAPI.md#MetricExportersStore) | **Post** /domains/{domain}/metric-exporters | Create new metric exporter
[**MetricExportersUpdate**](MetricExportersAPI.md#MetricExportersUpdate) | **Put** /domains/{domain}/metric-exporters/{metricExporterId} | Update a metric exporter
[**MetricExportersUpdateStatus**](MetricExportersAPI.md#MetricExportersUpdateStatus) | **Patch** /domains/{domain}/metric-exporters/{metricExporterId}/status | Update a metric exporter&#39;s status



## MetricExportersDestroy

> MessageResponse MetricExportersDestroy(ctx, domain, metricExporterId).Execute()

Delete a metric exporter

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shaahinmo/cdn-go-sdk"
)

func main() {
	domain := "example.com" // string | Domain name
	metricExporterId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Metric Exporter Id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetricExportersAPI.MetricExportersDestroy(context.Background(), domain, metricExporterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetricExportersAPI.MetricExportersDestroy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MetricExportersDestroy`: MessageResponse
	fmt.Fprintf(os.Stdout, "Response from `MetricExportersAPI.MetricExportersDestroy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Domain name | 
**metricExporterId** | **string** | Metric Exporter Id | 

### Other Parameters

Other parameters are passed through a pointer to a apiMetricExportersDestroyRequest struct via the builder pattern


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


## MetricExportersIndex

> MetricExportersIndex200Response MetricExportersIndex(ctx).PerPage(perPage).Page(page).Execute()

Show list of account's metric exporters

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shaahinmo/cdn-go-sdk"
)

func main() {
	perPage := int32(56) // int32 | Set how many items returned per page (optional)
	page := int32(56) // int32 | Set the desired page number (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetricExportersAPI.MetricExportersIndex(context.Background()).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetricExportersAPI.MetricExportersIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MetricExportersIndex`: MetricExportersIndex200Response
	fmt.Fprintf(os.Stdout, "Response from `MetricExportersAPI.MetricExportersIndex`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiMetricExportersIndexRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **perPage** | **int32** | Set how many items returned per page | 
 **page** | **int32** | Set the desired page number | [default to 1]

### Return type

[**MetricExportersIndex200Response**](MetricExportersIndex200Response.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MetricExportersShow

> MetricExporterResponse MetricExportersShow(ctx, domain, metricExporterId).Execute()

Show a metric exporter's details based on given id

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shaahinmo/cdn-go-sdk"
)

func main() {
	domain := "example.com" // string | Domain name
	metricExporterId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Metric Exporter Id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetricExportersAPI.MetricExportersShow(context.Background(), domain, metricExporterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetricExportersAPI.MetricExportersShow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MetricExportersShow`: MetricExporterResponse
	fmt.Fprintf(os.Stdout, "Response from `MetricExportersAPI.MetricExportersShow`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Domain name | 
**metricExporterId** | **string** | Metric Exporter Id | 

### Other Parameters

Other parameters are passed through a pointer to a apiMetricExportersShowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**MetricExporterResponse**](MetricExporterResponse.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MetricExportersStore

> MetricExporterResponse MetricExportersStore(ctx, domain).MetricExporter(metricExporter).Execute()

Create new metric exporter

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shaahinmo/cdn-go-sdk"
)

func main() {
	domain := "example.com" // string | Domain name
	metricExporter := *openapiclient.NewMetricExporter("Name_example", "Type_example", "Interval_example", false) // MetricExporter |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetricExportersAPI.MetricExportersStore(context.Background(), domain).MetricExporter(metricExporter).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetricExportersAPI.MetricExportersStore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MetricExportersStore`: MetricExporterResponse
	fmt.Fprintf(os.Stdout, "Response from `MetricExportersAPI.MetricExportersStore`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Domain name | 

### Other Parameters

Other parameters are passed through a pointer to a apiMetricExportersStoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **metricExporter** | [**MetricExporter**](MetricExporter.md) |  | 

### Return type

[**MetricExporterResponse**](MetricExporterResponse.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MetricExportersUpdate

> MetricExporterResponse MetricExportersUpdate(ctx, domain, metricExporterId).MetricExporter(metricExporter).Execute()

Update a metric exporter

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shaahinmo/cdn-go-sdk"
)

func main() {
	domain := "example.com" // string | Domain name
	metricExporterId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Metric Exporter Id
	metricExporter := *openapiclient.NewMetricExporter("Name_example", "Type_example", "Interval_example", false) // MetricExporter |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetricExportersAPI.MetricExportersUpdate(context.Background(), domain, metricExporterId).MetricExporter(metricExporter).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetricExportersAPI.MetricExportersUpdate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MetricExportersUpdate`: MetricExporterResponse
	fmt.Fprintf(os.Stdout, "Response from `MetricExportersAPI.MetricExportersUpdate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Domain name | 
**metricExporterId** | **string** | Metric Exporter Id | 

### Other Parameters

Other parameters are passed through a pointer to a apiMetricExportersUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **metricExporter** | [**MetricExporter**](MetricExporter.md) |  | 

### Return type

[**MetricExporterResponse**](MetricExporterResponse.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MetricExportersUpdateStatus

> MetricExporterResponse MetricExportersUpdateStatus(ctx, domain, metricExporterId).UpdateBooleanStatus(updateBooleanStatus).Execute()

Update a metric exporter's status

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/shaahinmo/cdn-go-sdk"
)

func main() {
	domain := "example.com" // string | Domain name
	metricExporterId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Metric Exporter Id
	updateBooleanStatus := *openapiclient.NewUpdateBooleanStatus() // UpdateBooleanStatus |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MetricExportersAPI.MetricExportersUpdateStatus(context.Background(), domain, metricExporterId).UpdateBooleanStatus(updateBooleanStatus).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MetricExportersAPI.MetricExportersUpdateStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MetricExportersUpdateStatus`: MetricExporterResponse
	fmt.Fprintf(os.Stdout, "Response from `MetricExportersAPI.MetricExportersUpdateStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**domain** | **string** | Domain name | 
**metricExporterId** | **string** | Metric Exporter Id | 

### Other Parameters

Other parameters are passed through a pointer to a apiMetricExportersUpdateStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateBooleanStatus** | [**UpdateBooleanStatus**](UpdateBooleanStatus.md) |  | 

### Return type

[**MetricExporterResponse**](MetricExporterResponse.md)

### Authorization

[ApiKey](../README.md#ApiKey), [UserToken](../README.md#UserToken)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

